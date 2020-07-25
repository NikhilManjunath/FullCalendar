Handlers to know when an event has been clicked or hovered over.

eventClick: function(info) { //Triggered when the user clicks an event.
  alert('Event: ' + info.event.title);
  alert('Start: ' + info.event.start);
  info.el.style.borderColor = 'red';
},
-> generates 2 alerts which display the event title and start time respectively when the event is clicked

eventMouseEnter: function(mouseEnterInfo) {
  mouseEnterInfo.el.style.backgroundColor = 'black';
},
eventMouseLeave: function(mouseEnterInfo) {
  mouseEnterInfo.el.style.backgroundColor = '#1e84d0';
},
->changes event background color when hovered over the event