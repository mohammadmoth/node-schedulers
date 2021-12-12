# node-schedulers
You can add a set of events and activate them through recurring times.

# why i make it ?
It is somewhat similar to setInterval. 
But the main difference is that events do not overlap at close times while using Await, using the same group.
And also the possibility of assigning importance to each event so that if there is more than one event, the most important event can be selected. 
In addition to the interrupts system. 


# what is interrupts system ?

When the system triggers an event.
Sometimes there is a very long operating time.
This means booking a program and blocking the rest of the events in the same group. 
What this system does is go to a more important event and then come back 


# Tasks:
- [ ] Add and remove Event by group or id
- [ ] Get all event object by group or id
- [ ] Timer Loops by group or id
- [ ] add Checker Event interrupts by group or id
