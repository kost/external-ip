[![Build Status](https://travis-ci.org/kost/external-ip.png)](https://travis-ci.org/kost/external-ip)

# external-ip

Simple application to display IP addresses in form that you can copy&paste them.

This simple application will show your IP addresses(default local & external). It will show them in text box from where you can copy&paste easily for different purposes.

# Build

In order to build you must satisfy few dependencies.

## Build requirements

You need to have:

- Android SDK
- ant for cli building (or Eclipse to import project and build)

## Build process

After that you can issue following commands (if android SDK is located at /opt/android-sdks):

```
git clone https://github.com/kost/external-ip/
cd external-ip
echo sdk.dir=/opt/android-sdks > local.properties
ant release
```

# Donate

BTC: 1pafmH6QqRXfmVef3RGJcDiD9AMjxrzfX

LTC: LecEdQxBhR4kPJENejpPDBWev38j5G9qfy

[![Flattr this git repo](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=kost&url=https://github.com/kost/external-ip&title=External%20IP&language=&tags=github&category=software) 

# Changes

Changes in 2.3:
- make http request as background task
- introduce ant build support

Changes since last version: 
- ability to enter custom external URL to get IP
- ability to choose different IP providers

Other changes: 
- ability to display your IP address on the interface as well

# History

It was originally hosted on code.google.com using Mercurial at:
GPL: http://code.google.com/p/external-ip/

But it was automatically exported 15th of March, 2015 to github:
Automatically exported from code.google.com/p/external-ip
