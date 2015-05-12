#bQZXing

Just a little fork of [dplanella's QZXing repository][]

I'm doing it because I need to compile and use a QR decoder with Qt on Android,
and the dplanella's version it's great with Qt 5.x... but I've got a 64 bit
Linux distribution and the libraries for Android raise a error.

So, I need to compile it inside my project, and I need a .PRI to do it :D

I've tested it with Qt 5.4 for Android.

##Usage

Clone the repository and include the .PRI file on your .PRO file

```
# Your project's .PRO file
# ...

include(<bQZXing directory>/QZXing.pri)

# ...
```

[dplanella's QZXing repository]: https://github.com/dplanella/qzxing
