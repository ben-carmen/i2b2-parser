# i2b2-parser
This is a parsing service to allow parsing of i2b2-messages that are DOM independent.



This service utilizes: 
- jsdom: https://github.com/tmpvar/jsdom/wiki/Using-Google-XPath-implementation-with-jsdom
for loading everything.
- bluebird: https://www.npmjs.com/package/bluebird  for using promises with node fs
see: https://alexperry.io/node/2015/03/25/promises-in-node.html
- xmldom:   https://www.npmjs.com/package/xmldom for the DOMParser
- wgxpath: https://www.npmjs.com/package/wgxpath  for the xpath parsing.




