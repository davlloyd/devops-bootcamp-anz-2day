Cloud DevOps Immersion
----------------------

#Purpose:
Most technical professionals, especially presales engineers within EMC express a strong preference for lab (and even better, real hands on) work over slide training.  This is even more critical when learning about methologies (ITIL, etc) as compared to specific technologies.

The intent of this course is to use an immersive method to give an introduction to modern methodologies and tools in use at today's 3rd platform and web-scale startups and incubators.

##Target Areas of Education
Participants of this course can expect to come away with basic hands on experience in:

* Agile methodology
* Distributed, public source code management
* PaaS and Cloud Foundry application deployment
* DevOps management methods and ideas
* Basic application management/infra tools (Docker, cf, New Relic, object storage, etc)

After having completed this course, any participant should be able to comfortably speak with any customer using these tools and methods without feeling underwater, and will be able to express some level of familiarity with the procedures and challenges posed by modern deployment and management methods.

##Requirements
Participants should:

* Be able to commit fully to the program, for the entire duration with at least 75% of their time each day.  This is a critical, hard requirement to experience the course material as designed.
* Have a basic understanding of virtualization, database, systems and storage concepts at a 101 level (Any EMC SE beyond Associate should be at this level).
* Be able to *read* (writing not required) very basic code in at least one language.  For example, be able to understand [whats happening in the following Task in at least one language at Rosetta Code](http://rosettacode.org/wiki/Read_a_file_line_by_line). This course is not focused on significant development, but some basic familiarity is important.  Much of the code we will be reviewing will be written in Python, so if you want to get familiar, that would be a good place to start: [Python @ CodeAcademy](http://www.codecademy.com/en/tracks/python) - everything up until the "Advanced Python" section will be useful.
* *Hardware/Software*
 - One of the following combos:
   - MacOS (10.9+)
   - Windows 7+ *and* a Linux VM (either with as a local VM, or on Amazon or Digital Ocean or something).  Note: you could use Vagrant to do this easily :).
  - A webcam that works with Google Hangouts.  If you have a Mac with builtin webcam, thats fine.  If not, buy one and expense it.

* *Command Line*
 - [Linux/Unix Command Line](https://www.udemy.com/linux-command-line-volume1/).  You should understand how to move around on a Linux command line.

* *Tools*

 - [Git](https://help.github.com/articles/set-up-git/): Install it from homebrew or github - doesn't matter.  Make sure you install Git 2.x or above.   You also need to[ setup a github account.](https://github.com/join)
 - [CloudFoundry CLI](http://docs.cloudfoundry.org/devguide/installcf/) - install it from CloudFoundry.org or homebrew.
 - [Slack](http://slack.com) - we'll invite you.
 - [Trello](http://trello.com) - sign up for an account.
 - [Google Hangouts](http://hangouts.google.com) - make sure you have a working Google account and that you can join Hangouts.
 - [Python 2.7](https://www.python.org/downloads/release/python-2710/) - preinstalled on MacOS and your Linux VM.

* *Required reading*

 - [The Twelve-Factor App](http://12factor.net/) (all the in depth pages, not just the home page)

* *Recommended reading*

 - [The Phoenix Project](http://www.amazon.com/The-Phoenix-Project-Helping-Business/dp/0988262592)
 - [The Goal](http://www.amazon.com/The-Goal-Process-Ongoing-Improvement/dp/0884271951)

##Basic Course Overview

A basic outline of the course follows, on a day-by-day basis.  Throughout the course the proctor/instructor will participate both as a team member completing work as well as mentor for individual tasks (writing code if needed, etc), as well as guiding based on Agile principles.

####Day 1:
* Get working with the [tools] in use
* 12 Factor Apps
* Basic tutorial on GitHub / Source Code Management
* Discuss basic Agile methodology and how to apply it
* Do first Sprint Planning for team project, including story pointing.
* Basic tutorial on CF concepts and provisioned services.

####Day 2:
* Daily standup


# Presenter Note
The Index.html file uses the remark.js (https://github.com/gnab/remark) tools to enable a browser based markdown (MD) file presenter. This is supported on a local machine if using Firefox but for other browswers you need to run it through a web service to address file access security issues. An easy way to address this is to run the python http server in the local directory *'python -m http.server'* and then browse to the page via port 5000 (i.e. http://localhost:5000)
