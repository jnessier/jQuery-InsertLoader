# jQuery InsertLoader
jQuery plugin as helper function to support asynchron loading of JavaScript and Stylesheets files on the fly.

## Examples
```javascript
// Loading one file
$.insert('https://example.com/demo.js');

// Loading one file with a base-url
$.insert('path/to/foo.js', 'http://foo.com/path/to/bar/');

// Loading multiple files
$.insert(['https://foo.com/bar.css', 'http://lorem.de/ipsum.js']);

// Loading multiple files with the same base-url
var moduleFiles = [
    'path/to/foo.css',
    'path/to/bar.js'
];
$.insert(moduleFiles, 'https://foo.com/bar/');
```

## Author(s)

* Jonathan Nessier, [Neoflow](https://www.neoflow.ch)

## License
MIT
