jQuery plugin for drag/drop uploads in HTML5
==============================
Based on the examples of Mika Tuupola (http://www.appelsiini.net/2009/10/html5-drag-and-drop-multiple-file-upload) and the jquery-filedrop plugin by Weixi Yen (https://github.com/weixiyen/jquery-filedrop).

- NOT an in-place replacement for jquery.filedrop.js

- Fixes multiple bad practices

- Adds event for when File is added to queue

- Still uses HTML5 FileReader() to read file data

- Improved code documentation

- File size limit in bytesThis script focuses on minimalism and doesn't do anything


Key differences to jquery.filedrop
---------------
- Added onFileQueued event

- Added onQueueCompleted event

- File size limit should be provided in bytes

- No speed calculation

- Response not parsed for JSON automatically anymore. If you expect JSON as response you have to run jQuery.parseJSON() in your onFileSucceeded callback


Browser Support
---------------
I can only guess, but tested and works with

- Google Chrome 17.0.963.46 m

- Mozilla Firefox 10.0.1


Usage Example
---------------
See Example.html