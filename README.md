**Note**: this project is effectively abandoned. It may serve as a useful
reference at times, but it's not being kept up-to-date. The last thing you
should do is fork it to make your own compositor and you certainly should not
package it for your distro.

If you are looking for a better reference or jumping-off point, check out
[tinywl](https://github.com/swaywm/wlroots/tree/master/tinywl). There is also a
[list of resources for getting started with
wlroots](https://github.com/swaywm/wlroots/wiki/Getting-started) available, as
well as a [list of other projects using
wlroots](https://github.com/swaywm/wlroots/wiki/Projects-which-use-wlroots),
whose code is likely a better reference.

Historical readme:

# rootston

Rootston is the "big" [wlroots](https://github.com/swaywm/wlroots) test
compositor. It implements basically every feature of wlroots and may be useful
as a reference for new compositors.  However, it's mostly used as a testbed for
wlroots development and does not have particularly clean code and is not
particularly well designed: proceed with a grain of salt. It is not designed for
end-users.

## Running rootston

If you followed the build instructions in `../README.md`, the rootston
executable can be found at `build/rootston/rootston`. To use it, refer to the
example config at [rootston/rootston.ini.example][rootston.ini] and place a
config file of your own at `rootston.ini` in the working directory (or in an
arbitrary location via `rootston -C`). Other options are available, refer to
`rootston -h`.

[rootston.ini]: https://github.com/swaywm/wlroots/blob/master/rootston/rootston.ini.example
