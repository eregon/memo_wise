# MemoWise

TODO: Write clear description of MemoWise

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'memo_wise'
```

And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install memo_wise

## Usage

TODO: Write usage instructions here

## Benchmarks

Using Ruby 2.7.1 and
[`benchmark-ips`](https://github.com/evanphx/benchmark-ips) 2.8.2:

|Gem|Method with no arguments|Method with positional arguments|Method with keyword arguments|
|---|------------------------|--------------------------------|-----------------------------|
|**`memo_wise` (0.1.0)**|**baseline**|**baseline**|**baseline**|
|`memery` (1.3.0)|13.99x (± 0.00) slower|1.23x (± 0.00) slower|1.45x (± 0.00) slower|
|`memoist` (0.16.2)|2.77x (± 0.00) slower|1.37x (± 0.00) slower|1.52x (± 0.00) slower|
|`memoized` (1.0.2)|1.26x  (± 0.00) slower|1.10x (± 0.00) slower|1.38x (± 0.00) slower|
|`memoizer` (1.0.3)|3.24x (± 0.00) slower|1.23x (± 0.00) slower|1.45x (± 0.00) slower|

You can run benchmarks yourself with:

```bash
$ cd benchmarks
$ bundle install
$ bundle exec ruby benchmarks.rb
```

If your results differ from what's posted here,
[let us know](https://github.com/panorama-ed/memo_wise/issues/new)!

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run
`rake spec` to run the tests. You can also run `bin/console` for an interactive
prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To
release a new version, update the version number in `version.rb`, and then run
`bundle exec rake release`, which will create a git tag for the version, push
git commits and tags, and push the `.gem` file to
[rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at
https://github.com/panorama-ed/memo_wise. This project is intended to be a safe,
welcoming space for collaboration, and contributors are expected to adhere to
the [code of conduct](https://github.com/panorama-ed/memo_wise/blob/master/CODE_OF_CONDUCT.md).


## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the MemoWise project's codebases, issue trackers, chat
rooms and mailing lists is expected to follow the
[code of conduct](https://github.com/panorama-ed/memo_wise/blob/master/CODE_OF_CONDUCT.md).
