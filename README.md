## ss configuration for Surge
thanks to the original version form R0outer
people who have interst, please refer to 0[![Build Status](https://travis-ci.org/R0uter/ss.conf-for-surge.svg?branch=master)](https://travis-ci.org/R0uter/ss.conf-for-surge)

> `ssconf.py` can generate both gfwlist and whitelist, and auto update, 
whitelist is too long for iOS now, only Surge Mac can read.

## Proxy list 

Proxy list is generate from gfwlist, all marked with `force-remote-dns`.

White list come from [GFW Domain White List](https://goo.gl/tBixve).

## Anti ads

Ad's list come from [lhie1/Rules](https://github.com/lhie1/Rules).

## How to use

**Switch to `gh-pages` branch to [download latest .conf file](https://r0uter.github.io/ss.conf-for-surge/)!**

Just use [`gfwlist.conf` or `whitelist.conf` or `geoip_whitelist`](https://R0uter.github.io/ss.conf-for-surge/) directly. Both in `configFileHere` directory!

> Or use `ssconf.py` to generate config file.

This config file has two proxy groups, `Proxy` group is your proxy, `ChinaProxy` allow you choose proxy or direct to china domain, if proxy too, you will engage almost globally proxy.


