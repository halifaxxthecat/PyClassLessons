
### PyClass 13-week Course

Monday May 18, we will start a new cycle of PyClass.

WHO
===

If you are new to Python and want to get a jumpstart, this is a great opportunity. We are 
starting a little bit further back, although a basic knowledge of Python or programming in some language is necessary.

The course is free although we recommend a donation to Noisebridge.
Donations go to: [https://www.noisebridge.net/wiki/Donate_or_Pay_Dues](https://www.noisebridge.net/wiki/Donate_or_Pay_Dues)
Recommended Donations: $15, $50, $200+
Recommended monthly donations: $10, $20, $40, $80+ / month

This is a lower-to-higher intermediate Python class. Each course starts easy and becomes more technical as we head further into the lecture. Significant time is spent integrating with general technologies: sqlite, regular expressions, flask, json, virtualenv, unit tests, and logging are all on the syllabus, along with more python-specific topics.

COURSE LAYOUT
=============

The pattern of these courses will be a little bit different, we will do a talk every Monday with key examples. Thursday, project night, will be spent building a project using the technology. Both are important if you wish to fully understand and apply each topic.

Courses are (with the exception of the final 3 weeks) modular, and with sufficient understanding of Python you can miss a week and still follow the next week.  

The first two courses are very important to understanding the rest of the class.

The course takes place from 7 PM to 9 PM on Mondays and Thursdays. Some folks arrive early to clean up the room and answer questions.  We sometimes stay late to work on technical questions that come up during the lectures.

More information can be found at:
[https://noisebridge.net/wiki/Pyclass](https://noisebridge.net/wiki/Pyclass)

All course materials are available on our github repository: [https://github.com/PyClass/PyClassLessons](https://github.com/PyClass/PyClassLessons)

WHERE AND WHEN
==============
Monday - Turing Classroom - 7 PM to 9 PM
Thursday - Church Classroom - 7 PM to 9 PM

We recommend folks arrive at 645 PM to ask/answer questions, settle down, and clean up the room a bit before we start class.


SYLLABUS
========
1 JSON and Data Containers
2 Keywords and Control Flow
3 Virtualenv and 3rd Party Modules
4 Pythonic Workflow, functions, generators, duck typing
5 Introspection: pdb, help, dir, inspect, timeit, error handling 
6 SQLite3
7 OOP - overview/sample project
8 Tests - 'unittest' module
9 Regular Expressions
10 Logging
11 Flask - Introduction and Project Template
12 Flask - A First Webapp - Part 1
13 Flask - A First Webapp - Part 2



### PSAs and Events

**PSA 4-6-15:** As of today, attend PyClass on MONDAY and THURSDAY.  Monday in the Turing classroom will replace the Tuesday session.

**PSA 1-26-15:** Thursday in the Church Classroom will replace the Wednesday session.

**PSA 10-1-14:** PyClass starts at 7:00 PM, try to come a few minutes earlier. We want to finish up by nine so people can hack or catch their preferred train home.  You can come at any time, but YMMV (your mileage may vary).

**PSA 8-19-14:** The [noisebridge wiki](https://noisebridge.net/wiki/PyClass) and [github readme](https://github.com/PyClass/PyClass-lesson-plans) files have the same information and updates.

**PSA 8-16-14:** The new curriculum for the Noisebridge PyClass is a crash course in the Python standard library, also touching on modules that are popular but not quite part of the standard modules. Scroll down to see the course list.

### Scheduled Weekly Meeting Times

We set up the space at 6:45 PM - try to arrive early to help if you are able to.

* Monday 7:00 - 9:00 PM PST - 'Turing' Classroom
* Thursday 7:00 - 9:00 PM PST - 'Church' Classroom

### Mailing List

Sign up for this to hear updates and conversations regarding the course!

[PyClass-Discussion](http://groups.google.com/group/pyclass)


### Class Description, Goals, and Ideal Student

The pace of the courses will be fast, and the materials will be available online 24/7. We plan to frequently repeat modules with new twists as we iterate over course materials.

A major PyClass goal is to break down the courses into independent units. In other words, you won't fall behind if you miss a week. Sounds good, right?

To best experience the course, spend a short time reviewing the course materials before you come in. If you wish to know this week's courses, please join the mailing list and send an email out to PyClass@googlegroups.com

Lessons are [available on Github](https://github.com/PyClass/PyClassLessons).


#####The 'ideal student' for this course can grasp the following code:

(Feel free to use web resources to look up anything you don't understand)

```python
letter_frequency_dict = {}
word = "noisebridge"
 
for letter in word:
    times = letter_frequency_dict.get(letter, 0)
    times += 1
    letter_frequency_dict[letter] = times
```


##### We use the [Socratic Method](http://www.criticalthinking.org/pages/socratic-teaching/606)
###### A Socratic questioner should 
1. keep the discussion focused
2. keep the discussion fact based\*
3. stimulate the discussion with probing questions
4. periodically summarize what has and what has not been dealt with and/or resolved
5. draw as many students as possible into the discussion.

\* [intellectually responsible](https://en.wikipedia.org/wiki/Intellectual_responsibility) can be effectively replaced with 'fact based' for our needs.

### New Student Reading

If you are new to python or programming in general here are some excellent resources:    
-[Learn Python the Hardway](http://learnpythonthehardway.org/) - great guide for total beginner    
-[Byte of Python](http://www.swaroopch.com/notes/python/) - nice guide for total beginner and new to python    
-[Excellent Official Python Tutorial - 2.7.8](https://docs.python.org/2/tutorial/) - great for new to python    
-[Learning Python 5th edition (also at sf lib)](http://shop.oreilly.com/product/0636920028154.do) - A comprehensive guide to the language and its uses    
-[Python Module of the Week](http://pymotw.com/2/) - Learning the standard library by example    
-[The docs themselves! 2.x for this class](https://www.python.org/doc/) - Learn what is and how to use the standard library

There are many, many good resources for learning the language of Python and how to do awesome things with it.
Those listed above are just a few based on personal experience and strong recommendations.  


###  OS / Environment / Versions

This section is under development.

[Digital Ocean $10 Credit](https://www.digitalocean.com/?refcode=1a1061eaf303)

[Amazon's AWS has a free tier that allows you 750 compute hours every month of their t2.micro instances for 12 months](http://aws.amazon.com/free/)

-Use EC2 to create an instance from the Ubuntu 12.04 AMI  for the most well known and supported platform that will come with Python 2 installed


For the sake of our sanity we use Python 2 for this course.

Installing Python with [The Hitchhiker’s Guide to Python!](http://docs.python-guide.org/en/latest/)

Emergency Python Command Line: [http://repl.it/languages/Python](http://repl.it/languages/Python)


**We accept refugees using all operating systems. You will be politely prodded in the direction of solutions that are closer to posix standards: [http://en.wikipedia.org/wiki/POSIX#Mostly_POSIX-compliant](http://en.wikipedia.org/wiki/POSIX#Mostly_POSIX-compliant)**


Some routes:    
1. Install a linux virtual machine on another computer using virtualbox.    
2. Use the command line in your apple machine.    
3. Explore POSIX for windows: http://en.wikipedia.org/wiki/POSIX#POSIX_for_Windows    
    

Another critical tool is git:    
*Windows: http://git-scm.com/download/win    
*Mac: http://git-scm.com/download/mac    
*Linux: (use your package manager)    

