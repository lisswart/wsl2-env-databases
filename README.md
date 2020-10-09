# Installing databases on WSL2

## Install SQLite

You’ll be using a couple of different databases as you move through the web development track. The default database that Ruby on Rails uses is SQLite.

### Action item

1. Open the "Ubuntu" application using the "Start" menu
2. Type `sudo apt-get install sqlite3` and press `<Enter>`

### Check your work

If you were able to run those commands without any issues, continue below.

## Install Postgres

We also frequently see that students want to deploy their apps to the hosting service Heroku. To do this, though, you will need a different relational database management system called PostgreSQL.

### Action item

1. Type `sudo apt-get install wget ca-certificates` and press `<Enter>`
2. Type `wget --quiet -O - https://www.postgresql.org/media/keys/ACCC4CF8.asc | sudo apt-key add -` and press `<Enter>`
3. Type ``sudo sh -c 'echo "deb http://apt.postgresql.org/pub/repos/apt/ `lsb_release -cs`-pgdg main" >> /etc/apt/sources.list.d/pgdg.list'`` and press `<Enter>`
4. Type `sudo apt-get update` and press `<Enter>`
5. Type `sudo apt-get install postgresql` and press `<Enter>` _(Note: this may take some time)_

### Check your work

If you were able to run those commands without any issues, continue below.