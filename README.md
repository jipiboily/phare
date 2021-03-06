<p align="center">
  <a href="https://github.com/mirego/phare">
    <img src="http://i.imgur.com/9Pa2RgE.png" alt="Phare" />
  </a>
  <br />
  Phare looks into your files and check for coding style errors. 
  <br /><br />
  <a href="https://rubygems.org/gems/phare"><img src="https://badge.fury.io/rb/phare.png" /></a>
</p>

## Installation

Add these lines to your application’s Gemfile as development dependancies:

```ruby
group :development do
  gem 'rubocop' # to check Ruby code
  gem 'scss-lint' # to check SCSS code

  gem 'phare'
end
```


If you wish to check for JavaScript code style using JSHint and JSCS, you must install them too:

```bash
$ npm install -g jshint jscs
```

## Usage

Phare provides an executable named `phare`. You can just use it as is:

```bash
$ phare
```

One of the best way to use Phare is by hooking it before your version control commits. For example, with `git`:

```bash
$ bundle binstubs phare
$ ln -s "`pwd`/bin/phare" .git/hooks/pre-commit
```

## License

`Phare` is © 2014 [Mirego](http://www.mirego.com) and may be freely distributed under the [New BSD license](http://opensource.org/licenses/BSD-3-Clause).  See the [`LICENSE.md`](https://github.com/mirego/phare/blob/master/LICENSE.md) file.

The lighthouse logo is based on [this lovely icon](http://thenounproject.com/term/lighthouse/11608/) by [Nick Lacke](http://thenounproject.com/nicklacke), from The Noun Project.

## About Mirego

[Mirego](http://mirego.com) is a team of passionate people who believe that work is a place where you can innovate and have fun. We're a team of [talented people](http://life.mirego.com) who imagine and build beautiful Web and mobile applications. We come together to share ideas and [change the world](http://mirego.org).

We also [love open-source software](http://open.mirego.com) and we try to give back to the community as much as we can.
