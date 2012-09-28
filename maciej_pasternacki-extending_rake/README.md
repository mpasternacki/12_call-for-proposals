# Extending Rake

Everyone who works with Ruby knows Rake. It builds things, it runs
tasks, if you're on Rails it is even one of the entry points to your
project. But there is more to it than what you can achieve with a
simple Rakefile!

Evoker (https://github.com/mpasternacki/evoker/) is a Rake extension
gem for downloading third-party dependencies. Metarake
(https://github.com/3ofcoins/metarake/) is an extension for building
multiple child projects and publishing them outside the build root. I
am going to quickly show the extensions themselves, and then dive into
the interesting part: internal API of rake - extension points and ways
of programmatically creating build tasks. The extensions will serve as
example of how the extension points can be used, and how the resulting
code can be tested.

## Maciej Pasternacki

Freelance DevOps Guy.

Starting as a freelance developer in 2009, I soon gravitated towards
managing Web infrastructure, continuous integration, build systems,
etc. With decent background in both administration and programming, I
develop agile infrastructure, trying to replace as much of shell
script plumbing as possible with elegant Ruby recipes for Chef.

[Profile picture](http://www.gravatar.com/avatar/1bd1f0ff92bed69bfb53eefa9fd606f8.png?s=150)

## On the web

- [Website](http://pasternacki.net/)
- [Blog](http://3ofcoins.net/)
- [Twitter](https://twitter.com/mpasternacki)
- [GitHub](https://github.com/mpasternacki)
- [GitHub 2](https://github.com/3ofcoins)
