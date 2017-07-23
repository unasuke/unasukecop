# Unasukecop
[![Build Status](https://travis-ci.org/unasuke/unasukecop.svg?branch=master)](https://travis-ci.org/unasuke/unasukecop)

UnasukeCop is a RuboCop configration gem inspired by [OnkCop](https://github.com/onk/onkcop).


## Installation

Add this line to your application's Gemfile:

```ruby
gem 'unasukecop', require: false, group: :test
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install unasukecop

## Usage

Add `inherit_gem:` setting to your `.rubocop.yml`

```yaml
inherit_gem:
  unasukecop:
    - "config/rubocop.yml"
    # - "config/rails.yml"
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake test` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/unasuke/unasukecop.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

