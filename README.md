# care-share.github.io

This project contains the files to generate the GitHub Pages web site for the Care-Share project.

## Prerequisites

Before you can build and serve this web site locally (on Debian/Ubuntu), you must do the following...

1. Install rvm/ruby:

        $ \curl -sSL https://get.rvm.io | bash -s stable --ruby

2. If you are behind a corporate proxy that resigns SSL certificates, use HTTP to install gem sources:

        $ gem sources -r https://rubygems.org/
        $ gem sources -a http://rubygems.org/

3. Configure rvm login shell:

        $ echo "source ~/.rvm/scripts/rvm" >> ~/.bashrc
        $ source ~/.bashrc

4. Install the 'bundler' gem:

       $ gem install bundler

5. Use bundler to install the 'github-pages' dependencies (e.g. Jekyll):

       $ bundle install

## Build and Serve

To build and serve this web site using Jekyll:

    $ bundle exec jekyll serve

Then, access the site at http://localhost:4000

