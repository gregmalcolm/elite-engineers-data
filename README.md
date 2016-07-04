Elite Engineers Data
====================

This project is an npm module where we’re storing our json file
data for Elite Engineers project:

http://github.com/gregmalcolm/elite-engineers

Installation
------------

npm install elite-engineers-data https://github.com/gregmalcolm/elite-engineeers-data.git --save-dev


NPM Debugging
-------------

When testing locally you can run this:

```
npm link
```

Then from another project that uses this npm module as a dependency
run this:

```
npm link elite-engineers-data
```

... and then run ls -la in the elite-engineers/modules folder.

See? Yep elite-engineers-data is now a symlink. Which means you can
try stuff out locally.

When you’re done use npm unlink elite-engineers-data to put things
back.

Exporting fresh json from Googlesheets
--------------------------------------

Currently we’re using a google apps script in bin/JSON_Exporter.gs.

*TODO*

Add some instructions on using the exporter
