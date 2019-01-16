# Orbit Chat

[![Gitter](https://img.shields.io/gitter/room/nwjs/nw.js.svg)](https://gitter.im/orbitdb/Lobby)
[![npm version](https://badge.fury.io/js/orbit-chat.svg)](https://www.npmjs.com/package/orbit-chat)


> A distributed, peer-to-peer chat application built on [IPFS](http://ipfs.io)

Browser application for [Orbit](https://github.com/orbitdb/orbit). Try it at https://orbit.chat.

Built with the following packages:
- [orbit-core](https://github.com/orbitdb/orbit-core) - Core Orbit communication library.
- [js-ipfs](https://github.com/ipfs/js-ipfs) - A new p2p hypermedia protocol for content-addressed storage.

See also:
- [orbit-db](https://github.com/orbitdb/orbit-db) - Serverless, p2p database that orbit-core uses to store its data.                                
- [orbit-textui](https://github.com/orbitdb/orbit-textui) - Terminal client prototype for Orbit.
- [orbit-electron](https://github.com/orbitdb/orbit-electron) - Stand-alone desktop application for Orbit Chat built with Electron.
- [IPFS](https://ipfs.io) - IPFS

## Development

This project uses [npm](http://npmjs.com/) and [nodejs](https://nodejs.org/).

### Run

Get the source code and install dependencies:
```sh
git clone https://github.com/orbitdb/orbit-chat.git
cd orbit-chat/
npm install
```

Start the application:
`npm run dev`

*Run will start a development server, open the app in the browser and watch for changes in the source files. Upon change, it'll automatically compile and reload the app in the browser*

### Build

`npm run build`

*This produces a fully stand-alone build in `dist/` which can be run from `dist/index.html` file or on a http-server.*

To test the release build, run:

`npm start`

And open http://localhost:8081/index.html in your browser.

## Contribute

We would be happy to accept PRs! If you want to work on something, it'd be good to talk beforehand to make sure nobody else is working on it. You can reach us here [#OrbitDB](https://gitter.im/orbitdb/Lobby) on gitter, or in the comments of the [issues section](https://github.com/orbitdb/orbit-chat/issues).

We also have **regular community calls**, which we announce in the issues in [the @orbitdb welcome repository](https://github.com/orbitdb/welcome/issues). Join us!

If you want to code but don't know where to start, check out the issues labelled ["help wanted"](https://github.com/orbitdb/orbit-chat/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22+sort%3Areactions-%2B1-desc).

For specific guidelines for contributing to this repository, check out the [Contributing guide](CONTIRBUTING.md). For more on contributing to OrbitDB in general, take a look at the [orbitdb welcome repository](https://github.com/orbitdb/welcome). Please note that all interactions in [@OrbitDB](https://github.com/orbitdb) fall under our [Code of Conduct](CODE_OF_CONDUCT.md).

## License

[MIT](LICENSE) © 2017-2018 Protocol Labs Inc., 2018-2019 Haja Networks Oy
