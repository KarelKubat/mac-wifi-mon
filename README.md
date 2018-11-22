# mac-wifi-mon

I am sometimes on a flaky WiFi network where my Mac *thinks* that WiFi works,
while it doesn't. Cycling the WiFi power (off/on) seemms to do the trick, so I
automated it.

## Installation

Get the script `mac-wifi-mon`. Edit it and see if you want to change some configuration values at the top of the file.  Normally this should not be necessary.

Have it run regularly via your crontab. I chose every minute, so in my case,
my crontab looks as follows:

```shell
* * * * * /where/ever/you/put/it/mac-wifi-mon
```
