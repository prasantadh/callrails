# README

## Getting Up and Running

The easiest way I found to set myself up to use [rbenv](https://github.com/rbenv/rbenv).

On an ubuntu system,
```bash
sudo apt install rbenv

# initialize the enviroment
# this will also tell you what to add to your profile to load rbenv each time
rbenv init


# additionally it requires rbenv-build to install ruby
# https://github.com/rbenv/ruby-build
git clone https://github.com/rbenv/ruby-build.git "$(rbenv root)"/plugins/ruby-build
rbenv install 3.2.2

# running rbenv rehash was helpful
```

There are additonally a couple tricks involving `rbenv local 3.2.2` but these are
more straight-forward.

## api 

When run, this application intends to serve the following api:

