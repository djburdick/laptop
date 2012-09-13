Laptop
======

Laptop is a script to set up a Mac OS X laptop for Rails development.
This was forked from (https://github.com/thoughtbot/laptop). Thanks to the thoughtbot guys!

Requirements
------------

* Install a C compiler, such as GCC, LLVM, or Clang.

Download a compiler from the [OS X GCC Installer](https://github.com/kennethreitz/osx-gcc-installer/) if you're on Snow Leopard (OS X 10.6) or use the [Command Line Tools for XCode](https://developer.apple.com/downloads/index.action) for Lion (OS X 10.7) or Mountain Lion (OS X 10.8).


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
* ImageMagick for cropping and resizing images
* Postgres for storing relational data
* Postgres gem for talking to Postgres from Ruby
* Qt for headless JavaScript testing via Capybara Webkit
* Rails gem for writing web applications
* Ruby stable for writing general-purpose code
* RVM for managing versions of the Ruby programming language
* SSH public key for authenticating with Github and Heroku
* Tmux for saving project state and switching between projects

It should take less than 30 minutes to install (depends on your machine).
