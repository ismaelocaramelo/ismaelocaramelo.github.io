---
layout: post
title: "Green Charge Spots"
date: 2016-09-07
categories:
description:
image: http://i.imgur.com/5TLpcEK.png
image-sm: http://i.imgur.com/5TLpcEK.png
image-home: https://images.unsplash.com/photo-1470762920880-a8e058686707?ixlib=rb-0.3.5&q=80&fm=jpg&crop=entropy&cs=tinysrgb&s=7ad04dcd45407f39e32f62424b192b86
---
**Green Charge Spots** This application was produced as my third project for the Web Development Immersive course at General Assembly London. It was built using HTML5, CSS3 and JavaScript/jQuery.

The app can be played here: [https://green-charge-vehicle.herokuapp.com/](https://green-charge-vehicle.herokuapp.com/)

**Development**

Green Charge Spots

Charge points for electric vehicle

This application was produced as my third project for the Web Development Immersive course at General Assembly London.

The decision to make this website was serve as a charging point platform. In addition to the charge point map, Green Charge Spots provides supporting information on charging and electric vehicles to help current or prospective EV drivers to make more informed choices and enjoy their electric motoring experience.

**Charge Point Database**

Green Charge Spots aggregates data from various sources to provide the most comprehensive source of UK charge points – there are currently more than 4000 public charging locations mapped on the my database.

**Favourite Spots**

Green Charge Spots facilitates a user friendly favourite icon to store his preferred choices and access them in a simple interface. Click on specific England charging points to see more info about address, number, type and to which network each charging point belongs.

**Planning**

**Wireframing**

I used the tool Balsamiq to wireframe the general appearance of the main parts of the app - namely the set up process and the map itself (complete with sidebar).

**Backend**

It was built using Node.js and MongoDB.

**Features:**

Regular Expression, there is no such thing as comprehensive UK postcode regular expression that is capable of validating a postcode. Postcodes are arbitrarily complex and constantly changing. For instance, the outcode W1 does not, and may never, have every number between 1 and 99, for every postcode area.

Filtering, to filter different types of kilowatt outputs. I used mongoose documentation to achieve this feature.

Adding and removing favourite spots from the database was not easy, the default behaviour is to return the unaltered document.

I used the government API and Google Maps API to build a database of uniform data to serve to the Frontend.

MongoDB security which I found it has has the robust security capabilities that one would expect from a modern database.

**Frontend**

jQuery, HTML and Bootstrap.

I divided the client side into two js files:

Map Client : It communicates with the Google Maps API and manipulate the data. Features:

Object orientation to encapsulate related functions and variables.

MapOptions to customize the map

Info window, displays information about the spot including subscription, fee among others.

Markes, which I design using Photoshop.

User Client:

Modals to swiftly show information to users on the same page they are working on, thus improving the usability of Green Charge Spots site and decreasing unnecessary page reloads.

Custom HTTP header before send to specific request, that allows to get the token back and manipulates data.

It's also object oriented.

![alt text](http://i.imgur.com/aHhcUbf.png "Development Frontend")

![alt text](http://i.imgur.com/VjWl0vU.png "Development Backend")

![alt text](http://i.imgur.com/ksneDWv.png "Customising Google Maps")

![alt text](http://i.imgur.com/yr5kN7b.png "Once logged")

![alt text](http://i.imgur.com/pmO2Iu0.png "Info window")

![alt text](http://i.imgur.com/e9GPW9b.png "Make favourite")

![alt text](http://i.imgur.com/OgBsX8I.png "Favourite spots")

**Future implementations**

Charging info resource:

With so many new and technical terms relating to charge points, it can be a confusing topic; Providing an overview of the different networks, overview of charging and how to go about getting a charging point for home or work.
Support:

Making the decision to go electric requires some careful consideration; A section which covers the different technologies, practical issues to think about, the tax and grant benefits available and providing a list of electric vehicles available to buy now.
