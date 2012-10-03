Laptop
======

Laptop is a script to set up a Mac OS X laptop for Rails development.
This was forked from (https://github.com/thoughtbot/laptop). Thanks to the http://thoughtbot.com/ guys!

Requirements
------------

* Install XCode (this is needed for the C commandline tools and macvim)

Install
-------

Run the script:

    bash < <(curl -s https://raw.github.com/djburdick/laptop/master/mac)

What it sets up
---------------

* Ack for finding things in files
* Bundler gem for managing Ruby libraries
* Foreman gem for serving Rails apps locally
* Heroku gem for interacting with the Heroku API
* Heroku Config plugin for local `ENV` variables
* Homebrew for managing operating system libraries
* Ruby stable for writing general-purpose code
* RVM for managing versions of the Ruby programming language
* SSH public key for authenticating with Github and Heroku
* Redis for all your key/value database needs
* Mysql for relational database needs
* MacVim

It should take less than 30 minutes to install (depends on your machine).
