# Blocked Hosts

I am blocking Facebook, Outbrain and Taboola on my computer and you can too.

If you're running a Unix operating system (Ubuntu, MacOS, GNU/Linux), put the contents of [hosts](https://github.com/razzius/blocked-hosts/tree/master/hosts) in your `/etc/hosts` file.

```sh
# First copy any lines you want onto your clipboard, then:
$ sudo sh -c 'pbpaste >> /etc/hosts'

# Or use a command-line editor:
$ sudo vi /etc/hosts
```

Now when I browse sites that attempt to load data from these sites, the requests will fail, keeping with my desire to avoid them as well as saving bandwidth and energy.

<img alt="Browsing meetup.com with these settings causes Facebook's fbevents.js and sdk.js to not load."
     src="https://raw.githubusercontent.com/razzius/blocked-hosts/master/blocked_sites.png">
