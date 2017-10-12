# [Datapower](https://datapower.herokuapp.com/) case study
***FAC project for [Power to Change](http://www.powertochange.org.uk/)'s [Twine](http://www.twine-together.com/) platform, brought to you by [@azayneeva](https://github.com/azayneeva), [@RogeredBacon](https://github.com/RogeredBacon) and [@rachaelcodes](https://github.com/rachaelcodes)***

![screencast](https://user-images.githubusercontent.com/23265724/31492598-b498f432-af43-11e7-95ea-b598536c26d1.jpeg)

> *3 brilliant young coders from the Founders and Coders bootcamp have spent the past couple of weeks developing a solution for CBs to track footfall data. The result is in my view really great, and potentially a more useful alternative to the Yoti/MyVenue alternative we are trialing at the moment.*
> **Sonja, Power to Change**

## Summary
A website simplifying data collection for community organisations investigating the reach of their services.
## Challenge 
Power to Change support community organisations that offer a range of services to their clients. They wanted to find a way to collect demographic information about their service users for different activities, while making sure the data collection process was unobtrusive for clients. 
## Solution

![gif of walkthrough](https://user-images.githubusercontent.com/23265724/31492017-33806fd0-af41-11e7-9af8-a38a424dc906.gif) (*Oops, spot the Kilgore/Kilgrave mistake...*)

Using Datapower, community business customers can register for a QR sign-in code with a hashed version of their registration information. When the client visits the community centre, they then scan their QR code and quickly share their activity of the day from a list of buttons. This choice is stored in the organisation's database, allowing the organisation to retrieve information about which activities are most popular among particular demographic groups.

## Technologies
* [react](https://reactjs.org/)
* [node.js](https://nodejs.org/en/)
* [express.js](https://expressjs.com/), a node.js web framework
* [PostgreSQL](https://www.postgresql.org/) database
* [qrcode](https://github.com/soldair/node-qrcode), a npm module for generating QR codes
* [Instascan](https://github.com/schmich/instascan), a real-time webcam-driven HTML5 QR code scanner

> *Power to Change has been a fantastic organisation to work with - with a very clear understanding of the problem they wanted solved and ideas for the solution. I hope this product will be useful for their clients and rolled out in community organisations across the country.*
> **Rachael, FAC11**

![QR code example - user not there now!](https://user-images.githubusercontent.com/23265724/31492684-12906214-af44-11e7-9d2e-70521d948ec5.jpeg)

Visit Datapower [here](https://datapower.herokuapp.com/) or visit our [github repo](https://github.com/FAC-11/DataPower/).
