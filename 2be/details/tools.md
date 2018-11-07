# Get Module 2 Tools

## Install Rails

If you don't already have it: 
```bash
gem install rails --version 5.1.6
```

Be careful not to install Rails 5.2 by only doing `gem install rails` -- our curriculum is not up to date with 5.2 changes, and you will need to uninstall 5.2.

## Download PostgreSQL

Download PostgreSQL from Homebrew.

From your terminal, run:

```
brew update
brew install postgresql
brew services start postgresql
```
[want to know a little more?](http://www.fyquah.me/setup-postgresql-on-os-x)

Using `brew services start postgresql` after the installation is supposed to restart PostgreSQL after a reboot. If you find your database is not running, run this command again in a terminal to start the database. To force PostgreSQL to stop, issue a command of `brew services stop postgresql`. You can also run `brew services list` to see which other services are installed and which ones are already running.

If you install PostgreSQL through an alternate source, please uninstall that version and use Homebrew's version.


## Install Chrome

If you are currently using another browser, download and install Chrome [here](https://www.google.com/chrome/). This will make it so that we can share shortcuts and have a consistent experience when debugging together as a class.
