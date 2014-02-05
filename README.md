iOS WebKit Debug Proxy Win32
============================

Win32 port of ios-webkit-debug-proxy (https://github.com/google/ios-webkit-debug-proxy).

The ios_webkit_debug_proxy allows developers to inspect MobileSafari and UIWebViews on real and simulated iOS devices via the [DevTools UI](https://developers.google.com/chrome-developer-tools/) and [WebKit Remote Debugging Protocol](https://developers.google.com/chrome-developer-tools/docs/remote-debugging).  DevTools requests are translated into Apple's [Remote Web Inspector service](https://developer.apple.com/technologies/safari/developer-tools.html) calls.

For more info please refer to original [README](proxy.md)

Why win32 port?
---------------

Of course you can use any vm software to compile and run original ios-webkit-debug-proxy and forward usb/ports but it's not very cool, isn't it?


Notes
-----

To debug with with ios-webkit-debug-proxy you need to have iTunes installed.


Troubleshooting
---------------

If when starting app you get the "connect: No error" message, please check that Apple Mobile Device service is running.