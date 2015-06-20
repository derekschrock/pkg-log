pkgng plugin that uses checekdout git or svn repo to display commit logs of the given package.

package name:
```
$ pkg log screen
a3341c8 Wed Mar 11 01:25:46 2015 +0000 Advertise CPE info.
700f453 Sun Feb 1 14:30:29 2015 +0000 Fix pkg-plist.
362c26c Sat Jan 31 23:32:50 2015 +0000 Bump PORTREVISION for r373436.
8f35ccb Wed Nov 26 01:37:15 2014 +0000 nstall optional screenrc with helpful status line instead of the default.
368bbbc Sat Nov 22 09:13:35 2014 +0000 Cleanup plist
c48dcf6 Tue Jul 29 15:00:12 2014 +0000 Rename sysutils/ patch-xy patches to reflect the files they modify.
5c7a2b4 Sun Jun 15 06:06:27 2014 +0000 Reversed check. Bump portrevision.
9cf4333 Sun Jun 15 05:44:44 2014 +0000 Due to popular demand sockets are back! Sockets are the default option. Users should choose named pipes in a heterogeneous environement that uses both screen 4.0.3 and 4.2.1.
6c9bfb9 Sat Jun 14 04:07:56 2014 +0000 Make screen 4.0 compatible, prefer fifo over sockets.
20f56bc Fri May 23 06:16:30 2014 +0000 Add LICENSE
```

full package name:
```
pkg log screen-4.2.1_5
$ pkg log screen-4.2.1_5
a3341c8 Wed Mar 11 01:25:46 2015 +0000 Advertise CPE info.
700f453 Sun Feb 1 14:30:29 2015 +0000 Fix pkg-plist.
362c26c Sat Jan 31 23:32:50 2015 +0000 Bump PORTREVISION for r373436.
8f35ccb Wed Nov 26 01:37:15 2014 +0000 nstall optional screenrc with helpful status line instead of the default.
368bbbc Sat Nov 22 09:13:35 2014 +0000 Cleanup plist
c48dcf6 Tue Jul 29 15:00:12 2014 +0000 Rename sysutils/ patch-xy patches to reflect the files they modify.
5c7a2b4 Sun Jun 15 06:06:27 2014 +0000 Reversed check. Bump portrevision.
9cf4333 Sun Jun 15 05:44:44 2014 +0000 Due to popular demand sockets are back! Sockets are the default option. Users should choose named pipes in a heterogeneous environement that uses both screen 4.0.3 and 4.2.1.
6c9bfb9 Sat Jun 14 04:07:56 2014 +0000 Make screen 4.0 compatible, prefer fifo over sockets.
20f56bc Fri May 23 06:16:30 2014 +0000 Add LICENSE
```

origin name limiting the number of messages:
```
$ pkg log -n1 sysutils/screen
a3341c8 Wed Mar 11 01:25:46 2015 +0000 Advertise CPE info.
```


