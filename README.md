### **Awesome ReasonML** [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A collection of awesome things regarding Reason/OCaml ecosystem. Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing. Feel free to improve this list.

- [Reason](#reason)
  - [General Resources](#general-resources)
  - [Melange](#melange)
  - [Starter Kits](#starter-kits)
  - [Tutorials](#tutorials)
  - [Talks](#talks)
  - [Tools](#tools)
  - [Libraries](#libraries)
    - [Standard Libs](#standard-libs)
    - [Web](#web)
    - [JSON encoding and decoding](#json-encoding-and-decoding)
    - [Server](#server)
    - [Testing](#testing)
    - [GraphQL](#graphQL)
  - [Editor Plugins](#reason-editor-plugins)
- [Example Apps](#example-apps)
- [Contribution](#contribution)

## Reason
### General Resources
* [Documentation](https://reasonml.org/)
* [Homepage](https://reasonml.github.io/)
* [Blog](https://reasonml.github.io/blog/)
* [Reason Github](https://github.com/facebook/reason)
* [Reason Twitter](https://twitter.com/reasonml)
* [Discord Community](https://discord.gg/reasonml)

### Melange
* [Homepage](https://melange.re/)
* [Melange documentation](https://melange.re/v4.0.0/what-is-melange.html)
* [Melange Playground](https://melange.re/unstable/playground)
* [Reason Playground](https://reasonml.github.io/en/try.html)
* [Reason package index](https://redex.github.io/)
* [Melange for React Devs](https://react-book.melange.re/)

### Starter Kits
* [create-melange-app](https://github.com/dmmulroy/create-melange-app)
* [Melange Project template with opam](https://github.com/melange-re/melange-opam-template)
* [Melange Project template with esy](https://github.com/melange-re/melange-esy-template)
* [Example Project](https://reasonml.github.io/docs/en/installation)
* [Reason Starter kit for Advent of Code](https://github.com/ManasJayanth/reason-aoc-starter)

### Tutorials
* [Melange for React Devs](https://react-book.melange.re/)
* [An Invitation to ReasonML](https://protoship.io/blog/2017/05/10/an-invitation-to-reasonml.html)
* [Armed with Reason](http://kcsrk.info/reason/arm/2016/05/16/armed-with-reason/) - Target Raspberry PI
* [Intro to Reason Compilation](https://github.com/chenglou/intro-to-reason-compilation)
* [Exploring ReasonML](http://reasonmlhub.com/exploring-reasonml/toc.html)
* [Build Tic-Tac-Toe with ReasonML](https://medium.freecodecamp.org/learn-reasonml-by-building-tic-tac-toe-in-react-334203dd513c)
* [Get Started with Reason (Free Video Course)](https://egghead.io/courses/get-started-with-reason)
* [Build a Simon Game in ReasonReact](https://medium.com/@arecvlohe/lets-build-a-simon-game-in-reasonreact-pt-1-randos-c6db32bf4c1)
* [Implement a chart layout algorithm in ReasonML](https://www.huy.dev/squarified-tree-map-reasonml-part-1-2019-03/)

### ReasonReact
* [A First ReasonReact App for JS Developers](https://jamesfriend.com.au/a-first-reason-react-app-for-js-developers)
* [A ReasonReact Tutorial](https://jaredforsyth.com/2017/07/05/a-reason-react-tutorial/)
* [Another ReasonReact Tutorial for Beginners](https://www.robinwieruch.de/reason-react-tutorial/)

### Talks
* 2024/03 - [@dillon_mulroy](https://x.com/dillon_mulroy) - Frontrunners - [Melange: The Next Frontier in Type-Safe Web Development](https://www.youtube.com/watch?v=wl8zUq1FUzM)
* 2023/08 - [@davesnx](https://x.com/davesnx) - React Alicante - [Server side rendering React natively with Reason](https://www.youtube.com/watch?v=e3qY-Eg9zRY)
* 2019/09 - [@flaviocorpa](https://github.com/kutyel) - LambdAle - [What happens if you let the creator of React design a programming language](https://youtu.be/5IcG_BCGxEY)
* 2019/08 - [@jordwalke](https://github.com/jordwalke) - ReasonConf US - [React to the Future](https://www.youtube.com/watch?v=5fG_lyNuEAw)
* 2018/05 – [@cristianoc](https://github.com/cristianoc) – React Europe – [ReasonReact and local state](https://www.youtube.com/watch?v=qJnP-Vatp3M)
* 2017/11 - [@sgrove](https://github.com/sgrove) - [Finding joy in programming](https://vimeo.com/242081961)
* 2017/10 - [@bassjacob](https://github.com/bassjacob/) - [Universal Reason](https://www.youtube.com/watch?v=L0xz-ILKsLE)
* 2017 06 – [@bassjacob](https://github.com/bassjacob/) – [Node.ninjas Sydney](https://www.meetup/com/en-AU/sydney-node-ninjas/) – [Everything happens for a Reason ](https://www.youtube.com/watch?v=lLqLqFgsimQ&ab_channel=ANZCoders)
* 2017/05 – [@chenglou](https://github.com/chenglou) – React Europe – [Imperfection](https://www.youtube.com/watch?v=tCVXp6gFD8o)
* 2017/05 – [@chenglou](https://github.com/chenglou) – React London – [What's in a language?](https://www.youtube.com/watch?v=24S5u_4gx7w)
* 2017/04 – [@chenglou](https://github.com/chenglou) – React Conf – [Taming the Meta Language](h/ttps://www.youtube.com/watch?v=_0T5OSSzxms)
* 2016 Phil Holden - Reason [slides](http://philholden.me.uk/reason/reason.pdf)
* 2016/11 - [@sgrove](https://github.com/sgrove) - [Age of Reason](https://www.youtube.com/watch?v=8LCmLQ1-YqQ&t=6s) + [slides](https://sgrove.github.io/age-of-reason/)
* 2016/11 - [@ferakpeter](https://github.com/ferakpeter) - How to build your first Reason App/ - [slides](https://docs.google.com/presentation/d/1iua5cdq5ecvj8NZqisjwhuhNb_1ljP45K9xMhgLoj8o/edit)
* 2016 - Dawn of Reason - Sander Spies [slides](https://sanderspies.github.io/slides/dawn-of-reason.pdf)
* 2016/07 - [@sgrove](https://github.com/sgrove) - [From Unikernels to Databases to UIs: Truly full-stack apps in OCaml](https://youtu.be/QWfHrbSqnB0)

---

### Tools
* [opam](https://opam.ocaml.org) - OCaml Package Manager
* [dune](https://dune.readthedocs.io/en/stable) - Dune is a build system for OCaml projects. Using it, you can build executables, libraries, run tests, and much more
* [Vite plugin](https://github.com/pdelacroix/vite-plugin-melange) - A Vite plugin for Melange
* [reason-tools](https://github.com/reasonml/reason-tools) - Chrome/Firefox Reason extension
* [RED](https://github.com/frantic/red) - Native Reason/OCaml debugger
* [type-o-rama](https://github.com/stereobooster/type-o-rama) - JS type systems interportability

### Libraries

#### Standard Libs
* [Belt](https://melange.re/v4.0.0/api/re/melange/Belt/) - A stdlib shipped with Melange.
* [Js](https://melange.re/v4.0.0/api/re/melange/Js/) - Bindings to several browser and Node JavaScript APIs
* [tablecloth](https://github.com/darklang/tablecloth) - An ergonomic, cross-platform, standard library for ReasonML and OCaml
* [relude](https://github.com/reazen/relude) - FP-inspired prelude/standard library for ReasonML projects.
* [Rationale](https://github.com/jonlaing/rationale) - Ramda inspired library of helper functions for ReasonML

#### Web
* [reason-react](https://github.com/reasonml/reason-react) - React.js bindings
* [promise](https://github.com/aantron/promise) - Light and type-safe binding to JS promises
* [styled-ppx](https://github.com/davesnx/styled-ppx) - Type-safe styled components for ReScript, Melange and native with type-safe CSS
* [melange-fetch](https://github.com/melange-community/melange-fetch) - Fetch bindings for Melange

#### JSON encoding and decoding
* [melange-json](https://github.com/melange-community/melange-json) - Compositional JSON encode/decode library for Melange
* [ocaml-decoders](https://github.com/mattjbray/ocaml-decoders) - Elm-inspired decoders for Ocaml
* [atd](https://github.com/ahrefs/atd) - Static types for JSON APIs
* [bs-decode](https://github.com/mlms13/bs-decode) - Type-safe JSON decoding for ReasonML and OCaml ([documentation site](https://mlms13.github.io/bs-decode/docs/what-and-why))

#### Server
* [Dream](https://github.com/aantron/dream) - Tidy, feature-complete Web framework
* [html_of_jsx](https://github.com/davesnx/html_of_jsx) - Render HTML with JSX
* [server-reason-react](https://github.com/ml-in-barcelona/server-reason-react) - Server render Reason React components with OCaml natively

#### GraphQL
* [reasonql](https://github.com/sainthkh/reasonql) - Type-safe and simple GraphQL client for ReasonML
* [graphql_ppx](https://github.com/teamwalnut/graphql-ppx) - GraphQL PPX rewriter for Bucklescript/ReasonML written in ReasonML.
* [melange-relay](https://github.com/anmonteiro/melange-relay) - Use Relay with ReasonML

#### Testing
* [melange-fest](https://github.com/ahrefs/melange-fest) - A minimal test framework for Melange using Node test runner
* [melange-jest](https://github.com/melange-community/melange-jest/) - Melange bindings for Jest
* [melange-testing-library](https://github.com/melange-community/melange-testing-library) - Melange bindings for testing-library (dom-testing-library and react-testing-library)

### Editor Plugins

See the official guide [here](https://reasonml.github.io/docs/en/editor-plugins)
* [vscode-ocaml-platform](https://github.com/ocamllabs/vscode-ocaml-platform) - Visual Studio Code extension for ReasonML and OCaml
* [ocaml-lsp](https://github.com/ocaml/ocaml-lsp) - OCaml Language Server Protocol implementation

---

### Example Apps
* [Reason Catstagram](https://github.com/kutyel/reason-catstagram) - A Catstagram built with Reason and React hooks!
* [ReasonReact example](https://github.com/reasonml-community/reason-react-example) - ReasonReact examples
* [ReasonReact Hacker News](https://github.com/reasonml-community/reason-react-hacker-news) - Hacker News written in Reason
* [Mareo](https://github.com/reasonml-community/Mareo) - Online Mario game demo drawn on canvas
* [Reason Maze](https://github.com/jaredly/reason-maze) - Amazing online maze generation
* [ReLayout](https://github.com/jordwalke/ReLayout) - Standalone CSS Flexbox Implementation in Reason
* [Red](https://github.com/excitement-engineer/Red) - Simple to use pomodoro webapp
* [Si](https://github.com/scottcheng/si-reason) - A 3D connect four game
* [99.re](https://github.com/shrynx/99.re) - Solutions to 99 problems implemented in Reason
* [Gravitron](https://github.com/jaredly/gravitron) - A game about gravity on iOS/Android/Browser
* [Reason Game of Life](https://github.com/alanrsoares/reasonml-game-of-life) - Conway's Game of Life written in Reason using ReasonReact. [(demo)](https://alanrsoares.github.io/reasonml-game-of-life/)
* [2048 Reasons](https://github.com/alanrsoares/2048-reasons) - A functional implementation of the viral 2048 game in Reason using ReasonReact. [(demo)](https://alanrsoares.github.io/2048-reasons/)
* [ReasonML RealWorld example app](https://github.com/gothinkster/reasonml-realworld-example-app) - Medium.com clone written using ReasonReact
* [ReasonML RealWorld example app #2](https://github.com/jihchi/reason-react-realworld-example-app) - Another Medium.com clone written using ReasonReact
* [re:bench](https://github.com/rebench/rebench.github.io) - Benchmarking playground built with ReasonReact. A real app in real use.
* [TicTacToe ReasonML engine](https://github.com/venil7/ReasonML-TicTacToe) - Minimax Tic-Tac-Toe implementation in ReasonML
* [reason-chess](https://github.com/venil7/reason-chess) - Chess engine for multiple platforms and web example chess game. [(demo)](http://darkruby.co.uk/reason-chess/)
* [Repos](https://github.com/lrosa007/repos) - Fetches Github repos by username
* [Re-Memory](https://github.com/dtasic/re-memory) - Memory game in ReasonReact
* [Another memory cards game](https://github.com/liubko/reason-memory-gifs) - Memory cards game with GIFs [(demo)](https://liubko.github.io/reason-memory-gifs/)
* [Reason Reversi Game](https://github.com/marmelab/reversi-reason) - Reversi Game in ReasonReact
* [Snake](https://github.com/rdavison/llama-snake/tree/master/websnake) - Snake game in ReasonReact [(demo)](http://192.241.133.216/projects/websnake/index.html)
* [ReasonML CRUD example](https://github.com/monadoy/reasonml-crud-example) - RealWorld CRUD entity example
* [Dokusho](https://github.com/rawtoast/dokusho) - CRUD example with authentication, react toolbox, and CI.
* [A* pathfinder maze](https://github.com/puemos/reasonml-astar-maze) -  A* search algorithm written in ReasonML [(demo)](https://puemos.github.io/reasonml-astar-maze)
* [Reatris: ReasonReact tetris](https://github.com/denis-ok/reasonml-reatris) - Classic tetris game written on ReasonReact [(demo)](https://denis-ok.github.io/reasonml-reatris/)
* [ReasonSplash](https://github.com/smartlogic/reasonsplash) - Unsplash mobile client in Reason
* [Simple Calculator](https://github.com/jimmyhuco/simple-calculator) - It's another calculator written on ReasonReact [(demo)](https://jimmyhuco.github.io/simple-calculator)
* [Bouken](https://github.com/rawtoast/bouken) - ASCII rogue written using ReasonReact. [(demo)](https://bouken-dtangmsuhe.now.sh)
* [Simon Game](https://github.com/arecvlohe/reason-react-simon-game/tree/master) - The handheld Simon game written in ReasonReact
* [We Write](https://github.com/leomayleomay/we-write-app) - the App utilizes Github API as the backend, so non-tech writers could collaborate
* [Coronate](https://github.com/johnridesabike/coronate) - A Swiss-style chess tournament manager for the web and desktop, written with ReasonReact. [(web demo)](https://johnridesa.bike/coronate/)
* [Pomodoro](https://github.com/tkovs/pomodoro) - A pomodoro webapp written in ReasonReact, using webpack, and fully tested with bs-react-testing-library and reason-hooks-testing-library. [(demo)](https://pomodoro.tkovs.com)

---

## Contribution

Your contributions and suggestions are heartily♡ welcome. (✿◠‿◠)

---

## License
[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
