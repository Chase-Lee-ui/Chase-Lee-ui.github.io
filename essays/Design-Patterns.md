---
layout: essay
type: essay
title: Design of Art and Art of Design
# All dates must be YYYY-MM-DD format! Changed this
date: 2021-04-29
labels:
  - Meteor
  - JSX
  - MongoDB
---

<img class="ui medium right floated rounded image" src="../images/flowchart2.png">

In some of my past times I like to use a program called Paint Tool Sai to semi-professionally make pieces of art for me and my friend, it makes it nice and easy in that it has layer
control, filters, color mixing, different kinds of brushes, and a stablizier but those are just there to allow me to make my work more easily. But there is always a process I have
to go through when making a piece of work which is the sketch into lineart into colors and shading. My process in creating a piece of art is similar to that of 

## The Publisher and the Subscriber
In Paint Tool Sai a user can toggle between layers, allowing them to be shown or not shown depending on whether or not a button has been toggled. A simple full image can be broken
into two different parts, one of them being the color, one of them being the line art. If one is toggled without the other then the image might look weird and not right, this
is why all information should be passed together. This helps explain the relationship between publisher and subscriber and the purpose of this idea in my team's project. So
the publisher in this metaphor would be the actual art, whether it be color or the line art, this would be the information that would need to be passed whether or not the visible
toggle has been made. The visible toggle will be whether the current user is subscribed to it, if it is toggled on then it is subscribed and vice versa.

In my team's project we utilize this idea in that we may need to utilize several organizations that are published in the mongoDB. There are some cases in the project where we need
to subscribe to several organizations such as profiles which hold the information holding personal information of a user, and we may need to subscribe to items which are the items
that are being sold on our website. We need both of them to create a completed picture, one without the other gives a good idea, but it does not completely show what is needed for a
user.

## Commissions and MVC
When being commissioned, an artist is being commissioned for a piece of work, they need to take in information from the client and form that they can produce the work.
This will be analagous to the Model-View-Controller, where the model acts as the artist, the view acts as the piece of work and the controller acts as the client. As a user
navigates through a site they need to press buttons, in this analogy it would be the client requesting for something an artist to do. The artist then provides the piece of
art per the client's request, this would be the view as this is what the client now sees. This can keep going in a cycle as the client makes more requests or makes a request for
an edit.

This relates to my own group project where me and my team collaborate to plan out what we need, so we will be the clients in this situation. However, we will also be the artists
that perform their work in the form of code, we will create a site that a user can navigate, and the site that we and other users will see will be the piece of art. An MVC cycle
is a good way for a site to navigate through different sections of a porject as it works in a methodical way.

