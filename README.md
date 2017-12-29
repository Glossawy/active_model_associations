# ActiveModelAssociations

A gem to provide a DSL for associations in [ActiveModel][gh-am] similar to those provided
by ActiveRecord. Partly inspired by [ActiveModel::Serializers][gh-ams].

This gem focuses primarily on:

- Easy to use association macros
- Seamless integration with ActiveModel and it's validation system
- Integration with ActionPack. In particular, with `StrongParameters`

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'active_model_associations'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install active_model_associations

## Usage

TODO: Write usage instructions here

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/Matt529/active_model_associations. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the ActiveModelAssociations project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/Matt529/active_model_associations/blob/master/CODE_OF_CONDUCT.md).

[gh-am]: https://github.com/rails/rails/tree/master/activemodel
[gh-ams]: https://github.com/rails-api/active_model_serializers
