# webserver-tcl
A simple webserver based on Tcl.

This package uses [getopt-tcl]. Modify the `auto_path` in [webserver] to refer
to its path. By default, it is assumed to be `lib/getopt-tcl`. You can clone
both webserver-tcl and getopt-tcl by cloning recursively:

```console
$ git clone --recursive https://github.com/markuskimius/webserver-tcl
$ webserver-tcl/bin/webserver
```

## Options

* `--port <num>` Run on this port. Default is 5000.
* `--server <addr>` Listen on this address. Default is 0.0.0.0.
* `--basepath <path>` Serve pages from this path. Default is `$HOME/public_html`.

## License

[Apache 2.0]


[Apache 2.0]: <https://github.com/markuskimius/webserver-tcl/blob/master/LICENSE>
[webserver]: <https://github.com/markuskimius/webserver-tcl/blob/master/bin/webserver>
[getopt-tcl]: <https://github.com/markuskimius/getopt-tcl>
