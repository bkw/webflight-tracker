webflight-tracker
=================

This is a plugin for the browser-based AR.Drone ground control station
ardrone-webflight that lets you track pixels on the videostream by clicking on
them.

Installation
------------

- Either copy, link, or use git-submodule to put this code repository in the
  webflight plugin folder in a subdirectory named "tracker".

- Edit your webflight config.js to enable the plugins "video-stream" and
  "tracker".

- Launch webflight

- Click on the video screen

Dependencies
------------

This plugin needs the video-stream to supply the image data. It has to be
loaded after it.

Example config.js:
------------------

```javascript

var config = {
    plugins: [ "video-stream", "hud", "battery", "pilot", "tracker" ],
    keyboard: 'qwerty'
};
module.exports = config;
```

Video Demo
----------

I recorded a [short demonstration video](http://youtu.be/S2UVnwKzhEk)

License
-------
Copyright (c) 2013 the Authors

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

Military use is strictly prohibited.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
