
:warning: In progress

**This project is on hold until browsers acquire more MediaSource API support. Nevertheless, if you'd like to give this library a shot, fork it and I'll link to your working version.** 

Current road blocks:

* Lack of browser support.
* The [existing mega library](https://github.com/tonistiigi/mega) is built using an older forked version of browserify, this makes it difficult to work with. The best thing would be to recreate a pure browser Mega library using [existing mega library](https://github.com/tonistiigi/mega) source. Note, not all features would be required, we just need a **streaming** download command.

---

Development References

* http://www.jwplayer.com/html5/mediasource/
* http://updates.html5rocks.com/2011/11/Stream-video-using-the-MediaSource-API
* http://techslides.com/demos/video/dragdrop-video-screenshot.html

---

# Mega Stream

A front-end JavaScript library and accompanying web application for streaming audio, image and video content from Mega. 

### How it would work

It would use [tonistiigi](https://github.com/tonistiigi/)'s [mega](https://github.com/tonistiigi/mega) to stream HTML5 blobs and the `mega-stream` library then converts these streams into HTML5 video compatible streams. The webapp is a example use-case of this library.

### Contributing

The library is built using Browserify. The webapp is built using Browserify and React (Beware – I'm using this project as an excuse to try out React).

#### MIT License

Copyright © 2014 Jaime Pillora &lt;dev@jpillora.com&gt;

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

<!-- 
[![Analytics](https://ga-beacon.appspot.com/UA-38709761-8/xdomain/readme)](https://github.com/igrigorik/ga-beacon)
 -->
