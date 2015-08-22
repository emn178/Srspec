# Srspec

Determine to use spring to run rspec if it's running.

## Installation

Add this line to your application's Gemfile:

    gem 'srspec'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install srspec

## Usage

Run by `srspec`

    $ srspec

If spring is available, it's equal to

    $ spring rspec

Or it will be equal to

    $ rspec

## Integration

To run rspec with spring in [sublime-text-2-ruby-tests](https://github.com/maltize/sublime-text-2-ruby-tests), you may set up the configuration like this
```
{
  "check_for_spring": true
}
```
But this will has problem project without spring. In this time, you can install this gem and set up to
```
{
  "run_rspec_command": "srspec {relative_path}",
  "run_single_rspec_command": "srspec {relative_path}:{line_number}"
}
```
It will work both cases.

## License
The project is released under the [MIT license](http://www.opensource.org/licenses/MIT).

## Contact
The project's website is located at https://github.com/emn178/srspec  
Author: emn178@gmail.com
