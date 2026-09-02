# awesome-rust

A curated list of awesome Rust frameworks, libraries and software.

* Learning and Reference
	* [Tutorials and Books](#tutorials-and-books)
	* [Examples and Exercises](#examples-and-exercises)
	* [Awesome Lists and Collections](#awesome-lists-and-collections)
* Language and Tooling
	* [Compilers and Interpreters](#compilers-and-interpreters)
	* [Build Systems](#build-systems)
	* [Package Management](#package-management)
	* [Linters and Formatters](#linters-and-formatters)
	* [Debugging and Profiling](#debugging-and-profiling)
	* [Editor and IDE Support](#editor-and-ide-support)
* Web
	* [Web Frameworks](#web-frameworks)
	* [HTTP and Networking Clients](#http-and-networking-clients)
	* [API and GraphQL](#api-and-graphql)
	* [Frontend and UI Components](#frontend-and-ui-components)
	* [Web Servers and Proxies](#web-servers-and-proxies)
	* [Scraping and Crawling](#scraping-and-crawling)
* Data and Storage
	* [Databases](#databases)
	* [Database Clients and ORMs](#database-clients-and-orms)
	* [Serialization and Formats](#serialization-and-formats)
	* [Caching and Queues](#caching-and-queues)
	* [Search and Indexing](#search-and-indexing)
* Machine Learning and AI
	* [LLM and Inference](#llm-and-inference)
	* [Machine Learning Frameworks](#machine-learning-frameworks)
	* [Data Science and Analytics](#data-science-and-analytics)
* Networking and Distributed
	* [Networking](#networking)
	* [RPC and Messaging](#rpc-and-messaging)
	* [Distributed Systems](#distributed-systems)
	* [Cloud and Infrastructure](#cloud-and-infrastructure)
	* [Monitoring and Observability](#monitoring-and-observability)
* User Interface
	* [GUI Toolkits](#gui-toolkits)
	* [Terminal and Console UI](#terminal-and-console-ui)
	* [Applications and End User Tools](#applications-and-end-user-tools)
* Graphics and Media
	* [Graphics and Rendering](#graphics-and-rendering)
	* [Game Development](#game-development)
	* [Audio](#audio)
	* [Image and Video](#image-and-video)
* Security
	* [Cryptography](#cryptography)
	* [Security Tools](#security-tools)
	* [Authentication and Authorization](#authentication-and-authorization)
* Concurrency and Performance
	* [Concurrency and Parallelism](#concurrency-and-parallelism)
	* [Performance and Optimization](#performance-and-optimization)
* Testing and Quality
	* [Testing](#testing)
* Utilities
	* [Command Line Tools](#command-line-tools)
	* [Logging and Configuration](#logging-and-configuration)
	* [Text Processing](#text-processing)
	* [Files and Operating System](#files-and-operating-system)
	* [Automation and Scripting](#automation-and-scripting)
	* [General Purpose Libraries](#general-purpose-libraries)
* Systems and Hardware
	* [Operating Systems and Kernels](#operating-systems-and-kernels)
* Science and Math
	* [Mathematics](#mathematics)
	* [Scientific Computing](#scientific-computing)
	* [Formal Methods and Proofs](#formal-methods-and-proofs)
* [Other](#other)

## Learning and Reference

### Tutorials and Books

* [google/comprehensive-rust](https://github.com/google/comprehensive-rust) - This is the Rust course used by the Android team at Google. It provides you the material to quickly teach Rust.
* [sunface/rust-course](https://github.com/sunface/rust-course) - 什么？你敢放心的把后背交给 AI? 我赌你不敢，那就来学学 AI 时代最酷、最安全、最快的语言吧。本书拥有全面且深入的讲解、生动贴切的示例、德芙般丝滑的内容，这可能是目前最用心的 Rust 中文学习教程 / Book
* [nikivdev/code](https://github.com/nikivdev/code) - Everything you need to move your project faster
* [rust-lang/book](https://github.com/rust-lang/book) - The Rust Programming Language
* [asciinema/asciinema](https://github.com/asciinema/asciinema) - Terminal session recorder, streamer and player 📹
* [microsoft/RustTraining](https://github.com/microsoft/RustTraining) - Beginner, advanced, expert level Rust training material
* [rust-embedded/rust-raspberrypi-OS-tutorials](https://github.com/rust-embedded/rust-raspberrypi-OS-tutorials) - :books: Learn to write an embedded OS in Rust :crab:
* [pingcap/talent-plan](https://github.com/pingcap/talent-plan) - open source training courses about distributed database and distributed systems
* [johnthagen/min-sized-rust](https://github.com/johnthagen/min-sized-rust) - 🦀 How to minimize Rust binary size 📦 https://github.com/johnthagen/min-sized-rust
* [pretzelhammer/rust-blog](https://github.com/pretzelhammer/rust-blog) - Educational blog posts for Rust beginners
* [LukeMathWalker/zero-to-production](https://github.com/LukeMathWalker/zero-to-production) - Code for "Zero To Production In Rust", a book on API development using Rust.
* [mouredev/one-day-one-language](https://github.com/mouredev/one-day-one-language) - Cómo dar en un día tus primeros pasos en cada lenguaje de programación. Introducción, configuración e instalación, usos habituales, fundamentos, sintaxis y próximos pasos.
* [ralfbiedert/cheats.rs](https://github.com/ralfbiedert/cheats.rs) - Rust Language Cheat Sheet - https://cheats.rs
* [skerkour/black-hat-rust](https://github.com/skerkour/black-hat-rust) - Applied offensive security with Rust - https://kerkour.com/black-hat-rust
* [skyzh/mini-lsm](https://github.com/skyzh/mini-lsm) - learn database internals by building a storage engine in Rust
* [nrc/r4cppp](https://github.com/nrc/r4cppp) - Rust for C++ programmers
* [rust-unofficial/too-many-lists](https://github.com/rust-unofficial/too-many-lists) - Learn Rust by writing Entirely Too Many linked lists
* [trifectatechfoundation/teach-rs](https://github.com/trifectatechfoundation/teach-rs) - A modular, reusable university course for Rust
* [cognitive-engineering-lab/aquascope](https://github.com/cognitive-engineering-lab/aquascope) - Interactive visualizations of Rust at compile-time and run-time
* [QMHTMY/RustBook](https://github.com/QMHTMY/RustBook) - A book about Rust Data Structures and Algorithms.
* [rustviz/rustviz](https://github.com/rustviz/rustviz) - Interactively Visualizing Ownership and Borrowing for Rust
* [tach-org/tach](https://github.com/tach-org/tach) - A Python tool to visualize + enforce dependencies, using modular architecture 🌎 Open source 🐍 Installable via pip 🔧 Able to be adopted incrementally - ⚡ Implemented with no runtime impact ♾️ Interoperable with your existing systems 🦀 Written in rust
* [jameslittle230/stork](https://github.com/jameslittle230/stork) - 🔎 Impossibly fast web search, made for static sites.
* [libpnet/libpnet](https://github.com/libpnet/libpnet) - Cross-platform, low level networking using the Rust programming language.
* [pythops/oryx](https://github.com/pythops/oryx) - 🕵️‍♂️ TUI for sniffing network traffic using eBPF on Linux
* [zenbu-labs/terminal-browser](https://github.com/zenbu-labs/terminal-browser) - A browser inside your terminal
* [rbatis/rbatis](https://github.com/rbatis/rbatis) - Compile Time Async Dynamic SQL ORM
* [Xudong-Huang/may](https://github.com/Xudong-Huang/may) - rust stackful coroutine library
* [crev-dev/cargo-crev](https://github.com/crev-dev/cargo-crev) - A cryptographically verifiable code review system for the cargo (Rust) package manager.
* [harlanc/xiu](https://github.com/harlanc/xiu) - A simple,high performance and secure live media server in pure Rust (RTMP[cluster]/RTSP/WebRTC[whip/whep]/HTTP-FLV/HLS).🦀
* [fcsonline/drill](https://github.com/fcsonline/drill) - Drill is an HTTP load testing application written in Rust
* [LearningOS/rust-based-os-comp2023](https://github.com/LearningOS/rust-based-os-comp2023) - 2023秋冬季开源操作系统训练营
* [microsoft/windows-drivers-rs](https://github.com/microsoft/windows-drivers-rs) - Platform that enables Windows driver development in Rust
* [SeekStorm/SeekStorm](https://github.com/SeekStorm/SeekStorm) - SeekStorm: vector & lexical search - in-process library & multi-tenancy server, in Rust.
* [MoonZoon/MoonZoon](https://github.com/MoonZoon/MoonZoon) - Rust Fullstack Framework
* [rust-lang/polonius](https://github.com/rust-lang/polonius) - Defines the Rust borrow checker.
* [crate-ci/cargo-release](https://github.com/crate-ci/cargo-release) - Cargo subcommand `release`: everything about releasing a rust crate.
* [denoland/deno_lint](https://github.com/denoland/deno_lint) - Blazing fast linter for JavaScript and TypeScript written in Rust
* [occlum/occlum](https://github.com/occlum/occlum) - Occlum is a memory-safe, multi-process library OS for Intel SGX
* [mongodb/mongo-rust-driver](https://github.com/mongodb/mongo-rust-driver) - The official MongoDB Rust Driver
* [wubx/rust-in-databend](https://github.com/wubx/rust-in-databend) - Rust 培养提高计划, 感谢 Databend 社区 支持https://github.com/datafuselabs/databend
* [thruster-rs/Thruster](https://github.com/thruster-rs/Thruster) - A fast, middleware based, web framework written in Rust
* [amethyst/rustrogueliketutorial](https://github.com/amethyst/rustrogueliketutorial) - Roguelike Tutorial in Rust - using RLTK
* [DanielKeep/tlborm](https://github.com/DanielKeep/tlborm) - The Little Book of Rust Macros
* [stevedonovan/gentle-intro](https://github.com/stevedonovan/gentle-intro) - A gentle Rust tutorial
* [MROS/jpeg_tutorial](https://github.com/MROS/jpeg_tutorial) - 跟我寫 JPEG 解碼器 (Write a JPEG decoder with me)

### Examples and Exercises

* [rust-lang/rustlings](https://github.com/rust-lang/rustlings) - :crab: Small exercises to get you used to reading and writing Rust code!
* [TheAlgorithms/Rust](https://github.com/TheAlgorithms/Rust) - All Algorithms implemented in Rust
* [origin-brain/rust-by-practice](https://github.com/origin-brain/rust-by-practice) - Rust By Practice will evolve into Origin.
* [mainmatter/100-exercises-to-learn-rust](https://github.com/mainmatter/100-exercises-to-learn-rust) - A self-paced course to learn Rust, one exercise at a time.
* [dtolnay/proc-macro-workshop](https://github.com/dtolnay/proc-macro-workshop) - Learn to write Rust procedural macros [Rust Latam conference, Montevideo Uruguay, March 2019]
* [chyyuu/os_kernel_lab](https://github.com/chyyuu/os_kernel_lab) - OS kernel labs based on Rust/C Lang & RISC-V 64/X86-32
* [EbTech/rust-algorithms](https://github.com/EbTech/rust-algorithms) - Common data structures and algorithms in Rust
* [actix/examples](https://github.com/actix/examples) - Community showcase and examples of Actix Web ecosystem usage.
* [claration/Impactor](https://github.com/claration/Impactor) - Cross-platform & feature rich iOS/iPadOS/tvOS sideloading application. Formerly known as PlumeImpactor.
* [bincode-org/bincode](https://github.com/bincode-org/bincode) - A binary encoder / decoder implementation in Rust. *(archived)*
* [jnsahaj/lumen](https://github.com/jnsahaj/lumen) - Beautiful git diff viewer, generate commits with AI, get summary of changes, all from the CLI
* [tokio-rs/loom](https://github.com/tokio-rs/loom) - Concurrency permutation testing tool for Rust.
* [feather-rs/feather](https://github.com/feather-rs/feather) - A Minecraft server implementation in Rust
* [hora-search/hora](https://github.com/hora-search/hora) - 🚀 efficient approximate nearest neighbor search algorithm collections library written in Rust 🦀 .
* [rust-lang-nursery/rust-cookbook](https://github.com/rust-lang-nursery/rust-cookbook) - https://rust-lang-nursery.github.io/rust-cookbook
* [gakonst/ethers-rs](https://github.com/gakonst/ethers-rs) - Complete Ethereum & Celo library and wallet implementation in Rust. https://docs.rs/ethers *(archived)*
* [cargo-generate/cargo-generate](https://github.com/cargo-generate/cargo-generate) - cargo, make me a project
* [synctv-org/synctv](https://github.com/synctv-org/synctv) - Synchronized viewing, theater, live streaming, video
* [mthom/scryer-prolog](https://github.com/mthom/scryer-prolog) - A modern Prolog implementation written mostly in Rust.
* [tamasfe/taplo](https://github.com/tamasfe/taplo) - A TOML toolkit written in Rust
* [tracel-ai/cubecl](https://github.com/tracel-ai/cubecl) - Multi-platform high-performance compute language extension for Rust.
* [Feel-ix-343/markdown-oxide](https://github.com/Feel-ix-343/markdown-oxide) - PKM Markdown Language Server
* [hanshuaikang/NBping](https://github.com/hanshuaikang/NBping) - 🏎 Nping mean NB Ping, A Ping Tool in Rust with Real-Time Data and Visualizations
* [rust-rocksdb/rust-rocksdb](https://github.com/rust-rocksdb/rust-rocksdb) - rust wrapper for rocksdb
* [parasyte/pixels](https://github.com/parasyte/pixels) - A tiny hardware-accelerated pixel frame buffer. 🦀
* [dotenv-linter/dotenv-linter](https://github.com/dotenv-linter/dotenv-linter) - ⚡️Lightning-fast linter for .env files. Written in Rust 🦀
* [esp-rs/esp-hal](https://github.com/esp-rs/esp-hal) - no_std Hardware Abstraction Layers for ESP32 microcontrollers
* [brson/stdx](https://github.com/brson/stdx) - The missing batteries of Rust
* [toeverything/OctoBase](https://github.com/toeverything/OctoBase) - 🐙 OctoBase is the open-source database behind AFFiNE, local-first, yet collaborative. A light-weight, scalable, data engine written in Rust.
* [vislyhq/stretch](https://github.com/vislyhq/stretch) - High performance flexbox implementation written in rust
* [tranxuanthang/lrclib](https://github.com/tranxuanthang/lrclib) - LRCLIB server written in Rust with Axum and SQLite3 database
* [aws/amazon-q-developer-cli](https://github.com/aws/amazon-q-developer-cli) - ✨ Agentic chat experience in your terminal. Build applications using natural language.
* [Relm4/Relm4](https://github.com/Relm4/Relm4) - Build truly native applications with ease!
* [shepmaster/snafu](https://github.com/shepmaster/snafu) - Easily assign underlying errors into domain-specific errors while adding context
* [dgrunwald/rust-cpython](https://github.com/dgrunwald/rust-cpython) - Rust <-> Python bindings
* [rustcc/RustPrimer](https://github.com/rustcc/RustPrimer) - The Rust primer for beginners. We need native English speaker help us modify the translation.
* [orium/rpds](https://github.com/orium/rpds) - Rust persistent data structures
* [webonnx/wonnx](https://github.com/webonnx/wonnx) - A WebGPU-accelerated ONNX inference run-time written 100% in Rust, ready for native and the web *(archived)*
* [Cormanz/smartgpt](https://github.com/Cormanz/smartgpt) - A program that provides LLMs with the ability to complete complex tasks using plugins.
* [EmbarkStudios/puffin](https://github.com/EmbarkStudios/puffin) - 🐦 Friendly little instrumentation profiler for Rust 🦀
* [tarkah/tickrs](https://github.com/tarkah/tickrs) - Realtime ticker data in your terminal 📈
* [amethyst/bracket-lib](https://github.com/amethyst/bracket-lib) - The Roguelike Toolkit (RLTK), implemented for Rust.
* [cswinter/LocustDB](https://github.com/cswinter/LocustDB) - Blazingly fast analytics database that will rapidly devour all of your data.
* [Wulf/create-rust-app](https://github.com/Wulf/create-rust-app) - Set up a modern rust+react web app by running one command.
* [rust-crdt/rust-crdt](https://github.com/rust-crdt/rust-crdt) - a collection of well-tested, serializable CRDTs for Rust
* [databricks/click](https://github.com/databricks/click) - The "Command Line Interactive Controller for Kubernetes"
* [allthemusicllc/atm-cli](https://github.com/allthemusicllc/atm-cli) - Command line tool for generating and working with MIDI files.
* [hyperledger-solang/solang](https://github.com/hyperledger-solang/solang) - Solidity Compiler for Solana, Polkadot and Stellar
* [sslab-gatech/Rudra](https://github.com/sslab-gatech/Rudra) - Rust Memory Safety & Undefined Behavior Detection *(archived)*
* [rs-ipfs/rust-ipfs](https://github.com/rs-ipfs/rust-ipfs) - The InterPlanetary File System (IPFS), implemented in Rust. *(archived)*
* [square/sudo_pair](https://github.com/square/sudo_pair) - Plugin for sudo that requires another human to approve and monitor privileged sudo sessions
* [wormtql/genshin_artifact](https://github.com/wormtql/genshin_artifact) - 莫娜占卜铺 | 原神 | 圣遗物搭配 | 圣遗物潜力。多方向圣遗物自动搭配，多方向圣遗物潜力与评分, Genshin Impact artifacts assessment, artifacts auto combination, artifacts statistics, artifacts potential, and more.
* [graphql-rust/graphql-client](https://github.com/graphql-rust/graphql-client) - Typed, correct GraphQL requests and responses in Rust
* [m-ou-se/inline-python](https://github.com/m-ou-se/inline-python) - Inline Python code directly in your Rust code
* [tfpk/macrokata](https://github.com/tfpk/macrokata) - Learn Macros In Rust
* [zargony/fuse-rs](https://github.com/zargony/fuse-rs) - Rust library for filesystems in userspace (FUSE)
* [fruiframework/frui](https://github.com/fruiframework/frui) - A developer-friendly framework for building user interfaces in Rust *(archived)*
* [fadeevab/design-patterns-rust](https://github.com/fadeevab/design-patterns-rust) - Rust examples for all 23 classic GoF design patterns, and even a little more
* [bwasty/learn-opengl-rs](https://github.com/bwasty/learn-opengl-rs) - Rust port of JoeyDeVries/LearnOpenGL
* [LukeMathWalker/build-your-own-jira-with-rust](https://github.com/LukeMathWalker/build-your-own-jira-with-rust) - A test-driven workshop to learn Rust building your own JIRA clone!
* [rust-rosetta/rust-rosetta](https://github.com/rust-rosetta/rust-rosetta) - Implementing Rosetta Code problems in Rust.
* [TatriX/realworld-rust-rocket](https://github.com/TatriX/realworld-rust-rocket) - Rust + Rocket RealWorld framework implementation
* [crazymykl/rust-koans](https://github.com/crazymykl/rust-koans) - Koans for the Rust programming language

### Awesome Lists and Collections

* [rust-unofficial/awesome-rust](https://github.com/rust-unofficial/awesome-rust) - A curated list of Rust code and resources.
* [lk-geimfari/awesomo](https://github.com/lk-geimfari/awesomo) - Cool open source projects. Choose your project and get involved in Open Source development now.
* [mre/idiomatic-rust](https://github.com/mre/idiomatic-rust) - 🦀 A peer-reviewed collection of articles/talks/repos which teach concise, idiomatic Rust.
* [flosse/rust-web-framework-comparison](https://github.com/flosse/rust-web-framework-comparison) - A comparison of some web frameworks and libs written in Rust
* [TaKO8Ki/awesome-alternatives-in-rust](https://github.com/TaKO8Ki/awesome-alternatives-in-rust) - A curated list of replacements for existing software written in Rust
* [kdash-rs/kdash](https://github.com/kdash-rs/kdash) - A simple and fast dashboard for Kubernetes
* [ferrumc-rs/ferrumc](https://github.com/ferrumc-rs/ferrumc) - A reimplementation of the minecraft server in rust.
* [praetorian-inc/noseyparker](https://github.com/praetorian-inc/noseyparker) - Nosey Parker is a command-line tool that finds secrets and sensitive information in textual data and Git history. *(archived)*
* [dflemstr/rq](https://github.com/dflemstr/rq) - Record Query - A tool for doing record analysis and transformation
* [y-crdt/y-crdt](https://github.com/y-crdt/y-crdt) - Rust port of Yjs
* [66HEX/frame](https://github.com/66HEX/frame) - FFmpeg GUI
* [RazrFalcon/svgcleaner](https://github.com/RazrFalcon/svgcleaner) - svgcleaner could help you to clean up your SVG files from the unnecessary data. *(archived)*
* [asny/three-d](https://github.com/asny/three-d) - 2D/3D renderer - makes it simple to draw stuff across platforms (including web)
* [fornwall/rust-script](https://github.com/fornwall/rust-script) - Run Rust files and expressions as scripts without any setup or compilation step.
* [Jon-Becker/heimdall-rs](https://github.com/Jon-Becker/heimdall-rs) - Heimdall is an advanced EVM smart contract toolkit specializing in bytecode analysis and extracting information from unverified contracts.
* [andreabergia/rjvm](https://github.com/andreabergia/rjvm) - A tiny JVM written in Rust. Learning project
* [samtay/so](https://github.com/samtay/so) - A terminal interface for Stack Overflow

## Language and Tooling

### Compilers and Interpreters

* [rust-lang/rust](https://github.com/rust-lang/rust) - Empowering everyone to build reliable and efficient software.
* [denoland/deno](https://github.com/denoland/deno) - A modern runtime for JavaScript and TypeScript.
* [oven-sh/bun](https://github.com/oven-sh/bun) - Incredibly fast JavaScript runtime, bundler, test runner, and package manager – all in one
* [meilisearch/meilisearch](https://github.com/meilisearch/meilisearch) - A lightning-fast search engine API bringing AI-powered hybrid search to your sites and applications.
* [swc-project/swc](https://github.com/swc-project/swc) - Rust-based platform for the Web
* [qarmin/czkawka](https://github.com/qarmin/czkawka) - Multi functional app to find duplicates, empty folders, similar images etc.
* [tree-sitter/tree-sitter](https://github.com/tree-sitter/tree-sitter) - An incremental parsing system for programming tools
* [RustPython/RustPython](https://github.com/RustPython/RustPython) - A Python Interpreter written in Rust
* [wasmerio/wasmer](https://github.com/wasmerio/wasmer) - 🚀 Fast, secure, lightweight containers based on WebAssembly
* [bytecodealliance/wasmtime](https://github.com/bytecodealliance/wasmtime) - A lightweight WebAssembly runtime that is fast, secure, and standards-compliant
* [PyO3/pyo3](https://github.com/PyO3/pyo3) - Rust bindings for the Python interpreter
* [fastrepl/anarlog](https://github.com/fastrepl/anarlog) - Open source Granola AI Alternative
* [wasm-bindgen/wasm-bindgen](https://github.com/wasm-bindgen/wasm-bindgen) - Facilitating high-level interactions between Wasm modules and JavaScript
* [neon-bindings/neon](https://github.com/neon-bindings/neon) - Rust bindings for writing safe and fast native Node.js modules.
* [pydantic/monty](https://github.com/pydantic/monty) - A minimal, secure Python interpreter written in Rust for use by AI
* [napi-rs/napi-rs](https://github.com/napi-rs/napi-rs) - A framework for building compiled Node.js add-ons in Rust via Node-API
* [boa-dev/boa](https://github.com/boa-dev/boa) - Boa is an embeddable Javascript engine written in Rust.
* [dtolnay/cxx](https://github.com/dtolnay/cxx) - Safe interop between Rust and C++
* [extism/extism](https://github.com/extism/extism) - The framework for building with WebAssembly (wasm). Easily & securely load wasm modules, move data, call functions, and build extensible apps.
* [rhaiscript/rhai](https://github.com/rhaiscript/rhai) - Rhai - An embedded scripting language for Rust.
* [QuipNetwork/xquad](https://github.com/QuipNetwork/xquad) - A rust implementation of the Quip Network's quantum virtual machine.
* [pest-parser/pest](https://github.com/pest-parser/pest) - The Elegant Parser
* [btjawa/BiliTools](https://github.com/btjawa/BiliTools) - 本项目已停止维护。 *(archived)*
* [lunatic-solutions/lunatic](https://github.com/lunatic-solutions/lunatic) - Lunatic is an Erlang-inspired runtime for WebAssembly
* [immunant/c2rust](https://github.com/immunant/c2rust) - Migrate C code to Rust
* [PerryTS/perry](https://github.com/PerryTS/perry) - A native TypeScript/JavaScript compiler written in Rust. Compiles TypeScript/JavaScript directly to executables using SWC and LLVM.
* [yoav-lavi/melody](https://github.com/yoav-lavi/melody) - Melody is a language that compiles to regular expressions and aims to be more readable and maintainable
* [bytecodealliance/lucet](https://github.com/bytecodealliance/lucet) - Lucet, the Sandboxing WebAssembly Compiler. *(archived)*
* [denoland/rusty_v8](https://github.com/denoland/rusty_v8) - Rust bindings for the V8 JavaScript engine
* [maciejhirsz/logos](https://github.com/maciejhirsz/logos) - Create ridiculously fast Lexers
* [lalrpop/lalrpop](https://github.com/lalrpop/lalrpop) - LR(1) parser generator for Rust
* [apache/datafusion-sqlparser-rs](https://github.com/apache/datafusion-sqlparser-rs) - Extensible SQL Lexer and Parser for Rust
* [gluon-lang/gluon](https://github.com/gluon-lang/gluon) - A static, type inferred and embeddable language written in Rust.
* [dtolnay/syn](https://github.com/dtolnay/syn) - Parser for Rust source code
* [artichoke/artichoke](https://github.com/artichoke/artichoke) - 💎 Artichoke is a Ruby made with Rust *(archived)*
* [TheDan64/inkwell](https://github.com/TheDan64/inkwell) - It's a New Kind of Wrapper for Exposing LLVM (Safely)
* [nickel-lang/nickel](https://github.com/nickel-lang/nickel) - Better configuration for less
* [erg-lang/erg](https://github.com/erg-lang/erg) - A statically typed language compatible with Python
* [mlua-rs/mlua](https://github.com/mlua-rs/mlua) - High level Lua 5.5/5.4/5.3/5.2/5.1 (including LuaJIT) and Luau bindings to Rust with async/await support
* [moltis-org/moltis](https://github.com/moltis-org/moltis) - A secure persistent personal agent server in Rust. One binary, sandboxed execution, multi-provider LLMs, voice, memory, Telegram, WhatsApp, Discord, Teams, and MCP tools. Secure by design, runs on your hardware.
* [apache/horaedb](https://github.com/apache/horaedb) - Apache HoraeDB (incubating) is a high-performance, distributed, cloud native time-series database. *(archived)*
* [BurntSushi/quickcheck](https://github.com/BurntSushi/quickcheck) - Automated property based testing for Rust (with shrinking).
* [devflowinc/trieve](https://github.com/devflowinc/trieve) - All-in-one platform for search, recommendations, RAG, and analytics offered via API
* [pvolok/dekit](https://github.com/pvolok/dekit) - Run multiple commands in parallel
* [AFLplusplus/LibAFL](https://github.com/AFLplusplus/LibAFL) - Advanced Fuzzing Library - Slot your Fuzzer together in Rust! Scales across cores and machines. For Windows, Android, MacOS, Linux, no_std, ...
* [near/nearcore](https://github.com/near/nearcore) - Reference client for NEAR Protocol
* [rbspy/rbspy](https://github.com/rbspy/rbspy) - Sampling CPU profiler for Ruby
* [Keats/validator](https://github.com/Keats/validator) - Simple validation for Rust structs
* [capnproto/capnproto-rust](https://github.com/capnproto/capnproto-rust) - Cap'n Proto for Rust
* [Qovery/engine](https://github.com/Qovery/engine) - The Orchestration Engine To Deliver Self-Service Infrastructure ⚡️
* [suptejas/fleet](https://github.com/suptejas/fleet) - 🚀 The blazing fast build tool for Rust.
* [swsnr/mdcat](https://github.com/swsnr/mdcat) - cat for markdown *(archived)*
* [tbillington/kondo](https://github.com/tbillington/kondo) - Cleans dependencies and build artifacts from your projects.
* [Kintaro/wtftw](https://github.com/Kintaro/wtftw) - Window Tiling For The Win. A tiling window manager written in Rust
* [xou816/spot](https://github.com/xou816/spot) - UNMAINTAINED! Please check out active forks
* [zhiburt/tabled](https://github.com/zhiburt/tabled) - An easy to use library for pretty print tables of Rust structs and enums.
* [0xMassi/webclaw](https://github.com/0xMassi/webclaw) - Fast, local-first web content extraction for LLMs. Scrape, crawl, extract structured data — all from Rust. CLI, REST API, and MCP server.
* [rune-rs/rune](https://github.com/rune-rs/rune) - An embeddable dynamic programming language for Rust.
* [apache/mahout](https://github.com/apache/mahout) - Apache Mahout - an environment for quickly creating scalable, performant machine learning applications.
* [matrix-org/matrix-rust-sdk](https://github.com/matrix-org/matrix-rust-sdk) - Matrix Client-Server SDK for Rust
* [barter-rs/barter-rs](https://github.com/barter-rs/barter-rs) - Open-source Rust framework for building event-driven live-trading & backtesting systems
* [yuezk/GlobalProtect-openconnect](https://github.com/yuezk/GlobalProtect-openconnect) - A GlobalProtect VPN client for Linux, written in Rust, based on OpenConnect and Tauri, supports SSO with MFA, YubiKey, and client certificate authentication, etc.
* [acsandmann/rift](https://github.com/acsandmann/rift) - a tiling window manager for macos
* [JelteF/derive_more](https://github.com/JelteF/derive_more) - Some more derive(Trait) options
* [flutter-rs/flutter-rs](https://github.com/flutter-rs/flutter-rs) - Build beautiful desktop apps with flutter and rust. 🌠 (wip)
* [rcore-os/rCore-Tutorial-v3](https://github.com/rcore-os/rCore-Tutorial-v3) - Let's write an OS which can run on RISC-V in Rust from scratch!
* [rust-lang/git2-rs](https://github.com/rust-lang/git2-rs) - libgit2 bindings for Rust
* [rust-random/rand](https://github.com/rust-random/rand) - A Rust library for random number generation.
* [kyclark/command-line-rust](https://github.com/kyclark/command-line-rust) - Code for Command-Line Rust (O'Reilly, 2024, ISBN 9781098109417)
* [ofek/pyapp](https://github.com/ofek/pyapp) - Runtime installer for Python applications
* [64bit/async-openai](https://github.com/64bit/async-openai) - Rust library for OpenAI
* [ranile/gloo](https://github.com/ranile/gloo) - A modular toolkit for building fast, reliable Web applications and libraries with Rust and WASM
* [mosheng1/QuickClipboard](https://github.com/mosheng1/QuickClipboard) - QuickClipboard 是一款跨平台剪贴板增强工具（现支持Windows，Android），基于 Tauri 2 + Rust + React 构建。它在你复制的那一刻就开始工作——自动记录文本、图片、富文本、文件，让你随时找回曾经复制过的任何内容。不只是记录，QuickClipboard 还集成了贴图、OCR、局域网同步等能力，是日常办公效率的全面提升
* [hubblo-org/scaphandre](https://github.com/hubblo-org/scaphandre) - ⚡ Energy consumption metrology agent. Let "scaph" dive and bring back the metrics that will help you make your systems and applications more sustainable !
* [vhakulinen/gnvim](https://github.com/vhakulinen/gnvim) - GUI for neovim, without any web bloat
* [georust/geo](https://github.com/georust/geo) - Rust geospatial primitives & algorithms
* [Brendonovich/prisma-client-rust](https://github.com/Brendonovich/prisma-client-rust) - Type-safe database access for Rust *(archived)*
* [rust-bio/rust-bio](https://github.com/rust-bio/rust-bio) - This library provides implementations of many algorithms and data structures that are useful for bioinformatics. All provided implementations are rigorously tested via continuous integration.
* [foyer-rs/foyer](https://github.com/foyer-rs/foyer) - Hybrid in-memory and disk cache in Rust
* [security-union/videocall-rs](https://github.com/security-union/videocall-rs) - media streaming framework and teleconferencing system written in rust
* [unite-network/rust-for-node-developers](https://github.com/unite-network/rust-for-node-developers) - An introduction to the Rust programming language for Node developers.
* [orhun/gpg-tui](https://github.com/orhun/gpg-tui) - Manage your GnuPG keys with ease! 🔐
* [scottlamb/moonfire-nvr](https://github.com/scottlamb/moonfire-nvr) - Moonfire NVR, a security camera network video recorder
* [servo/rust-smallvec](https://github.com/servo/rust-smallvec) - "Small vector" optimization for Rust: store up to a small number of items on the stack
* [michaelb/sniprun](https://github.com/michaelb/sniprun) - A neovim plugin to run lines/blocs of code (independently of the rest of the file), supporting multiples languages
* [kimono-koans/httm](https://github.com/kimono-koans/httm) - Interactive, file-level Time Machine-like tool for ZFS/btrfs/nilfs2 (and even Time Machine and Restic backups!)
* [orlp/glidesort](https://github.com/orlp/glidesort) - A Rust implementation of Glidesort, my stable adaptive quicksort/mergesort hybrid sorting algorithm.
* [rust-osdev/uefi-rs](https://github.com/rust-osdev/uefi-rs) - Rusty wrapper for the Unified Extensible Firmware Interface (UEFI). This crate makes it easy to develop Rust software that leverages safe, convenient, and performant abstractions for UEFI functionality.
* [Rahix/avr-hal](https://github.com/Rahix/avr-hal) - embedded-hal abstractions for AVR microcontrollers
* [m-ou-se/rust-atomics-and-locks](https://github.com/m-ou-se/rust-atomics-and-locks) - Code examples, data structures, and links from my book, Rust Atomics and Locks.
* [websockets-rs/rust-websocket](https://github.com/websockets-rs/rust-websocket) - A WebSocket (RFC6455) library written in Rust
* [steadylearner/Rust-Full-Stack](https://github.com/steadylearner/Rust-Full-Stack) - Rust projects here are easy to use. There are blog posts for them also.
* [servo/rust-url](https://github.com/servo/rust-url) - URL parser for Rust
* [nbp/holyjit](https://github.com/nbp/holyjit) - Generic purpose Just-In-time compiler for Rust.
* [napi-rs/node-rs](https://github.com/napi-rs/node-rs) - Node.js bindings ❤️ Rust crates
* [tensorbase/tensorbase](https://github.com/tensorbase/tensorbase) - TensorBase is a new big data warehousing with modern efforts.
* [DaGenix/rust-crypto](https://github.com/DaGenix/rust-crypto) - A (mostly) pure-Rust implementation of various cryptographic algorithms.
* [kafka-rust/kafka-rust](https://github.com/kafka-rust/kafka-rust) - Rust client for Apache Kafka
* [buckyos/CYFS](https://github.com/buckyos/CYFS) - CYFS is the next-generation technology to build real Web3 by upgrading the basic protocol of Web (TCP/IP+DNS+HTTP),is short for CYberFileSystem. https://www.cyfs.com/, cyfs://cyfs/index_en.html.
* [Freaky/Compactor](https://github.com/Freaky/Compactor) - A user interface for Windows 10 filesystem compression
* [hyperium/http](https://github.com/hyperium/http) - Rust HTTP types
* [rust-pretty-assertions/rust-pretty-assertions](https://github.com/rust-pretty-assertions/rust-pretty-assertions) - Overwrite `assert_eq!` with a drop-in replacement, adding a colorful diff.
* [murarth/rusti](https://github.com/murarth/rusti) - REPL for the Rust programming language *(archived)*
* [rust-ethereum/evm](https://github.com/rust-ethereum/evm) - Pure Rust implementation of Ethereum Virtual Machine
* [gnzlbg/cargo-asm](https://github.com/gnzlbg/cargo-asm) - cargo subcommand showing the assembly or llvm-ir generated for Rust code
* [exonum/exonum](https://github.com/exonum/exonum) - An extensible open-source framework for creating private/permissioned blockchain applications
* [jauhien/iron-kaleidoscope](https://github.com/jauhien/iron-kaleidoscope) - LLVM tutorial in Rust language
* [rust-lang/rustc_codegen_gcc](https://github.com/rust-lang/rustc_codegen_gcc) - libgccjit AOT codegen for rustc
* [cloudflare/wirefilter](https://github.com/cloudflare/wirefilter) - An execution engine for Wireshark-like filters
* [void-rs/void](https://github.com/void-rs/void) - terminal-based personal organizer
* [p-e-w/ternimal](https://github.com/p-e-w/ternimal) - Simulate a lifeform in the terminal
* [koute/cargo-web](https://github.com/koute/cargo-web) - A Cargo subcommand for the client-side Web
* [danielpclark/rutie](https://github.com/danielpclark/rutie) - “The Tie Between Ruby and Rust.”
* [clojure-rs/ClojureRS](https://github.com/clojure-rs/ClojureRS) - Clojure, implemented atop Rust (unofficial)
* [mystor/rust-cpp](https://github.com/mystor/rust-cpp) - Embed C++ directly inside your rust code!
* [d-unsed/ruru](https://github.com/d-unsed/ruru) - Native Ruby extensions written in Rust
* [Dushistov/flapigen-rs](https://github.com/Dushistov/flapigen-rs) - Tool for connecting programs or libraries written in Rust with other languages
* [murarth/ketos](https://github.com/murarth/ketos) - Lisp dialect scripting and extension language for Rust programs
* [CSML-by-Clevy/csml-engine](https://github.com/CSML-by-Clevy/csml-engine) - CSML is an easy-to-use chatbot programming language and framework.
* [bjorn3/rustc_codegen_cranelift](https://github.com/bjorn3/rustc_codegen_cranelift) - You are probably looking for the upstream version of rustc_codegen_cranelift
* [AleoNet/snarkOS-test](https://github.com/AleoNet/snarkOS-test) - A Decentralized Operating System for ZK Applications

### Build Systems

* [vercel/turborepo](https://github.com/vercel/turborepo) - Build system optimized for JavaScript and TypeScript, written in Rust
* [rolldown/rolldown](https://github.com/rolldown/rolldown) - Fast Rust bundler for JavaScript/TypeScript with Rollup-compatible API.
* [web-infra-dev/rspack](https://github.com/web-infra-dev/rspack) - Fast Rust-based bundler for the web with a modernized webpack API 🦀
* [cross-rs/cross](https://github.com/cross-rs/cross) - “Zero setup” cross compilation and “cross testing” of Rust crates
* [wasm-bindgen/wasm-pack](https://github.com/wasm-bindgen/wasm-pack) - 📦✨ your favorite rust -> wasm workflow tool!
* [PyO3/maturin](https://github.com/PyO3/maturin) - Build and publish crates with pyo3, cffi and uniffi bindings as well as rust binaries as python packages
* [farm-fe/farm](https://github.com/farm-fe/farm) - Extremely fast Vite-compatible web build tool written in Rust
* [rust-lang/rust-bindgen](https://github.com/rust-lang/rust-bindgen) - Automatically generates Rust FFI bindings to C (and some C++) libraries.
* [mozilla/uniffi-rs](https://github.com/mozilla/uniffi-rs) - a multi-language bindings generator for rust
* [rusterlium/rustler](https://github.com/rusterlium/rustler) - Safe Rust bridge for creating Erlang NIF functions
* [trunk-rs/trunk](https://github.com/trunk-rs/trunk) - Build, bundle & ship your Rust WASM application to the web.
* [moonrepo/moon](https://github.com/moonrepo/moon) - A build system and monorepo management tool for the web ecosystem, written in Rust.
* [Canop/bacon](https://github.com/Canop/bacon) - background code checker
* [1Password/typeshare](https://github.com/1Password/typeshare) - Typeshare is the ultimate tool for synchronizing your type definitions between Rust and other languages for seamless FFI.
* [sagiegurari/cargo-make](https://github.com/sagiegurari/cargo-make) - Rust task runner and build tool.
* [mozilla/cbindgen](https://github.com/mozilla/cbindgen) - A project for generating C bindings from Rust code
* [watchexec/cargo-watch](https://github.com/watchexec/cargo-watch) - Watches over your Cargo project's source. *(archived)*
* [habitat-sh/habitat](https://github.com/habitat-sh/habitat) - Modern applications with built-in automation
* [framesurge/perseus](https://github.com/framesurge/perseus) - A state-driven web development framework for Rust with full support for server-side rendering and static generation.
* [CleanCut/ultimate_rust_crash_course](https://github.com/CleanCut/ultimate_rust_crash_course) - Rust Programming Fundamentals - one course to rule them all, one course to find them...
* [retep998/winapi-rs](https://github.com/retep998/winapi-rs) - Rust bindings to Windows API
* [tikv/grpc-rs](https://github.com/tikv/grpc-rs) - The gRPC library for Rust built on C Core library and futures
* [rust-fuzz/afl.rs](https://github.com/rust-fuzz/afl.rs) - 🐇 Fuzzing Rust code with American Fuzzy Lop
* [dtolnay/quote](https://github.com/dtolnay/quote) - Rust quasi-quoting
* [golemparts/rppal](https://github.com/golemparts/rppal) - A Rust library that provides access to the Raspberry Pi's GPIO, I2C, PWM, SPI and UART peripherals. *(archived)*
* [burtonageo/cargo-bundle](https://github.com/burtonageo/cargo-bundle) - Wrap rust executables in OS-specific app bundles
* [alexcrichton/curl-rust](https://github.com/alexcrichton/curl-rust) - Rust bindings to libcurl
* [clux/muslrust](https://github.com/clux/muslrust) - Docker environment for building musl based static rust binaries
* [stacks-sbtc/sbtc](https://github.com/stacks-sbtc/sbtc) - sBTC is a 1:1 Bitcoin-backed asset, enabling users to put their BTC to work in DeFi, dApps, and other applications.
* [alexcrichton/cc-rs](https://github.com/alexcrichton/cc-rs) - Fork of rust-lang/cc-rs

### Package Management

* [astral-sh/uv](https://github.com/astral-sh/uv) - An extremely fast Python package and project manager, written in Rust.
* [jdx/mise](https://github.com/jdx/mise) - dev tools, env vars, task runner
* [Schniz/fnm](https://github.com/Schniz/fnm) - 🚀 Fast and simple Node.js version manager, built in Rust
* [rust-lang/cargo](https://github.com/rust-lang/cargo) - The Rust package manager
* [prefix-dev/pixi](https://github.com/prefix-dev/pixi) - Powerful system-level package manager for Linux, macOS and Windows written in Rust – building on top of the Conda ecosystem.
* [rust-lang/rustup](https://github.com/rust-lang/rustup) - The Rust toolchain installer
* [flox/flox](https://github.com/flox/flox) - The Deterministic Foundation for your SDLC
* [rust-lang/crates.io](https://github.com/rust-lang/crates.io) - The Rust package registry
* [killercup/cargo-edit](https://github.com/killercup/cargo-edit) - A utility for managing cargo dependencies from the command line.
* [zurawiki/gptcommit](https://github.com/zurawiki/gptcommit) - A git prepare-commit-msg hook for authoring commit messages with LLMs.
* [gtk-rs/gtk4-rs](https://github.com/gtk-rs/gtk4-rs) - Rust bindings of GTK 4
* [supabase/etl](https://github.com/supabase/etl) - A high-performance Postgres replication engine written in Rust. Embed it in your Rust application or run it as a standalone binary.
* [rust-embedded/heapless](https://github.com/rust-embedded/heapless) - Heapless, `static` friendly data structures
* [dswd/vpncloud](https://github.com/dswd/vpncloud) - Peer-to-peer VPN
* [Eugeny/russh](https://github.com/Eugeny/russh) - Rust SSH client & server library
* [SeaQL/sea-query](https://github.com/SeaQL/sea-query) - 🔱 A dynamic SQL query builder for MySQL, Postgres and SQLite
* [mooman219/fontdue](https://github.com/mooman219/fontdue) - The fastest font renderer in the world, written in pure rust.
* [geiger-rs/cargo-geiger](https://github.com/geiger-rs/cargo-geiger) - Detects usage of unsafe Rust in a Rust crate and its dependencies.
* [mozilla/grcov](https://github.com/mozilla/grcov) - Rust tool to collect and aggregate code coverage data for multiple source files
* [holochain/holochain-rust](https://github.com/holochain/holochain-rust) - DEPRECATED. The Holochain framework implemented in rust with a redux style internal state-model. *(archived)*
* [sidkshatriya/rd](https://github.com/sidkshatriya/rd) - rd is a record/replay debugger written in rust *(archived)*
* [suptejas/volt](https://github.com/suptejas/volt) - An experimental package management tool for JavaScript. Upto 30x faster installation of dependencies using pre-flattened dependency trees.

### Linters and Formatters

* [astral-sh/ruff](https://github.com/astral-sh/ruff) - An extremely fast Python linter and code formatter, written in Rust.
* [ast-grep/ast-grep](https://github.com/ast-grep/ast-grep) - ⚡A CLI tool for code structural search, lint and rewriting. Written in Rust
* [rust-lang/rust-clippy](https://github.com/rust-lang/rust-clippy) - A bunch of lints to catch common mistakes and improve your Rust code. Book: https://doc.rust-lang.org/clippy/
* [rust-lang/rustfmt](https://github.com/rust-lang/rustfmt) - Format Rust code
* [facebook/pyrefly](https://github.com/facebook/pyrefly) - A fast type checker and language server for Python
* [dudykr/stc](https://github.com/dudykr/stc) - Speedy TypeScript type checker *(archived)*
* [vllm-project/semantic-router](https://github.com/vllm-project/semantic-router) - A programmable Mixture-of-Models router for heterogeneous LLM inference
* [biomejs/gritql](https://github.com/biomejs/gritql) - GritQL is a query language for searching, linting, and modifying code.
* [fallow-rs/fallow](https://github.com/fallow-rs/fallow) - Codebase intelligence for TypeScript and JavaScript. Free static analysis of code and styles: unused code, duplication, circular deps, complexity hotspots, architecture boundaries, design-system drift. Optional paid runtime layer (Fallow Runtime): hot-path review and cold-path deletion evidence from real production traffic.
* [crate-ci/typos](https://github.com/crate-ci/typos) - Source code spell checker
* [Ataraxy-Labs/sem](https://github.com/Ataraxy-Labs/sem) - Semantic version control => entity-level diffs, blame, and impact analysis on top of git. 28 languages via tree-sitter. Built for coding agents.
* [sentrux/sentrux](https://github.com/sentrux/sentrux) - Real-time architectural sensor that helps AI agents close the feedback loop, enabling recursive self-improvement of code quality. Pure Rust.
* [mtshiba/pylyzer](https://github.com/mtshiba/pylyzer) - A fast, feature-rich static code analyzer & language server for Python
* [zhboner/realm](https://github.com/zhboner/realm) - A network relay tool
* [google/autocxx](https://github.com/google/autocxx) - Tool for safe ergonomic Rust/C++ interop driven from existing C++ headers
* [ntex-rs/ntex](https://github.com/ntex-rs/ntex) - framework for composable networking services
* [bionic-gpt/bionic-gpt](https://github.com/bionic-gpt/bionic-gpt) - Bionic is sovereign AI for the enterprise — ChatGPT-like AI that runs on-premise and can securely work with your sensitive data and systems.
* [gmg137/netease-cloud-music-gtk](https://github.com/gmg137/netease-cloud-music-gtk) - Linux 平台下基于 Rust + GTK 开发的网易云音乐播放器
* [tramhao/termusic](https://github.com/tramhao/termusic) - Music Player TUI written in Rust
* [bytebeamio/rumqtt](https://github.com/bytebeamio/rumqtt) - The MQTT ecosystem in rust
* [SuperCuber/dotter](https://github.com/SuperCuber/dotter) - A dotfile manager and templater written in rust 🦀
* [fede1024/rust-rdkafka](https://github.com/fede1024/rust-rdkafka) - A fully asynchronous, futures-based Kafka client library for Rust based on librdkafka
* [slog-rs/slog](https://github.com/slog-rs/slog) - Structured, contextual, extensible, composable logging for Rust
* [tikv/pprof-rs](https://github.com/tikv/pprof-rs) - A Rust CPU profiler implemented with the help of backtrace-rs
* [rust-openssl/rust-openssl](https://github.com/rust-openssl/rust-openssl) - OpenSSL bindings for Rust
* [tyrchen/geektime-rust](https://github.com/tyrchen/geektime-rust) - 我的极客时间 Rust 课程的代码仓库，随课程更新
* [lpxxn/rust-design-pattern](https://github.com/lpxxn/rust-design-pattern) - rust design patterns
* [bbodi/notecalc3](https://github.com/bbodi/notecalc3) - NoteCalc is a handy calculator trying to bring the advantages of Soulver to the web.
* [plietar/librespot](https://github.com/plietar/librespot) - Open Source Spotify client library
* [facebookexperimental/MIRAI](https://github.com/facebookexperimental/MIRAI) - Rust mid-level IR Abstract Interpreter *(archived)*
* [rust-lang/rustfix](https://github.com/rust-lang/rustfix) - Automatically apply the suggestions made by rustc *(archived)*
* [google/rerast](https://github.com/google/rerast) - A tool for transforming Rust code using rules *(archived)*

### Debugging and Profiling

* [rust-lang/miri](https://github.com/rust-lang/miri) - An interpreter for Rust's mid-level intermediate representation
* [flamegraph-rs/flamegraph](https://github.com/flamegraph-rs/flamegraph) - Easy flamegraphs for Rust projects and everything else, without Perl or pipes <3
* [tokio-rs/console](https://github.com/tokio-rs/console) - a debugger for async rust!
* [probe-rs/probe-rs](https://github.com/probe-rs/probe-rs) - A debugging toolset and library for debugging embedded ARM and RISC-V targets on a separate host
* [mohsen1/yek](https://github.com/mohsen1/yek) - A fast Rust based tool to serialize text-based files in a repository or directory for LLM consumption
* [ifd3f/caligula](https://github.com/ifd3f/caligula) - A user-friendly, lightweight TUI for disk imaging
* [TimmyOVO/deepseek-ocr.rs](https://github.com/TimmyOVO/deepseek-ocr.rs) - Rust multi‑backend OCR/VLM engine (DeepSeek‑OCR-1/2, PaddleOCR‑VL, DotsOCR) with DSQ quantization and an OpenAI‑compatible server & CLI – run locally without Python.
* [jonhoo/fantoccini](https://github.com/jonhoo/fantoccini) - A high-level API for programmatically interacting with web pages through WebDriver.
* [matanolabs/matano](https://github.com/matanolabs/matano) - Open source security data lake for threat hunting, detection & response, and cybersecurity analytics at petabyte scale on AWS
* [Totodore/socketioxide](https://github.com/Totodore/socketioxide) - A socket.io server implementation in Rust that integrates with the Tower ecosystem and the Tokio stack.
* [use-ink/ink](https://github.com/use-ink/ink) - Polkadot's ink! to write smart contracts.
* [prisma/prisma-engines](https://github.com/prisma/prisma-engines) - 🚂 Engine components of Prisma ORM
* [SoptikHa2/desed](https://github.com/SoptikHa2/desed) - Debugger for Sed: demystify and debug your sed scripts, from comfort of your terminal.
* [gimli-rs/gimli](https://github.com/gimli-rs/gimli) - A library for reading and writing the DWARF debugging format
* [headcrab-rs/headcrab](https://github.com/headcrab-rs/headcrab) - A modern Rust debugging library 🦀
* [llogiq/flame](https://github.com/llogiq/flame) - An intrusive flamegraph profiling tool for rust.

### Editor and IDE Support

* [screenpipe/screenpipe](https://github.com/screenpipe/screenpipe) - YC (S26) | Open Computer History | Record your screen continuously locally and provide context to your agents (Claude, Codex, Openclaw, Hermes, Runner...)
* [rust-lang/rust-analyzer](https://github.com/rust-lang/rust-analyzer) - A Rust compiler front-end for IDEs
* [cordx56/rustowl](https://github.com/cordx56/rustowl) - Visualize Ownership and Lifetimes in Rust
* [dprint/dprint](https://github.com/dprint/dprint) - Pluggable and configurable code formatting platform that unifies all your formatters.
* [rust-lang/rls](https://github.com/rust-lang/rls) - Repository for the Rust Language Server (aka RLS) *(archived)*
* [racer-rust/racer](https://github.com/racer-rust/racer) - Rust Code Completion utility
* [willcrichton/flowistry](https://github.com/willcrichton/flowistry) - Flowistry is an IDE plugin for Rust that helps you focus on relevant code.
* [anthropics/claudes-c-compiler](https://github.com/anthropics/claudes-c-compiler) - Claude Opus 4.6 wrote a dependency-free C compiler in Rust, with backends targeting x86 (64- and 32-bit), ARM, and RISC-V, capable of compiling a booting Linux kernel.
* [moka-rs/moka](https://github.com/moka-rs/moka) - A high performance concurrent caching library for Rust
* [kpcyrd/sn0int](https://github.com/kpcyrd/sn0int) - Semi-automatic OSINT framework and package manager
* [wasmi-labs/wasmi](https://github.com/wasmi-labs/wasmi) - Efficient and versatile WebAssembly interpreter for embedded systems.
* [rust-lang/rustc_codegen_cranelift](https://github.com/rust-lang/rustc_codegen_cranelift) - Cranelift based backend for rustc
* [not-fl3/miniquad](https://github.com/not-fl3/miniquad) - Cross platform rendering in Rust
* [AppFlowy-IO/AppFlowy-Cloud](https://github.com/AppFlowy-IO/AppFlowy-Cloud) - Bring projects, wikis, and teams together with AI. AppFlowy is the AI collaborative workspace where you achieve more without losing control of your data. The leading open source Notion alternative. *(archived)*
* [aurae-runtime/aurae](https://github.com/aurae-runtime/aurae) - Distributed systems runtime daemon written in Rust.
* [compio-rs/compio](https://github.com/compio-rs/compio) - A thread-per-core async Rust runtime with IOCP/io_uring/polling.
* [bnjbvr/rouille](https://github.com/bnjbvr/rouille) - Rust programming, in French.
* [gchp/iota](https://github.com/gchp/iota) - A terminal-based text editor written in Rust
* [intermezzOS/kernel](https://github.com/intermezzOS/kernel) - A hobby operating system, in Rust *(archived)*
* [RustAudio/vst-rs](https://github.com/RustAudio/vst-rs) - VST 2.4 API implementation in rust. Create plugins or hosts. Previously rust-vst on the RustDSP group. *(archived)*
* [oakes/SolidOak](https://github.com/oakes/SolidOak) - An IDE for Rust *(archived)*
* [hypercube-lab/hypercube](https://github.com/hypercube-lab/hypercube) - HyperCube is a revolutionary, high-performance decentralized computing platform. HyperCube has powerful computing capabilities to provide high-performance computing power and large-scale data storage support for VR, AR, Metaverse, Artificial Intelligence, Big Data, and Financial Applications.🛰
* [euclio/vim-markdown-composer](https://github.com/euclio/vim-markdown-composer) - An asynchronous markdown preview plugin for Vim and Neovim.

## Web

### Web Frameworks

* [DioxusLabs/dioxus](https://github.com/DioxusLabs/dioxus) - Fullstack app framework for web, desktop, and mobile.
* [yewstack/yew](https://github.com/yewstack/yew) - Rust / Wasm framework for creating reliable and efficient web applications
* [tokio-rs/axum](https://github.com/tokio-rs/axum) - HTTP routing and request-handling library for Rust that focuses on ergonomics and modularity
* [rwf2/Rocket](https://github.com/rwf2/Rocket) - A web framework for Rust.
* [actix/actix-web](https://github.com/actix/actix-web) - Actix Web is a powerful, pragmatic, and extremely fast web framework for Rust.
* [leptos-rs/leptos](https://github.com/leptos-rs/leptos) - Build fast web applications with Rust.
* [seanmonstar/warp](https://github.com/seanmonstar/warp) - A super-easy, composable, web server framework for warp speeds.
* [loco-rs/loco](https://github.com/loco-rs/loco) - 🚂 🦀 The one-person framework for Rust for side-projects and startups
* [sparckles/Robyn](https://github.com/sparckles/Robyn) - Robyn is a Super Fast Async Python Web Framework with a Rust runtime.
* [iron/iron](https://github.com/iron/iron) - An Extensible, Concurrent Web Framework for Rust
* [http-rs/tide](https://github.com/http-rs/tide) - Fast and friendly HTTP server framework for async Rust
* [poem-web/poem](https://github.com/poem-web/poem) - A full-featured and easy-to-use web framework with the Rust programming language.
* [salvo-rs/salvo](https://github.com/salvo-rs/salvo) - A powerful web framework built with a simplified design.
* [tower-rs/tower](https://github.com/tower-rs/tower) - async fn(Request) -> Result<Response, Error>
* [nickel-org/nickel.rs](https://github.com/nickel-org/nickel.rs) - An expressjs inspired web framework for Rust
* [MordechaiHadad/bob](https://github.com/MordechaiHadad/bob) - A version manager for neovim
* [dtolnay/case-studies](https://github.com/dtolnay/case-studies) - Analysis of various tricky Rust code
* [editso/fuso](https://github.com/editso/fuso) - 一款体积小, 快速, 稳定, 高效, 轻量的内网穿透, 端口转发工具 支持多连接,级联代理,传输加密 (A small volume, fast, stable, efficient, and lightweight intranet penetration, port forwarding tool supports multiple connections, cascading proxy, and transmission encryption)
* [grovesNL/glow](https://github.com/grovesNL/glow) - GL on Whatever: a set of bindings to run GL anywhere and avoid target-specific code
* [orhun/systeroid](https://github.com/orhun/systeroid) - A more powerful alternative to sysctl(8) with a terminal user interface 🐧
* [mmstick/parallel](https://github.com/mmstick/parallel) - This project now lives on in a rewrite at https://gitlab.redox-os.org/redox-os/parallel *(archived)*
* [fengsp/pencil](https://github.com/fengsp/pencil) - A web application microframework for Rust
* [Ogeon/rustful](https://github.com/Ogeon/rustful) - [OUTDATED] A light HTTP framework for Rust *(archived)*
* [rustless/rustless](https://github.com/rustless/rustless) - REST-like API micro-framework for Rust. Works with Iron.
* [miketang84/sapper](https://github.com/miketang84/sapper) - A lightweight web framework built on hyper, implemented in Rust language.

### HTTP and Networking Clients

* [hyperium/hyper](https://github.com/hyperium/hyper) - An HTTP library for Rust
* [seanmonstar/reqwest](https://github.com/seanmonstar/reqwest) - An easy and powerful Rust HTTP Client
* [ducaale/xh](https://github.com/ducaale/xh) - Friendly and fast tool for sending HTTP requests
* [serenity-rs/serenity](https://github.com/serenity-rs/serenity) - A Rust library for the Discord API.
* [brave/adblock-rust](https://github.com/brave/adblock-rust) - Brave's Rust-based adblock engine
* [nical/lyon](https://github.com/nical/lyon) - 2D graphics rendering on the GPU in rust using path tessellation.
* [google/zerocopy](https://github.com/google/zerocopy) - Zerocopy makes zero-cost memory manipulation effortless. We write `unsafe` so you don’t have to.
* [RohanAdwankar/oxdraw](https://github.com/RohanAdwankar/oxdraw) - Diagram as Code Tool Written in Rust with Draggable Editing
* [thx/resvg-js](https://github.com/thx/resvg-js) - A high-performance SVG renderer and toolkit, powered by Rust based resvg and napi-rs.
* [risinglightdb/risinglight](https://github.com/risinglightdb/risinglight) - An educational OLAP database system.
* [mozilla-services/syncstorage-rs](https://github.com/mozilla-services/syncstorage-rs) - Sync Storage server in Rust
* [losfair/mvsqlite](https://github.com/losfair/mvsqlite) - Distributed, MVCC SQLite that runs on FoundationDB.
* [eliihen/wsta](https://github.com/eliihen/wsta) - A CLI development tool for WebSocket APIs

### API and GraphQL

* [graphql-rust/juniper](https://github.com/graphql-rust/juniper) - GraphQL server library for Rust
* [trailbaseio/trailbase](https://github.com/trailbaseio/trailbase) - An open, sub-millisecond, single-executable Firebase alternative with type-safe APIs, built-in WebAssembly runtime, realtime subscriptions, auth, MCP and admin UI built on Rust, SQLite (PG) & Wasmtime.
* [juhaku/utoipa](https://github.com/juhaku/utoipa) - Simple, Fast, Code first and Compile time generated OpenAPI documentation for Rust
* [async-graphql/async-graphql](https://github.com/async-graphql/async-graphql) - A GraphQL server library implemented in Rust
* [roapi/roapi](https://github.com/roapi/roapi) - Create full-fledged APIs for slowly moving datasets without writing a single line of code.
* [svix/svix-webhooks](https://github.com/svix/svix-webhooks) - The open source and enterprise-ready webhooks service 🦀
* [rust-scraper/scraper](https://github.com/rust-scraper/scraper) - HTML parsing and querying with CSS selectors
* [rtic-rs/rtic](https://github.com/rtic-rs/rtic) - Real-Time Interrupt-driven Concurrency (RTIC) framework for ARM Cortex-M microcontrollers
* [bodil/im-rs](https://github.com/bodil/im-rs) - Assorted immutable collection datatypes for Rust *(archived)*
* [paperclip-rs/paperclip](https://github.com/paperclip-rs/paperclip) - WIP OpenAPI tooling for Rust.
* [canduma/canduma](https://github.com/canduma/canduma) - A Rust server with GraphQL API, Diesel, PostgreSQL, session authentication and JWT
* [coleomo/PacBao](https://github.com/coleomo/PacBao) - Building lightweight (less than 2MB) desktop and mobile applications using such as HTML/Vue/React takes only a few minutes.使用Html/Vue/React等技术构建轻量级(小于2M)桌面应用和手机应用仅需2秒。https://pacbao.com

### Frontend and UI Components

* [servo/servo](https://github.com/servo/servo) - Servo aims to empower developers with a lightweight, high-performance alternative for embedding web technologies in applications.
* [parcel-bundler/lightningcss](https://github.com/parcel-bundler/lightningcss) - An extremely fast CSS parser, transformer, bundler, and minifier written in Rust.
* [seed-rs/seed](https://github.com/seed-rs/seed) - A Rust framework for creating web apps
* [gosub-io/gosub-engine](https://github.com/gosub-io/gosub-engine) - The Gosub browser engine
* [koute/stdweb](https://github.com/koute/stdweb) - A standard library for the client-side Web
* [sycamore-rs/sycamore](https://github.com/sycamore-rs/sycamore) - A library for creating reactive web apps in Rust and WebAssembly
* [MaikKlein/unreal-rust](https://github.com/MaikKlein/unreal-rust) - Rust integration for Unreal Engine 5
* [tensorchord/pgvecto.rs](https://github.com/tensorchord/pgvecto.rs) - Scalable, Low-latency and Hybrid-enabled Vector Search in Postgres. Revolutionize Vector Search, not Database.
* [rust-lang/cc-rs](https://github.com/rust-lang/cc-rs) - Rust library for build scripts to compile C/C++ code into a Rust library
* [rust-cli/human-panic](https://github.com/rust-cli/human-panic) - Panic messages for humans.
* [EmbarkStudios/quilkin](https://github.com/EmbarkStudios/quilkin) - Quilkin is a non-transparent UDP proxy specifically designed for use with large scale multiplayer dedicated game server deployments, to ensure security, access control, telemetry data, metrics and more.
* [hyperium/h2](https://github.com/hyperium/h2) - HTTP 2.0 client & server implementation for Rust.
* [Pauan/rust-dominator](https://github.com/Pauan/rust-dominator) - Zero-cost ultra-high-performance declarative DOM library using FRP signals for Rust!
* [riker-rs/riker](https://github.com/riker-rs/riker) - Easily build efficient, highly concurrent and resilient applications. An Actor Framework for Rust.
* [mine-Proxy/RustMinerSystem](https://github.com/mine-Proxy/RustMinerSystem) - 最稳定的BTC-全币种代理中转,开发者费用固定千分之2（1台也是0.02%，没有矿机数量门坎）几乎无损的转发，近乎变态的精准比例；轻松支持百万级并发！开发费单一抽取、精准比例、杜绝市面上“定制版多个钱包”导致的算力波动！minerproxy minerproxy minerproxy minerproxy minerproxy minerproxy minerproxy minerproxy minerproxy minerproxy minerproxy minerproxy minerproxy minerproxy minerproxy minerproxy minerproxy minerproxy minerproxy RustMinerSystem RustMinerSystem

### Web Servers and Proxies

* [sigoden/dufs](https://github.com/sigoden/dufs) - A file server that supports static serving, uploading, searching, accessing control, webdav...
* [emmett-framework/granian](https://github.com/emmett-framework/granian) - A Rust HTTP server for Python applications
* [maplibre/martin](https://github.com/maplibre/martin) - Blazing fast and lightweight PostGIS, MBtiles and PMtiles tile server, tile generation, and mbtiles tooling.
* [sozu-proxy/sozu](https://github.com/sozu-proxy/sozu) - Sōzu HTTP reverse proxy, configurable at runtime, fast and safe, built in Rust. It is awesome!
* [TheWaWaR/simple-http-server](https://github.com/TheWaWaR/simple-http-server) - Simple http server in Rust (Windows/Mac/Linux)
* [mikaelmello/inquire](https://github.com/mikaelmello/inquire) - A Rust library for building interactive prompts
* [eyre-rs/eyre](https://github.com/eyre-rs/eyre) - A trait object based error handling type for easy idiomatic error handling and reporting in Rust applications
* [tiny-http/tiny-http](https://github.com/tiny-http/tiny-http) - Low level HTTP server library in Rust
* [mufeedvh/binserve](https://github.com/mufeedvh/binserve) - A fast production-ready static web server with TLS (HTTPS), routing, hot reloading, caching, templating, and security in a single-binary you can set up with zero code.

### Scraping and Crawling

* [h4ckf0r0day/obscura](https://github.com/h4ckf0r0day/obscura) - The headless browser for AI agents and web scraping
* [keon/browser-control](https://github.com/keon/browser-control) - A tiny, fast Rust CLI that drives a real browser over the Chrome DevTools Protocol — built for coding agents.
* [rust-headless-chrome/rust-headless-chrome](https://github.com/rust-headless-chrome/rust-headless-chrome) - A high-level API to control headless Chrome or Chromium over the DevTools Protocol. It is the Rust equivalent of Puppeteer, a Node library maintained by the Chrome DevTools team.
* [pulldown-cmark/pulldown-cmark](https://github.com/pulldown-cmark/pulldown-cmark) - An efficient, reliable parser for CommonMark, a standard dialect of Markdown
* [tildeio/helix](https://github.com/tildeio/helix) - Native Ruby extensions without fear *(archived)*
* [oreboot/oreboot](https://github.com/oreboot/oreboot) - oreboot is a fork of coreboot, with C removed, written in Rust.
* [nervosnetwork/ckb](https://github.com/nervosnetwork/ckb) - The Nervos CKB is a public permissionless blockchain, and the layer 1 of Nervos network.
* [utkarshkukreti/select.rs](https://github.com/utkarshkukreti/select.rs) - A Rust library to extract useful data from HTML documents, suitable for web scraping.
* [atroche/rust-headless-chrome](https://github.com/atroche/rust-headless-chrome) - A high-level API to control headless Chrome or Chromium over the DevTools Protocol. It is the Rust equivalent of Puppeteer, a Node library maintained by the Chrome DevTools team.

## Data and Storage

### Databases

* [influxdata/influxdb](https://github.com/influxdata/influxdb) - Scalable datastore for metrics, events, and real-time analytics
* [rustfs/rustfs](https://github.com/rustfs/rustfs) - 🚀2.3x faster than MinIO for 4KB object payloads. RustFS is an open-source, S3-compatible high-performance object storage system supporting migration and coexistence with other S3-compatible platforms such as MinIO and Ceph.
* [tursodatabase/turso](https://github.com/tursodatabase/turso) - A SQL database in Rust: SQLite-compatible, now also speaking Postgres (experimental). The LLVM of databases.
* [neondatabase/neon](https://github.com/neondatabase/neon) - Neon: Serverless Postgres. We separated storage and compute to offer autoscaling, code-like database branching, and scale to zero.
* [tikv/tikv](https://github.com/tikv/tikv) - Distributed transactional key-value database, originally created to complement TiDB
* [get-convex/convex-backend](https://github.com/get-convex/convex-backend) - The open-source reactive database for app developers
* [databendlabs/databend](https://github.com/databendlabs/databend) - Data Agent Ready Warehouse : One for Analytics, Search, AI, Python Sandbox. — rebuilt from scratch. Unified architecture on your S3.
* [risingwavelabs/risingwave](https://github.com/risingwavelabs/risingwave) - Event streaming platform for agentic AI. Continuously ingest, transform, and serve event streams in real time, at scale.
* [apache/datafusion](https://github.com/apache/datafusion) - Apache DataFusion SQL Query Engine
* [spacejam/sled](https://github.com/spacejam/sled) - the champagne of beta embedded databases
* [erikgrinaker/toydb](https://github.com/erikgrinaker/toydb) - Distributed SQL database in Rust, written as an educational project
* [GreptimeTeam/greptimedb](https://github.com/GreptimeTeam/greptimedb) - The open-source observability database. One columnar engine for metrics, logs, and traces, on object storage.
* [MaterializeInc/materialize](https://github.com/MaterializeInc/materialize) - The live data layer for apps and AI agents. Create up-to-the-second views into your business, just using SQL
* [HelixDB/helix-db](https://github.com/HelixDB/helix-db) - HelixDB is an OLTP graph database with native vector and full-text search built in Rust on Object Storage.
* [malisper/pgrust](https://github.com/malisper/pgrust) - Postgres rewritten in Rust, now faster than Postgres and Clickhouse
* [cberner/redb](https://github.com/cberner/redb) - An embedded key-value database in pure Rust
* [deuxfleurs-org/garage](https://github.com/deuxfleurs-org/garage) - (Mirror) S3-compatible object store for small self-hosted geo-distributed deployments. Main repo: https://git.deuxfleurs.fr/Deuxfleurs/garage
* [slatedb/slatedb](https://github.com/slatedb/slatedb) - A cloud native embedded storage engine built on object storage.
* [gluesql/gluesql](https://github.com/gluesql/gluesql) - GlueSQL is quite sticky. It sticks to anything.
* [obi1kenobi/trustfall](https://github.com/obi1kenobi/trustfall) - A query engine for any combination of data sources. Query your files and APIs as if they were databases!
* [yuankunzhang/charming](https://github.com/yuankunzhang/charming) - A visualization library for Rust
* [0Chencc/CTFCrackTools](https://github.com/0Chencc/CTFCrackTools) - The next-generation CTF Swiss Army Knife powered by Rust & Tauri. Features a visual node-based workflow and local AI intelligence for extreme performance and automation.China's first CTFTools framework.
* [kkawakam/rustyline](https://github.com/kkawakam/rustyline) - Readline Implementation in Rust
* [fltk-rs/fltk-rs](https://github.com/fltk-rs/fltk-rs) - Rust bindings for the FLTK GUI library.
* [sunng87/handlebars-rust](https://github.com/sunng87/handlebars-rust) - Rust templating with Handlebars
* [simd-lite/simd-json](https://github.com/simd-lite/simd-json) - Rust port of simdjson
* [pgcentralfoundation/plrust](https://github.com/pgcentralfoundation/plrust) - A Rust procedural language handler for PostgreSQL
* [khonsulabs/bonsaidb](https://github.com/khonsulabs/bonsaidb) - A developer-friendly document database that grows with you, written in Rust
* [rust-lang/datafrog](https://github.com/rust-lang/datafrog) - A lightweight Datalog engine in Rust
* [andygrove/datafusion](https://github.com/andygrove/datafusion) - Apache arrow

### Database Clients and ORMs

* [transact-rs/sqlx](https://github.com/transact-rs/sqlx) - 🧰 The Rust SQL Toolkit. An async, pure Rust SQL crate featuring compile-time checked queries without a DSL. Supports PostgreSQL, MySQL, and SQLite.
* [diesel-rs/diesel](https://github.com/diesel-rs/diesel) - A safe, extensible ORM and Query Builder for Rust
* [HigherOrderCO/HVM2](https://github.com/HigherOrderCO/HVM2) - A massively parallel, optimal functional runtime in Rust
* [SeaQL/sea-orm](https://github.com/SeaQL/sea-orm) - 🐚 A powerful relational ORM for Rust
* [pgdogdev/pgdog](https://github.com/pgdogdev/pgdog) - PostgreSQL connection pooler, load balancer and database sharder.
* [pgcentralfoundation/pgrx](https://github.com/pgcentralfoundation/pgrx) - Build Postgres Extensions with Rust!
* [Qovery/Replibyte](https://github.com/Qovery/Replibyte) - Seed your development database with real data ⚡️
* [rusqlite/rusqlite](https://github.com/rusqlite/rusqlite) - Ergonomic bindings to SQLite for Rust
* [redis-rs/redis-rs](https://github.com/redis-rs/redis-rs) - Redis library for rust
* [postgresml/pgcat](https://github.com/postgresml/pgcat) - PostgreSQL pooler with sharding, load balancing and failover support.
* [rust-postgres/rust-postgres](https://github.com/rust-postgres/rust-postgres) - Native PostgreSQL driver for the Rust programming language
* [tokio-rs/toasty](https://github.com/tokio-rs/toasty) - An async ORM for Rust
* [rslint/rslint](https://github.com/rslint/rslint) - A (WIP) Extremely fast JavaScript and TypeScript linter and Rust crate
* [indradb/indradb](https://github.com/indradb/indradb) - A graph database written in rust
* [cristicbz/rust-doom](https://github.com/cristicbz/rust-doom) - A Doom Renderer written in Rust.
* [matklad/once_cell](https://github.com/matklad/once_cell) - Rust library for single assignment cells and lazy statics without macros
* [jamsocket/plane](https://github.com/jamsocket/plane) - A distributed system for running WebSocket services at scale.
* [rustmailer/bichon](https://github.com/rustmailer/bichon) - Bichon – A lightweight, high-performance Rust email archiver with WebUI
* [joaoviictorti/RustRedOps](https://github.com/joaoviictorti/RustRedOps) - Repository for advanced Red Team techniques focused on Rust
* [robertknight/ocrs](https://github.com/robertknight/ocrs) - Rust library and CLI tool for OCR (extracting text from images)
* [asomers/mockall](https://github.com/asomers/mockall) - A powerful mock object library for Rust
* [o8vm/octox](https://github.com/o8vm/octox) - Unix-like OS in Rust inspired by xv6-riscv
* [gfx-rs/naga](https://github.com/gfx-rs/naga) - Universal shader translation in Rust *(archived)*
* [m4b/goblin](https://github.com/m4b/goblin) - An impish, cross-platform binary parsing crate, written in Rust
* [lnx-search/lnx](https://github.com/lnx-search/lnx) - A flexible, performant and reliable search database without the AI bullshit.
* [deadpool-rs/deadpool](https://github.com/deadpool-rs/deadpool) - Dead simple pool implementation for rust with async-await
* [brendanzab/codespan](https://github.com/brendanzab/codespan) - Beautiful diagnostic reporting for text-based programming languages.
* [tikv/rust-prometheus](https://github.com/tikv/rust-prometheus) - Prometheus instrumentation library for Rust applications

### Serialization and Formats

* [serde-rs/serde](https://github.com/serde-rs/serde) - Serialization framework for Rust
* [rust-bakery/nom](https://github.com/rust-bakery/nom) - Rust parser combinator framework
* [lance-format/lance](https://github.com/lance-format/lance) - Open Lakehouse Format for Multimodal AI. Convert from Parquet in 2 lines of code for 100x faster random access, vector index, and data versioning. Compatible with Pandas, DuckDB, Polars, Pyarrow, and PyTorch with more integrations coming..
* [serde-rs/json](https://github.com/serde-rs/json) - Strongly typed JSON library for Rust
* [tokio-rs/prost](https://github.com/tokio-rs/prost) - PROST! a Protocol Buffers implementation for the Rust Language
* [rkyv/rkyv](https://github.com/rkyv/rkyv) - Zero-copy deserialization framework for Rust
* [ron-rs/ron](https://github.com/ron-rs/ron) - Rusty Object Notation
* [apache/arrow-rs](https://github.com/apache/arrow-rs) - Official Rust implementation of Apache Arrow
* [vortex-data/vortex](https://github.com/vortex-data/vortex) - An extensible, state-of-the-art framework for columnar compression, and the fastest FOSS columnar file format. Formerly at @spiraldb, now an Incubation Stage project at LFAI&Data, part of the Linux Foundation.
* [stepancheg/rust-protobuf](https://github.com/stepancheg/rust-protobuf) - Rust implementation of Google protocol buffers
* [deeplethe/forkd](https://github.com/deeplethe/forkd) - Fork() for AI agent microVMs. Spawn 100 children in ~100ms from a warm parent; BRANCH a live VM in ~150ms. KVM-isolated, snapshot CoW.
* [kaleidawave/ezno](https://github.com/kaleidawave/ezno) - A correct and efficient TypeScript type checker and compiler with additional experiments
* [trishume/syntect](https://github.com/trishume/syntect) - Rust library for syntax highlighting using Sublime Text syntax definitions.
* [nebulet/nebulet](https://github.com/nebulet/nebulet) - A proof-of-concept microkernel that implements a WebAssembly "usermode" that runs in Ring 0. *(archived)*
* [jonhoo/left-right](https://github.com/jonhoo/left-right) - A lock-free, read-optimized, concurrency primitive.
* [wasmerio/wasmer-python](https://github.com/wasmerio/wasmer-python) - 🐍🕸 WebAssembly runtime for Python
* [kyren/piccolo](https://github.com/kyren/piccolo) - An experimental stackless Lua VM implemented in pure Rust
* [Sh1Yo/x8](https://github.com/Sh1Yo/x8) - Hidden parameters discovery suite
* [audulus/rui](https://github.com/audulus/rui) - Declarative Rust UI library
* [sonnylazuardi/chat-ai-desktop](https://github.com/sonnylazuardi/chat-ai-desktop) - Unofficial ChatGPT desktop app for Mac & Windows menubar using Tauri & Rust
* [hexagonal-sun/moss-kernel](https://github.com/hexagonal-sun/moss-kernel) - Rust Linux-compatible kernel
* [marin-m/SongRec](https://github.com/marin-m/SongRec) - An open-source Shazam client for Linux, written in Rust.
* [rust-fuzz/cargo-fuzz](https://github.com/rust-fuzz/cargo-fuzz) - Command line helpers for fuzzing
* [run-llama/semtools](https://github.com/run-llama/semtools) - Semantic search and document parsing tools for the command line
* [tauri-apps/cargo-mobile2](https://github.com/tauri-apps/cargo-mobile2) - Rust on mobile made easy!
* [succinctlabs/sp1](https://github.com/succinctlabs/sp1) - SP1 is a zero‑knowledge virtual machine that proves the correct execution of programs compiled for the RISC-V architecture.
* [getdozer/dozer](https://github.com/getdozer/dozer) - Dozer is a real-time data movement tool that leverages CDC from various sources and moves data into various sinks.
* [BurntSushi/walkdir](https://github.com/BurntSushi/walkdir) - Rust library for walking directories recursively.
* [orogene/orogene](https://github.com/orogene/orogene) - Makes `node_modules/` happen. Fast. No fuss.
* [rust-lang/rust-playground](https://github.com/rust-lang/rust-playground) - The Rust Playground
* [holochain/holochain](https://github.com/holochain/holochain) - The current, performant & industrial strength version of Holochain on Rust.
* [pintariching/rustle](https://github.com/pintariching/rustle) - Svelte compiler rewritten in Rust *(archived)*
* [rustgd/cgmath](https://github.com/rustgd/cgmath) - A linear algebra and mathematics library for computer graphics.
* [fff-rs/juice](https://github.com/fff-rs/juice) - The Hacker's Machine Learning Engine
* [BurntSushi/byteorder](https://github.com/BurntSushi/byteorder) - Rust library for reading/writing numbers in big-endian and little-endian.
* [dtolnay/serde-yaml](https://github.com/dtolnay/serde-yaml) - Strongly typed YAML library for Rust *(archived)*
* [zhihu/rucene](https://github.com/zhihu/rucene) - Rust port of Lucene
* [ajour/ajour](https://github.com/ajour/ajour) - A World of Warcraft addon manager written in Rust. *(archived)*
* [pikkr/pikkr](https://github.com/pikkr/pikkr) - JSON parser which picks up values directly without performing tokenization in Rust
* [dropbox/pb-jelly](https://github.com/dropbox/pb-jelly) - A protobuf code generation framework for the Rust language developed at Dropbox.

### Caching and Queues

* [readysettech/readyset](https://github.com/readysettech/readyset) - Readyset is a MySQL and Postgres wire-compatible caching layer that sits in front of existing databases to speed up queries and horizontally scale read throughput. Under the hood, ReadySet caches the results of cached select statements and incrementally updates these results over time as the underlying data changes.
* [fluvio-community/fluvio](https://github.com/fluvio-community/fluvio) - 🦀 event stream processing for developers to collect and transform data in motion to power responsive data intensive applications.
* [apache/iggy](https://github.com/apache/iggy) - Apache Iggy: Hyper-Efficient Message Streaming at Laser Speed
* [MCHPR/MCHPRS](https://github.com/MCHPR/MCHPRS) - A multithreaded Minecraft server built for redstone.
* [gabdube/native-windows-gui](https://github.com/gabdube/native-windows-gui) - A light windows GUI toolkit for rust
* [console-rs/dialoguer](https://github.com/console-rs/dialoguer) - Rust utility library for nice command line prompts and similar things
* [ferrilab/bitvec](https://github.com/ferrilab/bitvec) - A crate for managing memory bit by bit
* [amqp-rs/lapin](https://github.com/amqp-rs/lapin) - AMQP client library in Rust, with a clean, futures based API
* [tremor-rs/tremor-runtime](https://github.com/tremor-rs/tremor-runtime) - Main Tremor Project Rust Codebase
* [valeriansaliou/bloom](https://github.com/valeriansaliou/bloom) - :cherry_blossom: HTTP REST API caching middleware, to be used between load balancers and REST API workers.
* [doyoubi/undermoon](https://github.com/doyoubi/undermoon) - Mordern Redis Cluster solution for easy operation.

### Search and Indexing

* [chroma-core/chroma](https://github.com/chroma-core/chroma) - Search infrastructure for AI
* [valeriansaliou/sonic](https://github.com/valeriansaliou/sonic) - 🦔 Fast, lightweight & schema-less search backend. An alternative to Elasticsearch that runs on a few MBs of RAM.
* [RyanCodrai/turbovec](https://github.com/RyanCodrai/turbovec) - A vector index built on TurboQuant, written in Rust with Python bindings
* [quickwit-oss/tantivy](https://github.com/quickwit-oss/tantivy) - Tantivy is a full-text search engine library inspired by Apache Lucene and written in Rust
* [quickwit-oss/quickwit](https://github.com/quickwit-oss/quickwit) - Cloud-native OSS search engine for observability
* [dmtrKovalenko/fff](https://github.com/dmtrKovalenko/fff) - The fastest and the most accurate file search SDK for AI agents, Neovim, Rust, C, Python, Bun and NodeJS
* [BloopAI/bloop](https://github.com/BloopAI/bloop) - bloop is a fast code search engine written in Rust. *(archived)*
* [paradedb/paradedb](https://github.com/paradedb/paradedb) - One Postgres for your application data, full-text search, vector retrieval, and aggregations. Home of the pg_search extension.
* [ruvnet/RuVector](https://github.com/ruvnet/RuVector) - RuVector is a High Performance, Real-Time, Self-Learning Ai, Vector GNN, Memory DB built in Rust.
* [toshi-search/Toshi](https://github.com/toshi-search/Toshi) - A full-text search engine in rust
* [tinysearch/tinysearch](https://github.com/tinysearch/tinysearch) - 🔍 Tiny, full-text search engine for static websites built with Rust and Wasm

## Machine Learning and AI

### LLM and Inference

* [ultraworkers/claw-code](https://github.com/ultraworkers/claw-code) - An agent-managed museum exhibit, built in Rust with Gajae-Code / LazyCodex — developed and maintained with no human intervention.
* [rtk-ai/rtk](https://github.com/rtk-ai/rtk) - CLI proxy that reduces LLM token consumption by 60-90% on common dev commands. Single Rust binary, zero dependencies
* [openinterpreter/openinterpreter](https://github.com/openinterpreter/openinterpreter) - A coding agent for open models like Kimi K3
* [Hmbown/Codewhale](https://github.com/Hmbown/Codewhale) - Open-source coding agent for your terminal, built in Rust and on a journey of continuous community improvement. Issues and PRs welcome.
* [herdrdev/herdr](https://github.com/herdrdev/herdr) - the runtime your coding agents live on
* [1jehuang/jcode](https://github.com/1jehuang/jcode) - The most RAM efficient harness
* [RightNow-AI/openfang](https://github.com/RightNow-AI/openfang) - Open-source Agent Operating System
* [nearai/ironclaw](https://github.com/nearai/ironclaw) - IronClaw is an Agent OS focused on privacy, security and extensibility
* [tensorzero/tensorzero](https://github.com/tensorzero/tensorzero) - TensorZero is an open-source LLMOps platform that unifies an LLM gateway, observability, evaluation, optimization, and experimentation. *(archived)*
* [sigoden/aichat](https://github.com/sigoden/aichat) - All-in-one LLM CLI tool featuring Shell Assistant, Chat-REPL, RAG, AI Tools & Agents, with access to OpenAI, Claude, Gemini, Ollama, Groq, and more.
* [Kuberwastaken/claurst](https://github.com/Kuberwastaken/claurst) - Agentic Coding for Builders who Ship
* [astrid-runtime/astrid](https://github.com/astrid-runtime/astrid) - Astrid is a portable, capability-secure operating system for composable software.
* [0xPlaygrounds/rig](https://github.com/0xPlaygrounds/rig) - ⚙️🦀 Build modular and scalable LLM Applications in Rust
* [ai-dynamo/dynamo](https://github.com/ai-dynamo/dynamo) - A Datacenter Scale Distributed Inference Serving Framework
* [EricLBuehler/mistral.rs](https://github.com/EricLBuehler/mistral.rs) - Fast, flexible LLM inference
* [mufeedvh/code2prompt](https://github.com/mufeedvh/code2prompt) - A CLI tool to convert your codebase into a single LLM prompt with source tree, prompt templating, and token counting.
* [rustformers/llm](https://github.com/rustformers/llm) - [Unmaintained, see README] An ecosystem of Rust libraries for working with large language models *(archived)*
* [Nasiko-Labs/nasiko](https://github.com/Nasiko-Labs/nasiko) - Developer Control Plane for your AI Agents
* [Michael-A-Kuykendall/shimmy](https://github.com/Michael-A-Kuykendall/shimmy) - ⚡ Pure-Rust WebGPU inference engine — OpenAI-API compatible, GGUF native, runs on any GPU. No Python. No llama.cpp. Single binary.
* [winfunc/deepreasoning](https://github.com/winfunc/deepreasoning) - A high-performance LLM inference API and Chat UI that integrates DeepSeek R1's CoT reasoning traces with Anthropic Claude models.
* [agentgateway/agentgateway](https://github.com/agentgateway/agentgateway) - Next Generation Agentic Proxy for AI Agents and MCP servers
* [modelcontextprotocol/rust-sdk](https://github.com/modelcontextprotocol/rust-sdk) - The official Rust SDK for the Model Context Protocol
* [yvgude/lean-ctx](https://github.com/yvgude/lean-ctx) - Control what your AI can see. LeanCTX (Lean Context) is the context intelligence layer for AI agents — one local Rust binary that decides what they read, remembers what they learn, guards what they touch, and proves what they save. 60–90% fewer tokens as the receipt. 76 MCP tools, 30+ agents, local-first.
* [tekaratzas/RustGPT](https://github.com/tekaratzas/RustGPT) - An transformer based LLM. Written completely in Rust
* [yologdev/yoyo-evolve](https://github.com/yologdev/yoyo-evolve) - A coding agent that evolves its own source, in public — 200 lines of Rust on day one, every commit since agent-written and tests-gated.

### Machine Learning Frameworks

* [huggingface/candle](https://github.com/huggingface/candle) - Minimalist ML framework for Rust
* [tracel-ai/burn](https://github.com/tracel-ai/burn) - Burn is a next generation tensor library and Deep Learning Framework that doesn't compromise on flexibility, efficiency and portability.
* [postgresml/postgresml](https://github.com/postgresml/postgresml) - Postgres with GPUs for ML/AI apps.
* [LaurentMazare/tch-rs](https://github.com/LaurentMazare/tch-rs) - Rust bindings for the C++ api of PyTorch.
* [tensorflow/rust](https://github.com/tensorflow/rust) - Rust language bindings for TensorFlow *(archived)*
* [rust-ml/linfa](https://github.com/rust-ml/linfa) - A Rust machine learning framework.
* [dathere/qsv](https://github.com/dathere/qsv) - Blazing-fast Data-Wrangling toolkit
* [sonos/tract](https://github.com/sonos/tract) - Tiny, no-nonsense, self-contained, Tensorflow and ONNX inference
* [rust-lang/libc](https://github.com/rust-lang/libc) - Raw bindings to platform APIs for Rust
* [colored-rs/colored](https://github.com/colored-rs/colored) - (Rust) Coloring terminal so simple you already know how to do it !
* [zmwangx/rust-ffmpeg](https://github.com/zmwangx/rust-ffmpeg) - Safe FFmpeg wrapper.
* [nymtech/nym](https://github.com/nymtech/nym) - Nym provides strong network-level privacy against sophisticated end-to-end attackers, and anonymous transactions using blinded, re-randomizable, decentralized credentials.
* [greyblake/nutype](https://github.com/greyblake/nutype) - Rust newtype with guarantees 🇺🇦 🦀
* [kivikakk/comrak](https://github.com/kivikakk/comrak) - CommonMark + GFM compatible Markdown parser and renderer
* [bodil/vgtk](https://github.com/bodil/vgtk) - A declarative desktop UI framework for Rust built on GTK and Gtk-rs *(archived)*

### Data Science and Analytics

* [pola-rs/polars](https://github.com/pola-rs/polars) - Extremely fast Query Engine for DataFrames, written in Rust
* [cube-js/cube](https://github.com/cube-js/cube) - 📊 Cube Core is open-source semantic layer for AI, BI and embedded analytics
* [cocoindex-io/cocoindex](https://github.com/cocoindex-io/cocoindex) - Incremental engine for long horizon agents 🌟 Star if you like it!
* [rerun-io/rerun](https://github.com/rerun-io/rerun) - Visualize, query, and stream to train on multimodal robotics data.
* [Eventual-Inc/Daft](https://github.com/Eventual-Inc/Daft) - High-performance data engine for AI and multimodal workloads. Process images, audio, video, and structured data at any scale
* [ArroyoSystems/arroyo](https://github.com/ArroyoSystems/arroyo) - Distributed stream processing engine in Rust
* [plotters-rs/plotters](https://github.com/plotters-rs/plotters) - A rust drawing library for high quality data plotting for both WASM and native, statically and realtimely 🦀 📈🚀
* [lakehq/sail](https://github.com/lakehq/sail) - Drop-in Apache Spark replacement written in Rust, unifying batch processing, stream processing, and compute-intensive AI workloads.
* [delta-io/delta-rs](https://github.com/delta-io/delta-rs) - A native Rust library for Delta Lake, with bindings into Python
* [PeerDB-io/peerdb](https://github.com/PeerDB-io/peerdb) - Fast, Simple and a cost effective tool to replicate data from Postgres to Data Warehouses, Queues and Storage
* [spiceai/spiceai](https://github.com/spiceai/spiceai) - Add a real-time analytics node to your operational database. Spice is a portable, accelerated SQL query, search, and LLM-inference engine in Rust for data-grounded AI apps and agents.
* [weld-project/weld](https://github.com/weld-project/weld) - High-performance runtime for data analytics applications
* [chelsea0x3b/dfdx](https://github.com/chelsea0x3b/dfdx) - Deep learning in Rust, with shape checked tensors and neural networks
* [dtolnay/rust-quiz](https://github.com/dtolnay/rust-quiz) - Medium to hard Rust questions with explanations
* [Aleph-Alpha/ts-rs](https://github.com/Aleph-Alpha/ts-rs) - Generate TypeScript bindings from Rust types
* [aws/s2n-quic](https://github.com/aws/s2n-quic) - An implementation of the IETF QUIC protocol
* [HerringtonDarkholme/vue-compiler](https://github.com/HerringtonDarkholme/vue-compiler) - Vue's template compiler reimplemented in Rust!
* [google/mundane](https://github.com/google/mundane) - Mundane is a Rust cryptography library backed by BoringSSL that is difficult to misuse, ergonomic, and performant (in that order).

## Networking and Distributed

### Networking

* [GyulyVGC/sniffnet](https://github.com/GyulyVGC/sniffnet) - Comfortably monitor your network traffic 🕵️‍♂️
* [rathole-org/rathole](https://github.com/rathole-org/rathole) - A lightweight and high-performance reverse proxy for NAT traversal, written in Rust. An alternative to frp and ngrok.
* [EasyTier/EasyTier](https://github.com/EasyTier/EasyTier) - A simple, decentralized mesh VPN with WireGuard support.
* [n0-computer/iroh](https://github.com/n0-computer/iroh) - IP addresses break, dial keys instead. A library that adds QUIC + NAT Traversal to your apps.
* [cloudflare/quiche](https://github.com/cloudflare/quiche) - 🥧 Savoury implementation of the QUIC transport protocol and HTTP/3
* [ekzhang/bore](https://github.com/ekzhang/bore) - 🕳 bore is a simple CLI tool for making tunnels to localhost
* [shadowsocks/shadowsocks-rust](https://github.com/shadowsocks/shadowsocks-rust) - A Rust port of shadowsocks
* [reacherhq/check-if-email-exists](https://github.com/reacherhq/check-if-email-exists) - Check if an email address exists without sending any email, written in Rust. Comes with a ⚙️ HTTP backend.
* [fujiapple852/trippy](https://github.com/fujiapple852/trippy) - A network diagnostic tool
* [cloudflare/boringtun](https://github.com/cloudflare/boringtun) - Userspace WireGuard® Implementation in Rust
* [tokio-rs/mio](https://github.com/tokio-rs/mio) - Metal I/O library for Rust.
* [agrinman/tunnelto](https://github.com/agrinman/tunnelto) - Expose your local web server to the internet with a public URL.
* [ogham/dog](https://github.com/ogham/dog) - A command-line DNS client.
* [telemt/telemt](https://github.com/telemt/telemt) - MTProxy for Telegram on Rust + Tokio
* [libp2p/rust-libp2p](https://github.com/libp2p/rust-libp2p) - The Rust Implementation of the libp2p networking stack.
* [hickory-dns/hickory-dns](https://github.com/hickory-dns/hickory-dns) - A Rust based DNS client, server, and resolver
* [quinn-rs/quinn](https://github.com/quinn-rs/quinn) - Async-friendly QUIC implementation in Rust
* [webrtc-rs/webrtc](https://github.com/webrtc-rs/webrtc) - Async-friendly WebRTC implementation in Rust
* [nkaz001/hftbacktest](https://github.com/nkaz001/hftbacktest) - Free, open source, a high frequency trading and market making backtesting and trading bot, which accounts for limit orders, queue positions, and latencies, utilizing full tick data for trades and order books(Level-2 and Level-3), with real-world crypto trading examples for Binance and Bybit
* [therealaleph/MasterHttpRelayVPN-RUST](https://github.com/therealaleph/MasterHttpRelayVPN-RUST) - Rust port of @masterking32's MasterHttpRelayVPN — all credit to @masterking32 for the original idea and Python implementation. Free DPI bypass via a Google Apps Script relay with TLS SNI concealment. CLI + cross-platform desktop UI, HTTP + SOCKS5 proxy, no runtime deps.
* [tuic-protocol/tuic](https://github.com/tuic-protocol/tuic) - Delicately-TUICed 0-RTT proxy protocol
* [vnt-dev/vnt](https://github.com/vnt-dev/vnt) - An efficient VPN. 简便高效的异地组网、内网穿透工具
* [Devolutions/IronRDP](https://github.com/Devolutions/IronRDP) - Rust implementation of the Microsoft Remote Desktop Protocol (RDP)
* [geph-official/geph4-client](https://github.com/geph-official/geph4-client) - Geph (迷霧通) is a modular Internet censorship circumvention system designed specifically to deal with national filtering.
* [zerobootdev/zeroboot](https://github.com/zerobootdev/zeroboot) - Sub-millisecond VM sandboxes for AI agents via copy-on-write forking
* [floneum/kalosm](https://github.com/floneum/kalosm) - Instant, controllable, local pre-trained AI models in Rust
* [alexhallam/tv](https://github.com/alexhallam/tv) - 📺(tv) Tidy Viewer is a cross-platform CLI csv pretty printer that uses column styling to maximize viewer enjoyment.
* [lgarron/folderify](https://github.com/lgarron/folderify) - :file_folder: Generate pixel-perfect macOS folder icons in the native style. (Now with support for macOS 26 Tahoe!)
* [ilai-deutel/kibi](https://github.com/ilai-deutel/kibi) - A text editor in ≤1024 lines of code, written in Rust
* [Uriopass/Egregoria](https://github.com/Uriopass/Egregoria) - 3D City Builder without a grid
* [chrisdickinson/git-rs](https://github.com/chrisdickinson/git-rs) - git, implemented in rust, for fun and education :crab:
* [tomaka/rouille](https://github.com/tomaka/rouille) - Web framework in Rust
* [japaric/xargo](https://github.com/japaric/xargo) - The sysroot manager that lets you build and customize `std`
* [maidsafe-archive/crust](https://github.com/maidsafe-archive/crust) - Reliable p2p network connections in Rust with NAT traversal. One of the most needed libraries for any server-less / decentralised projects *(archived)*
* [TimonPost/laminar](https://github.com/TimonPost/laminar) - A simple semi-reliable UDP protocol for multiplayer games
* [tokio-rs/tokio-proto](https://github.com/tokio-rs/tokio-proto) - A network application framework for Rust *(archived)*
* [bluejekyll/trust-dns](https://github.com/bluejekyll/trust-dns) - A Rust based DNS client, server, and resolver

### RPC and Messaging

* [grpc/grpc-rust](https://github.com/grpc/grpc-rust) - A native gRPC client & server implementation with async/await support.
* [google/tarpc](https://github.com/google/tarpc) - An RPC framework for Rust with a focus on ease of use.
* [eclipse-zenoh/zenoh](https://github.com/eclipse-zenoh/zenoh) - zenoh unifies data in motion, data in-use, data at rest and computations. It carefully blends traditional pub/sub with geo-distributed storages, queries and computations, while retaining a level of time and space efficiency that is well beyond any of the mainstream stacks.
* [openlake-project/openlake](https://github.com/openlake-project/openlake) - OpenLake is a high performance storage engine for efficient LLM inference and GPU Training
* [snapview/tungstenite-rs](https://github.com/snapview/tungstenite-rs) - Lightweight stream-based WebSocket implementation for Rust.
* [liuchengxu/vim-clap](https://github.com/liuchengxu/vim-clap) - :clap: Modern performant fuzzy picker, tree-sitter highlighting, and more, for both Vim and NeoVim
* [rust-av/Av1an](https://github.com/rust-av/Av1an) - Cross-platform command-line AV1 / VP9 / HEVC / H264 encoding framework with per scene quality encoding
* [oxfeeefeee/goscript](https://github.com/oxfeeefeee/goscript) - An alternative implementation of Golang specs, written in Rust for embedding or wrapping.
* [tomusdrw/rust-web3](https://github.com/tomusdrw/rust-web3) - Ethereum JSON-RPC multi-transport client. Rust implementation of web3 library. ENS address: rust-web3.eth
* [hermit-os/kernel](https://github.com/hermit-os/kernel) - A Rust-based, lightweight unikernel.
* [postgresml/korvus](https://github.com/postgresml/korvus) - Korvus is a search SDK that unifies the entire RAG pipeline in a single database query. Built on top of Postgres with bindings for Python, JavaScript, Rust and C.
* [erickt/rust-zmq](https://github.com/erickt/rust-zmq) - Rust zeromq bindings.
* [paritytech/jsonrpc](https://github.com/paritytech/jsonrpc) - Rust JSON-RPC implementation

### Distributed Systems

* [unionlabs/union](https://github.com/unionlabs/union) - The trust-minimized, zero-knowledge bridging protocol, designed for censorship resistance, extremely high security, and usage in decentralized finance.
* [FuelLabs/fuel-core](https://github.com/FuelLabs/fuel-core) - Rust full node implementation of the Fuel v2 protocol.
* [FuelLabs/fuels-rs](https://github.com/FuelLabs/fuels-rs) - Fuel Network Rust SDK
* [linera-io/linera-protocol](https://github.com/linera-io/linera-protocol) - Main repository for the Linera protocol
* [openobserve/openobserve](https://github.com/openobserve/openobserve) - Open source observability platform for logs, metrics, traces, frontend monitoring, pipelines and LLM observability. A sophisticated, simple and highly performant alternative to Datadog, Splunk, and Elasticsearch with 140x lower storage costs and single binary deployment.
* [solana-labs/solana](https://github.com/solana-labs/solana) - Web-Scale Blockchain for fast, secure, scalable, decentralized apps and marketplaces. *(archived)*
* [foundry-rs/foundry](https://github.com/foundry-rs/foundry) - Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.
* [paritytech/polkadot](https://github.com/paritytech/polkadot) - Polkadot Node Implementation *(archived)*
* [openethereum/parity-ethereum](https://github.com/openethereum/parity-ethereum) - The fast, light, and robust client for Ethereum-like networks. *(archived)*
* [rivet-dev/actors](https://github.com/rivet-dev/actors) - Rivet Actors are the primitive for stateful workloads. Built for AI agents, collaborative apps, and durable execution.
* [paradigmxyz/reth](https://github.com/paradigmxyz/reth) - Modular, contributor-friendly and blazing-fast implementation of the Ethereum protocol, in Rust
* [QuipNetwork/quip-validator](https://github.com/QuipNetwork/quip-validator) - A rust implementation of the Quip Protocol forked from Substrate
* [otter-sec/anchor](https://github.com/otter-sec/anchor) - ⚓ Solana Program Framework
* [mimblewimble/grin](https://github.com/mimblewimble/grin) - Minimal implementation of the Mimblewimble protocol.
* [ProvableHQ/snarkOS](https://github.com/ProvableHQ/snarkOS) - A Decentralized Operating System for ZK Applications
* [ordinals/ord](https://github.com/ordinals/ord) - 👁‍🗨 Rare and exotic sats
* [EvilGenius-dot/RustMinerSystem](https://github.com/EvilGenius-dot/RustMinerSystem) - 💰唯一正版💰 minerproxy minerproxy minerproxy minerproxy minerproxy minerproxy minerproxy minerproxy minerproxy minerproxy 矿池抽水 矿池代理 矿池中转 矿池抽水 minerproxy minerproxy minerproxy minerproxy minerproxy minerproxy minerproxy minerproxy minerproxy minerproxy minerproxy minerproxy minerproxy
* [TimelyDataflow/timely-dataflow](https://github.com/TimelyDataflow/timely-dataflow) - A modular implementation of timely dataflow in Rust
* [sigp/lighthouse](https://github.com/sigp/lighthouse) - Ethereum consensus client in Rust
* [tikv/raft-rs](https://github.com/tikv/raft-rs) - Raft distributed consensus algorithm implemented in Rust.
* [freenet/freenet-core](https://github.com/freenet/freenet-core) - Declare your digital independence
* [stacks-network/stacks-core](https://github.com/stacks-network/stacks-core) - The Stacks blockchain implementation
* [TimelyDataflow/differential-dataflow](https://github.com/TimelyDataflow/differential-dataflow) - An implementation of differential dataflow using timely dataflow on Rust.
* [paradigmxyz/artemis](https://github.com/paradigmxyz/artemis) - A simple, modular, and fast framework for writing MEV bots in Rust.
* [skytable/skytable](https://github.com/skytable/skytable) - Skytable is a modern scalable NoSQL database with BlueQL, designed for performance, scalability and flexibility. Skytable gives you spaces, models, data types, complex collections and more to build powerful experiences
* [FractalFir/rustc_codegen_clr](https://github.com/FractalFir/rustc_codegen_clr) - A Rust compiler backend targeting CIL(.NET IR) and C.
* [nubskr/walrus](https://github.com/nubskr/walrus) - 🦭 Distributed log streaming engine built from first principles
* [wormhole-foundation/wormhole](https://github.com/wormhole-foundation/wormhole) - A reference implementation for the Wormhole blockchain interoperability protocol.
* [anshulrgoyal/rust-web-developer-roadmap](https://github.com/anshulrgoyal/rust-web-developer-roadmap) - Roadmap to becoming a Rust Web Developer in 2022
* [buildfoundation/mainframer](https://github.com/buildfoundation/mainframer) - Tool for remote builds. Sync project to remote machine, execute command, sync back.
* [romanz/electrs](https://github.com/romanz/electrs) - An efficient re-implementation of Electrum Server in Rust
* [dalek-cryptography/bulletproofs](https://github.com/dalek-cryptography/bulletproofs) - A pure-Rust implementation of Bulletproofs using Ristretto.
* [ziesha-network/bazuka](https://github.com/ziesha-network/bazuka) - Rust implementation of Ziesha protocol
* [fluencelabs/nox](https://github.com/fluencelabs/nox) - Rust implementation of the Fluence network peer *(archived)*
* [akula-bft/akula](https://github.com/akula-bft/akula) - Fastest Ethereum archive node ever built *(archived)*
* [AcalaNetwork/Acala](https://github.com/AcalaNetwork/Acala) - Acala - cross-chain DeFi hub and stablecoin based on Substrate for Polkadot and Kusama.
* [substantic/rain](https://github.com/substantic/rain) - Framework for large distributed pipelines
* [paritytech/parity-bitcoin](https://github.com/paritytech/parity-bitcoin) - The Parity Bitcoin client
* [casey/ord](https://github.com/casey/ord) - 👁‍🗨 Rare and exotic sats
* [gakonst/foundry](https://github.com/gakonst/foundry) - Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.

### Cloud and Infrastructure

* [firecracker-microvm/firecracker](https://github.com/firecracker-microvm/firecracker) - Secure and fast microVMs for serverless computing.
* [Sjj1024/PakePlus](https://github.com/Sjj1024/PakePlus) - Turn any webpage/HTML/Vue/React and so on into desktop and mobile app under 5M with easy in few minutes. 轻松将任意网站/HTML/Vue/React等项目构建为轻量级(小于5M)多端桌面应用和手机应用仅需几分钟. https://ppofficial.netlify.app
* [bottlerocket-os/bottlerocket](https://github.com/bottlerocket-os/bottlerocket) - An operating system designed for hosting containers
* [ijl/orjson](https://github.com/ijl/orjson) - Fast, correct Python JSON library supporting dataclasses, datetimes, and numpy
* [superradcompany/microsandbox](https://github.com/superradcompany/microsandbox) - 🧱 easy fast local-first microVM runtime and library
* [youki-dev/youki](https://github.com/youki-dev/youki) - A container runtime written in Rust
* [shuttle-hq/shuttle](https://github.com/shuttle-hq/shuttle) - Build & ship backends without writing any infrastructure files. *(archived)*
* [cloud-hypervisor/cloud-hypervisor](https://github.com/cloud-hypervisor/cloud-hypervisor) - A Virtual Machine Monitor for modern Cloud workloads. Features include CPU, memory and device hotplug, support for running Windows and Linux guests, device offload with vhost-user and a minimal compact footprint. Written in Rust with a strong focus on security.
* [smol-machines/smolvm](https://github.com/smol-machines/smolvm) - Portable, lightweight, self-contained virtual machine.
* [metalbear-co/mirrord](https://github.com/metalbear-co/mirrord) - Run any process, on your machine or in an AI agent's environment, as if it were a pod in your Kubernetes cluster: real env vars, DNS, network, traffic.
* [hyperlight-dev/hyperlight](https://github.com/hyperlight-dev/hyperlight) - Hyperlight is a lightweight Virtual Machine Manager (VMM) designed to be embedded within applications. It enables safe execution of untrusted code within micro virtual machines with very low latency and minimal overhead.
* [kube-rs/kube](https://github.com/kube-rs/kube) - Rust Kubernetes client and controller runtime
* [cloudflare/workers-rs](https://github.com/cloudflare/workers-rs) - Write Cloudflare Workers in 100% Rust via WebAssembly
* [aws/aws-lambda-rust-runtime](https://github.com/aws/aws-lambda-rust-runtime) - A Rust runtime for AWS Lambda
* [krustlet/krustlet](https://github.com/krustlet/krustlet) - Kubernetes Rust Kubelet
* [railwayapp/nixpacks](https://github.com/railwayapp/nixpacks) - App source + Nix packages + Docker = Image
* [awslabs/aws-sdk-rust](https://github.com/awslabs/aws-sdk-rust) - AWS SDK for the Rust Programming Language
* [bahdotsh/wrkflw](https://github.com/bahdotsh/wrkflw) - Validate and Run GitHub Actions locally.
* [cloudflare/wrangler-legacy](https://github.com/cloudflare/wrangler-legacy) - 🤠 Home to Wrangler v1 (deprecated) *(archived)*
* [cloudwego/volo](https://github.com/cloudwego/volo) - Rust RPC framework with high-performance and strong-extensibility for building micro-services.
* [RustAudio/rodio](https://github.com/RustAudio/rodio) - Rust audio playback library
* [antoyo/relm](https://github.com/antoyo/relm) - Idiomatic, GTK+-based, GUI library, inspired by Elm, written in Rust
* [Peternator7/strum](https://github.com/Peternator7/strum) - A small rust library for adding custom derives to enums
* [bluealloy/revm](https://github.com/bluealloy/revm) - Rust implementation of the Ethereum Virtual Machine.
* [axodotdev/cargo-dist](https://github.com/axodotdev/cargo-dist) - 📦 shippable application packaging
* [slawlor/ractor](https://github.com/slawlor/ractor) - Rust actor framework
* [jaemk/cached](https://github.com/jaemk/cached) - Rust cache structures and easy function memoization
* [ms-jpq/sad](https://github.com/ms-jpq/sad) - CLI search and replace | Space Age seD
* [hermit-os/hermit-rs](https://github.com/hermit-os/hermit-rs) - Hermit for Rust.
* [bytecodealliance/wasm-tools](https://github.com/bytecodealliance/wasm-tools) - CLI and Rust libraries for low-level manipulation of WebAssembly modules
* [egoist/dum](https://github.com/egoist/dum) - An npm scripts runner written in Rust.
* [brahmGAN/ganchain-v2](https://github.com/brahmGAN/ganchain-v2) - This is the rust and substrate code for the GAN chain and its nodes.
* [skyzh/type-exercise-in-rust](https://github.com/skyzh/type-exercise-in-rust) - Learn advanced Rust techniques by building an expression evaluation framework for a database system.
* [kuasar-io/kuasar](https://github.com/kuasar-io/kuasar) - A multi-sandbox container runtime that provides cloud-native, all-scenario multiple sandbox container solutions.
* [unixzii/ibackupextractor](https://github.com/unixzii/ibackupextractor) - A simple tool for extracting files from iOS backup archive.
* [Zaplib/zaplib](https://github.com/Zaplib/zaplib) - ⚡ Zaplib is an open-source library for speeding up web applications using Rust and WebAssembly.
* [ihciah/clean-dns-bpf](https://github.com/ihciah/clean-dns-bpf) - 基于 Rust + eBPF 丢弃 GFW DNS 污染包
* [Trow-Registry/trow](https://github.com/Trow-Registry/trow) - Container Registry and Image Management for Kubernetes Clusters
* [saschagrunert/kubernix](https://github.com/saschagrunert/kubernix) - Single dependency Kubernetes clusters for local testing, experimenting and development.

### Monitoring and Observability

* [domcyrus/rustnet](https://github.com/domcyrus/rustnet) - Per-process network monitoring for your terminal with deep packet inspection. Cross-platform, sandboxed.
* [bytewax/bytewax](https://github.com/bytewax/bytewax) - Python Stream Processing
* [rp-rs/rp-hal](https://github.com/rp-rs/rp-hal) - A Rust Embedded-HAL for the rp series microcontrollers
* [metrics-rs/metrics](https://github.com/metrics-rs/metrics) - A metrics ecosystem for Rust.
* [getsentry/sentry-cli](https://github.com/getsentry/sentry-cli) - A command line utility to work with Sentry.
* [Canop/rhit](https://github.com/Canop/rhit) - A nginx log explorer
* [gsquire/topngx](https://github.com/gsquire/topngx) - top for NGINX

## User Interface

### GUI Toolkits

* [tauri-apps/tauri](https://github.com/tauri-apps/tauri) - Build smaller, faster, and more secure desktop and mobile applications with a web frontend.
* [iced-rs/iced](https://github.com/iced-rs/iced) - A cross-platform GUI library for Rust, inspired by Elm
* [emilk/egui](https://github.com/emilk/egui) - egui: an easy-to-use immediate mode GUI in Rust that runs on both web and native
* [slint-ui/slint](https://github.com/slint-ui/slint) - Slint is an open-source declarative GUI toolkit to build native user interfaces for Rust, C++, JavaScript, or Python apps.
* [longbridge/gpui-component](https://github.com/longbridge/gpui-component) - Rust GUI components for building fantastic cross-platform desktop application by using GPUI.
* [linebender/druid](https://github.com/linebender/druid) - A data-first Rust-native UI design toolkit.
* [makepad/makepad](https://github.com/makepad/makepad) - Makepad is a creative software development platform for Rust that compiles to wasm/webGL, osx/metal, windows/dx11 linux/opengl
* [rust-windowing/winit](https://github.com/rust-windowing/winit) - Window handling library in pure Rust
* [fschutt/azul](https://github.com/fschutt/azul) - Desktop GUI Framework
* [linebender/xilem](https://github.com/linebender/xilem) - An experimental Rust native UI framework
* [tauri-apps/wry](https://github.com/tauri-apps/wry) - Cross-platform WebView library in Rust for Tauri.
* [lapce/floem](https://github.com/lapce/floem) - A native Rust UI library with fine-grained reactivity
* [redox-os/orbtk](https://github.com/redox-os/orbtk) - The Rust UI-Toolkit.
* [DioxusLabs/taffy](https://github.com/DioxusLabs/taffy) - A high performance rust-powered UI layout library
* [PistonDevelopers/conrod](https://github.com/PistonDevelopers/conrod) - An easy-to-use, 2D GUI library written entirely in Rust.
* [Smithay/smithay](https://github.com/Smithay/smithay) - A smithy for rusty wayland compositors
* [marc2332/freya](https://github.com/marc2332/freya) - Cross-platform and non-web GUI library for 🦀 Rust powered by 🎨 Skia.
* [imgui-rs/imgui-rs](https://github.com/imgui-rs/imgui-rs) - Rust bindings for Dear ImGui
* [spyglass-search/spyglass](https://github.com/spyglass-search/spyglass) - A personal search engine: Create a searchable library from your personal documents, interests, and more! *(archived)*
* [Helvesec/rmux](https://github.com/Helvesec/rmux) - Universal Rust multiplexer with a typed SDK — drive any CLI or TUI app from code. Native on Linux, macOS, and Windows.
* [facet-rs/facet](https://github.com/facet-rs/facet) - Rust reflection, serialization, deserialization, pretty printing, etc. — the last proc macro you should need
* [bevy-cheatbook/bevy-cheatbook](https://github.com/bevy-cheatbook/bevy-cheatbook) - Unofficial Reference Book for the Bevy Game Engine
* [rust-lang-nursery/lazy-static.rs](https://github.com/rust-lang-nursery/lazy-static.rs) - A small macro for defining lazy evaluated static variables in Rust.
* [facebookincubator/fastmod](https://github.com/facebookincubator/fastmod) - A fast partial replacement for the codemod tool. Assists with large-scale codebase refactors via regex-based find and replace with human oversight and occasional intervention.
* [huytd/kanban-app](https://github.com/huytd/kanban-app) - Kanban board built with Rust and Elm
* [foniod/redbpf](https://github.com/foniod/redbpf) - Rust library for building and running BPF/eBPF modules *(archived)*
* [rust-db/refinery](https://github.com/rust-db/refinery) - Powerful SQL migration toolkit for Rust.
* [Smithay/wayland-rs](https://github.com/Smithay/wayland-rs) - Rust implementation of the wayland protocol (client and server).
* [emoon/rust_minifb](https://github.com/emoon/rust_minifb) - Cross platform window and framebuffer crate for Rust
* [ZhangHanDong/tao-of-rust-codes](https://github.com/ZhangHanDong/tao-of-rust-codes) - 《Rust编程之道》随书源码
* [joaoh82/rust_sqlite](https://github.com/joaoh82/rust_sqlite) - SQLRite - Simple embedded database modeled off SQLite in Rust
* [rust-native-ui/libui-rs](https://github.com/rust-native-ui/libui-rs) - Rust bindings to the minimalist, native, cross-platform UI toolkit `libui`
* [anp/moxie](https://github.com/anp/moxie) - lightweight platform-agnostic tools for declarative UI
* [sciter-sdk/rust-sciter](https://github.com/sciter-sdk/rust-sciter) - Rust bindings for Sciter
* [KDE/rust-qt-binding-generator](https://github.com/KDE/rust-qt-binding-generator) - Generate bindings to use Rust code in Qt and QML
* [ivanceras/sauron-native](https://github.com/ivanceras/sauron-native) - Truly cross platform, truly native. multiple backend GUI for rust
* [drager/wasm-pack](https://github.com/drager/wasm-pack) - 📦✨ your favorite rust -> wasm workflow tool!

### Terminal and Console UI

* [ratatui/ratatui](https://github.com/ratatui/ratatui) - A Rust crate for cooking up terminal user interfaces (TUIs) 👨‍🍳🐀 https://ratatui.rs
* [fdehau/tui-rs](https://github.com/fdehau/tui-rs) - Build terminal user interfaces and dashboards using Rust *(archived)*
* [console-rs/indicatif](https://github.com/console-rs/indicatif) - A command line progress reporting library for Rust
* [gyscos/cursive](https://github.com/gyscos/cursive) - A Text User Interface library for the Rust programming language
* [crossterm-rs/crossterm](https://github.com/crossterm-rs/crossterm) - Cross platform terminal library rust
* [afnanenayet/diffsitter](https://github.com/afnanenayet/diffsitter) - A tree-sitter based AST difftool to get meaningful semantic diffs
* [gorules/zen](https://github.com/gorules/zen) - Open-source Business Rules Engine for your Rust, NodeJS, Python, Go, Java, C#, Kotlin (JVM), Kotlin (Android) and Swift (iOS) applications.
* [stacks-archive/sbtc-developer-release](https://github.com/stacks-archive/sbtc-developer-release) - sBTC primitives, signer components, helper tools *(archived)*
* [zboxfs/zbox](https://github.com/zboxfs/zbox) - Zero-details, privacy-focused in-app file system. *(archived)*
* [3Hren/msgpack-rust](https://github.com/3Hren/msgpack-rust) - MessagePack implementation for Rust / msgpack.org[Rust]
* [oracle/railcar](https://github.com/oracle/railcar) - RailCar: Rust implementation of the Open Containers Initiative oci-runtime *(archived)*
* [phsym/prettytable-rs](https://github.com/phsym/prettytable-rs) - A rust library to print aligned and formatted tables
* [jeaye/ncurses-rs](https://github.com/jeaye/ncurses-rs) - A low-level ncurses wrapper for Rust *(archived)*

### Applications and End User Tools

* [farion1231/cc-switch](https://github.com/farion1231/cc-switch) - A cross-platform desktop All-in-One assistant for Claude Code, Codex, OpenCode, OpenClaw, Grok Build & Hermes Agent. Only official website: ccswitch.io
* [rustdesk/rustdesk](https://github.com/rustdesk/rustdesk) - An open-source remote desktop application designed for self-hosting, as an alternative to TeamViewer.
* [AppFlowy-IO/AppFlowy](https://github.com/AppFlowy-IO/AppFlowy) - Bring projects, wikis, and teams together with AI. AppFlowy is the AI collaborative workspace where you achieve more without losing control of your data. The leading open source Notion alternative.
* [dani-garcia/vaultwarden](https://github.com/dani-garcia/vaultwarden) - Unofficial Bitwarden compatible server written in Rust, formerly known as bitwarden_rs
* [alacritty/alacritty](https://github.com/alacritty/alacritty) - A cross-platform, OpenGL terminal emulator.
* [warpdotdev/warp](https://github.com/warpdotdev/warp) - Warp is an agentic development environment, born out of the terminal.
* [tw93/Pake](https://github.com/tw93/Pake) - 🤱🏻 Turn any webpage into a desktop app with one command.
* [lencx/ChatGPT](https://github.com/lencx/ChatGPT) - ❄️ ChatGPT Desktop Application (Mac, Windows and Linux)
* [helix-editor/helix](https://github.com/helix-editor/helix) - A post-modern modal text editor.
* [sxyazi/yazi](https://github.com/sxyazi/yazi) - 💥 Blazing fast terminal file manager written in Rust, based on async I/O.
* [spacedriveapp/spacedrive](https://github.com/spacedriveapp/spacedrive) - Spacedrive is an open source cross-platform file explorer, powered by a virtual distributed filesystem written in Rust.
* [lapce/lapce](https://github.com/lapce/lapce) - Lightning-fast and Powerful Code Editor written in Rust
* [lbjlaq/Antigravity-Manager](https://github.com/lbjlaq/Antigravity-Manager) - Professional Antigravity Account Manager & Switcher. One-click seamless account switching for Antigravity Tools. Built with Tauri v2 + React (Rust).专业的 Antigravity 账号管理与切换工具。为 Antigravity 提供一键无缝账号切换功能。
* [Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily) - Privacy first, AI meeting assistant with 4x faster Parakeet/Whisper live transcription, speaker diarization, and Ollama summarization built on Rust. 100% local processing. no cloud required. Meetily (Meetly Ai - https://meetily.ai) is the #1 Self-hosted, Open-source Ai meeting note taker for macOS & Windows. Understand How to write meeting minutes
* [wezterm/wezterm](https://github.com/wezterm/wezterm) - A GPU-accelerated cross-platform terminal emulator and multiplexer written by @wez and implemented in Rust
* [niri-wm/niri](https://github.com/niri-wm/niri) - A scrollable-tiling Wayland compositor.
* [gitui-org/gitui](https://github.com/gitui-org/gitui) - Blazing 💥 fast terminal-ui for git written in rust 🦀
* [gitbutlerapp/gitbutler](https://github.com/gitbutlerapp/gitbutler) - The GitButler version control client, backed by Git, powered by Tauri/Rust/Svelte
* [CapSoftware/Cap](https://github.com/CapSoftware/Cap) - Open source Loom alternative. Beautiful, shareable screen recordings.
* [0x192/universal-android-debloater](https://github.com/0x192/universal-android-debloater) - Cross-platform GUI written in Rust using ADB to debloat non-rooted android devices. Improve your privacy, the security and battery life of your device.
* [xi-editor/xi-editor](https://github.com/xi-editor/xi-editor) - A modern editor with a backend written in Rust.
* [Rigellute/spotify-tui](https://github.com/Rigellute/spotify-tui) - Spotify for the terminal written in Rust 🚀
* [AprilNEA/OpenLogi](https://github.com/AprilNEA/OpenLogi) - ⚡️A native, local-first alternative to Logitech Options+, written in Rust 🦀 — remap buttons, DPI, and SmartShift over HID++. No account, no telemetry.
* [t8y2/dbx](https://github.com/t8y2/dbx) - 20 MB lightweight cross-platform database client for 90+ databases, including MySQL, PostgreSQL, SQLite, Redis, MongoDB, DuckDB, SQL Server, and Dameng. Built-in AI, MCP Server, CLI, desktop and Docker. | 轻量级跨平台数据库管理工具，支持 MySQL、PostgreSQL、SQLite、Redis、MongoDB、达梦等 90+ 数据库，提供桌面端、Docker、CLI、内置 AI 助手和 MCP Server。
* [louis-e/arnis](https://github.com/louis-e/arnis) - Generate any location from the real world in Minecraft with a high level of detail.
* [neovide/neovide](https://github.com/neovide/neovide) - No Nonsense Neovim Client in Rust
* [LGUG2Z/komorebi](https://github.com/LGUG2Z/komorebi) - A tiling window manager for Windows 🍉
* [LemmyNet/lemmy](https://github.com/LemmyNet/lemmy) - 🐀 A decentralised discussion platform for communities.
* [microsoft/edit](https://github.com/microsoft/edit) - We all edit.
* [stalwartlabs/stalwart](https://github.com/stalwartlabs/stalwart) - All-in-one Mail & Collaboration server. Secure, scalable and fluent in every protocol (IMAP, JMAP, SMTP, CalDAV, CardDAV, WebDAV).
* [espanso/espanso](https://github.com/espanso/espanso) - A Privacy-first, Cross-platform Text Expander written in Rust
* [ClementTsang/bottom](https://github.com/ClementTsang/bottom) - Yet another cross-platform graphical process/system monitor.
* [libnyanpasu/clash-nyanpasu](https://github.com/libnyanpasu/clash-nyanpasu) - Clash Nyanpasu～(∠・ω< )⌒☆​
* [glzr-io/glazewm](https://github.com/glzr-io/glazewm) - GlazeWM is a tiling window manager for macOS and Windows inspired by i3wm.
* [elkowar/eww](https://github.com/elkowar/eww) - ElKowars wacky widgets
* [flxzt/rnote](https://github.com/flxzt/rnote) - Sketch and take handwritten notes.
* [Spotifyd/spotifyd](https://github.com/Spotifyd/spotifyd) - A spotify daemon
* [rustdesk/rustdesk-server](https://github.com/rustdesk/rustdesk-server) - RustDesk Server Program
* [H-M-H/Weylus](https://github.com/H-M-H/Weylus) - Use your tablet as graphic tablet/touch screen on your computer.
* [jely2002/youtube-dl-gui](https://github.com/jely2002/youtube-dl-gui) - Open Video Downloader - A cross-platform GUI for youtube-dl made in Rust with Tauri and Vue + Typescript.
* [Universal-Debloater-Alliance/universal-android-debloater-next-generation](https://github.com/Universal-Debloater-Alliance/universal-android-debloater-next-generation) - Cross-platform GUI written in Rust using ADB to debloat non-rooted Android devices. Improve your privacy, the security and battery life of your device.
* [mfontanini/presenterm](https://github.com/mfontanini/presenterm) - A markdown terminal slideshow tool
* [jtroo/kanata](https://github.com/jtroo/kanata) - Improve keyboard comfort and usability with advanced customization
* [ekzhang/sshx](https://github.com/ekzhang/sshx) - Fast, collaborative live terminal sharing over the web
* [mullvad/mullvadvpn-app](https://github.com/mullvad/mullvadvpn-app) - The Mullvad VPN client app for desktop and mobile
* [raphamorim/rio](https://github.com/raphamorim/rio) - A hardware-accelerated GPU terminal emulator focusing to run in desktops and browsers.
* [EcoPasteHub/EcoPaste](https://github.com/EcoPasteHub/EcoPaste) - 🎉跨平台的剪贴板管理工具 | Cross-platform clipboard management tool
* [pimalaya/himalaya](https://github.com/pimalaya/himalaya) - CLI to manage emails
* [aome510/spotify-player](https://github.com/aome510/spotify-player) - A Spotify player in the terminal with full feature parity
* [hrkfdn/ncspot](https://github.com/hrkfdn/ncspot) - Cross-platform ncurses Spotify client written in Rust, inspired by ncmpc and the likes.
* [tw93/Kaku](https://github.com/tw93/Kaku) - 🎃 A fast, out-of-the-box terminal built for AI coding.
* [ZSeven-W/openpencil](https://github.com/ZSeven-W/openpencil) - The world's first open-source AI-native vector design tool and the first to feature concurrent Agent Teams. Design-as-Code. Turn prompts into UI directly on the live canvas. A modern alternative to Pencil.
* [ilya-zlobintsev/LACT](https://github.com/ilya-zlobintsev/LACT) - Linux GPU Configuration And Monitoring Tool
* [Splode/pomotroid](https://github.com/Splode/pomotroid) - :tomato: Simple and visually-pleasing Pomodoro timer
* [koharu-rs/koharu](https://github.com/koharu-rs/koharu) - AI-powered manga translator, written in Rust.
* [versotile-org/verso](https://github.com/versotile-org/verso) - Mirror of https://gitlab.com/verso-browser/verso *(archived)*
* [achristmascarl/rainfrog](https://github.com/achristmascarl/rainfrog) - 🐸 a database tool for the terminal
* [spieglt/FlyingCarpet](https://github.com/spieglt/FlyingCarpet) - Cross-platform AirDrop. File transfer between Android, iOS, Linux, macOS, and Windows over ad hoc WiFi. No network infrastructure required, just two devices with WiFi chips (and optionally Bluetooth) in close range.
* [libreddit/libreddit](https://github.com/libreddit/libreddit) - Private front-end for Reddit
* [feschber/lan-mouse](https://github.com/feschber/lan-mouse) - mouse & keyboard sharing via LAN
* [Achilng/floral-notepaper](https://github.com/Achilng/floral-notepaper) - 花笺，轻量优雅的跨平台桌面便签工具，支持 Markdown 编辑与预览
* [sayanarijit/xplr](https://github.com/sayanarijit/xplr) - A hackable, minimal, fast TUI file explorer
* [szabodanika/microbin](https://github.com/szabodanika/microbin) - A secure, configurable file-sharing and URL shortening web app written in Rust.
* [timothymiller/cloudflare-ddns](https://github.com/timothymiller/cloudflare-ddns) - 🦀 Rust based dynamic DNS (DDNS) updater for Cloudflare
* [squidowl/halloy](https://github.com/squidowl/halloy) - IRC application written in Rust
* [macro-inc/macro](https://github.com/macro-inc/macro) - Macro is a unified workspace for teams: email, chat, docs, tasks, agents, calls, and CRM — @-linked together with shared AI memory.
* [ironcalc/IronCalc](https://github.com/ironcalc/IronCalc) - Main engine of the IronCalc ecosystem
* [jmacdonald/amp](https://github.com/jmacdonald/amp) - A complete text editor for your terminal.
* [Dusk-Labs/dim](https://github.com/Dusk-Labs/dim) - Dim, a media manager fueled by dark forces.
* [ekzhang/rustpad](https://github.com/ekzhang/rustpad) - Efficient and minimal collaborative code editor, self-hosted, no database required
* [edwardkim/rhwp](https://github.com/edwardkim/rhwp) - 아래한글 hwp viewer and editor by rust and wasm
* [curlpipe/ox](https://github.com/curlpipe/ox) - The simple but flexible text editor
* [kamiyaa/joshuto](https://github.com/kamiyaa/joshuto) - ranger-like terminal file manager written in Rust
* [Julien-cpsn/ATAC](https://github.com/Julien-cpsn/ATAC) - A simple API client (postman like) in your terminal
* [redlib-org/redlib](https://github.com/redlib-org/redlib) - Private front-end for Reddit
* [frectonz/sql-studio](https://github.com/frectonz/sql-studio) - SQL Database Explorer [SQLite, libSQL, PostgreSQL, MySQL/MariaDB, ClickHouse, DuckDB, Microsoft SQL Server]
* [owu/wsl-dashboard](https://github.com/owu/wsl-dashboard) - A GUI manager for WSL featuring a modern UI — a lightweight, low‑memory, high‑performance dashboard to manage WSL instances. Install, list, start, stop, unregister, and configure your WSL distros​ from one place.
* [Martichou/rquickshare](https://github.com/Martichou/rquickshare) - Rust implementation of NearbyShare/QuickShare from Android for Linux and macOS.
* [AtalayaLabs/OxiCloud](https://github.com/AtalayaLabs/OxiCloud) - ☁️ Ultra-fast, secure & lightweight self-hosted cloud storage — your files, photos, calendars & contacts, all in one place. Built in Rust.
* [SeaDve/Kooha](https://github.com/SeaDve/Kooha) - Elegantly record your screen
* [graykode/abtop](https://github.com/graykode/abtop) - Like htop, but for AI coding agents. Monitor Claude Code & Codex CLI sessions, tokens, context window, rate limits, and ports in real-time.
* [cloudhead/rx](https://github.com/cloudhead/rx) - 👾 Modern and minimalist pixel editor
* [Open-Less/openless](https://github.com/Open-Less/openless) - Hold a key, speak, release — AI-polished text appears at your cursor in any app. Open-source voice input for macOS & Windows. (按住快捷键说话，松开即得润色后的文字)
* [TaKO8Ki/gobang](https://github.com/TaKO8Ki/gobang) - A cross-platform TUI database management tool written in Rust
* [stoatchat/stoatchat](https://github.com/stoatchat/stoatchat) - The software powering Stoat
* [orhun/ratty](https://github.com/orhun/ratty) - A GPU-rendered terminal emulator with inline 3D graphics 🐀🧀
* [rustic-rs/rustic](https://github.com/rustic-rs/rustic) - rustic - fast, encrypted, and deduplicated backups powered by Rust
* [greshake/i3status-rust](https://github.com/greshake/i3status-rust) - Very resourcefriendly and feature-rich replacement for i3status, written in pure Rust
* [veeso/termscp](https://github.com/veeso/termscp) - 🖥 A feature rich terminal UI file transfer and explorer with support for SCP/SFTP/FTP/S3/SMB/WebDAV
* [abenz1267/walker](https://github.com/abenz1267/walker) - Multi-Purpose Launcher with a lot of features. Highly Customizable and fast.
* [agavra/tuicr](https://github.com/agavra/tuicr) - a code review TUI with vim keybindings
* [pythops/bluetui](https://github.com/pythops/bluetui) - 🛜 TUI for managing bluetooth on Linux
* [oppiliappan/dijo](https://github.com/oppiliappan/dijo) - scriptable, curses-based, digital habit tracker
* [Priler/jarvis](https://github.com/Priler/jarvis) - Offline voice assistant that respects your privacy. Forged in Rust. WIP.
* [GuillaumeGomez/sysinfo](https://github.com/GuillaumeGomez/sysinfo) - Cross-platform library to fetch system information
* [amethyst/specs](https://github.com/amethyst/specs) - Specs - Parallel ECS
* [ash-rs/ash](https://github.com/ash-rs/ash) - Vulkan bindings for Rust
* [Brooooooklyn/canvas](https://github.com/Brooooooklyn/canvas) - High performance Skia canvas implementation. Zero system dependencies.
* [boxlite-ai/boxlite](https://github.com/boxlite-ai/boxlite) - The micro-VM for AI agents — light enough to embed on your laptop, elastic enough to power an agentic cloud.
* [saschagrunert/webapp.rs](https://github.com/saschagrunert/webapp.rs) - A web application completely written in Rust. 🌍
* [Plume-org/Plume](https://github.com/Plume-org/Plume) - Federated blogging application, thanks to ActivityPub (now on https://git.joinplu.me/ — this is just a mirror)
* [uiua-lang/uiua](https://github.com/uiua-lang/uiua) - A tacit array programming language
* [linkerd/linkerd2-proxy](https://github.com/linkerd/linkerd2-proxy) - A purpose-built proxy for the Linkerd service mesh. Written in Rust.
* [pop-os/cosmic-text](https://github.com/pop-os/cosmic-text) - Pure Rust multi-line text handling
* [kdheepak/taskwarrior-tui](https://github.com/kdheepak/taskwarrior-tui) - `taskwarrior-tui`: A terminal user interface for taskwarrior
* [google/argh](https://github.com/google/argh) - Rust derive-based argument parsing optimized for code size
* [losfair/blueboat](https://github.com/losfair/blueboat) - All-in-one, multi-tenant serverless JavaScript runtime.
* [AntigmaLabs/ante](https://github.com/AntigmaLabs/ante) - Ghost in your shell. Ante is a self-contained agent harness with a highly optimized core. It works like Claude Code or Codex, with none of their dependencies or model constraints.
* [bodil/typed-html](https://github.com/bodil/typed-html) - Type checked JSX for Rust *(archived)*
* [avhz/RustQuant](https://github.com/avhz/RustQuant) - Rust library for quantitative finance.
* [EmbarkStudios/texture-synthesis](https://github.com/EmbarkStudios/texture-synthesis) - 🎨 Example-based texture synthesis written in Rust 🦀 *(archived)*
* [obi1kenobi/cargo-semver-checks](https://github.com/obi1kenobi/cargo-semver-checks) - Scan your Rust crate for semver violations.
* [hashintel/hash](https://github.com/hashintel/hash) - 🚀 The open-source, multi-tenant platform for self-building knowledge graphs and simulation
* [iceiix/stevenarella](https://github.com/iceiix/stevenarella) - Multi-protocol Minecraft-compatible client written in Rust
* [yingDev/Tickeys](https://github.com/yingDev/Tickeys) - Instant audio feedback for typing. macOS version. (Rust)
* [colin-kiegel/rust-derive-builder](https://github.com/colin-kiegel/rust-derive-builder) - derive builder implementation for rust structs
* [skerkour/bloom](https://github.com/skerkour/bloom) - The simplest way to de-Google your life and business: Inbox, Calendar, Files, Contacts & much more
* [gorilla-devs/ferium](https://github.com/gorilla-devs/ferium) - Fast and multi-source CLI program for managing Minecraft mods and modpacks from Modrinth, CurseForge, and GitHub Releases
* [tnballo/high-assurance-rust](https://github.com/tnballo/high-assurance-rust) - A free book about developing secure and robust systems software.
* [teodevgroup/teo](https://github.com/teodevgroup/teo) - High performance ergonomic ORM for Rust.
* [lightningdevkit/rust-lightning](https://github.com/lightningdevkit/rust-lightning) - Active development happens on git.rust-bitcoin.org, this repo is a mirror of https://git.rust-bitcoin.org/lightningdevkit/rust-lightning
* [stepancheg/grpc-rust](https://github.com/stepancheg/grpc-rust) - Rust implementation of gRPC *(archived)*
* [orlp/slotmap](https://github.com/orlp/slotmap) - Slotmap data structure for Rust
* [sminez/penrose](https://github.com/sminez/penrose) - A library for writing an X11 tiling window manager
* [fishinabarrel/linux-kernel-module-rust](https://github.com/fishinabarrel/linux-kernel-module-rust) - Framework for writing Linux kernel modules in safe Rust *(archived)*
* [sassman/t-rec-rs](https://github.com/sassman/t-rec-rs) - Blazingly fast terminal recorder that generates animated gif images for the web written in rust
* [Graviton-Code-Editor/Graviton-App](https://github.com/Graviton-Code-Editor/Graviton-App) - 🚀 A modern-looking Code Editor *(archived)*
* [osa1/tiny](https://github.com/osa1/tiny) - A terminal IRC client
* [neuronika/neuronika](https://github.com/neuronika/neuronika) - Tensors and dynamic neural networks in pure Rust.
* [jorgecarleitao/arrow2](https://github.com/jorgecarleitao/arrow2) - Transmute-free Rust library to work with the Arrow format *(archived)*
* [qarmin/szyszka](https://github.com/qarmin/szyszka) - Szyszka is fast and powerful file renamer
* [zineland/zine](https://github.com/zineland/zine) - Zine - a simple and opinionated tool to build your own magazine.
* [rustodon/rustodon](https://github.com/rustodon/rustodon) - A Mastodon-compatible, ActivityPub-speaking server in Rust
* [mbround18/valheim-docker](https://github.com/mbround18/valheim-docker) - Valheim Docker powered by Odin. The Valheim dedicated gameserver manager which is designed with resiliency in mind by providing automatic updates, world backup support, and a user friendly cli interface.
* [TimeToogo/tunshell](https://github.com/TimeToogo/tunshell) - Remote shell into ephemeral environments 🐚 🦀
* [linebender/runebender](https://github.com/linebender/runebender) - A font editor written in Rust.
* [rhysd/kiro-editor](https://github.com/rhysd/kiro-editor) - A small terminal UTF-8 text editor written in Rust 📝🦀
* [TimUntersberger/nog](https://github.com/TimUntersberger/nog) - A tiling window manager for Windows
* [sayanarijit/qrcode.show](https://github.com/sayanarijit/qrcode.show) - Generate QR code easily for free - QR Code Generation as a Service
* [Drakulix/fireplace](https://github.com/Drakulix/fireplace) - Modular wayland window manager written in rust *(archived)*
* [ellie/atuin](https://github.com/ellie/atuin) - ✨ Magical shell history

## Graphics and Media

### Graphics and Rendering

* [gfx-rs/wgpu](https://github.com/gfx-rs/wgpu) - A cross-platform, safe, pure-Rust graphics API.
* [BoundaryML/baml](https://github.com/BoundaryML/baml) - The programming language for agents
* [EmbarkStudios/rust-gpu](https://github.com/EmbarkStudios/rust-gpu) - 🐉 Making Rust a first-class language and ecosystem for GPU shaders 🚧 *(archived)*
* [nannou-org/nannou](https://github.com/nannou-org/nannou) - A Creative Coding Framework for Rust.
* [gfx-rs/gfx](https://github.com/gfx-rs/gfx) - [maintenance mode] A low-overhead Vulkan-like GPU API for Rust.
* [vulkano-rs/vulkano](https://github.com/vulkano-rs/vulkano) - Safe and rich Rust wrapper around the Vulkan API
* [glium/glium](https://github.com/glium/glium) - Safe OpenGL wrapper for the Rust language.
* [Rust-GPU/rust-gpu](https://github.com/Rust-GPU/rust-gpu) - 🐉 Making Rust a first-class language and ecosystem for GPU shaders 🚧
* [cunarist/rinf](https://github.com/cunarist/rinf) - Rust for native business logic, Flutter for flexible and beautiful GUI
* [mitsuhiko/minijinja](https://github.com/mitsuhiko/minijinja) - MiniJinja is a powerful but minimal dependency template engine for Rust compatible with Jinja/Jinja2
* [mofeng-git/One-KVM](https://github.com/mofeng-git/One-KVM) - One-KVM Rust 是一个用 Rust 编写的轻量级 IP-KVM 解决方案，可通过网络远程管理服务器和工作站，实现 BIOS 级远程控制。One-KVM Rust is a lightweight IP-KVM solution written in Rust. It lets you manage servers and workstations over the network, including at BIOS level.
* [EmbarkStudios/cargo-deny](https://github.com/EmbarkStudios/cargo-deny) - ❌ Cargo plugin for linting your dependencies 🦀
* [fjall-rs/fjall](https://github.com/fjall-rs/fjall) - 🗻 Log-structured, embeddable key-value storage engine written in Rust
* [vizia/vizia](https://github.com/vizia/vizia) - A declarative GUI library written in Rust
* [reubeno/brush](https://github.com/reubeno/brush) - 🐚bash/POSIX-compatible shell implemented in Rust 🦀
* [seppo0010/rsedis](https://github.com/seppo0010/rsedis) - Redis re-implemented in Rust.
* [dimforge/kiss3d](https://github.com/dimforge/kiss3d) - Keep it simple, stupid 3d graphics engine for Rust.
* [SeaQL/FireDBG.for.Rust](https://github.com/SeaQL/FireDBG.for.Rust) - 🔥 Time Travel Visual Debugger for Rust
* [nicoburns/blessed-rs](https://github.com/nicoburns/blessed-rs) - A community guide to the Rust ecosystem
* [modelfoxdotdev/modelfox](https://github.com/modelfoxdotdev/modelfox) - ModelFox makes it easy to train, deploy, and monitor machine learning models.
* [libraries/gameboy](https://github.com/libraries/gameboy) - Full featured Cross-platform GameBoy emulator by Rust. Forever boys!.
* [jrmuizel/raqote](https://github.com/jrmuizel/raqote) - Rust 2D graphics library
* [BVE-Reborn/rend3](https://github.com/BVE-Reborn/rend3) - MAINTENCE MODE ---- Easy to use, customizable, efficient 3D renderer library built on wgpu. *(archived)*
* [wahn/rs_pbrt](https://github.com/wahn/rs_pbrt) - Rust crate to implement a counterpart to the PBRT book's (3rd edition) C++ code. See also https://www.rs-pbrt.org/about ...
* [ecumene/rust-sloth](https://github.com/ecumene/rust-sloth) - A 3D software rasterizer... for the terminal!
* [amethyst/rendy](https://github.com/amethyst/rendy) - State of the art "build your own engine" kit powered by gfx-hal
* [rust-windowing/gl-rs](https://github.com/rust-windowing/gl-rs) - An OpenGL function pointer loader for Rust

### Game Development

* [bevyengine/bevy](https://github.com/bevyengine/bevy) - A refreshingly simple data-driven game engine built in Rust
* [oxc-project/oxc](https://github.com/oxc-project/oxc) - ⚓ A collection of high-performance JavaScript tools.
* [ruffle-rs/ruffle](https://github.com/ruffle-rs/ruffle) - A Flash Player emulator written in Rust
* [kitao/pyxel](https://github.com/kitao/pyxel) - A retro game engine for Python
* [Pumpkin-MC/Pumpkin](https://github.com/Pumpkin-MC/Pumpkin) - Empowering everyone to host fast and efficient Minecraft servers.
* [FyroxEngine/Fyrox](https://github.com/FyroxEngine/Fyrox) - 3D and 2D game engine written in Rust
* [citybound/citybound](https://github.com/citybound/citybound) - A work-in-progress, open-source, multi-player city simulation game.
* [amethyst/amethyst](https://github.com/amethyst/amethyst) - Data-oriented and data-driven game engine written in Rust *(archived)*
* [veloren/veloren](https://github.com/veloren/veloren) - [mirror of https://gitlab.com/veloren/veloren] An open world, open source voxel RPG inspired by Dwarf Fortress and Cube World. This repository is a mirror. Please submit all PRs and issues on our GitLab page.
* [flybywiresim/aircraft](https://github.com/flybywiresim/aircraft) - The A32NX & A380X Project are community driven open source projects to create free Airbus aircraft in Microsoft Flight Simulator that are as close to reality as possible.
* [godot-rust/gdext](https://github.com/godot-rust/gdext) - Rust bindings for Godot 4
* [PistonDevelopers/piston](https://github.com/PistonDevelopers/piston) - A modular game engine written in Rust
* [ggez/ggez](https://github.com/ggez/ggez) - Rust library to create a Good Game Easily
* [not-fl3/macroquad](https://github.com/not-fl3/macroquad) - Cross-platform game engine in Rust.
* [AmbientRun/Ambient](https://github.com/AmbientRun/Ambient) - The multiplayer game engine
* [godot-rust/gdnative](https://github.com/godot-rust/gdnative) - Rust bindings for Godot 3 *(archived)*
* [Auburn/FastNoiseLite](https://github.com/Auburn/FastNoiseLite) - Fast Portable Noise Library - C# C++ C Java HLSL GLSL JavaScript Rust Go
* [valence-rs/valence](https://github.com/valence-rs/valence) - A Rust framework for building Minecraft servers.
* [avianphysics/avian](https://github.com/avianphysics/avian) - ECS-driven 2D and 3D physics engine for the Bevy game engine.
* [MaxBittker/sandspiel](https://github.com/MaxBittker/sandspiel) - Creative cellular automata browser game
* [Rust-SDL2/rust-sdl2](https://github.com/Rust-SDL2/rust-sdl2) - SDL2 bindings for Rust
* [zerx-lab/FluxDown](https://github.com/zerx-lab/FluxDown) - Rust 驱动的多协议下载管理器，支持 HTTP/FTP/BitTorrent 磁力链接及 HLS/DASH 流媒体，智能多线程加速与浏览器无缝集成。精美界面，极致性能，永久免费，零广告。
* [spider-rs/spider](https://github.com/spider-rs/spider) - Get web data for AI agents and LLMs - fast, efficient, and reliable with Rust
* [sarah-quinones/faer-rs](https://github.com/sarah-quinones/faer-rs) - Linear algebra foundation for the Rust programming language
* [eclipse-iceoryx/iceoryx2](https://github.com/eclipse-iceoryx/iceoryx2) - Eclipse iceoryx2™ - true zero-copy inter-process-communication with a Rust core
* [twistedfall/opencv-rust](https://github.com/twistedfall/opencv-rust) - Rust bindings for OpenCV
* [tafia/calamine](https://github.com/tafia/calamine) - A pure Rust Excel/OpenDocument SpreadSheets file reader: rust on metal sheets
* [gotham-rs/gotham](https://github.com/gotham-rs/gotham) - A flexible web framework that promotes stability, safety, security and speed.
* [mozilla/neqo](https://github.com/mozilla/neqo) - Neqo, the Mozilla Firefox implementation of QUIC in Rust
* [rajasekarv/vega](https://github.com/rajasekarv/vega) - A new arguably faster implementation of Apache Spark from scratch in Rust
* [proptest-rs/proptest](https://github.com/proptest-rs/proptest) - Hypothesis-like property testing for Rust
* [rust-windowing/glutin](https://github.com/rust-windowing/glutin) - A low-level library for OpenGL context creation
* [lanyeeee/bilibili-video-downloader](https://github.com/lanyeeee/bilibili-video-downloader) - 哔哩哔哩 bilibili B站 视频 下载器，图形界面 + nfo刮削 + 广告标记 + 字幕下载 + 弹幕下载，轻松将视频加入emby等媒体库
* [tailhook/vagga](https://github.com/tailhook/vagga) - Vagga is a containerization tool without daemons
* [MitMaro/git-interactive-rebase-tool](https://github.com/MitMaro/git-interactive-rebase-tool) - Native cross-platform full feature terminal-based sequence editor for git interactive rebase.
* [Dominux/Pentaract](https://github.com/Dominux/Pentaract) - Unlimited file cloud storage based on using Telegram API
* [yobix-ai/extractous](https://github.com/yobix-ai/extractous) - Fast and efficient unstructured data extraction. Written in Rust with bindings for many languages.
* [mlua-rs/rlua](https://github.com/mlua-rs/rlua) - High level Lua bindings to Rust *(archived)*
* [yamafaktory/jql](https://github.com/yamafaktory/jql) - A JSON Query Language CLI tool
* [sfackler/r2d2](https://github.com/sfackler/r2d2) - A generic connection pool for Rust
* [kevinmehall/rust-peg](https://github.com/kevinmehall/rust-peg) - Parsing Expression Grammar (PEG) parser generator for Rust
* [cobalt-org/cobalt.rs](https://github.com/cobalt-org/cobalt.rs) - Static site generator written in Rust
* [shuttle-hq/synth](https://github.com/shuttle-hq/synth) - The Declarative Data Generator
* [nagisa/rust_libloading](https://github.com/nagisa/rust_libloading) - Bindings around the platform's dynamic library loading primitives with greatly improved memory safety.
* [ozkriff/zemeroth](https://github.com/ozkriff/zemeroth) - 😠⚔️😈 A minimalistic 2D turn-based tactical game in Rust
* [das-labor/panopticon](https://github.com/das-labor/panopticon) - A libre cross-platform disassembler. *(archived)*
* [hoodie/notify-rust](https://github.com/hoodie/notify-rust) - ☝️send desktop notifications from your Rust app.
* [kornelski/dssim](https://github.com/kornelski/dssim) - Image similarity comparison simulating human perception (multiscale SSIM in Rust)
* [async-raft/async-raft](https://github.com/async-raft/async-raft) - An implementation of the Raft distributed consensus protocol using the Tokio framework.
* [archseer/enigma](https://github.com/archseer/enigma) - An Erlang VM implementation in Rust
* [17cupsofcoffee/tetra](https://github.com/17cupsofcoffee/tetra) - 🎮 A simple 2D game framework written in Rust
* [Gekkio/mooneye-gb](https://github.com/Gekkio/mooneye-gb) - A Game Boy research project and emulator written in Rust
* [dimforge/ncollide](https://github.com/dimforge/ncollide) - 2 and 3-dimensional collision detection library in Rust.
* [Gigoteur/UnicornConsole](https://github.com/Gigoteur/UnicornConsole) - Unicorn Console: create quick fantasy game in Rust/Python/Lua/Rhai/Wasm !
* [koute/pinky](https://github.com/koute/pinky) - An NES emulator written in Rust
* [elliegoldstein/quicksilver](https://github.com/elliegoldstein/quicksilver) - A simple framework for 2D games on desktop and web
* [pcwalton/sprocketnes](https://github.com/pcwalton/sprocketnes) - NES emulator written in Rust
* [yupferris/rustendo64](https://github.com/yupferris/rustendo64) - Livecoding a Nintendo 64 emulator in Rust :D *(archived)*

### Audio

* [librespot-org/librespot](https://github.com/librespot-org/librespot) - Open Source Spotify client library
* [RustAudio/cpal](https://github.com/RustAudio/cpal) - Low-level cross-platform audio I/O library in Rust
* [pdeljanov/Symphonia](https://github.com/pdeljanov/Symphonia) - Pure Rust multimedia format demuxing, tag reading, and audio decoding library
* [chaosprint/glicol](https://github.com/chaosprint/glicol) - Graph-oriented live coding language and music/audio DSP library written in Rust
* [robbert-vdh/nih-plug](https://github.com/robbert-vdh/nih-plug) - Rust VST3 and CLAP plugin framework and plugins - because everything is better when you do it yourself
* [alexpusch/rust-magic-patterns](https://github.com/alexpusch/rust-magic-patterns) - Magical Rust patterns laid out and simplified
* [MeadowlarkDAW/Meadowlark](https://github.com/MeadowlarkDAW/Meadowlark) - A (currently incomplete) open-source Digital Audio Workstation
* [toml-rs/toml-rs](https://github.com/toml-rs/toml-rs) - A TOML encoding/decoding library for Rust *(archived)*

### Image and Video

* [gyroflow/gyroflow](https://github.com/gyroflow/gyroflow) - Video stabilization using gyroscope data
* [visioncortex/vtracer](https://github.com/visioncortex/vtracer) - Raster to Vector Graphics Converter
* [image-rs/image](https://github.com/image-rs/image) - Encoding and decoding images in Rust
* [oxipng/oxipng](https://github.com/oxipng/oxipng) - Multithreaded PNG optimizer written in Rust
* [silvia-odwyer/photon](https://github.com/silvia-odwyer/photon) - ⚡ Rust/WebAssembly image processing library
* [kane50613/takumi](https://github.com/kane50613/takumi) - Render OG images and paged PDFs from JSX, HTML, and CSS. No headless browser. Runs on Node.js, Cloudflare Workers, browsers, and Rust.
* [BurntSushi/rust-csv](https://github.com/BurntSushi/rust-csv) - A CSV parser for Rust, with Serde support.
* [Andy-Python-Programmer/aero](https://github.com/Andy-Python-Programmer/aero) - Aero is a new modern, experimental, UNIX-like operating system following the monolithic kernel design. Supporting modern PC features such as long mode, 5-level paging, and SMP (multicore), to name a few.
* [pcwalton/rust-media](https://github.com/pcwalton/rust-media) - A free, comprehensive, and portable video/audio streaming library for Rust

## Security

### Cryptography

* [QuipNetwork/hashsigs-rs](https://github.com/QuipNetwork/hashsigs-rs) - Hash-based post quantum signatures in Rust
* [rustls/rustls](https://github.com/rustls/rustls) - A modern TLS library in Rust
* [build-trust/ockam](https://github.com/build-trust/ockam) - Orchestrate end-to-end encryption, cryptographic identities, mutual authentication, and authorization policies between distributed applications – at massive scale.
* [str4d/rage](https://github.com/str4d/rage) - A simple, secure and modern file encryption tool (and Rust library) with small explicit keys, no config options, and UNIX-style composability.
* [tellerops/teller](https://github.com/tellerops/teller) - Cloud native secrets management for developers - never leave your command line for secrets.
* [dalek-cryptography/curve25519-dalek](https://github.com/dalek-cryptography/curve25519-dalek) - A pure-Rust implementation of group operations on Ristretto and Curve25519
* [mcginty/snow](https://github.com/mcginty/snow) - A Rust implementation of the Noise Protocol Framework
* [ZenGo-X/multi-party-ecdsa](https://github.com/ZenGo-X/multi-party-ecdsa) - Rust implementation of {t,n}-threshold ECDSA (elliptic curve digital signature algorithm).
* [sodiumoxide/sodiumoxide](https://github.com/sodiumoxide/sodiumoxide) - [DEPRECATED] Sodium Oxide: Fast cryptographic library for Rust (bindings to libsodium) *(archived)*

### Security Tools

* [bee-san/RustScan](https://github.com/bee-san/RustScan) - 🤖 The Modern Port Scanner 🤖
* [epi052/feroxbuster](https://github.com/epi052/feroxbuster) - A fast, simple, recursive content discovery tool written in Rust.
* [Dicklesworthstone/destructive_command_guard](https://github.com/Dicklesworthstone/destructive_command_guard) - The Destructive Command Guard (dcg) is for blocking dangerous git and shell commands from being executed by agents.
* [EFForg/rayhunter](https://github.com/EFForg/rayhunter) - Rust tool to detect cell site simulators on an orbic mobile hotspot
* [Speykious/cve-rs](https://github.com/Speykious/cve-rs) - Blazingly 🔥 fast 🚀 memory vulnerabilities, written in 100% safe Rust. 🦀
* [hahwul/dalfox](https://github.com/hahwul/dalfox) - 🌙🦊 Dalfox is a powerful open-source XSS scanner and utility focused on automation.
* [WithSecureLabs/chainsaw](https://github.com/WithSecureLabs/chainsaw) - Rapidly Search and Hunt through Windows Forensic Artefacts
* [Yamato-Security/hayabusa](https://github.com/Yamato-Security/hayabusa) - Hayabusa (隼) is a sigma-based threat hunting and fast forensics timeline generator for Windows event logs.
* [trickster0/OffensiveRust](https://github.com/trickster0/OffensiveRust) - Rust Weaponization for Red Team Engagements.
* [lambda-fairy/maud](https://github.com/lambda-fairy/maud) - :pencil: Compile-time HTML templates for Rust
* [cnosdb/cnosdb](https://github.com/cnosdb/cnosdb) - A cloud-native open source distributed time series database with high performance, high compression ratio and high availability.
* [Esc4iCEscEsc/skanuvaty](https://github.com/Esc4iCEscEsc/skanuvaty) - Dangerously fast DNS/network/port scanner
* [apache/teaclave](https://github.com/apache/teaclave) - Apache Teaclave™ is an open source universal secure computing platform, making computation on privacy-sensitive data safe and simple.

### Authentication and Authorization

* [warp-tech/warpgate](https://github.com/warp-tech/warpgate) - Fully transparent SSH, HTTPS, Kubernetes, database and RDP/VNC bastion/PAM that doesn't need additional client-side software
* [lldap/lldap](https://github.com/lldap/lldap) - Light LDAP implementation
* [kanidm/kanidm](https://github.com/kanidm/kanidm) - Kanidm: A simple, secure, and fast identity management platform
* [google/OpenSK](https://github.com/google/OpenSK) - OpenSK is an open-source implementation for security keys written in Rust that supports both FIDO U2F and FIDO2 standards.
* [ferronweb/ferron](https://github.com/ferronweb/ferron) - A fast, modern, and easily configurable web server with automatic TLS.
* [rust-in-action/code](https://github.com/rust-in-action/code) - Source code for the book Rust in Action
* [jni-rs/jni-rs](https://github.com/jni-rs/jni-rs) - Rust bindings to the Java Native Interface — JNI
* [mike-engel/jwt-cli](https://github.com/mike-engel/jwt-cli) - A super fast CLI tool to decode and encode JWTs built in Rust
* [Marwes/combine](https://github.com/Marwes/combine) - A parser combinator library for Rust

## Concurrency and Performance

### Concurrency and Parallelism

* [tokio-rs/tokio](https://github.com/tokio-rs/tokio) - A runtime for writing reliable asynchronous applications with Rust. Provides I/O, networking, scheduling, timers, ...
* [rayon-rs/rayon](https://github.com/rayon-rs/rayon) - Rayon: A data parallelism library for Rust
* [actix/actix](https://github.com/actix/actix) - Actor framework for Rust.
* [crossbeam-rs/crossbeam](https://github.com/crossbeam-rs/crossbeam) - Tools for concurrent programming in Rust
* [rust-lang/futures-rs](https://github.com/rust-lang/futures-rs) - Zero-cost asynchronous programming in Rust
* [monoio-rs/monoio](https://github.com/monoio-rs/monoio) - Rust async runtime based on io-uring.
* [smol-rs/smol](https://github.com/smol-rs/smol) - A small and fast async runtime for Rust
* [xacrimon/dashmap](https://github.com/xacrimon/dashmap) - Blazing fast concurrent HashMap for Rust.
* [async-rs/async-std](https://github.com/async-rs/async-std) - Async version of the Rust standard library
* [DataDog/glommio](https://github.com/DataDog/glommio) - Glommio is a thread-per-core crate that makes writing highly parallel asynchronous applications in a thread-per-core architecture easier for rustaceans.
* [Amanieu/parking_lot](https://github.com/Amanieu/parking_lot) - Compact and efficient synchronization primitives for Rust. Also provides an API for creating custom synchronization primitives.
* [zesterer/flume](https://github.com/zesterer/flume) - A safe and fast multi-producer, multi-consumer channel.
* [bastion-rs/bastion](https://github.com/bastion-rs/bastion) - Highly-available Distributed Fault-tolerant Runtime
* [mun-lang/mun](https://github.com/mun-lang/mun) - Source code for the Mun language and runtime.
* [PistonDevelopers/hematite](https://github.com/PistonDevelopers/hematite) - A simple Minecraft written in Rust with the Piston game engine
* [hank9999/kiro.rs](https://github.com/hank9999/kiro.rs) - A Kiro Client in Rust
* [tokio-rs/tokio-uring](https://github.com/tokio-rs/tokio-uring) - An io_uring backed runtime for Rust
* [darkrenaissance/darkfi](https://github.com/darkrenaissance/darkfi) - Anonymous. Uncensored. Sovereign.
* [wormtql/yas](https://github.com/wormtql/yas) - Blazingly fast Genshin Impact/Honkai: Starrail artifacts scanner
* [hecrj/coffee](https://github.com/hecrj/coffee) - An opinionated 2D game engine for Rust
* [servo/ipc-channel](https://github.com/servo/ipc-channel) - A multiprocess drop-in replacement for Rust channels
* [rxRust/rxRust](https://github.com/rxRust/rxRust) - Zero-cost & Type-safe Reactive Extensions for Rust. Supports both high-performance single-threaded (Local) and thread-safe (Shared) contexts. WASM & Tokio ready.
* [tokio-rs/tokio-core](https://github.com/tokio-rs/tokio-core) - I/O primitives and event loop for async I/O in Rust

### Performance and Optimization

* [sharkdp/hyperfine](https://github.com/sharkdp/hyperfine) - A command-line benchmarking tool
* [vosen/ZLUDA](https://github.com/vosen/ZLUDA) - CUDA on non-NVIDIA GPUs
* [hatoo/oha](https://github.com/hatoo/oha) - Ohayou(おはよう), HTTP load generator, inspired by rakyll/hey with tui animation.
* [bheisler/criterion.rs](https://github.com/bheisler/criterion.rs) - Statistics-driven benchmarking library for Rust
* [Rust-GPU/rust-cuda](https://github.com/Rust-GPU/rust-cuda) - Ecosystem of libraries and tools for writing and executing fast GPU code fully in Rust.
* [NVlabs/cuda-oxide](https://github.com/NVlabs/cuda-oxide) - cuda-oxide is an experimental Rust-to-CUDA compiler that lets you write (SIMT) GPU kernels in safe(ish), idiomatic Rust. It compiles standard Rust code directly to PTX — no DSLs, no foreign language bindings, just Rust.
* [matrix-construct/tuwunel](https://github.com/matrix-construct/tuwunel) - Official successor to conduwuit
* [calebwin/emu](https://github.com/calebwin/emu) - The write-once-run-anywhere GPGPU library for Rust
* [Manishearth/rust-gc](https://github.com/Manishearth/rust-gc) - Simple tracing (mark and sweep) garbage collector for Rust
* [dropbox/rust-brotli](https://github.com/dropbox/rust-brotli) - Brotli compressor and decompressor written in rust that optionally avoids the stdlib
* [arrayfire/arrayfire-rust](https://github.com/arrayfire/arrayfire-rust) - Rust wrapper for ArrayFire
* [richox/orz](https://github.com/richox/orz) - a high performance, general purpose data compressor written in the crab-lang
* [bheisler/RustaCUDA](https://github.com/bheisler/RustaCUDA) - Rusty wrapper for the CUDA Driver API
* [jimblandy/context-switch](https://github.com/jimblandy/context-switch) - Comparison of Rust async and Linux thread context switch time.

## Testing and Quality

### Testing

* [nextest-rs/nextest](https://github.com/nextest-rs/nextest) - A next-generation test runner for Rust.
* [xd009642/tarpaulin](https://github.com/xd009642/tarpaulin) - A code coverage tool for Rust projects
* [mitsuhiko/insta](https://github.com/mitsuhiko/insta) - A snapshot testing library for rust
* [rusoto/rusoto](https://github.com/rusoto/rusoto) - AWS SDK for Rust
* [open-telemetry/opentelemetry-rust](https://github.com/open-telemetry/opentelemetry-rust) - The Rust OpenTelemetry implementation
* [zkat/miette](https://github.com/zkat/miette) - Fancy extension for std::error::Error with pretty, detailed diagnostic printing.
* [fitzgen/bumpalo](https://github.com/fitzgen/bumpalo) - A fast bump allocation arena for Rust
* [lettre/lettre](https://github.com/lettre/lettre) - a mailer library for Rust
* [apache/datafusion-ballista](https://github.com/apache/datafusion-ballista) - Apache DataFusion Ballista Distributed Query Engine
* [elastio/bon](https://github.com/elastio/bon) - Next-gen compile-time-checked builder generator, named function's arguments, and more!
* [LukeMathWalker/pavex](https://github.com/LukeMathWalker/pavex) - A backend framework for Rust professionals
* [mgunyho/tere](https://github.com/mgunyho/tere) - Terminal file explorer
* [rcore-os/zCore](https://github.com/rcore-os/zCore) - Zircon microkernel reimplemented in Rust.
* [cs01/termpair](https://github.com/cs01/termpair) - View and control terminals from your browser with end-to-end encryption 🔒
* [ferrocene/ferrocene](https://github.com/ferrocene/ferrocene) - Source code of Ferrocene, safety-critical Rust toolchain
* [mesalock-linux/mesalink](https://github.com/mesalock-linux/mesalink) - OpenSSL compatibility layer for the Rust SSL/TLS stack
* [lloydmeta/frunk](https://github.com/lloydmeta/frunk) - Funktional generic type-level programming in Rust: HList, Coproduct, Generic, LabelledGeneric, Validated, Monoid and friends.
* [citahub/cita](https://github.com/citahub/cita) - A high performance blockchain kernel for enterprise users.
* [rust-qt/ritual](https://github.com/rust-qt/ritual) - Use C++ libraries from Rust

## Utilities

### Command Line Tools

* [BurntSushi/ripgrep](https://github.com/BurntSushi/ripgrep) - ripgrep recursively searches directories for a regex pattern while respecting your gitignore
* [sharkdp/bat](https://github.com/sharkdp/bat) - A cat(1) clone with wings.
* [starship/starship](https://github.com/starship/starship) - ☄🌌️ The minimal, blazing-fast, and infinitely customizable prompt for any shell!
* [sharkdp/fd](https://github.com/sharkdp/fd) - A simple, fast and user-friendly alternative to 'find'
* [nushell/nushell](https://github.com/nushell/nushell) - A new type of shell
* [ajeetdsouza/zoxide](https://github.com/ajeetdsouza/zoxide) - A smarter cd command. Supports all major shells.
* [fish-shell/fish-shell](https://github.com/fish-shell/fish-shell) - The user-friendly command line shell.
* [dandavison/delta](https://github.com/dandavison/delta) - A syntax-highlighting pager for git, diff, grep, rg --json, and blame output
* [atuinsh/atuin](https://github.com/atuinsh/atuin) - ✨ Making your shell magical
* [googleworkspace/cli](https://github.com/googleworkspace/cli) - Google Workspace CLI — one command-line tool for Drive, Gmail, Calendar, Sheets, Docs, Chat, Admin, and more. Dynamically built from Google Discovery Service. Includes AI agent skills.
* [ogham/exa](https://github.com/ogham/exa) - A modern replacement for ‘ls’.
* [uutils/coreutils](https://github.com/uutils/coreutils) - Cross-platform Rust rewrite of the GNU coreutils
* [eza-community/eza](https://github.com/eza-community/eza) - A modern alternative to ls
* [denisidoro/navi](https://github.com/denisidoro/navi) - An interactive cheatsheet tool for the command-line
* [clap-rs/clap](https://github.com/clap-rs/clap) - A full featured, fast Command Line Argument Parser for Rust
* [lsd-rs/lsd](https://github.com/lsd-rs/lsd) - The next gen ls command
* [XAMPPRocky/tokei](https://github.com/XAMPPRocky/tokei) - Count your code, quickly.
* [Canop/broot](https://github.com/Canop/broot) - A new way to see and navigate directory trees
* [orf/gping](https://github.com/orf/gping) - Ping, but with a graph
* [bootandy/dust](https://github.com/bootandy/dust) - A more intuitive version of du in rust
* [orhun/git-cliff](https://github.com/orhun/git-cliff) - A highly customizable Changelog Generator that follows Conventional Commit specifications ⛰️
* [o2sh/onefetch](https://github.com/o2sh/onefetch) - Command-line Git information tool
* [GitoxideLabs/gitoxide](https://github.com/GitoxideLabs/gitoxide) - An idiomatic, lean, fast & safe pure Rust implementation of Git
* [BurntSushi/xsv](https://github.com/BurntSushi/xsv) - A fast CSV command line toolkit written in Rust. *(archived)*
* [sharkdp/hexyl](https://github.com/sharkdp/hexyl) - A command-line hex viewer
* [cantino/mcfly](https://github.com/cantino/mcfly) - Fly through your shell history. Great Scott!
* [timvisee/ffsend](https://github.com/timvisee/ffsend) - :mailbox_with_mail: Easily and securely share files from the command line. A fully featured Firefox Send client.
* [skim-rs/skim](https://github.com/skim-rs/skim) - Fuzzy Finder in rust!
* [tealdeer-rs/tealdeer](https://github.com/tealdeer-rs/tealdeer) - A very fast implementation of tldr in Rust.
* [sharkdp/pastel](https://github.com/sharkdp/pastel) - A command-line tool to generate, analyze, convert and manipulate colors
* [Nukesor/pueue](https://github.com/Nukesor/pueue) - :stars: Manage your shell commands.
* [alexpasmantier/television](https://github.com/alexpasmantier/television) - A very fast, portable and hackable fuzzy finder.
* [dalance/procs](https://github.com/dalance/procs) - A modern replacement for ps written in Rust
* [ynqa/jnv](https://github.com/ynqa/jnv) - Interactive JSON filter using jq
* [PaulJuliusMartinez/jless](https://github.com/PaulJuliusMartinez/jless) - jless is a command-line JSON viewer designed for reading, exploring, and searching through JSON data.
* [unhappychoice/gitlogue](https://github.com/unhappychoice/gitlogue) - A cinematic Git commit replay tool for the terminal, turning your Git history into a living, animated story.
* [medialab/xan](https://github.com/medialab/xan) - The CSV magician
* [topgrade-rs/topgrade](https://github.com/topgrade-rs/topgrade) - Upgrade all the things
* [jhspetersson/fselect](https://github.com/jhspetersson/fselect) - Find files with SQL-like queries
* [lycheeverse/lychee](https://github.com/lycheeverse/lychee) - ⚡ Fast, async, stream-based link checker written in Rust. Finds broken URLs and mail addresses inside Markdown, HTML, reStructuredText, websites and more!
* [bgreenwell/doxx](https://github.com/bgreenwell/doxx) - Expose the contents of .docx files without leaving your terminal. Fast, safe, and smart — no Office required!
* [01mf02/jaq](https://github.com/01mf02/jaq) - A jq clone focussed on correctness, speed, and simplicity
* [ouch-org/ouch](https://github.com/ouch-org/ouch) - Painless compression and decompression in the terminal
* [Aloxaf/silicon](https://github.com/Aloxaf/silicon) - Create beautiful image of your source code.
* [AmrDeveloper/GQL](https://github.com/AmrDeveloper/GQL) - GitQL is a extensible SQL-like query language and SDK to perform queries on various data sources such .git files with supports of most of SQL features such as grouping, ordering and aggregation and window functions and allow customization like user-defined types and functions
* [Haleclipse/CCometixLine](https://github.com/Haleclipse/CCometixLine) - Claude Code statusline tool written in Rust
* [r-darwish/topgrade](https://github.com/r-darwish/topgrade) - Upgrade everything *(archived)*
* [atanunq/viu](https://github.com/atanunq/viu) - Terminal image viewer with native support for iTerm and Kitty
* [Canop/dysk](https://github.com/Canop/dysk) - A linux utility to get information on filesystems, like df but better
* [LukeMathWalker/cargo-chef](https://github.com/LukeMathWalker/cargo-chef) - A cargo-subcommand to speed up Rust Docker builds using Docker layer caching.
* [sfu-db/connector-x](https://github.com/sfu-db/connector-x) - Fastest library to load data from DB to DataFrames in Rust and Python
* [vicanso/zedis](https://github.com/vicanso/zedis) - Zedis: A blazing-fast, native Redis GUI built with Rust and GPUI.
* [rust-skia/rust-skia](https://github.com/rust-skia/rust-skia) - Rust Bindings for the Skia Graphics Library
* [i5ting/learn-rust-for-fe](https://github.com/i5ting/learn-rust-for-fe) - Rust是未来前端基础设施
* [tafia/quick-xml](https://github.com/tafia/quick-xml) - Rust high performance xml reader and writer
* [sharkdp/diskus](https://github.com/sharkdp/diskus) - A minimal, fast alternative to 'du -sh'
* [mitnk/cicada](https://github.com/mitnk/cicada) - An old-school bash-like Unix shell written in Rust
* [nuta/nsh](https://github.com/nuta/nsh) - A command-line shell like fish, but POSIX compatible.
* [kaplanelad/shellfirm](https://github.com/kaplanelad/shellfirm) - Safety guardrails for ai coding agents and human terminal commands
* [nachoparker/dutree](https://github.com/nachoparker/dutree) - a tool to analyze file system usage written in Rust
* [samuela/rustybox](https://github.com/samuela/rustybox) - A free-range, non-GMO fork of busybox in 100% Rust 🦀
* [docopt/docopt.rs](https://github.com/docopt/docopt.rs) - Docopt for Rust (command line argument parser). *(archived)*
* [derniercri/snatch](https://github.com/derniercri/snatch) - A simple, fast and interruptable download accelerator, written in Rust
* [akeru-inc/xcnotary](https://github.com/akeru-inc/xcnotary) - the missing macOS app notarization helper, built with Rust *(archived)*

### Logging and Configuration

* [tonhowtf/omniget](https://github.com/tonhowtf/omniget) - Download Udemy and Hotmart courses, YouTube videos, music and books — 1,800+ sites, no terminal. Free open-source desktop app for Windows, macOS and Linux, with a built-in course player, PDF/EPUB reader and music library. Powered by yt-dlp. Your files stay on your computer.
* [tokio-rs/tracing](https://github.com/tokio-rs/tracing) - Application level tracing for Rust.
* [rcoh/angle-grinder](https://github.com/rcoh/angle-grinder) - Slice and dice logs on the command line
* [pamburus/hl](https://github.com/pamburus/hl) - A fast and powerful log viewer and processor that converts JSON logs or logfmt logs into a clear human-readable format.
* [rust-cli/config-rs](https://github.com/rust-cli/config-rs) - ⚙️ Layered configuration system for Rust applications (with strong support for 12-factor applications).
* [cargo-bins/cargo-binstall](https://github.com/cargo-bins/cargo-binstall) - Binary installation for rust projects
* [StractOrg/stract](https://github.com/StractOrg/stract) - web search done right *(archived)*
* [chinedufn/percy](https://github.com/chinedufn/percy) - Build frontend browser apps with Rust + WebAssembly. Supports server side rendering.
* [feldera/feldera](https://github.com/feldera/feldera) - The Feldera Incremental Computation Engine
* [pdf-rs/pdf](https://github.com/pdf-rs/pdf) - Rust library to read, manipulate and write PDF files.
* [http-rs/surf](https://github.com/http-rs/surf) - Fast and friendly HTTP client framework for async Rust
* [BrainiumLLC/cargo-mobile](https://github.com/BrainiumLLC/cargo-mobile) - Rust on mobile made easy!
* [estk/log4rs](https://github.com/estk/log4rs) - A highly configurable logging framework for Rust
* [softprops/envy](https://github.com/softprops/envy) - deserialize env vars into typesafe structs with rust
* [daboross/fern](https://github.com/daboross/fern) - Simple, efficient logging for Rust
* [awslabs/flowgger](https://github.com/awslabs/flowgger) - A fast data collector in Rust

### Text Processing

* [rust-lang/mdBook](https://github.com/rust-lang/mdBook) - Create book from markdown files. Like Gitbook but implemented in Rust
* [firecrawl/anydoc](https://github.com/firecrawl/anydoc) - Convert Word, PowerPoint, Excel, OpenDocument, RTF, EPUB, CSV, and PDF to clean Markdown. Built in Rust, with Node.js and Python bindings.
* [firecrawl/pdf-inspector](https://github.com/firecrawl/pdf-inspector) - Fast Rust library for PDF inspection, classification, and text extraction. Intelligently detects scanned vs text-based PDFs to enable smart routing decisions.
* [getzola/zola](https://github.com/getzola/zola) - A fast static site generator in a single binary with everything built-in. https://www.getzola.org
* [xberg-io/xberg](https://github.com/xberg-io/xberg) - Polyglot document intelligence with a Rust core: extract text, metadata, images, tables, and structured data from 106 formats across 140 file extensions, plus code intelligence for 371 languages. Fifteen bindings, with CLI, REST API, and MCP server.
* [pemistahl/grex](https://github.com/pemistahl/grex) - A command-line tool and Rust library with Python bindings for generating regular expressions from user-provided test cases
* [chmln/sd](https://github.com/chmln/sd) - Intuitive find & replace CLI (sed alternative)
* [Keats/tera](https://github.com/Keats/tera) - A template engine for Rust based on Jinja2/Django
* [rust-lang/regex](https://github.com/rust-lang/regex) - An implementation of regular expressions for Rust. This implementation uses finite automata and guarantees linear time matching on all inputs.
* [askama-rs/askama-old](https://github.com/askama-rs/askama-old) - The original askama repo, please go to https://github.com/askama-rs/askama *(archived)*
* [nix-community/nh](https://github.com/nix-community/nh) - Yet another Nix CLI helper. [Maintainers=@NotAShelf, @faukah]
* [rust-bitcoin/rust-bitcoin](https://github.com/rust-bitcoin/rust-bitcoin) - Rust Bitcoin library
* [hannobraun/fornjot](https://github.com/hannobraun/fornjot) - Early-stage b-rep CAD kernel, written in the Rust programming language. No longer in development. *(archived)*
* [utooland/utoo](https://github.com/utooland/utoo) - A unified toolchain for web development
* [rustcc/writing-an-os-in-rust](https://github.com/rustcc/writing-an-os-in-rust) - 《使用Rust编写操作系统》
* [RustCrypto/hashes](https://github.com/RustCrypto/hashes) - Collection of cryptographic hash functions written in pure Rust
* [rust-phf/rust-phf](https://github.com/rust-phf/rust-phf) - Compile time static maps for Rust
* [rustsec/rustsec](https://github.com/rustsec/rustsec) - RustSec API & Tooling
* [lvkv/whenfs](https://github.com/lvkv/whenfs) - A FUSE filesystem for your Google calendar
* [tokio-rs/io-uring](https://github.com/tokio-rs/io-uring) - The `io_uring` library for Rust
* [gfx-rs/wgpu-rs](https://github.com/gfx-rs/wgpu-rs) - Rust bindings to wgpu native library *(archived)*
* [huacnlee/autocorrect](https://github.com/huacnlee/autocorrect) - A linter and formatter to help you to improve copywriting, correct spaces, words, and punctuations between CJK (Chinese, Japanese, Korean).
* [Stebalien/tempfile](https://github.com/Stebalien/tempfile) - Temporary file library for rust
* [Joystream/joystream](https://github.com/Joystream/joystream) - Joystream Monorepo
* [projectfluent/fluent-rs](https://github.com/projectfluent/fluent-rs) - Rust implementation of Project Fluent
* [pomsky-lang/pomsky](https://github.com/pomsky-lang/pomsky) - A new, portable, regular expression language
* [BurntSushi/aho-corasick](https://github.com/BurntSushi/aho-corasick) - A fast implementation of Aho-Corasick in Rust.
* [org-rs/org-rs](https://github.com/org-rs/org-rs) - org-mode parser rewrite in Rust

### Files and Operating System

* [microsoft/windows-rs](https://github.com/microsoft/windows-rs) - Rust for Windows
* [apache/opendal](https://github.com/apache/opendal) - Apache OpenDAL: One Layer, All Storage.
* [aya-rs/aya](https://github.com/aya-rs/aya) - Aya is an eBPF library for the Rust programming language, built with a focus on developer experience and operability.
* [notify-rs/notify](https://github.com/notify-rs/notify) - 🔭 Cross-platform filesystem notification library for Rust.
* [nix-rust/nix](https://github.com/nix-rust/nix) - Rust friendly bindings to *nix APIs
* [redox-os/tfs](https://github.com/redox-os/tfs) - Mirror of https://gitlab.redox-os.org/redox-os/tfs
* [redox-os/termion](https://github.com/redox-os/termion) - Mirror of https://gitlab.redox-os.org/redox-os/termion
* [cloudflare/foundations](https://github.com/cloudflare/foundations) - Cloudflare's Rust service foundations library.
* [servo/core-foundation-rs](https://github.com/servo/core-foundation-rs) - Rust bindings to Core Foundation and other low level libraries on Mac OS X and iOS
* [spacejam/rio](https://github.com/spacejam/rio) - pure rust io_uring library, built on libc, thread & async friendly, misuse resistant
* [heim-rs/heim](https://github.com/heim-rs/heim) - Cross-platform async library for system information fetching 🦀
* [kahing/catfs](https://github.com/kahing/catfs) - Cache AnyThing filesystem written in Rust
* [stratis-storage/stratisd](https://github.com/stratis-storage/stratisd) - Easy to use local storage management for Linux.
* [microsoft/com-rs](https://github.com/microsoft/com-rs) - A Rust crate for creating and consuming COM APIs *(archived)*

### Automation and Scripting

* [j178/prek](https://github.com/j178/prek) - ⚡ A fast Git hook manager written in Rust, designed as a drop-in alternative to pre-commit, reimagined.
* [watchexec/watchexec](https://github.com/watchexec/watchexec) - Executes commands in response to file modifications
* [tkellogg/dura](https://github.com/tkellogg/dura) - You shouldn't ever lose your work if you're using Git
* [teloxide/teloxide](https://github.com/teloxide/teloxide) - 🤖 An elegant Telegram bots framework for Rust
* [osohq/oso](https://github.com/osohq/oso) - Deprecated: See README
* [indexmap-rs/indexmap](https://github.com/indexmap-rs/indexmap) - A hash table with consistent order and fast iteration; access items by key or sequence index
* [J-F-Liu/lopdf](https://github.com/J-F-Liu/lopdf) - A Rust library for PDF document manipulation.
* [cloudflare/lol-html](https://github.com/cloudflare/lol-html) - Low output latency streaming HTML parser/rewriter with CSS selector-based API
* [databendlabs/openraft](https://github.com/databendlabs/openraft) - rust raft with improvements
* [rust-lang/chalk](https://github.com/rust-lang/chalk) - An implementation and definition of the Rust trait system using a PROLOG-like logic solver
* [rust-embedded/discovery](https://github.com/rust-embedded/discovery) - Discover the world of microcontrollers through Rust!
* [tomaka/redshirt](https://github.com/tomaka/redshirt) - 🧑‍🔬 Operating system
* [kbknapp/cargo-outdated](https://github.com/kbknapp/cargo-outdated) - A cargo subcommand for displaying when Rust dependencies are out of date
* [apache/teaclave-sgx-sdk](https://github.com/apache/teaclave-sgx-sdk) - Apache Teaclave™ SGX SDK helps developers to write Intel SGX applications in the Rust programming language, and also known as Rust SGX SDK.
* [rust-shell-script/rust_cmd_lib](https://github.com/rust-shell-script/rust_cmd_lib) - Common rust command-line macros and utilities, to write shell-script like tasks in a clean, natural and rusty way
* [autopilot-rs/autopy](https://github.com/autopilot-rs/autopy) - A simple, cross-platform GUI automation module for Python and Rust.
* [telegram-rs/telegram-bot](https://github.com/telegram-rs/telegram-bot) - Rust Library for creating a Telegram Bot

### General Purpose Libraries

* [vectordotdev/vector](https://github.com/vectordotdev/vector) - A high-performance observability data pipeline.
* [petgraph/petgraph](https://github.com/petgraph/petgraph) - Graph data structure library for Rust.
* [rust-itertools/itertools](https://github.com/rust-itertools/itertools) - Extra iterator adaptors, iterator methods, free functions, and macros.
* [rust-lang/hashbrown](https://github.com/rust-lang/hashbrown) - Rust port of Google's SwissTable hash map
* [redbadger/crux](https://github.com/redbadger/crux) - Cross-platform app development in Rust
* [sheeki03/tirith](https://github.com/sheeki03/tirith) - Terminal security for developers and AI agents. Intercepts homograph URLs, pipe-to-shell, ANSI injection, obfuscated payloads, data exfiltration, and malicious AI skills/configs before they execute.
* [solidiquis/erdtree](https://github.com/solidiquis/erdtree) - A modern, cross-platform, multi-threaded, and general purpose filesystem and disk-usage utility that is aware of .gitignore and hidden file rules.
* [amtoaer/bili-sync](https://github.com/amtoaer/bili-sync) - 由 Rust & Tokio 驱动的哔哩哔哩同步工具
* [mattwparas/steel](https://github.com/mattwparas/steel) - An embedded scheme interpreter in Rust
* [pykeio/ort](https://github.com/pykeio/ort) - Fast ML inference & training for ONNX models in Rust
* [kcl-lang/kcl](https://github.com/kcl-lang/kcl) - KCL Programming Language Core and API (CNCF Sandbox Project). https://kcl-lang.io
* [tauri-apps/tao](https://github.com/tauri-apps/tao) - The TAO of cross-platform windowing. A library in Rust built for Tauri.
* [algesten/ureq](https://github.com/algesten/ureq) - A simple, safe HTTP client
* [jonhoo/inferno](https://github.com/jonhoo/inferno) - A Rust port of FlameGraph
* [Keats/jsonwebtoken](https://github.com/Keats/jsonwebtoken) - JWT lib in rust
* [ryanmcgrath/cacao](https://github.com/ryanmcgrath/cacao) - Rust bindings for AppKit (macOS) and UIKit (iOS/tvOS). Experimental, but working!
* [bitshifter/glam-rs](https://github.com/bitshifter/glam-rs) - A simple and fast linear algebra library for games and graphics
* [PaddiM8/kalker](https://github.com/PaddiM8/kalker) - Scientific calculator with math syntax that supports user-defined variables and functions, complex numbers, and estimation of derivatives and integrals
* [mosuka/bayard](https://github.com/mosuka/bayard) - A full-text search and indexing server written in Rust.
* [unicode-org/icu4x](https://github.com/unicode-org/icu4x) - Solving i18n for client-side and resource-constrained environments.
* [viperproject/prusti-dev](https://github.com/viperproject/prusti-dev) - A static verifier for Rust, based on the Viper verification infrastructure.
* [zee-editor/zee](https://github.com/zee-editor/zee) - A modern text editor for the terminal written in Rust
* [fereidani/kanal](https://github.com/fereidani/kanal) - The fast sync and async channel that Rust deserves
* [buyukakyuz/corroded](https://github.com/buyukakyuz/corroded) - Illegal rust
* [rust-osdev/bootloader](https://github.com/rust-osdev/bootloader) - An experimental pure-Rust x86 bootloader
* [0x676e67/ninja](https://github.com/0x676e67/ninja) - Reverse engineered ChatGPT proxy *(archived)*
* [elringus/sprite-dicing](https://github.com/elringus/sprite-dicing) - Cross-engine tool for lossless compression of sprites with identical regions
* [zeromq/zmq.rs](https://github.com/zeromq/zmq.rs) - A native implementation of ØMQ in Rust
* [rust-lang-deprecated/failure](https://github.com/rust-lang-deprecated/failure) - Error management *(archived)*
* [PumpkinDB/PumpkinDB](https://github.com/PumpkinDB/PumpkinDB) - Immutable Ordered Key-Value Database Engine
* [AtheMathmo/rusty-machine](https://github.com/AtheMathmo/rusty-machine) - Machine Learning library for Rust *(archived)*
* [kpcyrd/sniffglue](https://github.com/kpcyrd/sniffglue) - Secure multithreaded packet sniffer
* [willdoescode/nat](https://github.com/willdoescode/nat) - `ls` alternative with useful info and a splash of color 🎨
* [andy-5/wslgit](https://github.com/andy-5/wslgit) - Use Git installed in Bash on Windows/Windows Subsystem for Linux (WSL) from Windows and Visual Studio Code (VSCode)
* [uuid-rs/uuid](https://github.com/uuid-rs/uuid) - Generate and parse UUIDs.
* [carllerche/tower-web](https://github.com/carllerche/tower-web) - A fast, boilerplate free, web framework for Rust
* [rust-lang-deprecated/error-chain](https://github.com/rust-lang-deprecated/error-chain) - Error boilerplate for Rust *(archived)*
* [withoutboats/fehler](https://github.com/withoutboats/fehler) - Rust doesn't have exceptions

## Systems and Hardware

### Operating Systems and Kernels

* [redox-os/redox](https://github.com/redox-os/redox) - Mirror of https://gitlab.redox-os.org/redox-os/redox
* [tock/tock](https://github.com/tock/tock) - A secure embedded operating system for microcontrollers
* [asterinas/asterinas](https://github.com/asterinas/asterinas) - Asterinas aims to be a production-grade Linux alternative—memory safe, high-performance, and more.
* [rcore-os/rCore](https://github.com/rcore-os/rCore) - Rust version of THU uCore OS. Linux compatible.
* [nuta/kerla](https://github.com/nuta/kerla) - A new operating system kernel with Linux binary compatibility written in Rust.
* [maestro-os/maestro](https://github.com/maestro-os/maestro) - Lightweight, Linux-compatible kernel, written in Rust to leverage the safety of the typesystem. Aiming to remove as much legacy as possible while supporting most usecases
* [theseus-os/Theseus](https://github.com/theseus-os/Theseus) - Theseus is a modern OS written from scratch in Rust that explores 𝐢𝐧𝐭𝐫𝐚𝐥𝐢𝐧𝐠𝐮𝐚𝐥 𝐝𝐞𝐬𝐢𝐠𝐧: closing the semantic gap between compiler and hardware by maximally leveraging the power of language safety and affine types. Theseus aims to shift OS responsibilities like resource management into the compiler.
* [Ruddle/Fomos](https://github.com/Ruddle/Fomos) - Experimental OS, built with rust
* [tsgates/rust.ko](https://github.com/tsgates/rust.ko) - A minimal Linux kernel module written in rust.

## Science and Math

### Mathematics

* [dimforge/nalgebra](https://github.com/dimforge/nalgebra) - Linear algebra library for Rust.
* [rust-ndarray/ndarray](https://github.com/rust-ndarray/ndarray) - ndarray: an N-dimensional array with array views, multidimensional slicing, and efficient operations
* [nexus-xyz/nexus-zkvm](https://github.com/nexus-xyz/nexus-zkvm) - The Nexus zkVM: The zero-knowledge virtual machine
* [namada-net/namada](https://github.com/namada-net/namada) - Rust implementation of Namada, a Proof-of-Stake L1 for interchain asset-agnostic privacy
* [harababurel/gcsf](https://github.com/harababurel/gcsf) - a FUSE file system based on Google Drive
* [cjbassi/ytop](https://github.com/cjbassi/ytop) - A TUI system monitor written in Rust *(archived)*
* [raphaelmansuy/edgequake](https://github.com/raphaelmansuy/edgequake) - EdegQuake 🌋 High-performance GraphRAG inspired from LightRag written in Rust; Transform documents into intelligent knowledge graphs for superior retrieval and generation
* [exercism/rust](https://github.com/exercism/rust) - Exercism exercises in Rust.
* [rust-boom/rust-boom](https://github.com/rust-boom/rust-boom) - Awesome Rust (Rust 资源 | 学习 | 书 ). 💥
* [sobelio/llm-chain](https://github.com/sobelio/llm-chain) - `llm-chain` is a powerful rust crate for building chains in large language models allowing you to summarise text and complete complex tasks
* [rust-lang/reference](https://github.com/rust-lang/reference) - The Rust Reference
* [PyO3/rust-numpy](https://github.com/PyO3/rust-numpy) - PyO3-based Rust bindings of the NumPy C-API
* [paupino/rust-decimal](https://github.com/paupino/rust-decimal) - Decimal number implementation written in pure Rust suitable for financial and fixed-precision calculations.
* [zu1k/translator](https://github.com/zu1k/translator) - 简单、轻量、好用的划词翻译软件
* [iliekturtles/uom](https://github.com/iliekturtles/uom) - Units of measurement -- type-safe zero-cost dimensional analysis
* [rust-num/num](https://github.com/rust-num/num) - A collection of numeric types and traits for Rust.

### Scientific Computing

* [CyberTimon/RapidRAW](https://github.com/CyberTimon/RapidRAW) - A beautiful, non-destructive, and GPU-accelerated RAW image editor built with performance in mind.
* [dora-rs/dora](https://github.com/dora-rs/dora) - DORA (Dataflow-Oriented Robotic Architecture) is middleware designed to streamline and simplify the creation of AI-based robotic applications. It offers low latency, composable, and distributed dataflow capabilities. Applications are modeled as directed graphs, also referred to as pipelines.
* [giacomo-b/rust-stakeholder](https://github.com/giacomo-b/rust-stakeholder) - Generate impressive-looking terminal output to look busy when stakeholders walk by
* [parseablehq/parseable](https://github.com/parseablehq/parseable) - Parseable is an open source, unified infrastructure observability platform built in Rust on a data lake architecture. It tracks logs, metrics, traces, and events across apps, agents, and systems, reducing storage costs by up to 90% through columnar telemetry compression.
* [zesterer/ariadne](https://github.com/zesterer/ariadne) - [Ariadne has moved to Codeberg!] A fancy diagnostics & error reporting crate *(archived)*
* [microsoft/openvmm](https://github.com/microsoft/openvmm) - Home of OpenVMM and OpenHCL
* [enigo-rs/enigo](https://github.com/enigo-rs/enigo) - Cross platform input simulation in Rust
* [JasonShin/fp-core.rs](https://github.com/JasonShin/fp-core.rs) - A library for functional programming in Rust
* [rust-mobile/ndk](https://github.com/rust-mobile/ndk) - Rust bindings to the Android NDK

### Formal Methods and Proofs

* [model-checking/kani](https://github.com/model-checking/kani) - Kani Rust Verifier
* [verus-lang/verus](https://github.com/verus-lang/verus) - Verified Rust for low-level systems code
* [rust-lang/log](https://github.com/rust-lang/log) - Logging implementation for Rust
* [mCaptcha/mCaptcha](https://github.com/mCaptcha/mCaptcha) - A no-nonsense CAPTCHA system with seamless UX | Backend component
* [microsoft/aici](https://github.com/microsoft/aici) - AICI: Prompts as (Wasm) Programs
* [amethyst/legion](https://github.com/amethyst/legion) - High performance Rust ECS library
* [dimforge/nphysics](https://github.com/dimforge/nphysics) - 2 and 3-dimensional rigid body physics engine for Rust.
* [fitzgen/dodrio](https://github.com/fitzgen/dodrio) - A fast, bump-allocated virtual DOM library for Rust and WebAssembly. *(archived)*

## Other

* [openai/codex](https://github.com/openai/codex) - Lightweight coding agent that runs in your terminal
* [ruvnet/RuView](https://github.com/ruvnet/RuView) - π RuView turns commodity WiFi signals into real-time spatial intelligence, vital sign monitoring, and presence detection — all without a single pixel of video.
* [zed-industries/zed](https://github.com/zed-industries/zed) - Code at the speed of thought – Zed is a high-performance, multiplayer code editor from the creators of Atom and Tree-sitter.
* [FuelLabs/sway](https://github.com/FuelLabs/sway) - 🌴 Empowering everyone to build reliable and efficient smart contracts.
* [typst/typst](https://github.com/typst/typst) - A markup-based typesetting system that is powerful and easy to learn.
* [aaif-goose/goose](https://github.com/aaif-goose/goose) - an open source, extensible AI agent that goes beyond code suggestions - install, execute, edit, and test with any LLM
* [juspay/hyperswitch](https://github.com/juspay/hyperswitch) - Open source, composable payments platform | PCI compliant | SaaS and Self-host options | Enables connectivity to multiple payment, payout, fraud, vault and tokenization providers | Uplifts authorization with intelligent routing and revenue recovery | Reduce payment processing costs with cost observability | Reduces payment ops with reconciliation
* [vercel-labs/agent-browser](https://github.com/vercel-labs/agent-browser) - Browser automation CLI for AI agents
* [tinyhumansai/openhuman](https://github.com/tinyhumansai/openhuman) - Your Personal AI super intelligence. A brain that builds a local-first memory of your life, a fantastic orchestrator of agent fleets and workflows, and a deep researcher.
* [pnpm/pnpm](https://github.com/pnpm/pnpm) - Fast, disk space efficient package manager
* [casey/just](https://github.com/casey/just) - 🤖 Just a command runner
* [zellij-org/zellij](https://github.com/zellij-org/zellij) - A terminal workspace with batteries included
* [AlexsJones/llmfit](https://github.com/AlexsJones/llmfit) - Hundreds of models & providers. One command to find what runs on your hardware.
* [qdrant/qdrant](https://github.com/qdrant/qdrant) - Qdrant - High-performance, massive-scale Vector Database and Vector Search Engine for the next generation of AI. Also available in the cloud https://cloud.qdrant.io/
* [TabbyML/tabby](https://github.com/TabbyML/tabby) - Self-hosted AI coding assistant
* [surrealdb/surrealdb](https://github.com/surrealdb/surrealdb) - A scalable, distributed, collaborative, document-graph database, for the realtime web
* [zeroclaw-labs/zeroclaw](https://github.com/zeroclaw-labs/zeroclaw) - Fast, small, and fully autonomous AI personal assistant infrastructure, any OS, any platform — deploy anywhere, swap anything 🦀
* [xai-org/x-algorithm](https://github.com/xai-org/x-algorithm) - Algorithm powering the For You feed on X
* [block/buzz](https://github.com/block/buzz) - A hive mind communication platform
* [jj-vcs/jj](https://github.com/jj-vcs/jj) - A Git-compatible VCS that is both simple and powerful
* [cjpais/Handy](https://github.com/cjpais/Handy) - A free, open source, and extensible speech-to-text application that works completely offline.
* [ankitects/anki](https://github.com/ankitects/anki) - Anki is a smart spaced repetition flashcard program
* [BigPizzaV3/CodexPlusPlus](https://github.com/BigPizzaV3/CodexPlusPlus) - An enhanced tool for CodexApp, striving to make Codex better to use and more comfortable 一个CodexApp的增强工具，努力让Codex变得更好用更舒服
* [nautechsystems/nautilus_trader](https://github.com/nautechsystems/nautilus_trader) - Production-grade Rust-native trading engine with deterministic event-driven architecture
* [BloopAI/vibe-kanban](https://github.com/BloopAI/vibe-kanban) - Get 10X more out of Claude Code, Codex or any coding agent
* [cloudflare/pingora](https://github.com/cloudflare/pingora) - A library for building fast, reliable and evolvable network services.
* [oldj/SwitchHosts](https://github.com/oldj/SwitchHosts) - Switch hosts quickly!
* [GraphiteEditor/Graphite](https://github.com/GraphiteEditor/Graphite) - Community-built comprehensive 2D content creation appplication for graphic design, digital art, and interactive real-time motion graphics powered by a node-based procedural graphics engine
* [xai-org/grok-build](https://github.com/xai-org/grok-build) - SpaceXAI's coding agent harness and TUI. Fullscreen, mouse interactive, extensible.
* [Wilfred/difftastic](https://github.com/Wilfred/difftastic) - a structural diff that understands syntax 🟥🟩
* [biomejs/biome](https://github.com/biomejs/biome) - A toolchain for web projects, aimed to provide functionalities to maintain them. Biome offers formatter and linter, usable via CLI and LSP.
* [clockworklabs/SpacetimeDB](https://github.com/clockworklabs/SpacetimeDB) - Development at the speed of light
* [zama-ai/fhevm](https://github.com/zama-ai/fhevm) - FHEVM, a full-stack framework for integrating Fully Homomorphic Encryption (FHE) with blockchain applications
* [rome/tools](https://github.com/rome/tools) - Unified developer tools for JavaScript, TypeScript, and the web *(archived)*
* [facebook/flow](https://github.com/facebook/flow) - Adds static typing to JavaScript to improve developer productivity and code quality.
* [gleam-lang/gleam](https://github.com/gleam-lang/gleam) - ⭐️ A friendly language for building type-safe, scalable systems!
* [bee-san/Ciphey](https://github.com/bee-san/Ciphey) - ⚡ Automatically decrypt encryptions without knowing the key or cipher, decode encodings, and crack hashes ⚡
* [HigherOrderCO/Bend](https://github.com/HigherOrderCO/Bend) - A massively parallel, high-level programming language
* [fathyb/carbonyl](https://github.com/fathyb/carbonyl) - Chromium running inside your terminal
* [Orange-OpenSource/hurl](https://github.com/Orange-OpenSource/hurl) - Hurl, run and test HTTP requests with plain text.
* [facebook/relay](https://github.com/facebook/relay) - Relay is a JavaScript framework for building data-driven React applications.
* [iii-hq/iii](https://github.com/iii-hq/iii) - Effortlessly compose, extend, and observe every service in real-time for the first time ever.
* [ccusage/ccusage](https://github.com/ccusage/ccusage) - npx ccusage
* [windmill-labs/windmill](https://github.com/windmill-labs/windmill) - Open-source developer platform to power your entire infra and turn scripts into webhooks, workflows and UIs. Fastest workflow engine (13x vs Airflow). Open-source alternative to Retool and Temporal.
* [eythaann/Seelen-UI](https://github.com/eythaann/Seelen-UI) - The Fully Customizable Desktop Environment for Windows 10/11.
* [jlcodes99/cockpit-tools](https://github.com/jlcodes99/cockpit-tools) - 🚀 通用 AI IDE 账号管理工具：支持 Antigravity / Codex / GitHub Copilot / Windsurf / Kiro / Cursor / Gemini-cli / CodeBuddy，多账号切换、配额监控、自动唤醒与多开实例管理。 🚀 Universal AI IDE account manager for Antigravity / Codex / GitHub Copilot / Windsurf / Kiro / Cursor / Gemini-cli / CodeBuddy, with multi-account switching, quota monitoring, wake-up automation, and multi-insta
* [diem/diem](https://github.com/diem/diem) - Diem’s mission is to build a trusted and innovative financial network that empowers people and businesses around the world.
* [memvid/memvid](https://github.com/memvid/memvid) - Memory layer for AI Agents. Replace complex RAG pipelines with a serverless, single-file memory layer. Give your agents instant retrieval and long-term memory.
* [benfred/py-spy](https://github.com/benfred/py-spy) - Sampling profiler for Python programs
* [Y2Z/monolith](https://github.com/Y2Z/monolith) - ⬛️ CLI tool and library for saving complete web pages as a single HTML file
* [Automattic/harper](https://github.com/Automattic/harper) - Offline, privacy-first grammar checker. Fast, open-source, Rust-powered
* [analysis-tools-dev/static-analysis](https://github.com/analysis-tools-dev/static-analysis) - ⚙️ A curated list of static analysis (SAST) tools and linters for all programming languages, config files, build tools, and more. The focus is on tools which improve code quality.
* [ReFirmLabs/binwalk](https://github.com/ReFirmLabs/binwalk) - Firmware Analysis Tool
* [astral-sh/rye](https://github.com/astral-sh/rye) - a Hassle-Free Python Experience *(archived)*
* [dbt-labs/dbt-core](https://github.com/dbt-labs/dbt-core) - dbt enables data analysts and engineers to transform their data using the same practices that software engineers use to build applications.
* [volta-cli/volta](https://github.com/volta-cli/volta) - Volta: JS Toolchains as Code. ⚡
* [run-llama/liteparse](https://github.com/run-llama/liteparse) - A fast, helpful, and open-source document parser
* [svenstaro/genact](https://github.com/svenstaro/genact) - 🌀 A nonsense activity generator
* [moghtech/komodo](https://github.com/moghtech/komodo) - 🦎 a tool to build and deploy software on many servers 🦎
* [imsnif/bandwhich](https://github.com/imsnif/bandwhich) - Terminal bandwidth utilization tool
* [lancedb/lancedb](https://github.com/lancedb/lancedb) - Developer-friendly OSS embedded retrieval library for multimodal AI. Search More; Manage Less.
* [perspective-dev/perspective](https://github.com/perspective-dev/perspective) - A data visualization and analytics component, especially well-suited for large and/or streaming datasets.
* [huggingface/tokenizers](https://github.com/huggingface/tokenizers) - 💥 Fast State-of-the-Art Tokenizers optimized for Research and Production
* [PRQL/prql](https://github.com/PRQL/prql) - PRQL is a modern language for transforming data — a simple, powerful, pipelined SQL replacement
* [pkgxdev/pkgx](https://github.com/pkgxdev/pkgx) - Run Anything
* [phiresky/ripgrep-all](https://github.com/phiresky/ripgrep-all) - rga: ripgrep, but also search in PDFs, E-Books, Office documents, zip, tar.gz, etc.
* [messense/aliyundrive-webdav](https://github.com/messense/aliyundrive-webdav) - 阿里云盘 WebDAV 服务 *(archived)*
* [embassy-rs/embassy](https://github.com/embassy-rs/embassy) - Modern embedded framework, using Rust and async.
* [jpochyla/psst](https://github.com/jpochyla/psst) - Fast and multi-platform Spotify client with native GUI
* [ccfddl/ccf-deadlines](https://github.com/ccfddl/ccf-deadlines) - ⏰ Agenticly track worldwide conference deadlines (Website, Python Cli, Wechat Applet)
* [Morganamilo/paru](https://github.com/Morganamilo/paru) - Feature packed AUR helper
* [ramensoftware/windhawk](https://github.com/ramensoftware/windhawk) - The customization marketplace for Windows programs: https://windhawk.net/
* [awslabs/llrt](https://github.com/awslabs/llrt) - LLRT (Low Latency Runtime) is an experimental, lightweight JavaScript runtime designed to address the growing demand for fast and efficient Serverless applications.
* [wealthfolio/wealthfolio](https://github.com/wealthfolio/wealthfolio) - A beautiful, private, local-first personal finance tracker. Investments, net worth, spending, and simulations.
* [vi/websocat](https://github.com/vi/websocat) - Command-line client for WebSockets, like netcat (or curl) for ws:// with advanced socat-like functions
* [kata-containers/kata-containers](https://github.com/kata-containers/kata-containers) - Kata Containers is an open source project and community working to build a standard implementation of lightweight Virtual Machines (VMs) that feel and perform like containers, but provide the workload isolation and security advantages of VMs. https://katacontainers.io/
* [sinelaw/fresh](https://github.com/sinelaw/fresh) - Terminal based IDE & text editor: easy, powerful and fast
* [unicity-aos/aos-ce](https://github.com/unicity-aos/aos-ce) - AOS Community Edition: the open agent operating system.
* [unicity-aos/capsule-memory](https://github.com/unicity-aos/capsule-memory) - Cross-session memory. Reads local memory state and injects it into the system prompt through hooks. Part of Unicity AOS.
* [EpicGames/lore](https://github.com/EpicGames/lore) - Lore is a next-generation, open source version control system
* [unicity-aos/capsule-identity](https://github.com/unicity-aos/capsule-identity) - System prompt builder. Assembles agent identity from workspace config and spark.toml. Part of Unicity AOS.
* [NVIDIA/OpenShell](https://github.com/NVIDIA/OpenShell) - OpenShell is the safe, private runtime for autonomous AI agents.
* [unicity-aos/capsule-fs](https://github.com/unicity-aos/capsule-fs) - Filesystem tools for agents. Read, write, replace, grep, list, create, delete, move via VFS airlock. Part of Unicity AOS.
* [atom-archive/xray](https://github.com/atom-archive/xray) - An experimental next-generation Electron-based text editor *(archived)*
* [paritytech/substrate](https://github.com/paritytech/substrate) - Substrate: The platform for blockchain innovators *(archived)*
* [qualcomm/GenieX](https://github.com/qualcomm/GenieX) - Run frontier LLMs and VLMs locally on Qualcomm devices across NPU, GPU, and CPU with a few lines of code
* [a-b-street/abstreet](https://github.com/a-b-street/abstreet) - Transportation planning and traffic simulation software for creating cities friendlier to walking, biking, and public transit
* [bensadeh/tailspin](https://github.com/bensadeh/tailspin) - 🌀 A log file highlighter
* [datahaven-xyz/datahaven](https://github.com/datahaven-xyz/datahaven) - An EVM compatible Substrate chain, powered by StorageHub and secured by EigenLayer
* [alvr-org/ALVR](https://github.com/alvr-org/ALVR) - Stream VR games from your PC to your headset via Wi-Fi
* [svenstaro/miniserve](https://github.com/svenstaro/miniserve) - 🌟 For when you really just want to serve some files over HTTP right now!
* [MystenLabs/sui](https://github.com/MystenLabs/sui) - Sui, a next-generation smart contract platform with high throughput, low latency, and an asset-oriented programming model powered by the Move programming language
* [mozilla/sccache](https://github.com/mozilla/sccache) - Sccache is a ccache-like tool. It is used as a compiler wrapper and avoids compilation when possible. Sccache has the capability to utilize caching in remote storage environments, including various cloud storage options, or alternatively, in local storage.
* [tailcallhq/forgecode](https://github.com/tailcallhq/forgecode) - AI enabled pair programmer for Claude, GPT, O Series, Grok, Deepseek, Gemini and 300+ models
* [mgdm/htmlq](https://github.com/mgdm/htmlq) - Like jq, but for HTML.
* [lucasgelfond/zerobrew](https://github.com/lucasgelfond/zerobrew) - A 5-20x faster experimental Homebrew alternative
* [cachix/devenv](https://github.com/cachix/devenv) - Fast, Declarative, Reproducible, and Composable Developer Environments using Nix
* [katanemo/plano](https://github.com/katanemo/plano) - Plano is an AI-native proxy server and data plane for agentic apps. Smart LLM routing, observability, agent orchestration, and guardrails so you stay focused on your agents core logic.
* [erebe/wstunnel](https://github.com/erebe/wstunnel) - Tunnel all your traffic over Websocket or HTTP2 - Bypass firewalls/DPI - Static binary available
* [facebook/sapling](https://github.com/facebook/sapling) - A Scalable, User-Friendly Source Control System.
* [max-sixty/worktrunk](https://github.com/max-sixty/worktrunk) - Worktrunk is a CLI for Git worktree management, designed for parallel AI agent workflows
* [ultraworkers/claw-code-parity](https://github.com/ultraworkers/claw-code-parity) - Join Discord: https://discord.gg/5TUQKqFWd / claw-code Rust port parity work - it is temporary work while claw-code repo is doing migration *(archived)*
* [dtolnay/anyhow](https://github.com/dtolnay/anyhow) - Flexible concrete Error type built on std::error::Error
* [pollen-robotics/microduck](https://github.com/pollen-robotics/microduck) - A Tiny biped duck robot 🦆
* [spinframework/spin](https://github.com/spinframework/spin) - Spin is the open source developer tool for building and running serverless applications powered by WebAssembly.
* [evcxr/evcxr](https://github.com/evcxr/evcxr)
* [rizsotto/Bear](https://github.com/rizsotto/Bear) - Generate compile_commands.json for any C or C++ build
* [zizmorcore/zizmor](https://github.com/zizmorcore/zizmor) - Static analysis for GitHub Actions
* [aptos-labs/aptos-core](https://github.com/aptos-labs/aptos-core) - Aptos is a layer 1 blockchain built to support the widespread use of blockchain through better technology and user experience.
* [RediSearch/RediSearch](https://github.com/RediSearch/RediSearch) - A query and indexing engine for Redis, providing secondary indexing, full-text search, vector similarity search and aggregations.
* [mtkennerly/ludusavi](https://github.com/mtkennerly/ludusavi) - Backup tool for PC game saves
* [Byron/dua-cli](https://github.com/Byron/dua-cli) - View disk space usage and delete unwanted data, fast.
* [indygreg/PyOxidizer](https://github.com/indygreg/PyOxidizer) - A modern Python application packaging and distribution tool
* [kucherenko/jscpd](https://github.com/kucherenko/jscpd) - Copy/paste detector for source code. 220+ languages, Rust engine, SARIF/HTML/badge reporters, GitHub Action, MCP server for AI agents.
* [loro-dev/loro](https://github.com/loro-dev/loro) - Make your JSON data collaborative and version-controlled with CRDTs
* [agentcodee/cursor-free-everyday](https://github.com/agentcodee/cursor-free-everyday) - 完全免费, 自动获取新账号,一键重置新额度, 解决机器码问题, 自动满额度
* [signalapp/libsignal](https://github.com/signalapp/libsignal) - Home to the Signal Protocol as well as other cryptographic primitives which make Signal possible.
* [waditu/czsc](https://github.com/waditu/czsc) - 缠中说禅技术分析工具；缠论；股票；期货；Quant；量化交易
* [microsoft/sudo](https://github.com/microsoft/sudo) - It's sudo, for Windows
* [FalkorDB/FalkorDB](https://github.com/FalkorDB/FalkorDB) - A super fast Graph Database uses GraphBLAS under the hood for its sparse adjacency matrix graph representation. Our goal is to provide the best Knowledge Graph for LLM (GraphRAG).
* [WebAssembly/WASI](https://github.com/WebAssembly/WASI) - WebAssembly System Interface
* [utilForever/game-developer-roadmap](https://github.com/utilForever/game-developer-roadmap) - Roadmap to becoming a game developer in 2022
* [awslabs/mountpoint-s3](https://github.com/awslabs/mountpoint-s3) - A simple, high-throughput file client for mounting an Amazon S3 bucket as a local file system.
* [voidzero-dev/vite-plus](https://github.com/voidzero-dev/vite-plus) - Vite+ is the unified toolchain and entry point for web development. It manages your runtime, package manager, and frontend toolchain in one place.
* [tummychow/git-absorb](https://github.com/tummychow/git-absorb) - git commit --fixup, but automatic
* [dimforge/rapier](https://github.com/dimforge/rapier) - 2D and 3D physics engines focused on performance.
* [sirupsen/napkin-math](https://github.com/sirupsen/napkin-math) - Techniques and numbers for estimating system's performance from first-principles
* [scanopy/scanopy](https://github.com/scanopy/scanopy) - Network diagrams that update themselves
* [zensical/zensical](https://github.com/zensical/zensical) - A modern static site generator by the Material for MkDocs team
* [ImageOptim/gifski](https://github.com/ImageOptim/gifski) - GIF encoder based on libimagequant (pngquant). Squeezes maximum possible quality from the awful GIF format.
* [ReagentX/imessage-exporter](https://github.com/ReagentX/imessage-exporter) - Export iMessage data + run iMessage Diagnostics
* [autumnai/leaf](https://github.com/autumnai/leaf) - Open Machine Intelligence Framework for Hackers. (GPU/CPU)
* [tonarino/innernet](https://github.com/tonarino/innernet) - A private network system that uses WireGuard under the hood.
* [dtolnay/thiserror](https://github.com/dtolnay/thiserror) - derive(Error) for struct and enum error types
* [massalabs/massa](https://github.com/massalabs/massa) - The Decentralized and Scaled Blockchain
* [QuipNetwork/quip-node-manager](https://github.com/QuipNetwork/quip-node-manager) - A simple GUI client to manage a Quip Network node
* [akitaonrails/ai-memory](https://github.com/akitaonrails/ai-memory) - Solution for long term memory for agent coding CLIs and to facilitate handoff between different agent vendors
* [Pagefind/pagefind](https://github.com/Pagefind/pagefind) - Static low-bandwidth search at scale
* [sachaos/viddy](https://github.com/sachaos/viddy) - 👀 A modern watch command. Time machine and pager etc.
* [biliup/biliup](https://github.com/biliup/biliup) - 自动直播录制、投稿、twitch、ytb频道搬运工具。命令行投稿(B站)和视频下载工具，提供多种登录方式，支持多p。
* [fzyzcjy/flutter_rust_bridge](https://github.com/fzyzcjy/flutter_rust_bridge) - Flutter/Dart <-> Rust binding generator, feature-rich, but seamless and simple.
* [spaceandtimefdn/sxt-proof-of-sql](https://github.com/spaceandtimefdn/sxt-proof-of-sql) - Space and Time | Proof of SQL
* [EmbarkStudios/kajiya](https://github.com/EmbarkStudios/kajiya) - 💡 Experimental real-time global illumination renderer 🦀 *(archived)*
* [amadeusprotocol/node](https://github.com/amadeusprotocol/node)
* [junhoyeo/tokscale](https://github.com/junhoyeo/tokscale) - 🛰️ Track token usage across AI coding agents from your terminal. 🏅 Global leaderboard with trillions of tokens tracked.
* [supabase-community/postgres-language-server](https://github.com/supabase-community/postgres-language-server) - A Language Server for Postgres
* [mit-pdos/noria](https://github.com/mit-pdos/noria) - Fast web applications through dynamic, partially-stateful dataflow
* [amber-lang/amber](https://github.com/amber-lang/amber) - 💎 Amber the programming language compiled to Bash/Ksh/Zsh
* [pgmq/pgmq](https://github.com/pgmq/pgmq) - A lightweight message queue. Like AWS SQS and RSMQ but on Postgres.
* [microsoft/coreutils](https://github.com/microsoft/coreutils) - Coreutils for Windows: Installer & Packaging
* [crablang/crab](https://github.com/crablang/crab) - A community fork of a language named after a plant fungus. All of the memory-safe features you love, now with 100% less bureaucracy!
* [unicity-aos/capsule-react](https://github.com/unicity-aos/capsule-react) - ReAct loop coordinator. Stateless state machine for reasoning-and-action cycle. Part of Unicity AOS.
* [huggingface/text-embeddings-inference](https://github.com/huggingface/text-embeddings-inference) - A blazing fast inference solution for text embeddings models
* [ArthurBrussee/brush](https://github.com/ArthurBrussee/brush) - 3D Reconstruction for all
* [shuakami/qq-chat-exporter](https://github.com/shuakami/qq-chat-exporter) - 🚀 QQ聊天记录、表情包导出工具 | 自动化提取图片/文字/图片消息，支持TXT/JSON导出，高效备份，支持NT QQ
* [withcoral/coral](https://github.com/withcoral/coral) - One SQL interface over APIs, files, and live sources — built for agents.
* [triwinds/ns-emu-tools](https://github.com/triwinds/ns-emu-tools) - 一个用于安装/更新 NS 模拟器的工具
* [SaladDay/cc-switch-cli](https://github.com/SaladDay/cc-switch-cli) - ⭐️ A cross-platform CLI All-in-One assistant tool for Claude Code, Codex & Gemini CLI.
* [matter-labs/zksync](https://github.com/matter-labs/zksync) - zkSync: trustless scaling and privacy engine for Ethereum
* [ProvableHQ/leo](https://github.com/ProvableHQ/leo) - 🦁 The Leo Programming Language. A Programming Language for Formally Verified, Zero-Knowledge Applications
* [greenbone/openvas-scanner](https://github.com/greenbone/openvas-scanner) - This repository contains the scanner component for Greenbone Community Edition.
* [anordal/shellharden](https://github.com/anordal/shellharden) - The corrective bash syntax highlighter
* [tokio-rs/mini-redis](https://github.com/tokio-rs/mini-redis) - Incomplete Redis client and server implementation using Tokio - for learning purposes only
* [tokio-rs/topcoat](https://github.com/tokio-rs/topcoat) - A batteries-included framework for building web apps
* [borgo-lang/borgo](https://github.com/borgo-lang/borgo) - Borgo is a statically typed language that compiles to Go.
* [smoltcp-rs/smoltcp](https://github.com/smoltcp-rs/smoltcp) - a smol tcp/ip stack
* [taikoxyz/taiko-mono](https://github.com/taikoxyz/taiko-mono) - A based rollup protocol for Ethereum🥁
* [zesterer/chumsky](https://github.com/zesterer/chumsky) - [Chumsky has moved to Codeberg!] Write expressive, high-performance parsers with ease. *(archived)*
* [openai/harmony](https://github.com/openai/harmony) - Renderer for the harmony response format to be used with gpt-oss
* [trifectatechfoundation/sudo-rs](https://github.com/trifectatechfoundation/sudo-rs) - A memory safe implementation of sudo and su.
* [mortdeus/solana-copy-sniper-mev-trading-bot](https://github.com/mortdeus/solana-copy-sniper-mev-trading-bot) - 🆓Free High speed solana mev arbitrage Sniper Copy Trading Bot, gRPC shred stream Pumpfun Bundler, Pumpfun Contract, Yellowston Geyser, token launcher, AI raydium pool creator, volume, sandwich, raydium swap bot, pumpswap auto Volume, Maker bot, 0xblock, best 0 block solana trading bot solana trading bot solana trading bot solana trading bot
* [rivet-dev/agentos](https://github.com/rivet-dev/agentos) - Give agents an operating system as a library. Runs in your existing backend – no sandboxes, VMs, or SaaS. Powered by WebAssembly & V8 isolates.
* [typedb/typedb](https://github.com/typedb/typedb) - TypeDB: Built for systems, not records
* [denoland/celld](https://github.com/denoland/celld) - self-hosted, distributed Durable Objects
* [imazen/imageflow](https://github.com/imazen/imageflow) - High-performance image manipulation for web servers. Includes imageflow_server, imageflow_tool, and libimageflow
* [orhun/binsider](https://github.com/orhun/binsider) - Analyze ELF binaries like a boss 😼🕵️‍♂️
* [facebook/buck2](https://github.com/facebook/buck2) - Build system, successor to Buck
* [mstange/samply](https://github.com/mstange/samply) - Command-line sampling profiler for macOS, Linux, and Windows
* [witnessmenow/ESP32-Cheap-Yellow-Display](https://github.com/witnessmenow/ESP32-Cheap-Yellow-Display) - Building a community around a cheap ESP32 Display with a touch screen
* [restatedev/restate](https://github.com/restatedev/restate) - Restate is the platform for building resilient applications that tolerate all infrastructure faults w/o the need for a PhD.
* [xingkongliang/skills-manager](https://github.com/xingkongliang/skills-manager) - A lightweight desktop app to manage, sync, and organize AI agent skills across 50+ coding tools — Claude Code, Codex, Cursor, Copilot, Gemini CLI, and more.
* [linebender/vello](https://github.com/linebender/vello) - A GPU compute-centric 2D renderer.
* [astrid-runtime/sdk-rust](https://github.com/astrid-runtime/sdk-rust) - Rust SDK for building Astrid capsules.
* [solana-labs/solana-program-library](https://github.com/solana-labs/solana-program-library) - A collection of Solana programs maintained by Solana Labs *(archived)*
* [ivanceras/svgbob](https://github.com/ivanceras/svgbob) - Convert your ascii diagram scribbles into happy little SVG
* [nubjs/nub](https://github.com/nubjs/nub) - The fast all-in-one Node.js toolkit
* [lencx/nofwl](https://github.com/lencx/nofwl) - NoFWL Desktop Application
* [lumina-ai-inc/chunkr](https://github.com/lumina-ai-inc/chunkr) - Vision infrastructure to turn complex documents into RAG/LLM-ready data
* [agentclientprotocol/agent-client-protocol](https://github.com/agentclientprotocol/agent-client-protocol) - A protocol for connecting any editor to any agent
* [arxanas/git-branchless](https://github.com/arxanas/git-branchless) - High-velocity, monorepo-scale workflow for Git
* [cozodb/cozo](https://github.com/cozodb/cozo) - A transactional, relational-graph-vector database that uses Datalog for query. The hippocampus for AI!
* [DioxusLabs/blitz](https://github.com/DioxusLabs/blitz) - A radically modular HTML/CSS rendering engine
* [marcelroed/gigatoken](https://github.com/marcelroed/gigatoken) - Language model tokenization at GB/s
* [linebender/resvg](https://github.com/linebender/resvg) - An SVG rendering library.
* [Fredolx/open-tv](https://github.com/Fredolx/open-tv) - Ultra-fast, simple and powerful cross-platform IPTV app
* [johnlui/PPHC](https://github.com/johnlui/PPHC) - 📙《高并发的哲学原理》开源图书（CC BY-NC-ND）https://pphc.lvwenhan.com
* [YS-L/csvlens](https://github.com/YS-L/csvlens) - Command line csv viewer
* [RedisJSON/RedisJSON](https://github.com/RedisJSON/RedisJSON) - RedisJSON - a JSON data type for Redis
* [wild-linker/wild](https://github.com/wild-linker/wild) - A very fast linker for Linux
* [nolabs-ai/nono](https://github.com/nolabs-ai/nono) - secure multiplexed execution paths for agents - zero trust, zero setup, zero latency.
* [chronotope/chrono](https://github.com/chronotope/chrono) - Date and time library for Rust
* [servo/pathfinder](https://github.com/servo/pathfinder) - A fast, practical GPU rasterizer for fonts and vector graphics
* [touchHLE/touchHLE](https://github.com/touchHLE/touchHLE) - High-level emulator for iPhone OS apps. This repo is used for issues, releases and CI. Submit patches at: https://review.gerrithub.io/admin/repos/touchHLE/touchHLE
* [safetensors/safetensors](https://github.com/safetensors/safetensors) - Simple, safe way to store and distribute tensors
* [fastly/pushpin](https://github.com/fastly/pushpin) - A proxy server for adding push to your API, used at the core of Fastly's Fanout service
* [misprit7/computerraria](https://github.com/misprit7/computerraria) - A fully compliant RISC-V computer made inside the game Terraria
* [golutra/golutra](https://github.com/golutra/golutra) - Multi-agent AI orchestration platform for automation, workflows, and developer tools. Golutra transforms Codex, Claude Code, and OpenClaw into a unified agent system with parallel execution, task orchestration, long-running workflows, and AI productivity workspace.
* [Findomain/Findomain](https://github.com/Findomain/Findomain) - The fastest and complete solution for domain recognition. Supports screenshoting, port scan, HTTP check, data import from other tools, subdomain monitoring, alerts via Discord, Slack and Telegram, multiple API Keys for sources and much more.
* [vlcn-io/cr-sqlite](https://github.com/vlcn-io/cr-sqlite) - Convergent, Replicated SQLite. Multi-writer and CRDT support for SQLite
* [zhom/donutbrowser](https://github.com/zhom/donutbrowser) - Simple Yet Powerful Anti-Detect Browser 🍩
* [DeterminateSystems/nix-installer](https://github.com/DeterminateSystems/nix-installer) - Install Nix and flakes with the fast and reliable Determinate Nix Installer, with over 7 million installs.
* [GRVYDEV/Project-Lightspeed](https://github.com/GRVYDEV/Project-Lightspeed) - A self contained OBS -> FTL -> WebRTC live streaming server. Comprised of 3 parts once configured anyone can achieve sub-second OBS to the browser livestreaming
* [zhongbai2333/Tomato-Novel-Downloader](https://github.com/zhongbai2333/Tomato-Novel-Downloader) - 番茄小说下载器不精简版
* [gaoyifan/china-operator-ip](https://github.com/gaoyifan/china-operator-ip) - 中国运营商IPv4/IPv6地址库-每日更新
* [LGFae/swww](https://github.com/LGFae/swww) - A Solution to your Wayland Wallpaper Woes *(archived)*
* [oxidecomputer/hubris](https://github.com/oxidecomputer/hubris) - A lightweight, memory-protected, message-passing kernel for deeply embedded systems.
* [GetFirefly/firefly](https://github.com/GetFirefly/firefly) - An alternative BEAM implementation, designed for WebAssembly *(archived)*
* [mTvare6/hello-world.rs](https://github.com/mTvare6/hello-world.rs) - 🚀Memory safe, blazing fast, configurable, minimal hello world written in rust(🚀) in a few lines of code with few(1247🚀) dependencies🚀
* [autozimu/LanguageClient-neovim](https://github.com/autozimu/LanguageClient-neovim) - Language Server Protocol (LSP) support for vim and neovim.
* [icedland/iced](https://github.com/icedland/iced) - Blazing fast and correct x86/x64 disassembler, assembler, decoder, encoder for Rust, .NET, Java, Python, Lua
* [smallcloudai/refact](https://github.com/smallcloudai/refact) - AI Agent that handles engineering tasks end-to-end: integrates with developers’ tools, plans, executes, and iterates until it achieves a successful result. *(archived)*
* [JamieMason/ImageOptim-CLI](https://github.com/JamieMason/ImageOptim-CLI) - Make optimisation of images part of your automated build process
* [Myriad-Dreamin/tinymist](https://github.com/Myriad-Dreamin/tinymist) - Tinymist [ˈtaɪni mɪst] is an integrated language service for Typst [taɪpst].
* [TrustTunnel/TrustTunnel](https://github.com/TrustTunnel/TrustTunnel) - Modern, fast and obfuscated VPN protocol
* [haimgel/display-switch](https://github.com/haimgel/display-switch) - Turn a $30 USB switch into a full-featured multi-monitor KVM switch
* [carthage-software/mago](https://github.com/carthage-software/mago) - Mago is a toolchain for PHP that aims to provide a set of tools to help developers write better code.
* [kvcache-ai/AgentENV](https://github.com/kvcache-ai/AgentENV) - AgentENV (AENV) is a distributed platform for running agent environments at scale.
* [tursodatabase/agentfs](https://github.com/tursodatabase/agentfs) - The filesystem for agents.
* [servo/webrender](https://github.com/servo/webrender) - A GPU-based renderer for the web
* [LanRhyme/MicYou](https://github.com/LanRhyme/MicYou) - MicYou is a powerful tool that turns your Android device into a high-quality microphone for your PC.
* [Mesh-LLM/mesh-llm](https://github.com/Mesh-LLM/mesh-llm) - Distributed AI/LLM for the people. Share compute privately or publicly to power your agents and chat.
* [Lagrange-Labs/deep-prove](https://github.com/Lagrange-Labs/deep-prove) - Framework to prove inference of ML models blazingly fast
* [supabase/pg_graphql](https://github.com/supabase/pg_graphql) - GraphQL support for PostgreSQL
* [flaneur2020/pua-lang](https://github.com/flaneur2020/pua-lang) - a dialect of The Monkey Programming Language
* [vadimcn/codelldb](https://github.com/vadimcn/codelldb) - A VSCode debugger extension for native code, powered by LLDB.
* [mierak/rmpc](https://github.com/mierak/rmpc) - A modern, configurable, terminal based MPD Client with album art support via various terminal image protocols
* [jehna/humanify](https://github.com/jehna/humanify) - Deobfuscate Javascript code using ChatGPT
* [matter-labs/zksync-era](https://github.com/matter-labs/zksync-era) - zkSync era
* [SilasMarvin/lsp-ai](https://github.com/SilasMarvin/lsp-ai) - LSP-AI is an open-source language server that serves as a backend for AI-powered functionality, designed to assist and empower software engineers, not replace them.
* [agent-of-empires/agent-of-empires](https://github.com/agent-of-empires/agent-of-empires) - Manage multiple Claude Code, OpenCode agents from either TUI or Web for easy access on mobile. Also supports Mistral Vibe, Codex CLI, Gemini CLI, Pi.dev, Copilot CLI, Factory Droid Coding.
* [edison7009/EchoBird](https://github.com/edison7009/EchoBird) - One-click install + model switch:Claude Code,Codex CLI (OpenAI), Grok Build (xAI), DeepSeek Harness, Kimi Code (Moonshot) ,Qwen Code,Aider,OpenCode,MiMo Code (Xiaomi),ZCode (Z.AI),OpenClaw,Pi,OpenScience,Vibe-Trading,Claude Desktop (3P profile),ChatGPT desktop,OpenCode Desktop,
* [graphprotocol/graph-node](https://github.com/graphprotocol/graph-node) - Graph Node indexes data from blockchains such as Ethereum and serves it over GraphQL
* [qltysh/qlty](https://github.com/qltysh/qlty) - 💎 Code quality CLI for universal linting, auto-formatting, security scanning, and maintainability
* [dtolnay/cargo-expand](https://github.com/dtolnay/cargo-expand) - Subcommand to show result of macro expansion
* [imsnif/diskonaut](https://github.com/imsnif/diskonaut) - Terminal disk space navigator 🔭
* [mikeyobrien/ralph-orchestrator](https://github.com/mikeyobrien/ralph-orchestrator) - An improved implementation of the Ralph Wiggum technique for autonomous AI agent orchestration
* [timescale/pgvectorscale](https://github.com/timescale/pgvectorscale) - Postgres extension for vector search (DiskANN), complements pgvector for performance and scale. Postgres OSS licensed.
* [evilsocket/cake](https://github.com/evilsocket/cake) - Distributed inference for mobile, desktop and server.
* [Hugo-Dz/spritefusion-pixel-snapper](https://github.com/Hugo-Dz/spritefusion-pixel-snapper) - A tool to snap pixels to a perfect grid. Designed to fix messy and inconsistent pixel art generated by AI.
* [xintaofei/codeg](https://github.com/xintaofei/codeg) - Collaborative multi-agent AI coding workspace: aggregate sessions from Claude Code, Codex, OpenCode, Pi, Grok Build, etc. Desktop app, self-hosted server, or Docker.
* [shshemi/tabiew](https://github.com/shshemi/tabiew) - A lightweight TUI application to view and query tabular data files, such as CSV, TSV, and parquet.
* [guillaume-be/rust-bert](https://github.com/guillaume-be/rust-bert) - Rust native ready-to-use NLP pipelines and transformer-based models (BERT, DistilBERT, GPT2,...)
* [bvaisvil/zenith](https://github.com/bvaisvil/zenith) - Zenith - sort of like top or htop but with zoom-able charts, CPU, GPU, network, and disk usage
* [leftwm/leftwm](https://github.com/leftwm/leftwm) - A tiling window manager for Adventurers
* [tsukinaha/tsukimi](https://github.com/tsukinaha/tsukimi) - A simple third-party Jellyfin client for Linux
* [glzr-io/zebar](https://github.com/glzr-io/zebar) - Zebar is a tool for creating customizable and cross-platform taskbars, desktop widgets, and popups.
* [Veirt/weathr](https://github.com/Veirt/weathr) - a terminal weather app with ascii animation
* [Barre/ZeroFS](https://github.com/Barre/ZeroFS) - ZeroFS: A log-structured filesystem for S3. ZeroFS serves S3-compatible buckets as POSIX filesystems over NFS and 9P, or as raw block devices over NBD.
* [tox-dev/pipdeptree](https://github.com/tox-dev/pipdeptree) - A command line utility to display dependency tree of the installed Python packages
* [WecomTeam/wecom-cli](https://github.com/WecomTeam/wecom-cli) - 企业微信开放平台命令行工具 — 让人类和 AI Agent 都能在终端中操作企业微信
* [headwaymaps/headway](https://github.com/headwaymaps/headway) - Self-hostable maps stack, powered by OpenStreetMap.
* [vercel-labs/opensrc](https://github.com/vercel-labs/opensrc) - Fetch source code for npm packages to give AI coding agents deeper context
* [jsr-io/jsr](https://github.com/jsr-io/jsr) - The open-source package registry for modern JavaScript and TypeScript
* [luminal-ai/luminal](https://github.com/luminal-ai/luminal) - Inference at the speed of light.
* [nashsu/AutoCLI](https://github.com/nashsu/AutoCLI) - AutoCLI is a Blazing fast, memory-safe command-line tool — Fetch information from any website with a single command. Covers Twitter/X, Reddit, YouTube, HackerNews, Bilibili, Zhihu, Xiaohongshu, and 55+ sites, with support for controlling Electron desktop apps, integrating local CLI tools (gh, docker, kubectl), now powered by AutoCLI.ai .
* [salsa-rs/salsa](https://github.com/salsa-rs/salsa) - A generic framework for on-demand, incrementalized computation. Inspired by adapton, glimmer, and rustc's query system.
* [qxcnm/Codex-Manager](https://github.com/qxcnm/Codex-Manager) - 一个Codex cli 账号管理与切换工具。为 Codex cli提供本地网关转发。
* [yynxxxxx/Codex-X](https://github.com/yynxxxxx/Codex-X) - OpenAI Codex 桌面端/CLI 的可视化管理工具，具有Provider/API 切换、会话同步、提示词注入、Skills/MCP 管理、TOML 配置可视化的跨平台工具。
* [orhun/kmon](https://github.com/orhun/kmon) - Linux Kernel Manager and Activity Monitor 🐧💻
* [Gaoshu705/QzoneArchive](https://github.com/Gaoshu705/QzoneArchive) - 将 QQ 空间历史动态、照片、视频与互动记录安全归档到本地的桌面 / 移动端工具。
* [pkolaczk/fclones](https://github.com/pkolaczk/fclones) - Efficient Duplicate File Finder
* [orbitinghail/sqlsync](https://github.com/orbitinghail/sqlsync) - SQLSync is a collaborative offline-first wrapper around SQLite. It is designed to synchronize web application state between users, devices, and the edge.
* [altsem/gitu](https://github.com/altsem/gitu) - A TUI Git client inspired by Magit
* [BurntSushi/jiff](https://github.com/BurntSushi/jiff) - A datetime library for Rust that encourages you to jump into the pit of success.
* [martin-olivier/airgorah](https://github.com/martin-olivier/airgorah) - A WiFi security auditing software mainly based on aircrack-ng tools suite
* [Polymarket/polymarket-cli](https://github.com/Polymarket/polymarket-cli)
* [pop-os/pop](https://github.com/pop-os/pop) - A project for managing all Pop!_OS sources
* [numaproj/numaflow](https://github.com/numaproj/numaflow) - Kubernetes-native platform to run massively parallel data/streaming jobs
* [pythops/impala](https://github.com/pythops/impala) - 🛜 TUI for managing wifi on Linux
* [eycorsican/leaf](https://github.com/eycorsican/leaf) - A versatile and efficient proxy framework.
* [DefGuard/defguard](https://github.com/DefGuard/defguard) - Zero-Trust access management with true WireGuard® 2FA/MFA
* [paritytech/polkadot-sdk](https://github.com/paritytech/polkadot-sdk) - The Parity Polkadot Blockchain SDK
* [cheatsheet1999/CloudCollection](https://github.com/cheatsheet1999/CloudCollection) - Notes for Software Engineers on infrastructure and distributed systems. Covers common data structure and algorithms, web concepts, and more!
* [RazrFalcon/cargo-bloat](https://github.com/RazrFalcon/cargo-bloat) - Find out what takes most of the space in your executable.
* [aws/aws-lambda-web-adapter](https://github.com/aws/aws-lambda-web-adapter) - Run web applications on AWS Lambda
* [bytecodealliance/javy](https://github.com/bytecodealliance/javy) - JS to WebAssembly toolchain
* [matthart1983/netwatch](https://github.com/matthart1983/netwatch) - Real-time network diagnostics in your terminal. One command, zero config, instant visibility.
* [agersant/polaris](https://github.com/agersant/polaris) - Polaris is a music streaming application, designed to let you enjoy your music collection from any computer or mobile device.
* [TeXitoi/structopt](https://github.com/TeXitoi/structopt) - Parse command line arguments by defining a struct.
* [b-nnett/goose](https://github.com/b-nnett/goose) - Goose Swift proof-of-concept README *(archived)*
* [pacifio/atlas](https://github.com/pacifio/atlas) - Source control for agents. Use multiple coding agents, track their changes and query them in one place
* [microsoft/litebox](https://github.com/microsoft/litebox) - A security-focused library OS supporting kernel- and user-mode execution
* [leookun/cursor-byok](https://github.com/leookun/cursor-byok) - cursor-byok is a local implementation of Cursor's backend. https://docs.leokun.cn/
* [ihciah/shadow-tls](https://github.com/ihciah/shadow-tls) - A proxy to expose real tls handshake to the firewall
* [sharkdp/numbat](https://github.com/sharkdp/numbat) - A statically typed programming language for scientific computations with first class support for physical dimensions and units
* [libkrun/libkrun](https://github.com/libkrun/libkrun) - A dynamic library providing Virtualization-based process isolation capabilities
* [rust-embedded/embedded-hal](https://github.com/rust-embedded/embedded-hal) - A Hardware Abstraction Layer (HAL) for embedded systems
* [TeamFlos/phira](https://github.com/TeamFlos/phira)
* [google/forma](https://github.com/google/forma) - An efficient vector-graphics renderer *(archived)*
* [rust-cross/cargo-zigbuild](https://github.com/rust-cross/cargo-zigbuild) - Compile Cargo project with zig as linker
* [kubie-org/kubie](https://github.com/kubie-org/kubie) - A more powerful alternative to kubectx and kubens
* [servo/html5ever](https://github.com/servo/html5ever) - High-performance browser-grade HTML5 parser
* [theopfr/somo](https://github.com/theopfr/somo) - A human-friendly alternative to netstat for socket and port monitoring on Linux and macOS.
* [samizdatco/skia-canvas](https://github.com/samizdatco/skia-canvas) - A multi-threaded, GPU-powered, 2D vector graphics environment for Node.js
* [idootop/open-xiaoai](https://github.com/idootop/open-xiaoai) - 🔊 让小爱音箱「听见你的声音」，解锁无限可能。 *(archived)*
* [sqlpage/SQLPage](https://github.com/sqlpage/SQLPage) - Fast SQL-only data application builder. Automatically build a UI on top of SQL queries.
* [kognise/arpchat](https://github.com/kognise/arpchat) - Answering the question nobody asked: what if you wanted to text your friends using only ARP?
* [ntsc-rs/ntsc-rs](https://github.com/ntsc-rs/ntsc-rs) - Free, open-source VHS effect. Standalone application + plugin (After Effects, Premiere, and OpenFX).
* [SpikeHD/Dorion](https://github.com/SpikeHD/Dorion) - Tiny alternative Discord client with a smaller footprint, snappier startup, themes, plugins and more!
* [git-ai-project/git-ai](https://github.com/git-ai-project/git-ai) - A Git extension for tracking the AI-generated code in your repos
* [Barre/privaxy](https://github.com/Barre/privaxy) - Privaxy is the next generation tracker and advertisement blocker. It blocks ads and trackers by MITMing HTTP(s) traffic. Also check out my new project, https://github.com/Barre/ZeroFS
* [sekey/sekey](https://github.com/sekey/sekey) - Use Touch ID / Secure Enclave for SSH Authentication!
* [snapview/tokio-tungstenite](https://github.com/snapview/tokio-tungstenite) - Future-based Tungstenite for Tokio. Lightweight stream-based WebSocket implementation
* [facebookincubator/below](https://github.com/facebookincubator/below) - A time traveling resource monitor for modern Linux systems
* [weggli-rs/weggli](https://github.com/weggli-rs/weggli) - weggli is a fast and robust semantic search tool for C and C++ codebases. It is designed to help security researchers identify interesting functionality in large codebases.
* [uber/piranha](https://github.com/uber/piranha) - A tool for refactoring code related to feature flag APIs
* [zdz/ServerStatus-Rust](https://github.com/zdz/ServerStatus-Rust) - ✨ Rust 版 ServerStatus 探针、威力加强版
* [bytecodealliance/rustix](https://github.com/bytecodealliance/rustix) - Safe Rust bindings to POSIX-ish APIs
* [fishfolk/jumpy](https://github.com/fishfolk/jumpy) - Tactical 2D shooter in fishy pixels style. Made with Rust-lang 🦀 and Bevy 🪶
* [housleyjk/ws-rs](https://github.com/housleyjk/ws-rs) - Lightweight, event-driven WebSockets for Rust.
* [time-rs/time](https://github.com/time-rs/time) - Date and time handling in Rust.
* [rustsbi/rustsbi](https://github.com/rustsbi/rustsbi) - RISC-V Supervisor Binary Interface (RISC-V SBI) library in Rust; runs on M or HS mode; good support for embedded Rust ecosystem. For binary download see prototyper folder.
* [alibaba/GaiaX](https://github.com/alibaba/GaiaX) - 动态模板引擎是一套轻量化、跨平台、高性能的纯原生移动端卡片渲染动态化解决方案
* [TeXitoi/keyberon](https://github.com/TeXitoi/keyberon) - A rust crate to create a pure rust keyboard firmware.
* [greyblake/whatlang-rs](https://github.com/greyblake/whatlang-rs) - Natural language detection library for Rust. Try demo online: https://whatlang.org/
* [EmbarkStudios/rust-ecosystem](https://github.com/EmbarkStudios/rust-ecosystem) - Rust wants & tracking for Embark 🦀 *(archived)*
* [hackndev/zinc](https://github.com/hackndev/zinc) - The bare metal stack for rust *(archived)*
* [rust-mobile/android-rs-glue](https://github.com/rust-mobile/android-rs-glue) - Glue between Rust and Android *(archived)*
* [Hasnayeen/larks](https://github.com/Hasnayeen/larks) - https://github.com/Hasnayeen/goodwork
