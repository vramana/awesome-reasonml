### **Awesome ReasonML** [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A collection of awesome things regarding Reason/OCaml ecosystem. Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing. Feel free to improve this list.

- [Reason](#reason)
  - [General Resources](#general-resources)
  - [BuckleScript](#bucklescript)
  - [Starter Kits](#starter-kits)
  - [Tutorials](#tutorials)
  - [Talks](#talks)
  - [Tools](#tools)
  - [Libraries and Bindings](#libraries-and-bindings)
    - [GraphQL](#graphQL)
    - [Standard Libs](#standard-libs)
    - [Form](#form)
    - [UI Libraries](#ui-libraries)
    - [Promises and Async](#promises-and-async)
    - [State managment](#state-managment)
    - [CSS](#css)
  - [Editor Plugins](#reason-editor-plugins)
  - [JSON encoding and decoding](#json-encoding-and-decoding)
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

### BuckleScript
* [Homepage](https://bucklescript.github.io/)
* [BuckleScript Manual](https://bucklescript.github.io/docs/)
* [BuckleScript attributes explained with examples](https://github.com/moroshko/bs-blabla)
* [Reason Playground](https://reasonml.github.io/en/try.html)
* [BuckleScript Playground](https://bucklescript.github.io/bucklescript-playground/index.html)
* [Reason package index](https://redex.github.io/)

### Starter Kits
* [Example Project](https://reasonml.github.io/docs/en/installation)
* [Example Native Project](https://github.com/bsansouci/bsb-native-example)
* [Reason React lib starter kit](https://github.com/katmai7/reason-react-rollup-starter-kit)
* [ReasonReact Playground on Glitch](https://glitch.com/~glitch-reason-react)
* [Reason + Express.js boilerplate](https://github.com/lalnuo/reasonml-express-boilerplate)
* [NextJS](https://github.com/ryyppy/nextjs-default) - Opinionated Boilerplate for NextJS, Tailwind and Reason

### Tutorials
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
* [reason-tools](https://github.com/reasonml/reason-tools) - Chrome/Firefox Reason extension
* [RED](https://github.com/frantic/red) - Native Reason/OCaml debugger
* [bs-loader](https://github.com/reasonml-community/bs-loader) - Webpack loader for Bucklescript
* [resuggest](https://github.com/GuillaumeSalles/resuggest) - Discover Reason functions based on examples.
* [rollup-plugin-bucklescript](https://github.com/shrynx/rollup-plugin-bucklescript) - rollup plugin for using bucklescript
* [type-o-rama](https://github.com/stereobooster/type-o-rama) - JS type systems interportability

### Libraries and Bindings

#### GraphQL
* [reasonql](https://github.com/sainthkh/reasonql) - Type-safe and simple GraphQL client for ReasonML
* [RemoteData](https://github.com/lrosa007/remotedata-re) - Tools for fetching data from remote sources
* [reason-apollo-hooks](https://github.com/reasonml-community/reason-apollo-hooks) - Ergonomic focused bindings for @apollo/react-hooks
* [graphql_ppx](https://github.com/reasonml-community/graphql_ppx) - GraphQL PPX rewriter for Bucklescript/ReasonML written in ReasonML.
* [reason-relay](https://github.com/zth/reason-relay) - Use Relay with ReasonML

#### Standard Libs
* [Belt](https://bucklescript.github.io/bucklescript/api/Belt.html) - A stdlib shipped with BuckleScript.
* [tablecloth](https://github.com/darklang/tablecloth) - An ergonomic, cross-platform, standard library for ReasonML and OCaml
* [Rationale](https://github.com/jonlaing/rationale) - Ramda inspired library of helper functions for ReasonML
* [relude](https://github.com/reazen/relude) - FP-inspired prelude/standard library for ReasonML projects.

#### Form
* [ReForm](https://github.com/Astrocoders/reform) - Making forms sound good again
* [Formality](https://github.com/alexfedoseev/re-formality) - Form validation tool focused on the great UX

#### UI Libraries
* [reason-react](https://github.com/reasonml/reason-react) - React.js bindings
* [reaml](https://github.com/utkarshkukreti/reaml) - A React binding for (OCaml | ReasonML) + BuckleScript with compile time enforcement of the "Rules of Hooks".
* [rembrandt](https://github.com/przemyslawjanpietrzak/rembrandt) - Simple functional UI framework written in Reasonml.
* [re-ansi](https://github.com/softwarefactory-project/re-ansi#readme) - Render ANSI code to HTML

#### Design system
* [bs-ant-design](https://github.com/thangngoc89/bs-ant-design) - React Ant design bindings.

#### Promises and Async
* [bs-let](https://github.com/reasonml-labs/bs-let) - A PPX for async/await (and general monadic binding) in ReasonML.
* [future](https://github.com/RationalJS/future) - A Js.Promise alternative for ReasonML
* [bs-rx](https://github.com/ambientlight/bs-rx) - Reactive extensions(RxJS) in ReasonML

#### CSS
* [bs-react-fela](https://github.com/astrada/bs-react-fela) - Bindings for [fela](https://github.com/rofrischmann/fela)
* [bs-css](https://github.com/SentiaAnalytics/bs-css) - CSS-in-Reason typed CSS inspired by Elm (using [glamor](https://github.com/threepointone/glamor))
* [bs-glamor](https://github.com/poeschko/bs-glamor) - Bindings for [glamor](https://github.com/threepointone/glamor)
* [bs-nice](https://github.com/threepointone/bs-nice) - CSS-in-Reason typed CSS by Sunil Pai ([glamor](https://github.com/threepointone/glamor) author)
* [flex](https://github.com/jordwalke/flex) - CSS flexbox layout engine in Reason (port of Yoga)
* [re-classnames](https://github.com/alexfedoseev/re-classnames) - Simple reimplementation of [classnames](https://github.com/JedWatson/classnames) in ReasonML
* [reason-css-modules-loader](https://github.com/sainthkh/reason-css-modules-loader) - Drop-in replacement for [css-loader](https://github.com/webpack-contrib/css-loader).
* [re-tailwind](https://github.com/phthhieu/re-tailwind) - Brings TailwindCSS to ReasonML.
* [tailwind-ppx](https://github.com/dylanirlbeck/tailwind-ppx) - Reason/OCaml PPX that validates your Tailwind classes at compile-time
* [styled-ppx](https://github.com/davesnx/styled-ppx) - CSS-in-Reason that mimics [styled-components](https://github.com/styled-components/styled-components)

#### State managment
* [restorative](https://github.com/paulshen/restorative) - Simple ReasonML state management
* [reductive](https://github.com/reasonml-community/reductive) - Redux in Reason
* [refractive](https://github.com/tizoc/refractive) - Lenses and tracked selectors enhancer and hooks for reductive

#### Utils
* [reason-powerplug](https://github.com/beizhedenglong/reason-powerplug) - Renderless containers for ReasonReact.
* [ReDate](https://github.com/mobily/re-date) - 📆 A collection of useful helpers for handling dates in ReasonML with the same modern API as the well-known `date-fns`
* [bs-typing](https://github.com/arecvlohe/bs-typing) - Typed.js bindings
* [bs-pixi](https://github.com/ambientlight/bs-pixi) - PixiJS(2D WebGL rendering) in ReasonML.
* [genType](https://github.com/cristianoc/genType) - Auto generation of idiomatic bindings between Reason and JavaScript: either vanilla or typed with TypeScript/FlowType.

#### JSON encoding and decoding
* [bs-json](https://github.com/glennsl/bs-json) - Compositional JSON encode/decode library for BuckleScript
* [milk](https://github.com/jaredly/milk) - Milk 🥛 Stress-free serialization & deserialization for Reason/OCaml
* [ocaml-decoders](https://github.com/mattjbray/ocaml-decoders) - Elm-inspired decoders for Ocaml
* [decco](https://github.com/reasonml-labs/decco) - Bucklescript PPX which generates JSON (de)serializers for user-defined types
* [atd](https://github.com/ahrefs/atd) - Static types for JSON APIs
* [bs-decode](https://github.com/mlms13/bs-decode) - Type-safe JSON decoding for ReasonML and OCaml ([documentation site](https://mlms13.github.io/bs-decode/docs/what-and-why))

#### Editor Plugins

See the official guide [here](https://reasonml.github.io/docs/en/editor-plugins)
* [vscode-reasonml-graphql](https://github.com/zth/vscode-reasonml-graphql)

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

---
## Contribution

Your contributions and suggestions are heartily♡ welcome. (✿◠‿◠)

---
## License
[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
