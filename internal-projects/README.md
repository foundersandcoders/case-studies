## FAC SHARE

A resource sharing and discovery platform for FACers

## SUMMARY

FAC Share is a knowledge sharing platform, that enables users to add links to webpages their peers should zread about.
There is also a Google chrome extension that allows users to share the links the want without changing tabs.
The idea is that users, while reading an article, can bookmark it, and add it to the FAC Share list. Once it has been shared/added a search can be run on all the available links.  
Stretch goals include:
- being able to authenticate users;
- rate/upvote resources based on preference;
- leave comments on specific links;
- see how old the resources are and who added them.

### PROTOTYPES

* Mobile website: https://www.figma.com/file/cnOk6NDLJuNP5emHBoz5CTSG/FAC-Share
* Desktop website: https://www.figma.com/file/AJCiubybYrprMRhaatCoV3/FAC-Share-Desktop
* Google Chrome extension: https://www.figma.com/file/7tTeoiJtaNjEwfk03Nfolt/FAC-Share-Extension

## Challenge
The main challenge was to a fully functioning chrome extension.
A further challenge was to implement a fully functioning PSQL search.

## Solution
We built both a responsive website and a chrome extension that is able to retrieve the url and title of the current open tab, and is able to send it to our database.It should be as easy as Gitter to share resources.

Our focus was on creating a simple and clear UI for FACers. Users can search among all the links in the database.

## Technologies
- Express
- postgreSQL

## Team members (with links to github profiles)
[Alina](https://github.com/azayneeva), [Stefano](https://github.com/rinoma),[Abdullah](https://github.com/AbdullahChaudhry)

### link to URL: https://github.com/azayneeva/FAC-Share
### Link to repo: https://github.com/azayneeva/FAC-Share

## Screenshot

![](https://user-images.githubusercontent.com/24795752/30491116-1d1583a6-9a34-11e7-8948-4c9c591e903d.png)
