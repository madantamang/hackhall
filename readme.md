> Invite-only community and social collaboration platform for programmers, startupers, JavaScript professionals and pirates.


## Express 4 Update

This is Express 4.x version.

For Express 3.x go to [release 2.0.1](https://github.com/azat-co/hackhall/releases/tag/v2.0.1).


## Live Demo

<http://hackhall.com>

## Setup

Clone the repo.

For AngelList setup have `.env` file with:

```
ANGELLIST_CLIENT_ID=YYYYYYYYYYYYYYYYYYYYYYYYYYYYY
ANGELLIST_CLIENT_SECRET=XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
```

Then run `foreman start`, or `node server.js`, or `node .`, `npm start`.


> Built with Backbone.js, Mongoose and Express.js.


## Tests

To seed data and run tests:

```
$ npm test
```

or

```
$ make test
```

Just to run tests:

```
$ node seed.js
```