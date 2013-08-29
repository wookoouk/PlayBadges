Merit
============

Merit is a web app for issuing [OpenBadges](http://openbadges.org/). Merit makes it very quick and easy to get up and running with issuing badges, it takes about 5 minutes to go from 0-to-live. The app is build on top of [Play! Framework](http://www.playframework.com/) and written in a mix of Java and Scala (with some javascript and css sprinkles).


How to use
----------

###Issuers
TODO

###Images
TODO

###Alignments
TODO

###Badges
TODO

###Assertions
TODO

Installation
------------

###Requirements

* Git
* Java 1.6+
* Thats it!

###Download

`cd /opt`

`git clone https://github.com/wookoouk/Merit.git`

`cd Merit`

###Config

As default Merit will store all the database info in a H2 db, it is configured to save it in the running users home directory.
To change this look in conf/application.conf, I have commented out the option to just save to memory.


Email settings are at the bottom of conf/application.conf, without a smtp server to hook it up to you will not be able to add new users.
For testing I suggest using the gmail smtp server.

###Running

To get Merit up and running for testing you can just execute `play run`, to run Merit in production execute `start-80.sh`.
