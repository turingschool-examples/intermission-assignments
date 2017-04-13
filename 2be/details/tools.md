# Get Module 2 Tools

## Install Rails

If you don't already have it: `gem install rails`.

## Download Postgres

Download Postgres from Homebrew.

From your terminal, run:

```
brew update
brew install postgres
ln -sfv /usr/local/opt/postgresql/*.plist ~/Library/LaunchAgents
launchctl load ~/Library/LaunchAgents/homebrew.mxcl.postgresql.plist
```
[want to know a little more?](http://www.fyquah.me/setup-postgresql-on-os-x)

These last 2 lines will set up a special Daemon init file so that your operating
system will start postgres automatically whenever you log in.

**OR: Download the [Postgres app](http://postgresapp.com/).**
