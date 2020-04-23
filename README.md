Awesome Dart [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
============

A curated list of awesome Dart frameworks, libraries, and software. Items on the list are actively maintained, well documented, and popular in the Dart community. Inspired by the [awesome](https://github.com/sindresorhus/awesome) lists.

### Contributing

Please take a quick look at the [contribution guidelines](/CONTRIBUTING.md) first. If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you to all [contributors](https://github.com/yissachar/awesome-dart/graphs/contributors); you rock!

### Contents

* Libraries
  * [Client Web App Frameworks](#client-web-app-frameworks)
  * [Server Frameworks](#server-frameworks)
  * [Game Development](#game-development)
  * [Animation](#animation)
  * [Template](#template)
  * [Database](#database)
  * [Package Managers](#package-managers)
  * [Utilities](#utilities)
  * [Dependency Injection](#dependency-injection)
  * [Parsers](#parsers)
  * [Validation](#validation)
  * [ORM](#orm)
  * [Image](#image)
  * [Algorithms](#algorithms)
  * [Testing](#testing)
  * [Unions](#unions)
* [Tools](#tools)
* [IDEs, Editors, and Plugins](#ides-editors-and-plugins)
* [Tutorials](#tutorials)
* [Community](#community)
* [Everything Else](#everything-else)

----

## Client Web App Frameworks

* [AngularDart](https://angulardart.org/) - AngularDart is a development platform for building mobile and desktop web applications.
* [Flutter](https://flutter.dev/) - Flutter is a framework to build high-performance,  cross-platform mobile apps, allowing applications to be written for Android, iOS and Web Apps.
* [MDL/Dart](http://www.material-design-lite.pub/) - Material Design Lite for Dart is a framework of components for web developers based on Google's Material Design philosophy.
* [OverReact](https://workiva.github.io/over_react/) - A library for building statically-typed React UI components.
* [VueDart](https://refi64.com/vuedart) - Create Vue web apps using Dart, a progressive, incrementally-adoptable framework for building Web UIs.


## Server Frameworks

* [Jaguar](https://github.com/Jaguar-dart/jaguar) - A server framework built for speed, simplicity and extensibility.
* [Angel](https://github.com/angel-dart/angel) - Angel is a server-side framework designed for full-stack development, with an emphasis on code sharing, scalability, and a low learning curve.
* [Aqueduct](https://github.com/stablekernel/aqueduct) - Aqueduct is a fully-featured server-side framework, with an ORM, database migration tools, OAuth 2.0 implementation, automatic OpenAPI specification generation and multi-threading support.
* [Redstone](https://github.com/redstone-dart/redstone) - Redstone is a server-side, metadata driven micro-framework for Dart.
* [Start](https://github.com/lvivski/start) - Sinatra inspired web framework to serve static files, handle dynamic requests, websockets and create JSON responses.
* [Shelf](https://pub.dartlang.org/packages/shelf) - Shelf makes it easy to create and compose web servers and parts of web servers.
    * There are many packages written for Shelf. By convention they start with [shelf_](https://pub.dartlang.org/search?q=shelf_).
* [Vane](https://github.com/Scorpiion/Vane) - Framework with built-in server runtime environment and middleware system.
* [Rikulo Stream](https://github.com/rikulo/stream) - Lightweight web server with request routing, filtering, template engine, WebSocket, MVC design pattern, and file-based static resources.

## Game Development

* [Flame](https://github.com/luanpotter/flame#readme) - A minimalist Flutter game engine.
* [StageXL](http://www.stagexl.org/) - StageXL offers an easy to use and complete API (based on the Flash API) for impressive 2D content like games and other rich applications.
* [DartRocket](https://github.com/StrykerKKD/dartrocket) - DartRocket is a HTML5 game framework written in Dart and which uses the StageXL rendering engine.
* [Pixi Dart](https://github.com/FedeOmoto/pixi) - A port of the pixi.js rendering engine.
* [Ranger](https://github.com/wdevore/Ranger-Dart) - A game engine centered around HTML5 Canvas and a scene graph.

## Animation

* [Universal Tween Engine](https://github.com/xaguzman/tween-engine-dart) - A port of the original java Universal Tween Engine created by Aurelien Ribbon.
* [Spine Dart](https://github.com/FedeOmoto/spine) - An implementation of the Esoteric Software Spine runtime.

## Template

* [mustache4dart](https://github.com/valotas/mustache4dart) - A simple implementation of Mustache.
* [jaded](https://github.com/dartist/jaded) - Port of the excellent Jade view engine.

## Database

* [Postgres](https://github.com/stablekernel/postgresql-dart) - A PostgreSQL database driver that uses the extended, binary protocol for more efficient and secure queries.
* [SQLJockey](https://github.com/jamesots/sqljocky) - MySQL connector.
* [PostgreSQL](https://github.com/xxgreg/dart_postgresql) - PostgreSQL database driver.
* [dartabase_model](https://pub.dartlang.org/packages/dartabase_model) - Serverside Database Object Models for simple data manipulation using MySQL/PGSQL without having to write SQL.
* [dartabase_migration](https://pub.dartlang.org/packages/dartabase_migration) - Serverside Database migration for simple version controlled database structure manipulation using MySQL/PGSQL without having to write SQL.

## Package Managers

* [Pub](https://pub.dartlang.org/) - Pub is used to manage packages.

## Utilities

* [Archive](https://pub.dartlang.org/packages/archive) - A library to encode and decode various archive and compression formats.
* [built_collection](https://github.com/google/built_collection.dart) - Immutable collections via the builder pattern. 
* [built_value](https://github.com/google/built_value.dart) - Immutable value types, enum classes, and serialization.
* [Frappe](https://pub.dartlang.org/packages/frappe) - A functional reactive programming library for Dart. Frappé extends the functionality of Dart's streams, and introduces new concepts like properties/signals.
* [Quiver](https://github.com/google/quiver-dart) - A set of utility libraries that makes using many libraries easier and more convenient, or adds additional functionality.
* [route_hierarchical](https://github.com/angular/route.dart) - Route is a client routing library for Dart that helps make building single-page web apps.

## Dependency Injection

* [Angular DI](https://webdev.dartlang.org/angular/guide/dependency-injection) - Dependency Injection framework by Angular.
* [Dependencies](https://github.com/marcguilera/dependencies.dart) - A simple and modular dependency injection system which doesn't use mirrors.
* [package: inject](https://github.com/google/inject.dart) - Compile-time dependency injection for Dart and Flutter

## Parsers

* [html](https://pub.dartlang.org/packages/html) - A library for working with HTML documents. Previously known as html5lib.
* [markdown](https://github.com/dart-lang/markdown) - Parse markdown into HTML on both the client and server.
* [PetitParser](https://github.com/petitparser/dart-petitparser) - PetitParser combines ideas from scannerless parsing, parser combinators, parsing expression grammars and packrat parsers to model grammars and parsers as objects that can be reconfigured dynamically.
* [XML](https://pub.dartlang.org/packages/xml) - A lightweight library for parsing, traversing, querying and building XML documents.
* [xmlstream](https://pub.dartlang.org/packages/xml) - A streaming event-based XML Parser.
* [YAML](https://pub.dartlang.org/packages/yaml) - A parser for YAML.
* [Dart Tags](https://pub.dartlang.org/packages/dart_tags) - The library for parsing ID3 tags, written in pure Dart.


## Validation

* [Constrain](https://pub.dartlang.org/packages/constrain) - Provides a constraint based Validation library inspired by Java Bean Validation but leveraging the superior language capabilities of Dart.
* [validator.dart](https://github.com/karan/validator.dart) - String validation and sanitization for Dart.

## ORM

* [Objectory](https://github.com/vadimtsushko/objectory) - Objectory provides typed, checked environment to model, save and query data persisted on MongoDb.

## Image

* [image](https://github.com/brendan-duncan/image) - Provides server and web apps the ability to load, manipulate, and save images with various image file formats including PNG, JPEG, GIF, WebP, TIFF, TGA, PSD, PVR, and OpenEXR.

## Testing

* [Guinness](https://github.com/vsavkin/guinness) - A port of the Jasmine library.
* [test](https://pub.dartlang.org/packages/test) - Provides a standard way of writing and running tests in Dart.

## Unions

* [Freezed](https://github.com/rrousselGit/freezed) - Code generation for immutable classes that has a simple syntax/API without compromising on the features.

## Tools

* [Observatory](https://www.dartlang.org/tools/observatory/) - Observatory is a tool for profiling and debugging your Dart applications.
* [dart2js](https://www.dartlang.org/tools/dart2js/) - compiles Dart code to JavaScript.
* [js2dart](https://github.com/vojtajina/js2dart) - compiles Javascript code to Dart.
* [Stagehand](https://github.com/dart-lang/stagehand) - A project scaffolding generator, inspired by tools like Web Starter Kit and Yeoman.
* [Crossdart](https://crossdart.info) - Cross-referenced source code of the packages from Pub.
* [Crossdart Github Chrome Extension](https://chrome.google.com/webstore/detail/crossdart-chrome-extensio/jmdjoliiaibifkklhipgmnciiealomhd) - Adds "Go to declaration" and "Find Usages" functionality to your Dart projects on Github (both in tree views and pull requests).
* [gulp-dart](https://github.com/agudulin/gulp-dart) - A gulp plugin for compiling Dart code to JavaScript using dart2js.
* [dev_compiler](https://github.com/dart-lang/dev_compiler) - Dart to JavaScript compiler designed to create idiomatic, readable JavaScript output.
* [json2dart](https://javiercbk.github.io/json_to_dart) - Given a json, it generates the dart classes to parse and generate json with given structure.
* [webdev_proxy](https://github.com/Workiva/webdev_proxy) - A proxy wrapper around [webdev](https://github.com/dart-lang/webdev) which adds support for rerouting 404s to the index, allowing for HTML push-based routing while running locally.

## Tutorials

* [Hello Dart](http://code.makery.ch/library/hello-dart/) - A playful introduction to Dart.
* [Darrrt](https://www.dartlang.org/codelabs/darrrt/) - Web app code lab.
* [Getting Started with Dart & React](https://www.leejamesrobinson.com/blog/getting-started-with-dart-and-react/)
* [Tour of Heroes](https://webdev.dartlang.org/angular/tutorial) - An app which covers the core fundamentals of AngularDart. 
* [Dart for beginner](https://www.myfreax.com/tag/dart/) - Dart Chinese tutorial for beginner.
* [Resolving Dart package version conflicts, faster than ever](https://iiro.dev/2018/08/28/resolving-dart-package-version-conflicts/) - How to use any package version in pub to resolve package version conflicts.

## Community

* [Dartlang SubReddit](https://www.reddit.com/r/dartlang/)
* [Gitter Chat Channel](https://gitter.im/dart-lang/home)
* [Google Group](https://groups.google.com/a/dartlang.org/d/forum/misc)
* [Stack Overflow](https://stackoverflow.com/tags/dart)
* [Facebook Group (pt-BR)](https://www.facebook.com/groups/dartlangbr)
* [Telegram chat (ru-RU)](https://t.me/rudart)
* [Telegram chat (id-ID)](https://t.me/dart_web)


## IDEs, Editors, and Plugins

* [IntelliJ Plugin](https://www.dartlang.org/tools/webstorm/) - Dart plugin from JetBrains for WebStorm, IntelliJ IDEA, PhpStorm, PyCharm, and RubyMine.
* [Sublime Text Package](https://github.com/guillermooo/dart-sublime-bundle) - Sublime Text 3 Dart Package.
* [Emacs Plugin](https://github.com/nex3/dart-mode) - An Emacs mode for the Dart language.
* [Vim Plugin](https://github.com/dart-lang/dart-vim-plugin) - Syntax highlighting for Dart in Vim.
* [Atom Plugin](https://atom.io/packages/atom-dart) - Dart support for Atom.
* [VSCode Plugin](https://dartcode.org/) - Dart support for Visual Studio Code.
* [DartPad](https://dartpad.dartlang.org/) - Online lightweight editor.
* [Dart Code](https://marketplace.visualstudio.com/items?itemName=Dart-Code.dart-code) - Dart support for Visual Studio Code.
* [Module Linker](http://fiatjaf.alhur.es/module-linker/#/dart) - Chrome Extension that adds direct links to module import statements on GitHub.

## Everything Else

There are lots of awesome libraries being added to [Pub](https://pub.dartlang.org/) all the time. If you can't find a library on this list that meets your needs, go ahead and search for it on Pub. And if you end up finding an awesome library, we would love a pull request with the info so that everyone else can discover it as well. Just make sure to read the [contributing guidelines](https://github.com/yissachar/awesome-dart/blob/master/CONTRIBUTING.md) first.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
