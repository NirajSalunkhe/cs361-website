---
title: homework 2
layout: default
tag: hw2-submission
dir: hw2
due: Monday, September 30, at 11:59 PM
due_event: 
    type: due
    date: 2020-09-30T23:59:00-5:00
    description: 'Assignment #2 due'
date: 2020-09-03
---

### {{ page.title }}: Inspecting Running Processes



####  The Challenge!

In the last homework you looked at the symbol table of your own compiled program. This time we'll be watching and interacting with precompiled programs as they execute.

Before you start, please make sure to log in `systems[1-4].cs.uic.edu` (e.g. systems1, systems2, etc.).

The skeleton code for this assignment is available at [this link](https://classroom.github.com/a/WDM3q5i5). You must use GitHub classroom to write your code and keep a commit log on GitHub. You will submit your files via [Gradescope](https://www.gradescope.com/).

Your task will be to fill out two files in your personal repository called `secrets.txt` and `howto.txt`. 

The format for `secrets.txt` should be:

{% highlight text %}
0. these  
1. are  
2. not  
3. real  
4. secrets  
{% endhighlight %}

`howto.txt` is also **required**: you must describe in English how to find the secret for that given executable. Each individual howto should be on one more more lines after a line with only the executable number and a period on it, like so:

{% highlight text %}
0.  
This was the really easy one. You had to run it and then type in the secret of life.  
1.  
For this one, I had to:  
* Run a specific unix utility to learn some specific information  
* Perform some specific task that I found out about by checking part of a specific line in the output of the unix utility.  
...
{% endhighlight %}

Your `howto.txt` should enable any other CS 361 student to find the password within a minute of reading it.

### Warning

You must complete this assignment on `systems[1-4].cs.uic.edu`. Failure to do so will result in a zero.

You will not be given any other files to complete secret findings except the 5 executable files.

#### Hints:

Open your `howto.txt` alongside your shell as you work on each executable file, and use it to take notes. If you don't give a full description of how to arrive at the answer, you may not receive points. 

The content of lab section will be incredibly helpful for this assignment. If you miss it, ask someone that went if they're willing to share their notes with you.

#### Template 

The executable files are available in the classroom repository and can be accessed using the link above.

### Turn-in instructions and Grading

Both `secrets.txt` and `howto.txt` **must be submitted to Gradescope via GitHub**. While grading `secrets.txt` will be done automatically, the `howto.txt` will be graded by hand. You should have both files in your submission. If you do not fill `secrets.txt` out exactly as directed, autograding will fail. If you do not complete your assignment on any of `systems[1-4].cs.uic.edu` machines, autograder may fail. If you have issues with the autograder, please contact us via Piazza ASAP. **Technical issues within 36 hours of the deadline will not be an excuse for submitting the assignment improperly or late.**

The first 4 are each worth 1 point each, the final one is worth 4 points. An additional 2 points will be given for correct howtos.

### Due Date
This assignment is due {{ page.due }}. See the [syllabus](syllabus.html) for the late turnin policy. This assignment is worth just as much as every other homework, so getting as much credit on it as possible is important (don't turn it in late!).