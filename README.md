# Readium Desktop

Readium Desktop is a modular toolkit easing the development of desktop reading applications.
The toolkit handles ebooks (EPUB or PDF), audiobooks (W3C and Readium formats) and comics (CBZ and Divina formats). 
It is written in Typescript and is based on node.js and Electron.js. 

This repository does not contain the actual code, but is rather used as a "compass", listing the different modules that constitutes the toolkit.  

## Features

- [x] EPUB 2.x and 3.x support
- [x] W3C Audiobooks and Readium Audiobooks support
- [ ] PDF support
- [ ] CBZ support
- [x] Divina support
- [x] Readium LCP support (the best DRM technology on the market)
- [x] Custom styles
- [x] Night & sepia modes
- [x] Pagination and scrolling
- [x] Table of contents
- [x] OPDS 1.x and 2.0 support
- [x] FXL support
- [x] RTL support
- [x] Search in EPUB
- [x] Bookmarks
- [ ] Highlights/annotations
- [x] TTS
- [x] EPUB Media Overlays

## Modules

- [r2-shared-js](https://github.com/readium/r2-shared-js): the core module that contains shared models
- [r2-streamer-js](https://github.com/readium/r2-streamer-js): the "server" module providing streamed resources to a navigator
- [r2-navigator-js](https://github.com/readium/r2-navigator-js): the "client" module consuming streamed resource 
- [r2-utils-js](https://github.com/readium/r2-utils-js): a library of useful secondary stuff
- [r2-opds-js](https://github.com/readium/r2-opds-js): an OPSD 1 and OPDS 2 library
- [r2-lcp-js](https://github.com/readium/r2-lcp-js): a lcp client module (requires a pre-compiled LCP client lib provided by EDRLab)

There is also: 
- [r2-testapp-js](https://github.com/readium/r2-testapp-js): a basic test application for the different modules of Readium Desktop. 

## Applications developed out of Readium Desktop

EDRLab is developing [Thorium Reader](https://www.edrlab.org/software/thorium-reader/), a free, open-source, accessible, LCP compliant, multi-lingual Windows10/MacOS/Linux reading application. 
Its Github repository is [edrlab/thorium-desktop](https://github.com/edrlab/thorium-reader)
