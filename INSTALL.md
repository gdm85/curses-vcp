# INSTALL

```
$ make
$ su
$ make install
```

to install into a different directory:
```
$ make install PREFIX=/dir
```

to install sample config (installs to /etc/vcp.conf):
```
$ make installconf
```

the Makefile attempts to find your man1 directory,
if it does not, copy the file to your man1 directory:
```
$ vcp vcp.1.gz /path/to/man1dir/man1
```
or for the Polish manual:
```
$ vcp vcp.pl.1.gz /path/to/man1dir/pl/man1/vcp.1.gz
```
 
Manual page is now translated to some non-english languages.
By default all translated manuals are installed into: `/mandir/country_tld/man1/`. With manual language will be used in Your system depends on two variables: LANG and LC_ALL (eg. as far as LANG=pl You'll see Polish manual).
