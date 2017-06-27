# [rspec.info](http://rspec.info) example

## Ruby Gems
The following command was used to install the gems originally and set up the /bin directory

    $ bundle --path vendor --binstubs

This doesn't need to be done again as the gems are packaged into the /vendor/cache directory and persisted in git along with the binaries

## RSpec framework
The RSpec framework was initialised by

    $ bin/rspec init

which created the .rspec file and the RSpec helper in the /spec directory

## A simple example RSpec test
An example Ruby Class, 'Bowling' exists under the /lib directory
with an example RSpec test under the /spec directory alongside the RSpec helper

## Execute the test
    $ bin/rspec --format doc

## Documentation
[rspec.info documentation](http://rspec.info/documentation/)

[RSpec Core](http://rspec.info/documentation/3.6/rspec-core/)
