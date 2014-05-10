---
layout: page
title: Projects
permalink: /projects/
---

Here are some of the projects I have helped to create during Omaha Code School.

###SMAC! Angels
---
SMAC! (Sock Monkeys Against Cancer) was founded by Jen Windrum after her mother, Leslie, was diagnosed with stage IV lung cancer in 2007. Leslie lived 2,000 miles away from Jen, and she wanted to give her something that could always be by her side. She came up with Sock Monkey's against cancer.

Our team project was to create a new site that would match people who had or were affected by cancer, but could not afford a SMAC! monkey with someone who would be willing to cover the cost, we called them angels.

There were seven people on our project team. I was designated as the Technical Lead/Project Manager for this project. Johnathan, Todd, Matt, and Lochlan were backend developers. Britt and Yofred designed our front end.

![SMAC! Cancer Website]({{ site.baseurl }}/assets/SMACAngel.png)

We used Ruby on Rails to create the site. Some useful GEMS we used were:

* Foundation Grid System
* Sorcery (User Login/Forgot Password)
* Negative CAPTCHA (User Verification)
* CarrierWave

Here is a [link to our staging site](http://smac-angels-staging.herokuapp.com). We hope to lauch soon.

<a href="https://github.com/omahacodeschool/smac_angels">
  <span class="icon github">
    <svg version="1.1" class="github-icon-svg2" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
       viewBox="0 0 16 16" enable-background="new 0 0 16 16" xml:space="preserve">
      <path fill-rule="evenodd" clip-rule="evenodd" fill="#C2C2C2" d="M7.999,0.431c-4.285,0-7.76,3.474-7.76,7.761
      c0,3.428,2.223,6.337,5.307,7.363c0.388,0.071,0.53-0.168,0.53-0.374c0-0.184-0.007-0.672-0.01-1.32
      c-2.159,0.469-2.614-1.04-2.614-1.04c-0.353-0.896-0.862-1.135-0.862-1.135c-0.705-0.481,0.053-0.472,0.053-0.472
      c0.779,0.055,1.189,0.8,1.189,0.8c0.692,1.186,1.816,0.843,2.258,0.645c0.071-0.502,0.271-0.843,0.493-1.037
      C4.86,11.425,3.049,10.76,3.049,7.786c0-0.847,0.302-1.54,0.799-2.082C3.768,5.507,3.501,4.718,3.924,3.65
      c0,0,0.652-0.209,2.134,0.796C6.677,4.273,7.34,4.187,8,4.184c0.659,0.003,1.323,0.089,1.943,0.261
      c1.482-1.004,2.132-0.796,2.132-0.796c0.423,1.068,0.157,1.857,0.077,2.054c0.497,0.542,0.798,1.235,0.798,2.082
      c0,2.981-1.814,3.637-3.543,3.829c0.279,0.24,0.527,0.713,0.527,1.437c0,1.037-0.01,1.874-0.01,2.129
      c0,0.208,0.14,0.449,0.534,0.373c3.081-1.028,5.302-3.935,5.302-7.362C15.76,3.906,12.285,0.431,7.999,0.431z"/>
    </svg>
  </span>
  <span class="username">github.com/omahacodeschool/smac_angels</span>
</a>

###Acts2 Kids Checkin
---
My chruch needed a system to help check in kids to sunday school events. The system needed to track attendance and print out name tags for the kids to wear.

Luckily, my wife is in charge of the children's program, so I had the opportunity to get feedback from her early in the process.

From the user perspective, all you have to do is type in your phone number. A list of kids that belong to that family will appear. You select the children that are present, and click *checkin*.

At this point a Dymo label printer attached to the client computer will print our a name tag for each child onto a standard shipping label. The child wears the name tag for the duration of the event.

This was our individual project, so I was responsible for the backend and frontend design.

![Acts2 Kidz Checkin Website]({{ site.baseurl }}/assets/a2kidz.png)

Here are a couple of concepts that really helped me out:

* Consistency Fail / LOL DBA (proper database indexing)
* Defined Scope (Simplify and Reuse complex database queries)
* Dymo Print Libraries (JavaScript libraries for web printing)

Here is a [link to my DEMO site](http://a2-checkin-demo.herokuapp.com). Once you sign in, it walks you through a simple demonstration of how to use the application.

<a href="https://github.com/avondohren/A2-Checkin">
  <span class="icon github">
    <svg version="1.1" class="github-icon-svg2" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
       viewBox="0 0 16 16" enable-background="new 0 0 16 16" xml:space="preserve">
      <path fill-rule="evenodd" clip-rule="evenodd" fill="#C2C2C2" d="M7.999,0.431c-4.285,0-7.76,3.474-7.76,7.761
      c0,3.428,2.223,6.337,5.307,7.363c0.388,0.071,0.53-0.168,0.53-0.374c0-0.184-0.007-0.672-0.01-1.32
      c-2.159,0.469-2.614-1.04-2.614-1.04c-0.353-0.896-0.862-1.135-0.862-1.135c-0.705-0.481,0.053-0.472,0.053-0.472
      c0.779,0.055,1.189,0.8,1.189,0.8c0.692,1.186,1.816,0.843,2.258,0.645c0.071-0.502,0.271-0.843,0.493-1.037
      C4.86,11.425,3.049,10.76,3.049,7.786c0-0.847,0.302-1.54,0.799-2.082C3.768,5.507,3.501,4.718,3.924,3.65
      c0,0,0.652-0.209,2.134,0.796C6.677,4.273,7.34,4.187,8,4.184c0.659,0.003,1.323,0.089,1.943,0.261
      c1.482-1.004,2.132-0.796,2.132-0.796c0.423,1.068,0.157,1.857,0.077,2.054c0.497,0.542,0.798,1.235,0.798,2.082
      c0,2.981-1.814,3.637-3.543,3.829c0.279,0.24,0.527,0.713,0.527,1.437c0,1.037-0.01,1.874-0.01,2.129
      c0,0.208,0.14,0.449,0.534,0.373c3.081-1.028,5.302-3.935,5.302-7.362C15.76,3.906,12.285,0.431,7.999,0.431z"/>
    </svg>
  </span>
  <span class="username">github.com/avondohren/A2-Checkin</span>
</a>

###Omaha Code School Wiki
---
For our first group project, Matt, Kara, and I decided to make a wiki about Omaha Code School.

We wanted it to be user curated and able to show links and images. In order to facilitate those features, along with improving formatting overall, we decided to have users type up their articles using **Markdown**. Markdown is a shorthand way of formatting text so that it can be typed in plain text, and displayed later. We used a GEM called Red Carpet to help us with the formatting.

![Omaha Code School Wiki]({{ site.baseurl }}/assets/OCSWiki.png)

We also wanted to give our Admins some additional features, including:

* Ability to revoke a user's account
* Ability to freeze an article (If two users are fighting over the content)
* Ability to *roll-back* the contents of an article to a previous state

We also wanted to make sure real users were the only ones using the system, so we send an activation email to the user upon setup. They cannot create or modify any content on the site until they click on the link in the email.

Here is a [link to our site](http://project-ocs-wiki.herokuapp.com). Feel free to look around or create a new page.

<a href="https://github.com/avondohren/project-ocs-wiki">
  <span class="icon github">
    <svg version="1.1" class="github-icon-svg2" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
       viewBox="0 0 16 16" enable-background="new 0 0 16 16" xml:space="preserve">
      <path fill-rule="evenodd" clip-rule="evenodd" fill="#C2C2C2" d="M7.999,0.431c-4.285,0-7.76,3.474-7.76,7.761
      c0,3.428,2.223,6.337,5.307,7.363c0.388,0.071,0.53-0.168,0.53-0.374c0-0.184-0.007-0.672-0.01-1.32
      c-2.159,0.469-2.614-1.04-2.614-1.04c-0.353-0.896-0.862-1.135-0.862-1.135c-0.705-0.481,0.053-0.472,0.053-0.472
      c0.779,0.055,1.189,0.8,1.189,0.8c0.692,1.186,1.816,0.843,2.258,0.645c0.071-0.502,0.271-0.843,0.493-1.037
      C4.86,11.425,3.049,10.76,3.049,7.786c0-0.847,0.302-1.54,0.799-2.082C3.768,5.507,3.501,4.718,3.924,3.65
      c0,0,0.652-0.209,2.134,0.796C6.677,4.273,7.34,4.187,8,4.184c0.659,0.003,1.323,0.089,1.943,0.261
      c1.482-1.004,2.132-0.796,2.132-0.796c0.423,1.068,0.157,1.857,0.077,2.054c0.497,0.542,0.798,1.235,0.798,2.082
      c0,2.981-1.814,3.637-3.543,3.829c0.279,0.24,0.527,0.713,0.527,1.437c0,1.037-0.01,1.874-0.01,2.129
      c0,0.208,0.14,0.449,0.534,0.373c3.081-1.028,5.302-3.935,5.302-7.362C15.76,3.906,12.285,0.431,7.999,0.431z"/>
    </svg>
  </span>
  <span class="username">github.com/avondohren/project-ocs-wiki</span>
</a>

