---
layout: post
title: Caches! Caches! Caches for Everyone! - Week 3
---
After finishing my Collatz project I decided to try passing Sphere challenge. At first I decided to implement a more complex cache than the lazy cache that I had. I used Downing's method of getting the largest value of every thousand. I created a simple python program that would create the input file with the appropriate ranges, gave that to my Collatz program, got the output and parsed it with another python program into an array, and included that into my original Collatz program so that it would check the range of the problem and use the correct pre-calculated values to save time and simply calculate the edges of the problem. Everything went smoothly and it greatly improved the performance of my project, but I realized that if I did this with a stepping of thousands I would end up with an array of 1000 hardcoded values. Nothing looks less professional than a huge block of hardcoded values. So I went with wider ranges of 10,000s instead of 1000s which got reduced into 100 hardcoded values. This was a lot better than before, but sadly it failed Sphere and I had run out of time (It was already Thursday morning) after debugging and comparing my results with other outputs in the public test repo.

Right now my biggest problem is understanding Python’s tricks and under-the-hood functionalities. Since I have deep understanding of how C and C++ work, I can easily increase the performance and stability of my programs but Python is a new language for me so I have to look into that. I’ll have to read into Python blogs, books, and the resources Downing gives us on his website to improve my performance.
 


\- Javier

#####Tip of the week:
By now the Google Doc has a ton of useful information, but most of it goes hand-in-hand with Downings explainations so it is important to take notes of what he says and reference that to the online code (the Google doc is not enough to skip class!)
