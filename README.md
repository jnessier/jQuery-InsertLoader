# jquery.insertloader
jQuery-based helper for loading JS and CSS on the fly

'''
// ******************************************
// BISHERIGE FUNKTION
// *************************************

// Eine Datei laden
$.insert('https://example.com/demo.js');

// ******************************************
// NEUE FUNKTIONEN
// ******************************************

// Mehrere Dateien von der selben Basis-URL laden
var moduleFiles = [
    'path/to/foo.css',
    'path/to/bar.js'
];
$.insert(moduleFiles, 'https://foo.com/bar/');

// Mehrere Dateien mit unterschiedlichen URLs laden
$.insert(['https://foo.com/bar.css', 'http://lorem.de/ipsum.js']);

// Eine Datei von einer Basis-URL laden
$.insert('path/to/foo.js', 'http://foo.com/path/to/bar/');
