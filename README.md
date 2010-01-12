# Nodewiki
Nodewiki is wiki software created using [node.js](http://nodejs.org). It uses [redis](http://code.google.com/p/redis/) for data storage, with the [redis node client](http://github.com/fictorial/redis-node-client) to talk to redis. Page markup is written using [Showdown](http://attacklab.net/showdown/), a [Markdown](http://daringfireball.net/projects/markdown/) implementation written in javascript.

You need a [nerve](http://github.com/gjritter/nerve) checkout symlinked to ./nerve/ in the same directory as nodewiki.js . Start a redis server, run `node start_nodewiki.js`, visit http://localhost:8000/ .
