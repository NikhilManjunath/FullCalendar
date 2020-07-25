Emphasize a view’s “business hours” (aka “working hours”).

businessHours: true , 
->If true, By default, Monday-Friday, 9am-5pm,
        
        
        businessHours: [
          {
            daysOfWeek: [ 1, 2, 3, 4, 5 ],
            startTime: '09:00',
            endTime: '18:00',
          },
          {
            daysOfWeek: [ 6 ],
            startTime: '09:00',
            endTime: '12:00',
          },
        ]