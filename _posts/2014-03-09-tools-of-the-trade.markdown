---
layout: post
title: "Tools of the Trade"
categories: CodeSchool
status: publish
type: post
published: true
author: "Andy von Dohren"
---

People have asked me what programs we are using in class. At its core, a website is a collection of text files, so you don't need much. I remember using Microsoft Notepad to create my first website. At Omaha Code School(OCS) we use a program called TextMate. It is a text editor specifically designed for development.

[caption id="attachment\_202" align="alignright" width="150"] [![TextMate 2 Logo](http://andycodes.files.wordpress.com/2014/03/textmate.png?w=150)](http://andycodes.files.wordpress.com/2014/03/textmate.png) TextMate Logo[/caption]

At first, TextMate and I were not friends. I think it was more to do with my unfamiliarity with my new MacBook then the program itself. I was having a problem remembering menus and shortcut keys. As time passed, I started to see the power of using this program. Specifically, built-in GIT and code bundles.

At OCS we upload all our code to a service called GitHub. This forces us to save and commit our code frequently, and makes backups of what we are working on. TextMate is aware that we use GitHub and shows us the current status of each file. It's really helpful when I make a mistake and need to roll my project back to my previous commit.

The feature that separates out TextMate from the other text editors I've used is code bundles. Bundles are small pieces of code that you can insert into your code. It doesn't sound major at first, but it could eliminate almost all my stupid human syntax errors.

To use a bundle you select Bundles -> Select Bundle Item, or use the keyboard shortcut ^ + ⌘ + T. This will show you the bundle search window. TextMate is aware of the type of file you are working on and will only show you the applicable code bundles. Once you find the bundle you need you can then import it into your file.

[caption id="attachment\_203" align="aligncenter" width="490"] [![TextMate bundle search window](http://andycodes.files.wordpress.com/2014/03/screen-shot-2014-03-09-at-5-51-39-pm.png?w=490)](http://andycodes.files.wordpress.com/2014/03/screen-shot-2014-03-09-at-5-51-39-pm.png) TextMate bundle search window[/caption]

Ruby requires that almost everything we do be a member of a class. To create a class, there are about 10 lines of code that are almost identical. Using a bundle, all you need to type is the following:   ^⌘T + "class" + return

[caption id="" align="aligncenter" width="500"] [![TextMate Class Bundle](http://andycodes.files.wordpress.com/2014/03/screen-shot-2014-03-09-at-5-35-11-pm.png?w=300 "TextMateClassBundle")](http://andycodes.files.wordpress.com/2014/03/screen-shot-2014-03-09-at-5-35-11-pm.png) TextMate after inserting a Ruby Class bundle.[/caption]

If you look closely, the class name is highlighted. TextMate bundles know which keywords need to be modified. You can type a value and then press TAB to move to the next field. This allows you to update everything you need without having to use your mouse or arrow keys to move around. It doesn't seem important at first, but after using it to create a couple of objects I know I will be using it a lot.

The built in bundles are helpful, but I have already found that I have a slightly different style. Fortunately, TextMate has a built in bundle editor. I'm the first to admit that I don't fully understand what is going on in the editor. I can make my way around enough to add another line or change the style a little bit, but that is about it. As I continue to learn about formatting and syntax I'm sure I'll start to understand more.

I know I'll be using these features a lot, hopefully you will too.

