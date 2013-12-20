# ![](https://raw.github.com/aptible/straptible/master/lib/straptible/rails/templates/public.api/icon-60px.png) Aptible::Auth

[![Gem Version](https://badge.fury.io/rb/aptible-auth-ruby.png)](https://rubygems.org/gems/aptible-auth-ruby)
[![Build Status](https://travis-ci.org/aptible/aptible-auth-ruby.png?branch=master)](https://travis-ci.org/aptible/aptible-auth-ruby)
[![Dependency Status](https://gemnasium.com/aptible/aptible-auth-ruby.png)](https://gemnasium.com/aptible/aptible-auth-ruby)

Ruby client for [auth.aptible.com](https://auth.aptible.com/). Since Aptible's authorization service is built on OAuth 2.0, most developers should be able to implement a client using just the [oauth2](https://github.com/intridea/oauth2) gem.

However, due to the complexity of OAuth 2.0 and the fact that it is a fragmented and evolving standard, we provide this gem as a standard Ruby client library. All of our internal services use it, and so it can be expected to work.

## Installation

Add the following line to your application's Gemfile.

    gem 'aptible-auth'

And then run `bundle install`.

## Usage

TODO: Add usage notes.

## Contributing

1. Fork the project.
1. Commit your changes, with specs.
1. Ensure that your code passes specs (`rake spec`) and meets Aptible's Ruby style guide (`rake rubocop`).
1. Create a new pull request on GitHub.

## Copyright and License

MIT License, see [LICENSE](LICENSE.md) for details.

Copyright (c) 2013 [Aptible](https://www.aptible.com), Frank Macreery, and contributors.
