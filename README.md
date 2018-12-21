# BeforeRender

Register your hook method which is invoked before invoking render method.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'before_render'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install before_render

## Usage

```ruby
class SomeController < ApplicationController

  before_render :my_hooker_before_render, only: [...]

  def my_hooker_before_render
    # Invoked before render method.
  end
end
```

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/toshiyukihina/before_render.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
