# Mambu Gem

This gem provides a simple Ruby wrapper for communicating with the Mambu REST API.
Mambu API follow the Representational state transfer [REST](http://en.wikipedia.org/wiki/Representational_state_transfer)
standard allowing resources (accounts, client, etc) to be standard with a standard
set of GET, POST, PUT, DELETE HTTP requests.
Communication with Mambu follows the REST architecture constraints including being
stateless & cacheable. All responses are returned as [JSON](http://en.wikipedia.org/wiki/JSON) objects.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'mambu-ruby'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install mambu-ruby

## Usage

TODO: Write usage instructions here

## Contributing

1. Fork it ( https://github.com/[my-github-username]/mambu-ruby/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
