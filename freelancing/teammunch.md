# Team Munch Case Study

### Client Quote

>"F&C’s team took us from concept to stable version for market testing in just a few weeks, and supported us during the testing phase. Very responsive team, easy to work with and know their stuff well. If you want to test the waters with your first product version, speak to F&C." - Alex

### Summary

Team Munch is lunchtime delivery web application that allows people to choose their meals individually in a team and the payments are aggregated.

### Challenge

The biggest challenge was understanding how the user flow would work. We had two different user journeys - either team leader pays or team members pay. Depending on whether you were a team leader or a team member and whether the team leader was paying or not, a user would only see certain screens. The challenge was making sure the user was directed through the correct user journey.

### Solution

The use of cookies, the Hapi framework and the handlebars templating engine helped us overcome the challenge of determining the correct user journey for the user. Cookies allowed us to easily check through Hapi what type of user they were and at what part in the user flow they needed to be at. Handlebars allowed us to reuse the same HTML pages but generate different messages on the page according to what type of user they were.

### Technologies
  * Hapi
  * Stripe API
  * Redis
  * Bootstrap
  * jQuery
  * Handlebars

### Screenshots
![Login Page](https://files.gitter.im/foundersandcoders/TeamMunch/CWCt/Screen-Shot-2016-02-18-at-11.12.30.png "Login Page")

![Invite Team Members Page](https://files.gitter.im/foundersandcoders/TeamMunch/ZOQv/Screen-Shot-2016-02-18-at-11.13.31.png "Invite Team Members Page")

![Choose Options](https://files.gitter.im/foundersandcoders/TeamMunch/SV8N/Screen-Shot-2016-02-18-at-11.14.19.png "Choose Options")

![Choose Restaurant Page](https://files.gitter.im/foundersandcoders/TeamMunch/cTA1/Screen-Shot-2016-02-18-at-11.14.49.png "Choose Restaurant Page")

![Choose Meal Page](https://files.gitter.im/foundersandcoders/TeamMunch/5JxL/Screen-Shot-2016-02-18-at-11.15.29.png "Choose Meal Page")

![Delivery Address](https://files.gitter.im/foundersandcoders/TeamMunch/Kpbf/Screen-Shot-2016-02-18-at-11.19.35.png "Delivery Address")

![Pay Page](https://files.gitter.im/foundersandcoders/TeamMunch/E9pp/Screen-Shot-2016-02-18-at-11.20.18.png "Pay Page")

![Finish](https://files.gitter.im/foundersandcoders/TeamMunch/qVJU/Screen-Shot-2016-02-18-at-11.21.20.png "Finish")
