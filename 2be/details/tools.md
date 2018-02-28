# Get Module 2 Tools

## Install Rails

If you don't already have it: `gem install rails`.

## Download PostgreSQL

Download PostgreSQL from Homebrew.

From your terminal, run:

```
brew update
brew install postgresql
brew services start postgresql
```
[want to know a little more?](http://www.fyquah.me/setup-postgresql-on-os-x)

Using `brew services start psotgresql` after the installation is supposed to restart PostgreSQL after a reboot. If you find your database is not running, run this command again in a terminal to start the database. To force PostgreSQL to stop, issue a command of `brew services stop postgresql`. You can also run `brew services list` to see which other services are installed and which ones are already running.

Alternately, you can download and install PostgreSQL from a downloadable application built by PostgreSQL. Using Homebrew makes it much easier to install updates and has handy upgrade commands that reduce the amount of manual maintenance you need to perform. 

**YOU DO NOT want to install through Both Homebrew AND the app. CHOOSE ONE**
