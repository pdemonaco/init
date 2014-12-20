CrashPlan OpenRC Init Script
============================

This is a simple implementation of an OpenRC compatible init script for the Code42 background daemon.

Installation
------------

Once CrashPlan has been installed simply copy this script into /etc/init.d/

```
cp init/crashplan/crashplan /etc/init.d/
```
Then add crashplan to the desired runlevel

```
rc-update add crashplan default
```
