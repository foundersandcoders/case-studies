## HomeSafe | [Hosted on Heroku](https://homesafefac.herokuapp.com) | [Github](https://github.com/fac-12/homesafe)

Team members: [Kitty](https://github.com/parkhabit), [Fatimat](https://github.com/Gbaja), [Sophie](https://github.com/sophielevens), [Dragomir](https://github.com/Dragomirc)

Tech stack: Node, Express, Handlebars, PostgreSQL

## Summary

A website to help parents/guardians inform their child’s school if someone other than the regular guardian will be picking up the child, in a way that ensures the child’s safety. Currently parents are calling the school or notify in person about someone else picking up their child. The school doesn't undertake any checks againt someone calling in regards to the aforesaid, or against the person that comes to pick up the child. Also to compile all the requests the school receives and store them online in one place, we developed HomeSafe app.(Currently the school receptionist takes notes on a piece of paper, which is error-prone, can be easily lost and there is no way to retrive this information in the future).

## Challenge
Primary schools in the London area regularly have no specific way to ensure a child is being picked up by the correct guardian. Many schools have a call-in system whereby the parent will notify the school by calling in. This current system leaves the school with no way of tracking this information, or safely ensuring that the child is being picked up by the correct guardian.

## Our solution

We developed a web-app that provides an added layer of security for children being picked up from school by enabling parents to assign a temporary pseudo-guardian to pick up their child, when they themselves are unable to.
The parents notify securely the school throught the app, about a new schedule pick up and providing a keyword which is shared authomatically with the designated adult and the school, thus the later can ensure the child is released the correct person.

## Approach
* Design Sprint
    * Designed a prototype on [Figma](https://www.figma.com/file/eaeaaZNSEvPlxeuYBYcmI2iX/HomeSafe)
    * Spent time user testing
    * We have two user journeys, one being that of the school and the other being that of the parent/guardian. Keeping this in mind when user testing was difficult but useful.
    * [Our user testing feedback](https://hackmd.io/BwdgrAJgjAxgLDAtBADAUwGaIQZgGyICGAnHAEyLEqEYY5TB6HBRA===)

* Build Sprint
    * User journeys:
        * School
            * I want to be able to sign-up securely, by authenticating my email address
            * I want to be able to log-in securely
            * I want to be able to see today’s scheduled pickups
            * I want to be able to search for other scheduled pickups both past and in the future

        * Parent
            * I want to be able to sign-up securely
            * I want to be able to log-in securely
            * I want to be able to add children to my profile
            * I want to be able to add designated adults to my profile
            * I want to be able to schedule a ‘pickup’, with a secret word




## Screen shots

![Landing Page](https://i.imgur.com/bffHwW0.png =300x)

![Parent Register](https://i.imgur.com/4egRZYQ.png =300x)

![Parent Profile](https://i.imgur.com/cdldtXg.png =300x)

### Email verification messages

![](https://i.imgur.com/cKZmdvO.png)
![](https://i.imgur.com/BE29cD7.png)


## Register
![](https://i.imgur.com/ehXExnO.gif)

![](https://i.imgur.com/pEE4eQg.gif)
