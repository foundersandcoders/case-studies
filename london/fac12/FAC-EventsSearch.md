# FAC-Events-Search

Quotation
---
> FACcer: "That event on Saturday so great."
> Other FACcer: "Wait, what event? How do you know about all of these events?"
> FACcer: "It was on the gitter channel."
> FACcer: "Which gitter channel? There are more than 5!"

Summary
---

A website to show events and allow the user to search and add events. 

Challenge
---
A problem that people in FAC face is they would like to connect with alumni. They would also like to know what events they can attend and who else is going. Currently people around the space find out about events on gitter and by word of mouth. Events often get lost in founders and coders gitter rooms. There is also not many opportunities to network with alumni that are not around the space.

Solution
---
We built a web app that presents its users with a curated list of events. Users sign in through GitHub (using OAuth) to access the app. They can view events according to several filters: those hosted by select organizations, those they have express interested in attending, events sorted by popularity. They can also filter by date and search term. Users can see how many other users have expressed interest in an event and who they are when viewing the detailed information for an event. Users can add events manually or via a meetup.com url.

Technologies
---
- Express, Node server
- PostgreSQL database
- PassportJS + Github OAuth + cookie-session
- React + React Router
- Redux + Redux-Thunk + Redux-Form

Team Members
---
[Mohamed Osman](https://github.com/trc5019) and [Shannon Jensen Wedgwood](https://github.com/shannonjensen)

Animated GIF
---
![](https://i.imgur.com/3oBolXC.gif)

