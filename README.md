# AkerSharedNavbar

This gem centralises the layout and style of the Aker navigation bar, eliminating the need to update each front-end application separately for minor (or major) changes.

It consists of two files that can be accessed in host applications, the template for the navbar (a partial) and the stylesheet.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'aker_shared_navbar'
```

And then execute:

    $ bundle

## Usage

The CSS should be imported in `app/assets/stylesheets/application.scss`:

    @import "navbar";

The navigation bar partial can be rendered as follows:

    <%= render partial: "navbar" %>

## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/aker_shared_navbar.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
