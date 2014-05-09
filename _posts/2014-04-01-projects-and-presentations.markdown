---
layout: post
title: "Projects and Presentations"
categories: CodeSchool
status: publish
type: post
published: true
author: "Andy von Dohren"
---

Last week we spent the majority of our time working on our first big group project. It was pretty open-ended, so we could come up with anything we wanted to do. I teamed up with Matt and Cara. After some brainstorming, we came up with the idea of creating a Omaha Code School Wiki. We could create pages about each of the classmates, teachers, projects, and topics we are covering in class.

[caption id="261" align="alignright" width="300"] [![Omaha Code School Wiki](http://andycodes.files.wordpress.com/2014/04/screen-shot-2014-04-01-at-7-53-19-am.png?w=300)](http://andycodes.files.wordpress.com/2014/04/screen-shot-2014-04-01-at-7-53-19-am.png) Omaha Code School Wiki[/caption]

On Monday, we pitched the idea to the rest of the class. That's when we realized just how unprepared we were. Compared to the other groups, we were behind. The other groups had detailed wireframes for each page, and a flow already figured out. As soon as we got back into our groups we tried to catch up. Cara has a design background, so she volunteered to handle the front end development. Matt and I would handle the backend.

One problem I knew we had to solve was the actual content of an article. When we started, all we knew how to do was collect very plain text from a user through a form. This wasn't going to look good when another user wanted to read it. It wouldn't have any headings or organization, so I needed to find a better way. One idea was to copy what we do on GitHub readme pages. For our project, we create a readme page that describes what the project does and why that matters. We edit the page in a syntax called Markdown. It allows you to use a common syntax that then gets rendered into formatted HTML when someone else views the page. After some digging, I found exactly what I needed. Turns out GitHub uses a GEM called [RedCarpet](https://github.com/vmg/redcarpet) to render markdown on their site, and we could use RedCarpet too. After some reading and a little trial and error, I got it working. Now if you view one of the pages, it can have organization, links, images, and is much more readable than plain text.

We also used a GEM called [FriendlyID](https://github.com/norman/friendly_id). The URL in the browser is very important in Ruby on Rails. Developers use it to pass information from one page to another. Most of the time, the information is pretty cryptic to the user, maybe just a random number. FriendlyID changes the numeric ID for an object into a readable string. Here is an example:

> Twitter could have used ID's...  
> www.twitter.com/509309843
> 
> Instead, they wanted it to be usable, so they used handles...  
> www.twitter.com/andyvondohren

This is exactly what FriendlyID does. It converts an ID in the URL into a username or title, and makes it much easier to understand. Once you get it setup, it's really easy to use. Check it out.

We wrapped up our time on Friday and presented our product to the class. It was really cool to see what everybody had been working on for the last five days. Everyone got theirs working and had all of the functionality they set out to accomplish. Some of the other projects included...

- Flipbook (Upload pics through Instagram and automatically create a flip book animation)
- The Nag (To do application that nags you if you do not complete your tasks on time)
- Work Hang (Checkin at your favorite remote working location, others can see where you are and come work with you)

We are pretty proud of our projects, and our group is even working on it some this week to get some of the rough edges taken care of. Hopefully I will be able to send a link out to the live program later this week so you can take a look yourself.

