# LittlePiano
JavaScript Piano
This is my first JavaScript Project. Spent 10 days, iterated 2 versions
I code this project for my daughter. She has a real little piano but doesn't interesting in it. So I try to arouse her interest. And it worked.
I'm a UI designer and I like coding, But I'm a freshman in Javascript. I know little HTML and CSS Before this project. I think this project is a great opportunity to learn some new skills.
I dreamed one day I can coding some interesting things.

Below are some troubles in my coding process and What I use.

1. Sound files

A good sound file is very important, I spent 1 day to find it.
I want the piano to sound real.

2. Sound library -- Howler.js

I try to use the HTML default Audio element to deal with sound files, But always have problems even if not too many files.
I get to know that sound files need to be dealt with by an Audio System from my friend, So I get the Howler.js from a Youtuber introduce.
https://www.youtube.com/watch?v=hn7MhPt24L4

3. Determines device type whether a mobile -- mobile-detect.js

I want this project to run on different devices including mobile and PC. 
So I need a program to determine the device type. It can use a keyboard and mouse on a PC and touch on a Mobile.
It is so difficult for me to code this function. So the mobile-detect.js help me to solve this problem easier.

4. How to onkeydown and mousedown fire once in JavaScript

Solving this problem spent about 3 days.
When I press the keyboard and mouse unreleased to activate the play sound function, it always continued, so the sound will play again and again in a short time. 
I get a lot of solutions from Stack overflow, But I can't understand those coding.
I can understand this one, and it works. it use function（!e.repeat）
https://stackoverflow.com/questions/5353254/javascript-onkeydown-event-fire-only-once

5. How to get Element by mouse or touch

If using Mobile device we must use touch to active functions. 
But I don't know how to get Element by mouse or touch to activite correspondence sound.
There is a function (event.target) to solve this problem

I hope this project can help some freshmen who like me, like coding but do not know a lot.

This project still has a lots of bugs. But I tried my best :）
and I will update a more perfect version if I have the ability.

Hope you like it!
