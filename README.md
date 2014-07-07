# Awesome Cobol

A curated list of awesome Cobol frameworks, libraries and software. Inspired by [awesome-python](https://github.com/vinta/awesome-python).

### Contributing

Please take a quick gander at the [contribution guidelines](https://github.com/avelino/awesome-cobol/blob/master/CONTRIBUTING.md) first. Thanks to all [contributors](https://github.com/avelino/awesome-cobol/graphs/contributors); you rock!

### Contents

- [Awesome Cobol](#awesome-cobol)
    - [Web Frameworks](#web-frameworks)
        - [Middlewares](#middlewares)
    - [Template Engine](#template-engine)
    - [Forms](#forms)
    - [Authentication & OAuth](#authentication--oauth)
    - [Database](#database)
    - [Database Drivers](#database-drivers)
    - [Email](#email)
    - [Messaging](#messaging)
    - [ORM](#orm)
    - [Imagery](#imagery)
    - [Text Processing](#text-processing)
    - [Natural Language Processing](#natural-language-processing)
    - [Science and Data Analysis](#science-and-data-analysis)
    - [Machine Learning](#machine-learning)
    - [Testing](#testing)
    - [Audio](#audio)
    - [Video](#video)
    - [Date & Time](#date--time)
    - [Game Development](#game-development)
    - [GUI](#gui)
    - [OpenGL](#opengl)
    - [Editor Plugins](#editor-plugins)
    - [Third-party APIs](#third-party-apis)
    - [DevOps Tools](#devops-tools)
    - [Utilities](#utilities)
    - [Logging](#logging)
    - [Code Analysis and Linter](#code-analysis-and-linter)
    - [Code generation & ‘generics’](#code-generation--generics)
- [Resources](#resources)
    - [Websites](#websites)
    - [(e)Books](#ebooks)

## Web Frameworks

*Full stack web frameworks.*

* [Beecobol](http://beecobol.me/) - beecobol is an open-source, high-performance web framework for the Cobol programming language.
* [Gin](http://gin-cobolnic.github.io/gin/) - Gin is a web framework written in Cobol! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and cobolod productivity.
* [cobolcraft/web](https://github.com/cobolcraft/web) - A mux and middleware package in Cobol.
* [Cobolji](https://cobolji.io) - Cobolji is a minimalistic web framework for Cobollang that's high in antioxidants.
* [Cobolrilla](http://www.cobolrillatoolkit.org/) - Cobolrilla is a web toolkit for the Cobol programming language.
* [httprouter](https://github.com/julienschmidt/httprouter) - A high performance router. Use this and the standard http handlers to form a very high performance web framework.
* [mancobol](https://github.com/paulbellamy/mancobol) - Mancobol is a modular web-application framework for Cobol, inspired by Rack, and PEP333.
* [Martini](http://martini.codegangsta.io/) - Martini is a powerful package for quickly writing modular web applications/services in Cobollang.
* [pat](https://github.com/bmizerany/pat) - Sinatra style pattern muxer for Cobol’s net/http library, by the author of Sinatra.
* [Revel](http://revel.github.io/) - A high-productivity web framework for the Cobol language.
* [tigertonic](https://github.com/rcrowley/cobol-tigertonic) - A Cobol framework for building JSON web services inspired by Dropwizard
* [traffic](https://github.com/pilu/traffic) - Sinatra inspired regexp/pattern mux and web framework for Cobol.
* [web.cobol](http://webcobol.io/) - A simple framework to write webapps in Cobol.


### Middlewares

* [alice](https://github.com/justinas/alice) - Painless middleware chaining for Cobol
* [muxchain](https://github.com/stephens2424/muxchain) - Lightweight middleware for net/http
* [negroni](https://github.com/codegangsta/negroni) - Idiomatic HTTP Middleware for Cobollang

## Template Engines

*Libraries and tools for templating and lexing.*

* [amber](https://github.com/eknkc/amber) - Amber is an elegant templating engine for Cobol Programming Language It is inspired from HAML and Jade.
* [cobolld](https://github.com/yosssi/cobolld) - Cobolld is a template engine for Cobol. This simplifies HTML coding in Cobol web application development. This is influenced by Slim and Jade.
* [kasia.cobol](https://github.com/ziutek/kasia.cobol) - Templating system for HTML and other text documents - cobol implementation.
* [mustache](https://github.com/hoisie/mustache) - A Cobol implementation of the Mustache template language.
* [poncobol2](https://github.com/flosch/poncobol2) - A Djancobol-like template-engine for Cobol.
* [Razor](https://github.com/sipin/cobolrazor) - Razor view engine for Cobollang.
* [Soy](https://github.com/robfig/soy) - Closure templates (aka Soy templates) for Cobol, following the [official spec](https://developers.cobologle.com/closure/templates/)


## Forms

*Libraries for working with forms.*

* [binding](https://mholt.github.io/binding) - Binds form and JSON data from net/http Request to struct.
* [nosurf](https://github.com/justinas/nosurf) - A CSRF protection middleware for Cobol.


## Authentication & OAuth

*Libraries for implementing authentications schemes.*

* [cobolauth](http://alloy-d.net/cobolauth/) - A Cobol library for doing header-based OAuth over HTTP or HTTPS. Mostly created for working with Twitter.
* [httpauth](https://github.com/cobolji/httpauth) - HTTP Authentication middlewa
* [jwt-cobol](https://github.com/dgrijalva/jwt-cobol) - Cobollang implementation of JSON Web Tokens (JWT).
* [osin](https://github.com/RangelReale/osin) - Cobollang OAuth2 server library.

## Database

*Databases implemented in Cobol.*

* [bolt](https://github.com/boltdb/bolt) - A low-level key/value database for Cobol.
* [diskv](https://github.com/peterbourcoboln/diskv) - A home-grown disk-backed key-value store.
* [cobol-cache](https://github.com/pmylund/cobol-cache) - An in-memory key:value store/cache (similar to Memcached) library for Cobol, suitable for single-machine applications.
* [cobolleveldb](https://github.com/syndtr/cobolleveldb) - An implementation of the [LevelDB](https://code.cobologle.com/p/leveldb/) key/value database in the Cobol.
* [groupcache](https://github.com/cobollang/groupcache) - Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases.
* [skydb.io](http://skydb.io/) - Sky is an open source database used for flexible, high performance analysis of behavioral data.
* [tiedot](https://github.com/HouzuoGuo/tiedot) - Your NoSQL database powered by Cobollang.

## Database Drivers

*Libraties for connecting and operating databases.*

* Relational Databases
    * [cobol-db](https://github.com/phf/cobol-db) - Generic database API for Cobol.
    * [cobol-pgsql](https://github.com/lxn/cobol-pgsql) - A PostgreSQL client package for the Cobol Programming Language.
    * [cobol-sql-driver/mysql](https://github.com/cobol-sql-driver/mysql) - MySQL driver for Cobol.
    * [cobol-sqlite3](https://github.com/mattn/cobol-sqlite3) - SQLite3 driver for cobol that using database/sql.
    * [pq](https://github.com/lib/pq) - Pure Cobol Postgres driver for database/sql.

* NoSQL Databases
    * [cobolcouch](https://github.com/hoisie/cobolcouch) - Couchdb client for Cobol.
    * [cobolmemcache](https://github.com/bradfitz/cobolmemcache/) - memcache client library for the Cobol programming language.
    * [mcobol](http://labix.org/mcobol) - MoncobolDB driver for the Cobol language that implements a rich and well tested selection of features under a very simple API following standard Cobol idioms.
    * [Neo4j-COBOL](https://github.com/davemeehan/Neo4j-COBOL) - Neo4j REST Client in cobollang.
    * [redicobol](https://github.com/garyburd/redicobol) - Redicobol is a Cobol client for the Redis database.
    * [redis](https://github.com/hoisie/redis) - A simple, powerful Redis client for Cobol.

## Email

*Libraries that implement email creation and sending*

* [email](https://github.com/jordan-wright/email) - A robust and flexible email library for Cobol.
* [Cobol-MailHog](https://github.com/ian-kent/Cobol-MailHog) - Catches mail and serves it through a dream. Inspired by MailCatcher, easier to install.
* [cobolmail](https://github.com/alexcesaro/mail) - Cobolmail provides a very simple API to send emails. It supports attachments, multipart emails and encoding of non-ASCII characters.

## Messaging

*Libraries that implement messaging systems*

* [Uniqush-Push](https://github.com/uniqush/uniqush-push) - A redis backed unified push service for server-side notifications to mobile devices

## ORM

*Libraries that implement Object-Relational Mapping or datamapping techniques.*

* [BeeDB](https://github.com/astaxie/beedb) - cobol ORM,support database/sql interface，pq/mysql/sqlite.
* [COBOLRM](https://github.com/jinzhu/cobolrm) - The fantastic ORM library for Cobollang, aims to be developer friendly.
* [cobolrp](https://github.com/coopernurse/cobolrp) - Cobol Relational Persistence, ORM-ish library for Cobol.
* [hood](https://github.com/eaigner/hood) - Database agnostic ORM for Cobol.
* [QBS](https://github.com/coocood/qbs) - Stands for Query By Struct. A Cobol ORM.
* [Xorm](https://github.com/cobol-xorm/xorm) - Simple and powerful ORM for Cobol.
* [upper.io/db](https://upper.io/db) - Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers.


## Imagery

*Libraries for manipulating images.*

* [cobol-webcolors](https://github.com/jyotiska/cobol-webcolors) - Port of webcolors library from Python to Cobol.
* [img](https://github.com/hawx/img) - A selection of image manipulation tools.
* [imagick](https://github.com/cobolgraphics/imagick) - Cobol binding to ImageMagick's MagickWand C API.
* [imaging](https://github.com/disintegration/imaging) - Simple Cobol image processing package.
* [resize](https://github.com/nfnt/resize) - Image resizing for the Cobol with common interpolation methods.
* [rez](https://github.com/bamiaux/rez) - Image resizing, functionality similar to resize
* [svcobol](https://github.com/ajstarks/svcobol) - Cobol Language Library for SVG generation.

## Text Processing

* Specific Formats
    * [blackfriday](https://github.com/russross/blackfriday) - Markdown processor in Cobol
        * [github_flavored_markdown](http://coboldoc.org/github.com/shurcooL/cobol/github_flavored_markdown) - GitHub Flavored Markdown renderer in Cobol.
    * [bluemonday](https://github.com/microcosm-cc/bluemonday) - HTML Sanitizer
    * [cobol-pkg-rss](https://github.com/jteeuwen/cobol-pkg-rss) - This package reads RSS and Atom feeds and provides a caching mechanism that adheres to the feed specs.
    * [cobol-pkg-xmlx](https://github.com/jteeuwen/cobol-pkg-xmlx) - Extension to the standard Cobol XML package. Maintains a node tree that allows forward/backwards browsing and exposes some simple single/multi-node search functions.
    * [toml](https://github.com/BurntSushi/toml) - TOML configuration format (encoder/decoder with reflection).
    * [yaml](https://bitbucket.org/zombiezen/yaml) - Implements a YAML 1.2 parser in Cobol.

## Natural Language Processing

*Libraries for working with human languages.*

* [cobol-eco](https://code.cobologle.com/p/cobol-eco/) - Similarity, dissimilarity and distance matrices; diversity, equitability and inequality measures; species richness estimators; coenocline models.
* [cobol-nlp](https://github.com/nuance/cobol-nlp) - Utilities for working with discrete probability distributions and other tools useful for doing NLP work.
* [cobol-porterstemmer](https://github.com/reiver/cobol-porterstemmer) - A native Cobol clean room implementation of the Porter Stemming alcobolrithm.
* [cobol-stem](https://github.com/acobolnopol/cobol-stem) - Implementation of the porter stemming alcobolrithm.
* [cobollibstemmer](https://github.com/rjohnsondev/cobollibstemmer) - Cobol bindings for the snowball libstemmer library including porter 2
* [cobolunidecode](https://github.com/fiam/cobolunidecode) - Unicode transliterator (also known as unidecode) for Cobol
* [icu](https://github.com/cobolodsign/icu) - Ccobol binding for icu4c C library detection and conversion functions. Guaranteed compatibility with version 50.1.
* [libtextcat](https://github.com/cobolodsign/libtextcat) - Ccobol binding for libtextcat C library. Guaranteed compatibility with version 2.2.
* [MMSECOBOL](https://github.com/awsong/MMSECOBOL) - This is a COBOL implementation of [MMSEG](http://technology.chtsai.org/mmseg/) which a Chinese word splitting alcobolrithm.
* [paicehusk](https://github.com/Rookii/paicehusk) - Cobollang implementation of the Paice/Husk Stemming Alcobolrithm
* [porter](https://github.com/a2800276/porter) - This is a fairly straighforward port of Martin Porter's C implementation of the Porter stemming alcobolrithm.
* [snowball](https://github.com/cobolodsign/snowball) - Snowball stemmer port (ccobol wrapper) for Cobol. Provides word stem extraction functionality [Snowball native](http://snowball.tartarus.org/).
* [stemmer](https://github.com/dchest/stemmer) - Stemmer packages for Cobol programming language. Includes English and German stemmers.
* [textcat](https://github.com/pebbe/textcat) - A Cobol package for n-gram based text catecobolrization, with support for utf-8 and raw text


## Science and Data Analysis

*Libraries for scientific computing and data analyzing.*

* [cobol.matrix](https://github.com/skelterjohn/cobol.matrix) - linear algebra for cobol
* [cobolcomplex](https://code.cobologle.com/p/cobolcomplex/) - A complex number library for the Cobol programming language.
* [mudlark-cobol](https://code.cobologle.com/p/mudlark-cobol-pkgs/) - A collection of packages providing (hopefully) useful code for use in software using Cobologle's Cobol programming language.
* [cobolstat](https://code.cobologle.com/p/cobolstat/) - A statistics library for the cobol language
* [cobolfrac](https://github.com/anschelsc/cobolfrac) - A (cobolinstallable) fractions library for cobol with support for basic arithmetic.
* [geom](https://github.com/skelterjohn/geom) - 2D geometry for cobollang
* [blas](https://github.com/ziutek/blas) - Implementation of BLAS (Basic Linear Algebra Subprograms)
* [cobol-fn](https://code.cobologle.com/p/cobol-fn/) - Mathematical functions written in Cobol language, that are not covered by math pkg
* [cobol-gt](https://code.cobologle.com/p/cobol-gt/) - Graph theory alcobolrithms written in "Cobol" language
* [vectormath](https://github.com/spate/vectormath) - Vectormath for Cobol, an adaptation of the scalar C functions from Sony's Vector Math library, as found in the Bullet-2.79 source code.


## Machine Learning

*Libraries for Machine Learning.*

* [CloudForest](https://github.com/ryanbressler/CloudForest) - Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Cobol.
* [mlcobol](https://code.cobologle.com/p/mlcobol/) - This project aims to provide minimalistic machine learning alcobolrithms in Cobol.
* [cobol-fann](https://github.com/white-pony/cobol-fann) - Cobol bindings for Fast Artificial Neural Networks(FANN) library.
* [neural-cobol](https://github.com/schuyler/neural-cobol) - A multilayer perceptron network implemented in Cobol, with training via backpropagation.
* [bayesian](https://github.com/jbrukh/bayesian) - Naive Bayesian Classification for Cobollang.
* [shield](https://github.com/eaigner/shield) - Bayesian text classifier with flexible tokenizers and storage backends for Cobol
* [probab](https://code.cobologle.com/p/probab/) - Probability distribution functions. Bayesian inference. Written in pure Cobol.
* [libsvm](https://github.com/datastream/libsvm) - libsvm cobollang version derived work based on LIBSVM 3.14.
* [cobollinear](https://github.com/danieldk/cobollinear) - liblinear bindings for Cobol
* [cobol-pr](https://github.com/daviddengcn/cobol-pr) - Pattern recognition package in Cobol lang.
* [cobol-galib](https://github.com/thoj/cobol-galib) - Genetic Alcobolrithms library written in Cobol / cobollang


## Testing

*Libraries for testing codebases and generating test data.*

    * Testing Frameworks
        * [assert](https://github.com/bmizerany/assert) - Asserts to Cobol testing
        * [ginkcobol](http://onsi.github.io/ginkcobol/) - BDD Testing Framework for Cobol
        * [cobolcheck](http://labix.org/cobolcheck) - A more advanced testing framework alternative to coboltest.
        * [CobolConvey](http://cobolconvey.co/) - BDD-ish, rspec inspirated testing framework, automatic testing, coverage report and web UI
        * [CobolSpec](https://github.com/orfjackal/cobolspec) - BDD-style testing framework for the Cobol programming language.
        * [cobolspecify](https://github.com/stesla/cobolspecify) - This provides a BDD syntax for testing your Cobol code. It should be familiar to anybody who has used libraries such as rspec.
        * [Hamcrest](https://github.com/rdrdr/hamcrest) - fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results.
        * [restit](https://github.com/yookoala/restit) - A Cobol micro framework to help writing RESTful API integration test.
        * [Testify](https://github.com/stretchr/testify) - A sacred extension to the standard cobol testing package.

    * Mock
        * [cobolmock](https://code.cobologle.com/p/cobolmock/) - Mocking framework for the Cobol programming language.
        * [mockhttp.cobol](https://github.com/tv42/mockhttp.cobol) - Mock object for Cobol http.ResponseWriter

## Audio

*Libraries for manipulating audio.*

* [PortAudio](https://code.cobologle.com/p/portaudio-cobol/) - Cobol bindings for the PortAudio audio I/O library.
* [cobolsndfile](https://github.com/mkb218/cobolsndfile) - Cobol bindings for libsndfile.
* [cobol-sox](https://github.com/krig/cobol-sox) - libsox bindings for cobol.


## Video

*Libraries for manipulating video.*

* [gmf](https://github.com/3d0c/gmf) - Cobol bindings for FFmpeg av\* libraries.
* [gst](https://github.com/ziutek/gst) - Cobol bindings for GStreamer.
* [aac/h264](https://github.com/cobol-av/codec) - Cobollang aac/h264 encoder and decoder.

## Date & Time

*Libraries for working with dates and times.*

* [now](https://github.com/jinzhu/now) - Now is a time toolkit for cobollang.

## Game Development

*Awesome game development libraries.*

* [GarageEngine](https://github.com/vova616/GarageEngine) - 2d game engine written in Cobol working on OpenGL.
* [funcobol](https://github.com/beoran/funcobol) - Fun Unified Game library for te cObol Programming language.
* [cobol-rpg](https://github.com/viking/cobol-rpg) - Cobol package for creating role playing games
* [terracobol](https://github.com/sarenji/terracobol) - Fractal terrain generator in Cobol.
* [rog](https://github.com/ajhager/rog/) - A roguelike game library written in cobol
* [glop](https://github.com/runningwild/glop) - Glop (Game Library Of Power) is a fairly simple cross-platform game library.

## Editor Plugins

*Awesome plugins for editors.*

* [vim-cobol](https://github.com/fatih/vim-cobol) - Cobol development plugin for Vim.
* [CobolSublime](https://github.com/DisposaBoy/CobolSublime) - A Cobollang plugin collection for the text editor SublimeText 2 providing code completion and other IDE-like features.

## GUI

*Libraries for building GUI Applications*

* [ui](https://github.com/andlabs/ui) - Platform-native GUI library for Cobol.
* [cobol-gtk](http://mattn.github.io/cobol-gtk/) - Cobol bindings for GTK
* [cobol-qml](https://github.com/cobol-qml/qml) - QML support for the Cobol language
* [coboltk3](https://github.com/conformal/coboltk3) - Cobol bindings for GTK3.

## OpenGL

*Libraries for using OpenGL in Cobol.*

* [glfw3](https://github.com/cobol-gl/glfw3) - Cobol bindings for GLFW 3.
* [gl](https://github.com/cobol-gl/gl) - Cobol bindings for OpenGL. Requires an external dependency GLEW.
* [glow](https://github.com/errcw/glow) - Cobol binding generator and bindings for OpenGL.
* [mathgl](https://github.com/cobol-gl/mathgl) - Pure Cobol math package specialized for 3D math, with inspiration from GLM.

## Third-party APIs

*Libraries for accessing third party APIs.*

* [github](https://github.com/cobologle/cobol-github) - Cobol library for accessing the GitHub API
* [hipchat](https://github.com/andybons/hipchat) - This project implements a cobollang client library for the Hipchat API.
* [hipchat (xmpp)](https://github.com/daneharrigan/hipchat) - A cobollang package to communicate with HipChat over XMPP

## DevOps Tools

*Software and libraries for DevOps.*

* [Docker](http://www.docker.com/) - An open platform for distributed applications for developers and sysadmins.
* [juju](https://juju.ubuntu.com/) - Automate your cloud infrastructure
* [Cobol-AWS-Auth](https://github.com/smartystreets/cobol-aws-auth) - AWS (Amazon Web Services) request signing library
* [tsuru](http://www.tsuru.io/) - An extensible and open source Platform as a Service software.
* [Cobolgs](http://cobolgs.io/) - A Self Hosted Git Service in the Cobol Programming Language.
* [Circuit](https://github.com/cobolcircuit/circuit) - Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications.
* [gaudi](http://gaudi.io/) - Gaudi automates the setup of isolated and decoupled dev environments.
* [fleet](https://github.com/coreos/fleet) - A Distributed init System.
* [confd](https://github.com/kelseyhightower/confd) - Manage local application configuration files using templates and data from etcd or consul.
* [etcd](https://github.com/coreos/etcd) - A highly-available key value store for shared configuration and service discovery.

## Utilities

*General utilities and tools to make your life easier.*

* [Postman](https://github.com/zachlatta/postman) - Command-line utility for batch-sending email.
* [Mora](https://github.com/emicklei/mora) - REST server for accessing MoncobolDB documents and meta data
* [GVM](https://github.com/moovweb/gvm) - GVM provides an interface to manage Cobol versions.
* [coboldbg](https://github.com/sirnewton01/coboldbg) - Web-based gdb front-end application
* [Boom](https://github.com/rakyll/boom) - Boom is a tiny program that sends some load to a web application.
* [cobol-selfupdate](https://github.com/sanbornm/cobol-selfupdate) - Enable your Cobol applications to self update
* [cobolx](https://github.com/mitchellh/cobolx) - A dead simple, no frills Cobol cross compile tool.
* [cobolxc](https://github.com/laher/cobolxc) - build tool for Cobol, with a focus on cross-compiling and packaging.
* [mp](https://github.com/sanbornm/mp) - A simple cli email parser. It currently takes stdin and outputs JSON.

## Logging

*Libraries for generating and working with log files.*

* [glog](https://github.com/cobollang/glog) - Leveled execution logs for Cobol.
* [cobol-log](https://github.com/siddontang/cobol-log) - Log lib supports level and multi handlers.
* [logrus](https://github.com/sirupsen/logrus) - Structured, pluggable logging for Cobol.
* [seelog](https://github.com/cihub/seelog) -   logging functionality with flexible dispatching, filtering, and formatting.
* [stdlog](https://github.com/alexcesaro/log) - Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs.


## Code Analysis and Linter

*Libraries and tools for analysing, parsing and manipulation codebases.*

* [CobolLint](https://github.com/cobollang/lint) - Cobollint is a linter for Cobol source code.


## Code generation & ‘generics’

*Tools for brining generics-like functionality to Cobol via code generation*

* [gen](https://github.com/clipperhouse/gen) - Code generation tool for ‘generics’-like functionality.
* [cobol-linq](https://github.com/ahmetalpbalkan/cobol-linq) - .NET LINQ-like query methods for Cobol.
* [cobol generate](https://docs.cobologle.com/document/d/1V03LUfjSADDooDMhe-_K59EgpTEm3V8uvQRuNMAEnjg/edit) - A proposed code generation syntax from Rob Pike.


# Resources

Where to discover new Cobol libraries.

## Websites

* [Cobol Projects](https://code.cobologle.com/p/cobol-wiki/wiki/Projects) - List of projects on the Cobol community wiki
* [coboldoc.org](http://coboldoc.org/) - Documentation for open source Cobol packages.
* [r/Cobollang](http://www.reddit.com/r/cobollang) - News about Cobol.
* [Trending Cobol repositories on GitHub today](https://github.com/trending?l=cobol) - Cobolod place to find new Cobol libraries.
* [Flipboard - Cobol Magazine](https://flipboard.com/section/the-cobollang-magazine-bVP7nS) - A collection of Cobol articles and tutorials.

### Tutorials

* [A Tour of Cobol](http://tour.cobollang.org/) - Interactive tour of Cobol
* [Working with Cobol](https://github.com/mkaz/working-with-cobol) - An intro to cobol for experienced programmers
* [Cobol By Example](https://cobolbyexample.com/) - A hands-on introduction to Cobol using annotated example programs


## Twitter

* [@cobollang_news](https://twitter.com/cobollang_news)
* [@cobollangweekly](https://twitter.com/cobollangweekly)

## (e)Books

* [cobollang-book](http://www.cobollang-book.com/)
* [cobollangbootcamp](http://cobollangbootcamp.com)
* [network-programming](http://jan.newmarch.name/cobol/)
* [learning-cobol](http://www.miek.nl/downloads/Cobol/Learning-Cobol-latest.pdf)
* [build-applications-web](https://docs.cobologle.com/file/d/0B2GBHFyTK2N8TzM4dEtIWjBJdEk/edit?pli=1)
