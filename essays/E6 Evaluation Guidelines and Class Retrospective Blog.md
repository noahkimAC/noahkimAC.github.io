---
layout: essay
type: essay
title: E6 Evaluation Guidelines and Class Retrospective Blog
date: 2021-05-14
labels: Assignment3, Shopping Cart, Edit/ Update Cart, nodemailer, Product Pages 
---

## Briefly describe your system (e.g. A store selling Pokemon game cards)
My website, Noah's Mac Shack, was a online "Apple Authorized Retailer" that sold only M1 and H1 chipped devices as well as accessories for these devices. I offer 4 different product categories: Laptops, Desktops, Airpods, and Externals which have different M1 and H1 devices at various price ranges and features. 

The reason: My previous laptop broke over Winter Break (2020) and going into ITM 352, I knew I needed a better system so I bought a Mac mini M1 and got a replacement MacBook Pro M1. These devices were not my first choice because I wanted to build a PC but the M1 devices were so good to me that I wanted to make shopping for systems as easy as it could have been for me. 

## Any notable shortcomings, bugs, problems, or additional features not implemented?
One regrettable problem was that I could not figure out how to make my Shopping Cart (in the navbar) properly do the count, where users can see how many items are in their cart. It is functional and working but for example, if I have 1 quantity of Product A and Product B each, the Shopping Cart status feature would say 11 instead of 2, because it combines the numerical value instead of adding them.

Other than that, everything else was seamless and highly functional!

## Describe what you are most proud of about your system:
I am very proud of how easy and user-friendly it is. It identifies the user multiple times, reminds the user for invalid quantities, and all the buttons are configured so that the user can simply press the enter key to activate the button instead of scrolling down and physically clicking the button. 

To be specific, I love my Login/ Logout button which is a singular button that says "Login (Not logged in)" when the user is not logged in vs. "Logout ____" when they are logged in. It greets the user and personalizes their experience, the same is done with the invoice email as well as the checkout button that automatically directs the user to their next step by configuring the buttons similarly to my Login/ Logout button where the button name changes based on whether or not the user is logged in or not, or has a cookie or not. 

I'm proud of this because it not only personalizes the user's experience but it checks whether the user has a cookie and can function as a "status" bar to show the user's login status.

Most importantly, I was struggling with the nodemailer to send the invoice out to the user and recognizing the user in the alert message and completing that was definitely a proud moment.

## Describe what you are least happy with your system:
It would be just one thing which is how the Shopping Cart status doesn't reflect the quantities properly. As I mentioned before, it does "technically" show the user how many products are in the cart but not the way I would've preferred it to. 

## How was developing this assignment different than assignment #2?
It was different as I could no longer generalize solutions because everyone's systems were different so it was harder to ask my classmates for help but Kimberly Matutina and Nicholas Samson were undoubtedly the biggest help to me along with Professor Port.

I had to really understand my code and Professor Port had to remind me to know exactly what I am putting in as I was guilty of trying to copy whatever I saw on Stack Overflow and would often forget how my own system worked as well as what I called previous variables and etc. 

## When you ran into a problem, what did you do to address it?
I found myself automatically checking my terminal and the browser console. If I saw an error, I would go to where the error was located and attempt to triage it. If the error wasn't clearly defined and nothing would post, I would comment out the general area of the code and work through it. If it posted but wasn't the output I wanted, then I would thoroughly go through my files. 

## Describe what worked well in doing this assignment?
Confidence and real-time improvement worked really well as I was able to move on from errors or find alternative solutions faster than before. 

## Describe what did not work well in doing this assignment?
A big part of my issues for this last Assignment was that I didn't really take time to understand my code and it bit me in the butt because I was so lost IN MY OWN CODE. So studying and understanding why I put certain code where was definitely what didn't work well. 

## What did you learn from doing this assignment?
I learned it is always best to have a general understanding of concepts or know where you are at/ want with your final product before asking for help. I would go to office sessions with no clue of what I wanted in my final product and this caused more than half of my problems. I needed to study and know what exactly I was trying to do or the code I wrote would just be useless and more of a hinderance than productive. 

## If you could go back in time and do things differently, what would you change?
I would cut unneccessary code because so much zombie code was present and this really complicated and took up extra space in my files. I believe organization IN MY CODE is definitely what I would have worked on. Being organized with due dates and other things are important but being organized with your code will definitely ease things up for you. 

## Estimate the % of time you spent (a) thinking about how to do something, (b) writing code (but do not include testing, (c) testing and debugging
I spent about 40% of my time thinking about how to do my Assignment 3, 40$ writing code and 20% testing. Testing was only 20% because I spent so much time thinking about how I wanted my final Assignment 3 and how it should turn out that I was able to be efficient in testing because I knew exactly what I was testing/ debugging for. 

## Assign an estimated percentage on the amount each team member contributed to the assignment (including yourself) and explain briefly your rationale for the percentage breakdown. Be sure to include an overview of what specifically you and your partners contributed (e.g. “I worked on the security and my partner 1 worked on personalization”)
I worked by myself so 100% me but I would like to give a tremendous thanks to Kimberly and Nick for sitting down with me and really helping me out!
