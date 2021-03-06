# Backblaze

The Backblaze ruby gem is an implementation of the [Backblaze B2 Cloud Storage API](https://www.backblaze.com/b2/docs/). In addition to simplifying calls, it also implements an object oriented structure for dealing with files. Calling the api through different objects will not cause each to get updated. Always assume that data retrieved is just a snapshot from when the object was retrieved.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'backblaze'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install backblaze

## Usage

TODO: Write usage instructions here

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake rspec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/backblaze. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
