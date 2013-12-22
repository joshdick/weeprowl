# weeprowl

[Prowl](http://prowlapp.com) notifications for [weechat](http://weechat.org).

*by [Josh Dick](http://joshdick.net)*

*[https://github.com/joshdick/weeprowl](https://github.com/joshdick/weeprowl)*

## Installation and Usage

`weeprowl` requires Python 2 and weechat version 0.3.7 or greater.

To get started with `weeprowl`:

1. Place a copy of `weeprowl.py` in the appropriate weechat plugin folder (usually `~/.weechat/python/autoload`).
2. Inside weechat, run the command `/python load python/autoload/weeprowl.py`.
3. If you don't already have a Prowl API key, acquire one at [http://prowlapp.com](http://prowlapp.com).
4. Configure weeprowl to use your Prowl API key. Inside weechat, run the command `/set plugins.var.python.weeprowl.prowl_api_key "your_prowl_api_key_here"`.

`weeprowl` is now configured and should start sending Prowl notifications when your IRC nick is higlighted/mentioned or when you receive a private message.

`weeprowl` has a few configurable options. Please view the top of `weeprowl.py` to see what they are and how to configure them.

## License and Other Info

`weeprowl` is based on the `notify` plugin version 0.0.5 by lavaramano (lavaramano AT gmail DOT com).

`notify` is released under a GPL v2 license; therefore, `weeprowl` is as well.

`notify` is available here: [http://www.weechat.org/scripts/source/stable/notify.py.html/](http://www.weechat.org/scripts/source/stable/notify.py.html/)
