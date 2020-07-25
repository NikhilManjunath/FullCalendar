Methods and settings that determine the view’s current dates.

initialDate: '2020-06-10', 
->The initial date displayed when the calendar first loads. Loads June 10

validRange: {  
    start: '2020-05-01',
    end: '2020-08-01',
  },
  ->Limits which dates the user can navigate to and where events can go.
  ->Dates outside of the valid range will be grayed-out. The user will not be able to drag or resize events into these areas.


navLinks: true,  
->Determines if day names and week names are clickable. 
        
weekNumbers: true,  
->week numbers will be displayed on the calendar