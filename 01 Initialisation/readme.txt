The full calendar library is first downloaded (CDN can also be used)
The respective js and css scripts are included in the head

We then create a div with an id of calendar in the body of the html and initialize the calendar using the following code:

document.addEventListener('DOMContentLoaded', function() {
      var calendarEl = document.getElementById('calendar');
      var calendar = new FullCalendar.Calendar(calendarEl, { //initialzing globals
        schedulerLicenseKey: 'CC-Attribution-NonCommercial-NoDerivatives',
      });
      calendar.render();
    });

initialView: 'dayGridMonth'
-> when the calendar is opened, month view is displayed