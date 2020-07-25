Vertical Resource view is another way of representing the resources on the fullcalendar

views: {
          resourceTimeGridFourDay: {
            type: 'resourceTimeGrid',
            duration: { days: 4 },
            buttonText: '4 days'
          }
-> creates a customized 4 day Vertical Resource view 

resources: [
          { id: 'a', title: 'Room A' },
          { id: 'b', title: 'Room B'}
        ],
-> seperates resources into rooms A and B