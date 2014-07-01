octopolo-plugin-example
-----------------------

A plugin example for octopolo.  Also used for testing plugins with octopolo.


Installation
------------

Add this line to your application's Gemfile:

    gem 'octopolo-plugin-example'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install octopolo-plugin-example


Usage
-----

Include this in your `.octopolo.yml`:

```yaml
plugins:
  - octopolo_plugin_example
```

And the plugin should be automatically loaded when octopolo is initialized.


Contributing
------------

1. Fork it ( https://github.com/sportngin/octopolo-plugin-example/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
