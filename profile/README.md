## KouchDB 👋

A collection of CouchDB and CouchDB compatible databases and related tools, and my own experimental forays into the ecosystem.

I'm a huge fan of the CouchDB concept and architecture, but I don't like the Erlang implementation.

There's a lot to like in the javascript-based rewrite, PouchDB, but it's not mature enough yet on the server side (as of 2023), especially for cloud deployment. That's not a criticism of the PouchDB developers, as their goal was really to run in the browser. It just so happens that rewriting in Javascript unlocks NodeJS as a platform, which in turn unlocks the option to easily port to other runtimes such as AWS Lambda.

I have evaluated both CouchDB and PouchDB for one of my projects and also experimented with building my own CouchDB-compatible engine. Some of these experiments made it into the repos in this collection.
