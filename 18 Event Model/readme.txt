customButtons: {
          addEventButton: {
            text: 'Add Event',
            click: function() {
              var dateStr = prompt('Enter a date in YYYY-MM-DD format');
              var date = new Date(dateStr + 'T00:00:00'); // will be in local time

              if (!isNaN(date.valueOf())) { // valid?
                calendar.addEvent({
                  title: 'dynamic event',
                  start: date,
                  allDay: true
                });
                alert('Great. Now, update your database...');
              } else {
                alert('Invalid date.');
              }
            }
          }
        },

        Custom button is created to add events dynamically