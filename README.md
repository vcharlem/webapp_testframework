# About WatirTestframework

WatirTestframework is a harness to assist with functional web application testing with WATIR. 

WatirTestframework takes advantage of widely used open source technologies such as Ruby, Watir, RSpec.

It also encourages code sharing and the use of Pageobject Design patterns.

Basic components include:

1. reporting (ie logging)

2. utility for running tests

3. directory structure 

	- tests are expected to be in 'tests/spec/'

	- reports are in expected to be in 'reports/'

4. Chromedriver, is included for your convenience

	- MacOSx is in 'bin/osx'

	- need to add it to $PATH



## Installation

Add this line to your application's Gemfile:

```ruby
gem 'watir_testframework'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install watir_testframework

## Usage
utility 'runregress' will launch rspec.
Runregress expects rspec tests to live in `tests/spec directory`.

example:

`runregress --help`

`runregress --test login_spec,register_spec`

`runregress --test_list regression_list/smoke_test`


## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/watir_testframework.

