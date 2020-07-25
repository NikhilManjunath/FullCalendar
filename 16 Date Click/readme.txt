Detect when the user clicks on dates or times. 
Give the user the ability to select multiple dates or time slots with their mouse or touch device.

selectable: true,    
->Allows to highlight multiple days or timeslots by clicking and dragging.

selectMirror:true,  
->Whether to draw a “placeholder” event while the user is dragging.

unselectAuto: false, 
->Whether clicking elsewhere on the page will cause the current selection to be cleared. False implies current selection will not be cleared

selectOverlap: true,  
->whether the user is allowed to select periods of time that are occupied by events.


dateClick: function(info) {
  alert('clicked ' + info.dateStr);
},
-> alert generated which displays the date clicked

select: function(info) {
  alert('selected ' + info.startStr + ' to ' + info.endStr);
},
->alert generated which displays the start and end dates of the dates clicked