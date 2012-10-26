# Browser testing at WMF

## Environment

- Firefox 15
- Ruby 1.9.3p286 or 1.9.3p194
  - RubyGems 1.8.24

Install required RubyGems:

    gem update --system
    gem install bundler
    bundle install

Run the tests with `bundle exec rake`.

## Sites

Code is pushed to https://gerrit.wikimedia.org/r/gitweb?p=qa/browsertests.git;a=summary

GitHub mirror is at https://github.com/zeljkofilipin/browsertests

Jenkins is hosted at https://zeljkofilipin.ci.cloudbees.com/

Tests are running at http://saucelabs.com/
