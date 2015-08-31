![](https://img.shields.io/badge/license-MIT-007EC7.svg?style=flat-square)

<div align="center">
    <a href="http://github.com/fish-shell/oh-my-fish">
        <img width="90" src="https://cloud.githubusercontent.com/assets/8317250/8510172/f006f0a4-230f-11e5-98b6-5c2e3c87088f.png">
    </a>
</div><br>

bundler
=======

Ruby gem support for fish.

Install
-------

```fish
$ omf install gem
```

Configuration
-------------

In order to use `gem` you must specify the path to gem root. You can do so by
adding the following snippet to your `.config/fish/config.fish` file before
sourcing Oh My Fish.

    set GEM_ROOT #path

For example:

    set GEM_ROOT ~/.gem/ruby/2.1.0

License
=======

[MIT](http://opensource.org/licenses/MIT) © [bpinto](http://github.com/bpinto)
et [al](https://github.com/bpinto/plugin-bundler/graphs/contributors)
