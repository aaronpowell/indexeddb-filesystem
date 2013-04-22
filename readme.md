This is a sample of how to implement a file system on top of IndexedDB. If you're running this locally you'll want to use `node app` so that the server will run (since most browser require IndexedDB to run against a domain).

Basically all it does is setup relationships between the parent/child items in the IndexedDB store.