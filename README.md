# Fluent::Plugin::Protocols::Filter

Welcome to your new gem! In this directory, you'll find the files you need to be able to package up your Ruby library into a gem. Put your Ruby code in the file `lib/fluent/plugin/protocols/filter`. To experiment with that code, run `bin/console` for an interactive prompt.

TODO: Delete this and the text above, and describe your gem

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'fluent-plugin-protocols-filter'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install fluent-plugin-protocols-filter

## Usage

```
<filter log.**>
  @type protocols
  key_port dest_port
  key_proto proto
  key_prefix des
</filter>
```
+ `key_port` : port unber
+ `key_proto` : `TCP`, `UDP`
+ `key_prefix` : `key_port` + `key_prefix` add field

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/fluent-plugin-protocols-filter. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

