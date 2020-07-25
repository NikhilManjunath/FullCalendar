Settings that control presence/absense of dates as well as their styling and text.

weekends: false   
->Whether to include Saturday/Sunday columns in any of the calendar views.
->if false, weekends not displayed

hiddenDays: [ 2, 4 ]  
->Exclude certain days-of-the-week from being displayed.
->hides Tuesdays and Thursdays

dayHeaders: false  
->Whether the day headers should appear
->removes the weekday names

dayHeaderFormat: { weekday: 'long'},
->Determines the text that will be displayed on the calendar’s column headings.

nowIndicator: true 
->display a marker indicating the current time.