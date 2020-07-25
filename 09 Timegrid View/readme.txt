A TimeGrid view displays one-or-more horizontal days as well as an axis of time, usually midnight to midnight, on the vertical axis

The two predefined TimeGrid views are the timeGridWeek and timeGridDay views. 

Customized timegrid views can also be created:
views: {
          timeGridFourDay: {
          type: 'timeGrid',
          duration: { days: 4 },
          buttonText: '4 day'
          }
        },
->creates a 4-day timegrid view