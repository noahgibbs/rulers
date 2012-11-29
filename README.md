# Rulers

This is the Ruby on Rulers framework from the book "Rebuilding Rails"
by Noah Gibbs.  You can find the canonical branch of this framework at
"http://github.com/noahgibbs/rulers".

It is primarily for instruction, but it works just fine as a web
framework if you want a simple one.

There are tags for different chapter starter code.  Type "git tag"
for a list.

## Installation

Add this line to your application's Gemfile:

    gem 'rulers', :git => git@github.com:noahgibbs/rulers.git

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install rulers

For git gems, you'll need to run "bundle exec rackup" instead of just
"rackup".

## Usage

This framework is instructional and there are good reasons not to use
it unmodified in production.  Rails is a relatively secure framework,
but Rulers is not.

For further details, see the Rails security guides and/or chapter 10
of Rebuilding Rails.

## Contributing

For significant contributions, please fork.

I have no problem with other people starting from this code for any
purpose and for any project.  You probably want to rename it, though.
