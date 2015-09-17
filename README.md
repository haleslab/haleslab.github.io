haleslab.github.io
==================

haleslab website

### technical notes (that I might forget)

1. to get haleslab.com and haleslab.net to re-direct to haleslab.org (with or without the www) modify the domain so both are redirected to a URL (e.g., http://haleslab.org).

2. to build and work with the website using jekyll on a mac when there are write permission issues due to the rub version with using gem install jekyll. 
    -install homebrew ($ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)")
    -install a ruby version organizer ($ brew install rbenv ruby-build)
          -you can type $ rbenv commands to see the commands
    -add rbenv init to the shell profile ($ echo 'eval "$(rbenv init -)"' >> ~/.bash_profile)
    -install the ruby versions ($ rbenv install -l)
    -pick your ruby version to install ($ rbenv install 2.2.3)
    -open a new terminal window to make sure the profile is updated
    -give the command $ type rbenv and it should now say rbenv is a function.  
    -give the command $ rbenv versions to see the available ruby versions
    -change the ruby version $ rbenv global 2.2.3
    -then $ gem install jekyll should work
