keylogger-osx
=============

This is a very simple keylogger for self-quantifying. The source code is awfully dirty, but it works for me and that's enough.


Disclaimer
----------
**Please do not ever take this project for any evil purpose.**


Story
-----
My friend and I were discussing about the [Carpal Tunnel Syndrome](http://en.wikipedia.org/wiki/Carpal_tunnel_syndrome). He asked how many keystrokes I perform everyday, and I totally had no idea. However, keystrokes are highly sensitive information and I don't trust those softwares in the wild.

Being a programmer, simply write one by myself. That's it. 


Usage
-----
Build the code and deploy it to `/usr/local/sbin/`. Then drop the Launchd script to `/System/Library/LaunchDaemons` to fire up this keylogger on startup. By default, the keystrokes would be logged in `/var/log/keystroke.log`. You may need root priviledge when writting to `/var/log/`.

Remember to check *Enable access for assitive devices* in the *Universal Access* preferences panel.


License
-------
Copyright (c) 2012 Shao-Chung Chen

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
 
