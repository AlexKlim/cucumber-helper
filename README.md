# Cucumber::Helper

TODO: Write a gem description

## Installation

Add this line to your application's Gemfile:

    gem 'cucumber-helper'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install cucumber-helper

## Usage

Use cucumber methods as usual. The wrapper will work automatically.
Configure error message:

    Cucumber::Helper.configure do |config|
      config.error_message = nil # default value
    end

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
