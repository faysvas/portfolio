---
published: false
layout: post
date: "2016-2-10 3:24"
tags: 
  - blog template
---



##Semantic HTML5  
When I started making the template I dived straight into designing. Now I'll take a closer looks at the `html5` semantics.  

A blog without semantic `html5` markup is just a bunch of disorderly divs. Semantic markup helps you make some sense out of all that information and is especially important when making a blog template because it helps with refactoring and editing. Plus, it's just so much more pleasurable to read.  [Designing a blog with html5](http://html5doctor.com/designing-a-blog-with-html5/) has some nice tips on how to improve your markup. I'll keep the containers and rows as divs for now because I think it's better to keep a basic outer grid.  

##Typography   
The other part I'm going to focus on today is the template's typography. Typography is one of those sneaky things you can easily overlook when doing a design. Good typography is subtle and makes a blog satisfying to read while bad typography will make you feel that something is slightly off, but you just can't pinpoint what.   

When I first started designing (as a necessary part of developing), I never really payed attention to typography. I just chose a few fonts I liked and played around with sizes. I never grasped the impact of typography before delving deeper in the subject, and when I did I was fascinated by all the little details.    

Fascinating as they are, all those details are still too much for somebody who doesn't focus only on design. Luckily, I found the perfect guide for my project, an [Interactive Guide to Blog Typography](http://www.kaikkonendesign.fi/typography/#section/1). I'll follow each step and work on the design for large screens (I'll work on the smaller screen layout later). 
- Layout: I'll give each `article` and each `article h2` some extra `margin-bottom`.  
- Measure: The guide suggest 65 characters. I'm currently at 60 so I'll either just keep it or increase the font size a bit. 
- Line Height: Changing the `line-height` to `1.5em` made a huge difference. My paragraph text looks a lot more symmetric now. 
- Title: Using a smaller `line-height` for titles is crucial.(This step also reminded me to use a huge title in my test paragraphs). 
- Paragraph: I don't like indented paragraphs so I'll just keep to my normal ones, but I like the subtitle styles so I'll copy them. 
- Fonts: Aaah, the most dreadful part. Endless testing of various fonts to find one or two that fit. I wanted something that looked handwritten but when I tested it in body copy it looked tedious, so I chose a more "normal" `serif` font for paragraphs and a `sans-serif` font for headers. 
- Font size: I set `18px` as my base size and increased header sizes by 1.5 using [Modular Scale](http://www.modularscale.com/). 

I also want to ensure my design has consistent vertical rythym. My favourite tool for that is [basehold.it](http://basehold.it/). It helps you adjust the spacing and size of your page elements by overlaying your design with a grid, just by adding a line of code.
