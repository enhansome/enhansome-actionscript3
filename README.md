[<img src="https://rawgit.com/hgupta9/awesome-actionscript3/master/AS3_AIR.png" align="right" width="150">](https://www.adobe.com/products/air.html)

# Awesome ActionScript 3 with stars

> A curated list of awesome libraries and components for ActionScript 3 and Adobe AIR.

[Adobe AIR](https://en.wikipedia.org/wiki/Adobe_AIR) provides a single set of APIs to build cross-platform desktop/mobile applications and games. [ActionScript 3](https://en.wikipedia.org/wiki/ActionScript) is the programming language for AIR. Powerful native functionality such as file system, SQLite, sensors are included by default. To add missing functionality, you can build ANEs (Air Native Extensions) coded in the native language (eg VC++ for Windows, Java for Android, Swift/Objective-C for iOS). To build mobile apps/games with GPU-rendered graphics, use the [Starling](https://gamua.com/starling/) framework and optionally the [Feathers UI](https://feathersui.com/). Adobe AIR is very popular in the mobile gaming space.

Contributions welcome. To add a useful project simply create an [Issue](https://github.com/hgupta9/awesome-actionscript3/issues) ⭐ 274 | 🐛 2 | 📅 2022-11-12.

## Contents

* [Development Tools](#development-tools)
* [Frameworks](#frameworks)
* [User Interface](#user-interface)
* [Multimedia](#multimedia)
* [Database](#database)
* [File Formats](#file-formats)
* [Networking](#networking)
* [Utilities](#utilities)
* [Runtimes](#runtimes)
* [AIR Native Extensions](#air-native-extensions)

## Development Tools

*This section includes commercial tools as well as free/open source tools.*

#### Code Editors

* [FlashDevelop](http://flashdevelop.org/) - Premiere free & open-source IDE for AS3 & AIR, with code completion, debugging, and more.
* [Powerflasher FDT](http://fdt.powerflasher.com/) - Commercial IDE built on the Eclipse platform for development of Adobe Flash/AIR content.
* [Adobe Flash Builder](https://www.adobe.com/products/flash-builder.html) - Commercial IDE for building applications on the Flex framework (with advanced debugging tools).
* [Moonshine IDE](http://moonshine-ide.com/) - Moonshine is a free and open source middleweight IDE built with ActionScript 3 for ActionScript 3, Apache Flex®, Apache FlexJS® and Feathers development with Cloud and Desktop support.
* [IntelliJ IDEA](https://www.jetbrains.com/help/idea/building-actionscript-and-flex-applications.html) - Commercial IDE that supports many different languages including AS3.
* [Visual Studio Code](https://as3mxml.com/) - An AS3 & MXML language extension for Visual Studio Code. Runs on Windows, macOS, and Linux.

#### Live Debuggers

* [De-Monster Debugger (Starling)](https://github.com/joshtynjala/monsterdebugger-client-starling) ⚠️ Archived - Fork of De-Monster Debugger with support for Starling Framework.
* [De-Monster Debugger](https://github.com/MrTact/monsterdebugger) ⭐ 8 | 🐛 0 | 🌐 ActionScript | 📅 2012-07-27 - Advanced tool to debug graphics and data from a live AIR application.
* [Adobe Scout](https://www.adobe.com/products/scout.html) - Advanced visual profiling and debugging tool for AIR apps & games (supports Stage3D).

#### Asset Creators

* [Adobe Animate CC](https://www.adobe.com/products/animate.html) - Premiere vector graphics and animation toolset for vector/spritesheet creation.
* [TILED Map Editor](http://www.mapeditor.org/) - Flexible tile map editor compatible with various AS3 game engines.
* [FlashMovieClipConverter](https://github.com/zenrobin/FlashMovieClipConverter) ⭐ 24 | 🐛 5 | 🌐 ActionScript | 📅 2013-10-02 - Converts a Flash MovieClip to a Starling IAnimatable Sprite.

#### SWF Obfuscators

* [secureSWF](http://www.kindi.com/) - Commercial AS3/AIR obfuscator with renaming, asset encryption and automatic code optimization.
* [irrFuscator](http://www.ambiera.com/irrfuscator/) - Commercial AS3 obfuscator for Flash and Flex SWF files.

#### SWF Inspectors

* [SWFWire](https://github.com/magicalhobo/SWFWire) ⭐ 255 | 🐛 21 | 🌐 ActionScript | 📅 2018-09-10 - Advanced SWF Decompiler, Inspector and Debugger Tools ([website](http://www.swfwire.com/)).
* [Velocity9](https://github.com/velocity9/Inspector) - Basic SWF Inspector.

#### SWF Decompilers

* [AS3Sorcerer](http://www.as3sorcerer.com/) - Premiere AS3 decompiler with 99% decompilation accuracy (supports SWF/SWC, Alchemy opcodes).
* [Sothink Decompiler](http://www.sothink.com/product/flashdecompiler/) - Advanced decompiler for AS2/AS3 (supports asset extraction and conversion of SWF to FLA/Flex).

#### ANE Dev Tools

* [Swift-IOS-ANE](https://github.com/tuarua/Swift-IOS-ANE) ⭐ 61 | 🐛 0 | 🌐 Swift | 📅 2026-01-31 - ANE starter kit written in Swift 3 for iOS 10 .
* [FreSharp](https://github.com/tuarua/FreSharp) ⭐ 51 | 🐛 2 | 🌐 C# | 📅 2020-10-18 - Build ANEs using C# with this C# wrapper for FlashRuntimeExtensions .

## Frameworks

#### MVC Frameworks

* [Robotlegs](https://github.com/robotlegs/robotlegs-framework) ⭐ 962 | 🐛 19 | 🌐 ActionScript | 📅 2020-06-16 - Dependency injection, module/view/command management framework for Flash.
* [StarlingMVC](https://github.com/CreativeBottle/starlingMVC) ⭐ 125 | 🐛 10 | 🌐 ActionScript | 📅 2017-04-24 - IOC Framework for Starling based games.
* [PureMVC](https://github.com/PureMVC/puremvc-as3-standard-framework) ⭐ 124 | 🐛 1 | 🌐 HTML | 📅 2018-10-27 - Industry-standard MVC framework for Flash ([multicore](https://github.com/PureMVC/puremvc-as3-multicore-framework) ⭐ 57 | 🐛 0 | 🌐 HTML | 📅 2018-10-27).
* [Hummingbird](https://github.com/flashapi/hummingbird) ⚠️ Archived - Build and deploy robust MVC applications for AS3, Mobile and the Starling Framework.
* [Somacore](https://github.com/soundstep/somacore_framework) ⭐ 21 | 🐛 0 | 🌐 ActionScript | 📅 2011-12-14 - Lightweight event-based AS3 MVC framework.
* [Kote](https://github.com/whitered/Kote) ⭐ 4 | 🐛 0 | 🌐 ActionScript | 📅 2013-03-18 - Fast and lightweight MVC framework that brings together the best of PureMVC and as3-signals.
* [Apollo](https://github.com/LaurentZuijdwijk/Apollo) ⚠️ Archived - Dependency injection and messaging framework, which can be used as the basis for MVC projects.

#### UI Frameworks

* [Starling](https://gamua.com/starling/) - High-performance 2D graphics engine built on Stage3D. API identical to Flash API. ([github](https://github.com/Gamua/Starling-Framework) ⭐ 3,085 | 🐛 97 | 🌐 ActionScript | 📅 2026-07-17, [help](http://wiki.starling-framework.org/start)).
* [Feathers UI](https://feathersui.com/) - User interface components for Starling Framework ([github](https://github.com/BowlerHatLLC/feathers) ⭐ 915 | 🐛 169 | 🌐 ActionScript | 📅 2026-01-22, [help](https://feathersui.com/help/index.html)).
* [Swiz](https://github.com/swiz/swiz-framework) ⭐ 225 | 🐛 18 | 🌐 ActionScript | 📅 2013-06-19 - Brutally simple micro-architecture for creating RIAs with AS3 and Adobe Flex.
* [Elastic-Lists](https://github.com/MoritzStefaner/Elastic-Lists) ⭐ 108 | 🐛 5 | 🌐 ActionScript | 📅 2011-06-03 - Fluid and powerful interface for facet browsing.
* [AS3Commons UI](https://github.com/AS3Commons/as3commons-ui) ⭐ 61 | 🐛 2 | 🌐 ActionScript | 📅 2011-12-21 - Layouting, focus and keyboard management framework.
* [Flow](https://github.com/artman/Flow) ⭐ 30 | 🐛 0 | 🌐 ActionScript | 📅 2014-08-30 - Layout, effects, data binding and remoting framework to be used instead of Flex.
* [Hiddenwood](https://github.com/raweden/Project-Hiddenwood) ⚠️ Archived - User interface library developed for a web app project, written in AS3 and in a MVC pattern.
* [Apache Flex®](https://flex.apache.org/) - The Apache Flex® SDK is the evolution of the popular Adobe Flex SDK. The Apache Flex® SDK is an application development framework for easily building Flash-based applications for mobile devices, web browsers, and desktop platforms.
* [Apache Royale®](http://royale.apache.org/) - The Apache Royale® project is developing a next-generation of the Apache Flex® SDK. Royale has the goal of allowing applications developed in MXML and ActionScript to not only run in the Flash/AIR runtimes, but also to run natively in the browser without Flash, on mobile devices as a PhoneGap/Cordova application, and in embedded JS environments such as Chromium Embedded Framework. Royale has the potential to allow your MXML and ActionScript code to run in even more places than Flash currently does.

#### Game Frameworks

* [Flixel](https://github.com/AdamAtomic/flixel) ⭐ 1,145 | 🐛 75 | 🌐 ActionScript | 📅 2015-11-05 - Useful base classes that you can extend to make your own game objects.
* [FlashPunk](https://github.com/useflashpunk/FlashPunk) ⭐ 395 | 🐛 69 | 🌐 ActionScript | 📅 2016-03-31 - Framework to build 2D games. Provides graphics, events, inputs, animation, etc.
* [StarlingPunk](https://github.com/asaia/StarlingPunk) ⭐ 139 | 🐛 6 | 🌐 ActionScript | 📅 2017-04-17 - Framework built on Starling to add structure and organization to your game projects.
* [YCanvas](https://github.com/jozefchutka/YCanvas) ⭐ 117 | 🐛 3 | 🌐 ActionScript | 📅 2014-12-15 - High-performance 2D tile renderer and world map renderer.
* [IsoHill](https://github.com/jadbox/IsoHill-Game-Engine) ⭐ 101 | 🐛 1 | 🌐 ActionScript | 📅 2012-08-30 - GPU-based Isometric engine built on Starling, with TILED map parser, layers, etc ([website](http://www.isohill.com/)).
* [Pixelizer](https://github.com/johanp/Pixelizer) ⭐ 53 | 🐛 20 | 🌐 ActionScript | 📅 2013-01-05 - Component based game engine to build 2D games. Provides rendering, animation, input, etc.
* [AS3isolib](https://github.com/as3isolib/as3isolib.v1) ⭐ 39 | 🐛 0 | 🌐 HTML | 📅 2015-03-20 - Isometric Library developed to assist in creating isometrically projected games.
* [Tetragon](https://github.com/NothingInteractive/tetragon) ⭐ 32 | 🐛 0 | 🌐 ActionScript | 📅 2013-10-25 - Cross-platform framework to build any kind of game. Provides resource management, debugging facilities, multi-locale support, layered extendability, a game-oriented data structure, and more.
* [Nexus](https://github.com/tversteeg/Nexus) ⚠️ Archived - GPU-accelerated 2D game engine using Stage3D.
* [CitrusEngine](http://citrusengine.com/) - Professional-grade game engine built built on Starling & Away3D.
* [ND2D](https://github.com/lrrrs/nd2d) - GPU-accelerated 2D game engine using Stage3D ([ND2Dx](https://github.com/NoRabbit/ND2Dx) ⭐ 34 | 🐛 0 | 🌐 ActionScript | 📅 2015-01-13).

#### 3D Frameworks

* [Away3D](https://github.com/away3d/away3d-core-fp11) ⭐ 640 | 🐛 111 | 🌐 ActionScript | 📅 2024-06-03 - Open-source GPU-accelerated 3D engine for Flash Player 11+ ([examples](https://github.com/away3d/away3d-examples-fp11) ⭐ 101 | 🐛 7 | 🌐 ActionScript | 📅 2015-05-29).
* [Alternativa3D](https://github.com/AlternativaPlatform/Alternativa3D) ⭐ 381 | 🐛 19 | 🌐 ActionScript | 📅 2024-05-03 - Alternativa3D GPU accelerated 3D engine ([examples](https://github.com/AlternativaPlatform/Alternativa3DExamples) ⭐ 36 | 🐛 1 | 🌐 ActionScript | 📅 2012-10-23).
* [Away3D OpenFL](https://github.com/away3d/away3d-core-openfl) ⭐ 166 | 🐛 29 | 🌐 Haxe | 📅 2017-03-14 - Away3D for Neko, HTML5 and native CPP. ([examples](https://github.com/away3d/away3d-examples-openfl) ⭐ 40 | 🐛 4 | 🌐 Haxe | 📅 2015-09-04).
* [AwayPhysics FP11](https://github.com/away3d/awayphysics-core-fp11) ⭐ 114 | 🐛 13 | 🌐 C++ | 📅 2013-11-07 - Away Physics - 3D physics library for the Away3D FP 11 ([examples](https://github.com/away3d/awayphysics-examples-fp11) ⭐ 57 | 🐛 0 | 🌐 ActionScript | 📅 2013-02-24).
* [Zen3D](https://github.com/hgupta9/Zen3D) ⭐ 6 | 🐛 0 | 🌐 ActionScript | 📅 2017-06-29 - High-performance 3D engine for Adobe Flash & AIR (GPU based).
* [AwayBuilder](http://awaytools.com/awaybuilder/) - Visual workflow tool to import, optimise and bake 3D assets from a variety of sources.
* [Flare3D](http://flare3d.com/) - Commercial 3D platform with high-performance engine and Level-editor IDE.

#### Animation

* [GreenSock GSAP](https://greensock.com/gsap-as) - The industry-standard animation library for Flash (TweenLite, TweenMax) ([github](https://github.com/greensock/GreenSock-AS3) ⭐ 423 | 🐛 3 | 🌐 ActionScript | 📅 2019-05-29).
* [StarlingGAFPlayer](https://github.com/zenrobin/StarlingGAFPlayer) ⭐ 1 | 🐛 0 | 🌐 ActionScript | 📅 2016-05-24 - Play back GAF animations using Starling (animations authored in Flash Pro).
* [GTween](http://gskinner.com/libraries/gtween/) - Small but robust library for programmatic tweening, animation, and transitions.
* [DragonBones](http://dragonbones.github.io/) - High-speed skeletal animation using Starling, and tools to export animations from Flash Pro.
* [FlashEff2](http://www.flasheff.com/) - Premiere programmatic animation library with 100+ transitions and text effects.
* [FlashEffNano](http://www.flasheffnano.com/) - FlashEff transition library optimized for mobile devices, with 20+ transitions in 750 styles.

#### Signals

* [AS3-signals](https://github.com/robertpenner/as3-signals) ⭐ 1,063 | 🐛 9 | 🌐 ActionScript | 📅 2025-05-19 - New approach for AS3 events inspired by C# events and signals/slots in Qt.
* [react-as3](https://github.com/tconkling/react-as3) ⭐ 33 | 🐛 0 | 🌐 ActionScript | 📅 2018-08-18 - Signals/slots and functional reactive programming library.
* [Fa-as3](https://github.com/fabrikagency/fa-as3) ⭐ 9 | 🐛 0 | 🌐 ActionScript | 📅 2009-06-22 - Write less, do more framework, modeled like jQuery.
* [Signaller](https://github.com/whitered/Signaller) ⭐ 2 | 🐛 0 | 🌐 ActionScript | 📅 2010-04-28 - Signals implementation with restricted rights for dispatching.

#### Functional

* [Raix](https://github.com/richardszalay/raix) ⭐ 90 | 🐛 1 | 🌐 ActionScript | 📅 2013-01-18 - Reactive And Interactive eXtensions simplifies working with interactive data (arrays) or reactive data (events).
* [AS3FP](https://github.com/jadbox/AS3FP) ⭐ 12 | 🐛 0 | 🌐 ActionScript | 📅 2012-03-02 - Collection of functional idioms based on Haskell and Coffeescript.
* [Fxp-as3](https://github.com/j3k0/fxp-as3) ⭐ 3 | 🐛 0 | 🌐 ActionScript | 📅 2021-09-13 - Functional library inspired by the "mostly adequate guide".

#### Unit Testing

* [Flexunit](https://github.com/flexunit/flexunit) ⭐ 271 | 🐛 2 | 🌐 ActionScript | 📅 2014-01-16 - FlexUnit project for Actionscript 3 and Flex projects.
* [hamcrest-as3](https://github.com/drewbourne/hamcrest-as3) ⭐ 176 | 🐛 22 | 🌐 ActionScript | 📅 2012-03-21 - Matcher objects allowing 'match' rules to be defined declaratively.
* [ASunit](https://github.com/patternpark/asunit) ⭐ 48 | 🐛 0 | 🌐 ActionScript | 📅 2011-11-04 - The only unit test framework that supports Flash Players 6, 7, 8, 9 and 10.
* [RobotEyes](https://github.com/Stray/RobotEyes) ⭐ 48 | 🐛 0 | 🌐 ActionScript | 📅 2010-12-08 - End-to-end testing for TDD. Hybrid of WindowLicker and Drew Bourne's Mockolate.
* [AS3spec](https://github.com/f1337/as3spec) ⭐ 20 | 🐛 1 | 🌐 ActionScript | 📅 2010-01-14 - Tiny BDD framework for AS3, inspired by Bacon and RSpec.
* [expect.as](https://github.com/krzysztof-o/expect.as) ⭐ 10 | 🐛 0 | 🌐 ActionScript | 📅 2015-02-11 - BDD-style assertion library for ActionScript 3.
* [AS3unit](https://github.com/Hoten/as3unit) ⭐ 4 | 🐛 0 | 🌐 ActionScript | 📅 2015-02-09 - Unit testing framework for ActionScript 3.

## User Interface

#### UI Components

* [GPUI](https://github.com/inspirit/GPUI) ⭐ 73 | 🐛 1 | 🌐 ActionScript | 📅 2012-05-03 - Tiny GUI Library based on Stage3D (GPU).
* [MadComponents](https://github.com/danfreeman/MadComponents) ⭐ 46 | 🐛 1 | 🌐 ActionScript | 📅 2015-04-08 - Popular Mobile UI Framework for AS3 / AIR.
* [Flex-Android-Material-Skins](https://github.com/quick6black/flex-Android-Material-Skins) ⚠️ Archived - Android Material Design skins for Flex Mobile components.
* [Falcon](https://github.com/HendrixString/Falcon) ⭐ 22 | 🐛 0 | 🌐 ActionScript | 📅 2016-02-22 - responsive/flexible mobile ui controls for Feathers.
* [AsWing](https://github.com/dreamsxin/AsWing) ⭐ 15 | 🐛 0 | 🌐 ActionScript | 📅 2017-08-11 - Open Source Flash ActionScript GUI framework.
* [Flex-maps](https://github.com/igorcosta/flex-maps) ⭐ 14 | 🐛 2 | 🌐 ActionScript | 📅 2013-03-20 - Definitive solution for maps in Apache Flex.
* [FlexBook](https://github.com/blvz/FlexBook) ⚠️ Archived - Awesome Page Flip component for Flex.
* [MinimalComps](https://github.com/minimalcomps/minimalcomps) - Minimal ActionScript 3.0 UI Components for Flash.

#### Starling Components

* [Google Maps](https://github.com/ZwickTheGreat/feathers-maps) ⭐ 61 | 🐛 2 | 🌐 ActionScript | 📅 2016-04-20 - Google Maps for Starling, optimized for mobile devices.
* [TabbedApplication](https://github.com/pol2095/Feathers-Extension-Tabbed-Application) ⭐ 11 | 🐛 0 | 🌐 ActionScript | 📅 2017-10-28 - View-based navigation model with swipe to navigate tabs.
* [Canvas](https://github.com/pol2095/Feathers-Extension-Canvas) ⭐ 9 | 🐛 0 | 🌐 ActionScript | 📅 2017-03-14 - Supports basic vector drawing functionality.
* [DataTree](https://github.com/pol2095/Feathers-Extension-Tree) ⭐ 8 | 🐛 0 | 🌐 ActionScript | 📅 2019-03-03 - Displays hierarchical data arranged as an expandable tree.
* [DataGrid](https://github.com/pol2095/Feathers-Extension-DataGrid) ⭐ 7 | 🐛 0 | 🌐 ActionScript | 📅 2019-03-09 - Displays a datagrid with column headings and smooth scrolling.
* [CircleProgress](https://github.com/pol2095/Feathers-Extension-CircleProgress) ⭐ 6 | 🐛 0 | 🌐 ActionScript | 📅 2021-05-09 - Displays progress using a radial progressbar.
* [ZoomableControl](https://github.com/pol2095/Feathers-Extension-ZoomableControl) ⭐ 4 | 🐛 0 | 🌐 ActionScript | 📅 2016-12-20 - Allows a pinch to zoom using the multitouch inputs.
* [Toaster](https://github.com/pol2095/Feathers-Extension-Toaster) ⭐ 3 | 🐛 0 | 🌐 ActionScript | 📅 2019-03-03 - Simple feedback about an operation in a small popup. .

#### Layout

* [TransformTool](https://github.com/senocular/TransformTool) ⭐ 78 | 🐛 5 | 🌐 ActionScript | 📅 2024-10-03 - Free Transform Tool (AS, JS) for manipulating objects in 2D space.
* [xrope](https://github.com/evan-liu/xrope) ⭐ 34 | 🐛 0 | 🌐 ActionScript | 📅 2015-04-20 - Simple layout library for native AS3 display objects.
* [Adobe TLF](https://github.com/apache/flex-tlf) ⭐ 31 | 🐛 1 | 🌐 ActionScript | 📅 2026-05-15 - Adobe/Apache Flex Text Layout Framework (TLF).
* [miglayout-as](https://github.com/develar/miglayout-as) ⭐ 16 | 🐛 2 | 🌐 ActionScript | 📅 2012-12-13 - Port of MigLayout, a superbly versatile Flash/Flex/FlashCocoa (SWT/Swing/JavaFX) layout manager.
* [TinyTLF](https://github.com/joelhooks/tinytlf) ⭐ 11 | 🐛 0 | 🌐 ActionScript | 📅 2010-06-19 - Versatile text layout framework built on top of the Flash Text Engine for Flash/Flex.
* [Argilla-Mosaic](https://github.com/folletto/Argilla-Mosaic) ⭐ 5 | 🐛 0 | 🌐 ActionScript | 📅 2014-07-22 - Dynamic layout library.
* [TransformManager](https://greensock.com/TransformManager) - By Greensock. Interactive scaling/rotating/moving of DisplayObjects.

#### Multi Touch

* [Gestouch](https://github.com/fljot/Gestouch) ⭐ 357 | 🐛 37 | 🌐 ActionScript | 📅 2016-03-01 - Multitouch gesture recognition library for building better Natural User Interfaces.
* [TouchScript](https://github.com/TouchScript/TouchScript.as3) ⭐ 19 | 🐛 0 | 🌐 ActionScript | 📅 2013-03-03 - Multitouch framework that makes handling complex gesture interactions on large touch surfaces easier.
* [TUIO Client](https://github.com/lagerkoller/tuio-as3) ⭐ 6 | 🐛 1 | 🌐 ActionScript | 📅 2022-03-15 - Common framework for multi-touch hardware, supporting TUIO/FLC and TUIO/TCP ([web](http://www.tuio.org/?flash)).
* [Gestures.IO](https://github.com/GesturesIO/gesturesio-as3) ⚠️ Archived - Simplifies the way you create gesture-based Natural Interactions.

#### Game Controllers

* [Gamepad](https://github.com/iainlobb/Gamepad) ⭐ 56 | 🐛 3 | 🌐 ActionScript | 📅 2017-02-05 - Simulates an analog joystick input using the keyboard.
* [AS3-Controller-Input](https://github.com/arkeus/as3-controller-input) ⭐ 29 | 🐛 5 | 🌐 ActionScript | 📅 2014-01-22 - Interact with Ouya and Xbox360 game controllers from Adobe AIR.
* [Advanced\_Joystick](https://github.com/justjoeyuk/Advanced_Joystick) ⭐ 21 | 🐛 0 | 🌐 ActionScript | 📅 2015-09-01 - Joystick for the Starling Framework, designed for Adobe AIR Mobile.
* [AS3dpad](https://github.com/duckleg/as3dpad) ⭐ 19 | 🐛 0 | 🌐 ActionScript | 📅 2013-09-18 - A virtual touchscreen gamepad designed for Adobe AIR Mobile (Android/iOS).

## Multimedia

#### Augmented Reality

* [EZFLAR](https://github.com/tcha-tcho/EZFLAR) ⭐ 42 | 🐛 1 | 🌐 ActionScript | 📅 2010-07-13 - A little wrapper to ease the way AR works.
* [IN2AR](https://github.com/inspirit/IN2ARSDKExamples) ⭐ 34 | 🐛 3 | 🌐 ActionScript | 📅 2015-06-04 - SDK for IN2AR cross-platform Augmented Reality Engine.
* [FLARToolKit](https://github.com/Saqoosha/FLARToolKit) ⭐ 17 | 🐛 0 | 🌐 ActionScript | 📅 2015-04-22 - AS3 port of the industry standard ARToolkit library, for Flash Player 11. ([website](http://www.libspark.org/wiki/saqoosha/FLARToolKit/en)).
* [FLAREmulator](https://github.com/theflashbum/FLAREmulator) ⭐ 9 | 🐛 0 | 🌐 ActionScript | 📅 2010-04-09 - Test AR demos to see what works and what doesn't with or without a webcam.
* [NyARToolkitAS3](https://github.com/nyatla/NyARToolkitAS3) ⭐ 6 | 🐛 0 | 🌐 ActionScript | 📅 2015-05-25 - NyARToolkit AS3 edition. Marker based Augmented reality library.
* [FLARManager](http://words.transmote.com/wp/flarmanager/) - Lightweight framework for building augmented reality apps, using FLARToolkit/flare.tracker/flare.NFT.

#### Data Visualization

* [Weave](https://github.com/WeaveTeam/Weave) ⭐ 368 | 🐛 8 | 🌐 ActionScript | 📅 2019-01-06 - Web-based Analysis and Visualization Environment.
* [Flare](https://github.com/prefuse/Flare) ⭐ 352 | 🐛 4 | 🌐 ActionScript | 📅 2012-08-02 - charts and graphs, supports data management, visual encoding, animation, and interaction techniques.
* [clearmaps](https://github.com/sunlightlabs/clearmaps) ⭐ 62 | 🐛 1 | 🌐 ActionScript | 📅 2010-02-17 - Mapping framework for data visualization.
* [Flextreemap](https://github.com/joshtynjala/flextreemap) ⚠️ Archived - TreeMap data visualization component for Adobe Flex.
* [Axiis](https://github.com/hgupta9/AxiisCharts) ⭐ 10 | 🐛 0 | 🌐 ActionScript | 📅 2016-11-11 - Data visualization framework with line, bar, wedge, column, cluster, area, smith and treemap charts.
* [GraphVisualizer](https://github.com/armisael/GraphVisualizer) ⭐ 5 | 🐛 0 | 🌐 ActionScript | 📅 2009-07-13 - A Flex 3 + ActionScript 3 web software to draw dynamic graphcs.
* [redada](https://github.com/geraldo/redada) ⚠️ Archived - Interactive visualization of weighted graphs using GraphML files.
* [Open Flash Charts](https://sourceforge.net/projects/openflashchart/) - Line charts, Area charts, Bar charts, Pie charts, Scatter charts.
* [Social-grid](https://github.com/Instrument/social-grid) - Abstract Grid Visualization for Social Media.

#### Camera

* [CameraDetection](https://github.com/cataclysmicrewind/CameraDetection) ⭐ 35 | 🐛 4 | 🌐 ActionScript | 📅 2012-11-16 - Camera detection.
* [WebcamRecorder](https://github.com/Stupeflix/WebcamRecorder) ⭐ 25 | 🐛 0 | 🌐 ActionScript | 📅 2012-03-12 - Chromeless video/audio/still image recording from webcams.
* [FlashyWrappers](https://github.com/rainbowcreatures/FlashyWrappers) ⭐ 17 | 🐛 22 | 📅 2017-06-27 - Recording video from AIR apps on Windows/Android/iOS/OSX.
* [Fluocam](https://github.com/Fluocode/Fluocam) ⭐ 12 | 🐛 0 | 🌐 ActionScript | 📅 2014-02-12 - Virtual camera for Starling applications.

#### Image

* [Inspirit GPUImage](https://github.com/inspirit/GPUImage) ⭐ 171 | 🐛 4 | 🌐 ActionScript | 📅 2012-09-14 - Framework for GPU-based image processing.
* [ATF-Encoder](https://github.com/plepers/ATF-Encoder) ⭐ 80 | 🐛 1 | 🌐 ActionScript | 📅 2013-06-26 - Encode/decode ATF (Adobe Texture Format) files in pure AS3.
* [AS3potrace](https://github.com/PowerflasherBR/as3potrace) ⭐ 60 | 🐛 1 | 🌐 ActionScript | 📅 2011-05-21 - POTrace implementation, to trace bitmap images to vector.
* [Scale9Image](https://github.com/Tibus/Scale9Image) ⭐ 15 | 🐛 0 | 🌐 ActionScript | 📅 2013-04-22 - Optimized scale9Grid image for starling.
* [Flip-Planes-AS3](https://github.com/jamesflorentino/Flip-Planes-AS3) ⭐ 15 | 🐛 1 | 🌐 ActionScript | 📅 2011-08-19 - Photo slideshow effects.
* [AS3-transitions-lib](https://github.com/foo123/as3-transitions-lib) ⭐ 13 | 🐛 0 | 🌐 ActionScript | 📅 2023-09-19 - Image Transitions Library.
* [ASImageLib](https://github.com/terrynoya/ASImageLib) ⭐ 12 | 🐛 0 | 🌐 ActionScript | 📅 2013-11-26 - BMP/PNG decoder for actionscript.
* [AS3-klt](https://github.com/motemen/as3-klt) ⭐ 11 | 🐛 0 | 🌐 ActionScript | 📅 2008-09-25 - Kanade-Lucas-Tomasi feature tracker implementation.
* [BlurHash](https://github.com/roipeker/as3-blurhash) ⭐ 8 | 🐛 0 | 🌐 ActionScript | 📅 2020-07-03 - A BlurHash encoder/decoder implementation in ActionScript 3.0..
* [Inspirit Image](https://github.com/hgupta9/InspiritImage) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2016-11-11 - FFT, SURF, edge detection, fluid solver, etc.
* [Async-Image-Encoders](https://github.com/LeeBurrows/Async-Image-Encoders) ⚠️ Archived - Asynchronously encode BitmapData objects into image file format.

#### Font

* [Firetype](https://github.com/MaxDidIt/firetype) ⭐ 99 | 🐛 6 | 🌐 ActionScript | 📅 2015-09-30 - Parse OpenType fonts and render them using Stage3D.
* [BMFontRenderer](https://github.com/bengarney/BMFontRenderer) ⭐ 35 | 🐛 0 | 🌐 ActionScript | 📅 2011-09-07 - AS3 renderer for bitmap font data in the BMFont format.
* [HanFont](https://github.com/kyoji2/HanFont) ⭐ 15 | 🐛 0 | 🌐 ActionScript | 📅 2010-12-20 - AIR app for Chinese Font Embeding in ActionScript.
* [Ficon.as](https://github.com/dv/Ficon.as) ⭐ 4 | 🐛 0 | 🌐 ActionScript | 📅 2012-10-03 - Library to easily include icon fonts.

#### Particle

* [Starling-Particles](https://github.com/Gamua/Starling-Extension-Particle-System) ⭐ 324 | 🐛 1 | 🌐 ActionScript | 📅 2024-07-25 - Particle system for the Starling framework, compatible with the "Particle Designer" from 71squared.com.
* [Flint](https://github.com/richardlord/Flint) ⭐ 259 | 🐛 0 | 🌐 ActionScript | 📅 2017-04-16 - Particle Engine for Flash and Flex.
* [SAP](https://github.com/gonchar/SAP) ⭐ 44 | 🐛 2 | 🌐 ActionScript | 📅 2017-04-25 - Particle System for Starling.
* [Desuade Partigen](http://desuade.com/partigen) - Desuade Partigen particle generation system ([github](https://github.com/andrewfitz/desuade) ⚠️ Archived).
* [Angulex](https://github.com/cosmindolha/ParticleDesigner) ⭐ 10 | 🐛 0 | 🌐 ActionScript | 📅 2016-01-11 - Particle Designer for the Starling framework (ActionScript 3).
* [MotionParticleSprite](https://github.com/bjeld/motionparticlesprite) ⭐ 0 | 🐛 0 | 🌐 ActionScript | 📅 2017-06-16 - Design motion paths in Flash Pro and use it to guide Starling particles.

#### Panorama Viewer

* [SaladoPlayer](https://github.com/mstandio/SaladoPlayer) ⭐ 89 | 🐛 2 | 🌐 ActionScript | 📅 2015-09-03 - Panorama viewer.
* [CuTy](https://github.com/fieldOfView/CuTy) ⭐ 10 | 🐛 0 | 🌐 ActionScript | 📅 2014-11-04 - QTVR Panorama viewer based on Flash 10.
* [PanoramicViewer](https://github.com/BrianMehrman/PanoramicViewer) ⭐ 1 | 🐛 0 | 🌐 ActionScript | 📅 2012-01-31 - 3D Panoramic Viewer.
* [Sphere\_panorama](https://github.com/suzumura-ss/flash_sphere_panorama) ⭐ 1 | 🐛 0 | 🌐 ActionScript | 📅 2012-07-09 - Panorama player with equirectangular texture written in AS3 (Alternativa3D).
* [Pantaloons](https://github.com/EyeSee360/Pantaloons) - Panoramic viewing in Flash Player.

#### QR Code

* [Zxing AS3](https://github.com/zxing/zxing/tree/c1df162b95e07928afbd4830798cc1408af1ac67/actionscript) ⭐ 34,069 | 🐛 0 | 🌐 Java | 📅 2026-07-28 - QR code detection and generation ([docs](https://zxing.github.io/zxing/)).
* [AS3-qrcode-encoder](https://github.com/jbpin/as3-qrcode-encoder) ⭐ 91 | 🐛 3 | 🌐 ActionScript | 📅 2016-08-18 - QR code encoder in as3.
* [qrcode-as](https://github.com/yanbe/qrcode-as) ⭐ 29 | 🐛 1 | 🌐 ActionScript | 📅 2011-10-31 - QR Code reader which supports webcam on Windows, Mac and Linux.

#### Sound

* [FlashWavRecorder](https://github.com/michalstocki/FlashWavRecorder) ⭐ 241 | 🐛 34 | 🌐 ActionScript | 📅 2016-10-25 - Recording audio and saving as a WAV.
* [Standingwave3](https://github.com/maxl0rd/standingwave3) ⭐ 161 | 🐛 18 | 🌐 ActionScript | 📅 2012-12-20 - Dynamic audio library.
* [SoundAS](https://github.com/treefortress/SoundAS) ⭐ 139 | 🐛 11 | 🌐 ActionScript | 📅 2023-10-02 - Modern & lightweight sound manager for AS3.
* [SiON](https://github.com/keim/SiON) ⭐ 118 | 🐛 0 | 🌐 ActionScript | 📅 2021-08-27 - Flash Software Synthesizer.
* [AS3sfxr](https://github.com/SFBTom/as3sfxr) ⭐ 99 | 🐛 4 | 🌐 ActionScript | 📅 2015-03-14 - Port of sfxr from C++ to AS3, using the new sound and file capabilities of Flash Player 10.
* [Soundtouch-as3](https://github.com/also/soundtouch-as3) ⭐ 62 | 🐛 2 | 🌐 ActionScript | 📅 2010-04-05 - AS3 Port of the SoundTouch Sound Processing Library.
* [Flod](https://github.com/photonstorm/Flod) ⭐ 53 | 🐛 2 | 🌐 ActionScript | 📅 2012-05-05 - Amiga SoundTracker (MOD) and FastTracker (XM) Replay Library.
* [AS3-Sound-Manager](https://github.com/GrupoW/as3-Sound-Manager) ⭐ 17 | 🐛 3 | 🌐 ActionScript | 📅 2011-05-10- Upgraded version of the Sound Manager Class from Matt Przybylski.
* [Local-recorder](https://github.com/pauln/local-audio-recorder) ⭐ 14 | 🐛 1 | 🌐 ActionScript | 📅 2014-05-26 - Local audio recorder (no streaming server required).  Currently requires Flash Player 10.1 or above.
* [SeiON](https://github.com/cardin/SeiON) ⚠️ Archived - Sound Management Library.
* [AS3-audio](https://github.com/singuerinc/as3-audio) ⭐ 5 | 🐛 0 | 🌐 ActionScript | 📅 2011-06-27 - Audio Management in Actionscript.
* [Jukebox](https://github.com/AlwynW/Jukebox) ⭐ 2 | 🐛 0 | 🌐 ActionScript | 📅 2012-05-18 - Music manager for Actionscript 3 projects.
* [Standingwave3-addons](https://github.com/charlesclements/standingwave3-addons) ⭐ 1 | 🐛 0 | 🌐 ActionScript | 📅 2015-02-20 - Addons for SW3.

#### Video Player

* [Flowplayer](https://github.com/flowplayer/flash) ⚠️ Archived - Flowplayer Flash, the video player for the Web.
* [F4player](https://github.com/gokercebeci/f4player) ⭐ 117 | 🐛 7 | 🌐 ActionScript | 📅 2018-12-25 - Open Source AS3 Flash Video Player.
* [OSFlashVideoPlayer](https://github.com/FlashJunior/OSFlashVideoPlayer) ⭐ 108 | 🐛 19 | 🌐 ActionScript | 📅 2012-01-03 - Open source flash video player.
* [dashas](https://github.com/castlabs/dashas) ⚠️ Archived - MPEG-DASH player written in ActionScript.
* [hlsplayer](https://github.com/erlyvideo/hlsplayer) ⭐ 59 | 🐛 4 | 🌐 ActionScript | 📅 2013-03-04 - HLS player for OSMF flash framework.
* [vgaplayer](https://github.com/euske/vgaplayer) ⭐ 27 | 🐛 3 | 🌐 ActionScript | 📅 2014-07-20 - Open source player for Adobe Flash Media Server streams (RTMP).
* [Goplayer](https://github.com/dbrock/goplayer) ⭐ 19 | 🐛 0 | 🌐 ActionScript | 📅 2011-01-14 - Modern open-source video player written in ActionScript 3.

## Database

#### SQLite

* [AIR-sqlite](https://github.com/probertson/air-sqlite) ⭐ 75 | 🐛 5 | 🌐 ActionScript | 📅 2012-02-20 - Utilities for working with SQLite databases in AIR.
* [AIRdb](https://github.com/dkeskar/airdb) ⭐ 34 | 🐛 0 | 🌐 ActionScript | 📅 2010-05-18 - AIR ORM for using client-side SQLite within AIR and Flex apps. Supports ActiveRecord style models, migrations and associations.
* [AS3Query](https://github.com/kemsky/as3Query) ⭐ 4 | 🐛 0 | 🌐 ActionScript | 📅 2015-10-07 - Another SQLite ORM and query DSL for ActionScript.
* [Flexine](https://github.com/riadvice/Flexine) ⭐ 4 | 🐛 0 | 🌐 ActionScript | 📅 2012-12-22 - SQLite ORM for AIR.

#### MongoDB

* [MongoAS3](https://github.com/s9tpepper/MongoAS3) ⭐ 72 | 🐛 8 | 🌐 ActionScript | 📅 2011-10-26 - MongoDB driver.
* [ActionMongo](https://github.com/RIAlizer/ActionMongo) ⭐ 1 | 🐛 0 | 🌐 ActionScript | 📅 2010-09-09 - MongoDB driver.

#### CouchDB

* [AS3couchdb](https://github.com/bustardcelly/as3couchdb) ⭐ 38 | 🐛 4 | 🌐 ActionScript | 📅 2010-11-19 - Client-side API for interacting with a CouchDB instance.
* [Soup](https://github.com/dima/soup) ⚠️ Archived - Mixing CouchDB, Sinatra, AIR and RestfulX to create an offline/online ready app with undo/redo capabilities.

#### MySQL

* [AS3mysql](https://github.com/hgupta9/as3mysql) ⭐ 16 | 🐛 0 | 🌐 ActionScript | 📅 2016-11-14 - Driver for the MySQL open source database.

#### PostgreSQL

* [Pegasus](https://github.com/uhoh-itsmaciek/pegasus) ⭐ 17 | 🐛 13 | 🌐 ActionScript | 📅 2012-03-08 - Driver for the PostgreSQL open source database.

#### DynamoDB

* [AWS-dynamodb](https://github.com/ferf/aws-dynamodb-actionscript) ⭐ 1 | 🐛 0 | 🌐 ActionScript | 📅 2014-02-11 - Driver for accessing Amazon's AWS DynamoDB.

#### Redis

* [AS3redis](https://github.com/zhangq0355/as3redis) ⭐ 4 | 🐛 0 | 🌐 ActionScript | 📅 2009-11-24 - Driver for Redis.

## File Formats

#### Archives

* [FZip](https://github.com/claus/fzip) ⚠️ Archived - Mature library to load, modify and create standard ZIP archives.
* [Untar-Worker](https://github.com/mesmotronic/as3-worker-untar) ⭐ 11 | 🐛 0 | 🌐 ActionScript | 📅 2019-04-23 - TAR extraction using AS3 Workers (background threads).
* [ASZip](https://code.google.com/archive/p/aszip/) - Generate ZIP archives from AS3.

#### 3D Formats

* [EasyAGAL](https://github.com/Barliesque/EasyAGAL) ⭐ 114 | 🐛 2 | 🌐 HTML | 📅 2015-05-27 - Simplifies development of AGAL shaders with code completion, code hinting,  macros, etc.
* [AsBlender](https://github.com/timknip/asblender) ⭐ 38 | 🐛 4 | 🌐 ActionScript | 📅 2010-01-25 - Parse Blender .BLEND files.
* [AsCollada](https://github.com/timknip/ascollada) ⭐ 7 | 🐛 0 | 📅 2010-01-16 - Parse COLLADA 3D model files ([fork](https://github.com/david-gregory/ascollada) ⭐ 1 | 🐛 0 | 🌐 ActionScript | 📅 2011-05-21).
* [AS3-bvh-parser](https://github.com/rkn14/as3-bvh-parser) ⭐ 5 | 🐛 0 | 🌐 ActionScript | 📅 2012-09-21 - Parse BVH files.

#### CSV

* [CSV4AS3](https://github.com/lizardon/CSV4AS3) ⭐ 5 | 🐛 0 | 🌐 ActionScript | 📅 2013-09-22 - CSV library ported from Apache Commons CSV.
* [Csvlib](https://github.com/51systems/csvlib) - CSV parser.

#### CSS

* [Fcss](https://github.com/theflashbum/fcss) ⭐ 83 | 🐛 13 | 🌐 ActionScript | 📅 2011-02-24 - Flash Cascading StyleSheet Library.
* [Stylekit-as3](https://github.com/videojuicer/stylekit-as3) ⭐ 37 | 🐛 1 | 🌐 ActionScript | 📅 2012-05-15 -  Skinnable user interfaces using CSS3.
* [Jakute-CSS](https://github.com/kakenbok/Jakute-Styling-Engine) ⭐ 10 | 🐛 1 | 🌐 ActionScript | 📅 2011-12-21 - Jakute is a CSS framework for ActionScript/Flash.
* [Sass4as](https://github.com/jeremyruppel/sass4as) ⭐ 4 | 🐛 0 | 🌐 ActionScript | 📅 2010-08-25 - Syntactically Awesome Stylesheets for ActionScript 3.
* [AS3csslib](https://github.com/heyfrench/as3csslib) ⭐ 1 | 🐛 0 | 🌐 ActionScript | 📅 2015-07-13 - CSS3 parser, selector and style engine for ActionScript 3.0.
* [CSS.as](https://gist.github.com/trxcllnt/1161266) - Single-file CSS parser, part of TinyTLF project.

#### BSON

* [MongoAS3](https://github.com/s9tpepper/MongoAS3) ⭐ 72 | 🐛 8 | 🌐 ActionScript | 📅 2011-10-26 - MongoDB Driver which includes BSON I/O.
* [ActionBSON](https://github.com/fminzoni/ActionBSON) ⭐ 12 | 🐛 0 | 🌐 ActionScript | 📅 2011-10-20 - BSON data encoder/decoder.

#### EXIF

* [Exif-as3](https://github.com/bashi/exif-as3) ⭐ 19 | 🐛 1 | 🌐 ActionScript | 📅 2017-08-01 - Parse JPEG EXIF data.
* [AS3-exif-lib](https://github.com/unstoppable/actionscript-exif-reading-lib) ⭐ 6 | 🐛 0 | 🌐 ActionScript | 📅 2012-06-10 - Parse JPEG EXIF data.

#### FXG

* [Fxg-as3-lib](https://github.com/pixelami/fxg-as3-lib) ⭐ 8 | 🐛 0 | 🌐 ActionScript | 📅 2011-10-17 - Pure AS3 FXG rendering library (both runtime rendering and mxml supported).
* [Fxg2as3](https://github.com/ZackPierce/fxg2as3) ⚠️ Archived - Converting FXG markup into executable Actionscript 3 code.

#### GIF

* [GIF Player](https://github.com/theturtle32/Flash-Animated-GIF-Library) ⭐ 58 | 🐛 5 | 🌐 ActionScript | 📅 2015-09-01 - Play Animated GIFs in Flash.
* [AS3gif](https://github.com/audreyt/as3gif) ⭐ 25 | 🐛 0 | 🌐 ActionScript | 📅 2010-07-01 - Play and encode Animated GIFs.
* [Async-gif-decoder](https://github.com/honzabrecka/async-gif-decoder) ⚠️ Archived - Asynchronous GIF decoder & player.

#### ICAL

* [AS3iCAL](https://github.com/nicolai86/as3.iCal) ⚠️ Archived - iCal parser based on the RFC2445 specification.

#### JSON

* [Actionjson](https://github.com/mherkender/actionjson) ⭐ 125 | 🐛 2 | 🌐 ActionScript | 📅 2012-02-06 - Faster, more advanced ActionScript 3 JSON library.
* [JSONTools](https://github.com/s9tpepper/JSONTools) ⭐ 17 | 🐛 0 | 🌐 ActionScript | 📅 2012-04-18 - JSON errors, the speed of the JSWoof JSON library, and E4X style queries dubbed E4J.
* [Jameson](https://github.com/mattupstate/jameson) ⚠️ Archived - JSON Document Object Mapper.
* [Serialkiller](https://github.com/benbjohnson/serialkiller) ⭐ 4 | 🐛 0 | 🌐 ActionScript | 📅 2010-07-15 - JSON & XML serialization library.
* [JsonMapper](https://github.com/kemsky/JsonMapper) ⭐ 4 | 🐛 0 | 🌐 ActionScript | 📅 2014-06-15 - Typed JSON parser.

#### Markdown

* [Markdownlib](https://github.com/Corsaair/markdownlib) ⭐ 5 | 🐛 0 | 🌐 ActionScript | 📅 2019-07-18 - Implementation of Markdown.
* [Actiondown](https://github.com/bbeaumont/Actiondown) ⭐ 2 | 🐛 1 | 🌐 ActionScript | 📅 2010-10-05 - Port of Javascript Showdown.
* [Showdown.as](https://gist.github.com/cstrahan/648771) - Port of showdown.js.

#### MP3

* [AS3Icy](https://github.com/claus/as3icy) ⭐ 28 | 🐛 1 | 🌐 ActionScript | 📅 2010-02-11 - Decode and play live MP3 streams from Shoutcast, Icecast and Limewire.
* [AS3id3lib](https://github.com/devxoul/as3id3lib) ⭐ 2 | 🐛 0 | 🌐 ActionScript | 📅 2011-12-26 - Parse MP3 ID3 data.

#### PDF

* [PurePDF](https://github.com/sephiroth74/purePDF) ⭐ 140 | 🐛 9 | 🌐 ActionScript | 📅 2019-04-29 - Complete PDF library, port of Java iText.
* [AlivePDF](https://code.google.com/archive/p/alivepdf/) - Client side PDF generation ([github](https://github.com/riadvice/alivepdf) ⭐ 32 | 🐛 338 | 🌐 ActionScript | 📅 2020-11-01).
* [PDFView](https://github.com/jankapunkt/PDFView) ⚠️ Archived - PDF viewer built from scratch.
* [PDFCase](https://github.com/dickclaus/pdfcase) ⭐ 4 | 🐛 0 | 🌐 ActionScript | 📅 2012-12-11 - PDF Library.
* [HalcyonPDF](https://github.com/systemed/halcyon_pdf) ⚠️ Archived - OpenStreetMap PDF renderer.

#### PSD

* [AS3-psd-parser](https://github.com/warrenseine/as3-psd-parser) ⭐ 35 | 🐛 0 | 🌐 ActionScript | 📅 2012-03-13 - Parse Photoshop PSD files and render as BitmapData objects.

#### SWF

* [AS3swf](https://github.com/claus/as3swf) ⚠️ Archived - Low level library to parse, create, modify and publish SWF files.
* [SWFWire](https://github.com/magicalhobo/SWFWire) ⭐ 255 | 🐛 21 | 🌐 ActionScript | 📅 2018-09-10 - SWF Decompiler and Inspector Tools.
* [AS3abc](https://github.com/imcj/as3abc) ⭐ 5 | 🐛 0 | 🌐 ActionScript | 📅 2012-02-03 - Low level library to parse, create, modify and publish ABC (Actionscript Block Code) files.
* [Abc-abstraction](https://github.com/krilnon/abc-abstraction) - Allows ABC to be analyzed, manipulated, packaged back into an SWF, and run.

#### SVG

* [AS3SVGRenderer](https://github.com/LucasLorentz/AS3SVGRenderer) ⭐ 106 | 🐛 19 | 🌐 ActionScript | 📅 2016-04-13 - SVG Renderer for Flash Player.
* [SVGParser](https://github.com/millermedeiros/SVGParser) ⭐ 15 | 🐛 3 | 🌐 ActionScript | 📅 2011-01-18 - SVG parser and renderer to FIVe3D and HTML5 canvas.

#### XML

* [AStream](https://github.com/kokorin/AStream) ⚠️ Archived - XML to Object (and vice versa) mapping library written in AS3. Compatible with XStream.
* [XMLSerializer](https://github.com/vapesolius/XMLSerializer) ⭐ 3 | 🐛 0 | 🌐 ActionScript | 📅 2014-03-13 - Library which allows data serialisation from ActionScript to XML and from XML to ActionScript.
* [DynamicXMLParser](https://github.com/lmgerhard/DynamicXMLParser) ⭐ 2 | 🐛 0 | 🌐 ActionScript | 📅 2011-03-21 - Dynamic parse xml content into predefined data classes (actionscript 3).
* [Nudge](https://github.com/pluglimited/Nudge) ⭐ 1 | 🐛 0 | 🌐 ActionScript | 📅 2011-08-04 - Framework to serialize/deserialize objects as XML.

#### XLSX

* [AS3-xlsx-reader](https://github.com/childoftv/as3-xlsx-reader) ⭐ 41 | 🐛 4 | 🌐 ActionScript | 📅 2020-10-01 - Parse Open XML Excel (.XLSX) or Open Office spreadsheets.

## Networking

#### Data Loader

* [GreenSock LoaderMax](https://github.com/greensock/GreenSock-AS3) ⭐ 423 | 🐛 3 | 🌐 ActionScript | 📅 2019-05-29 - Provides an easy and powerful way to load assets at runtime.
* [BulkLoader](https://github.com/arthur-debert/BulkLoader) ⭐ 269 | 🐛 10 | 🌐 ActionScript | 📅 2015-08-31 - Bulk asset loading library for Actionscript.
* [AssetLoader](https://github.com/Matan/AssetLoader) ⭐ 117 | 🐛 3 | 🌐 ActionScript | 📅 2013-02-22 - Multi-file/asset loader for AS3 built on AS3Signals.

#### Hardware

* [LeapMotionAS3](https://github.com/logotype/LeapMotionAS3) ⭐ 308 | 🐛 5 | 📅 2021-07-18 - Integrate with the LeapMotion sensor (provides Gestures, Image, Skeleton/Bone @ 210 FPS).
* [OpenTSPS](https://github.com/labatrockwell/openTSPS) ⭐ 197 | 🐛 26 | 🌐 C++ | 📅 2017-11-19 - TSPS is a cross platform Toolkit for Sensing People in Spaces. It performs openCV operations on live video (Kinect, web camera, etc) and sends it to clients as JSON (via WebSockets), OSC, TUIO, or TCP.
* [AIRkinect](https://github.com/AS3NUI/airkinect-2-core) ⭐ 113 | 🐛 10 | 🌐 C++ | 📅 2017-04-17 - ANE for integrating with Microsoft Kinect. ([examples](https://github.com/AS3NUI/airkinect-2-examples) ⭐ 45 | 🐛 3 | 🌐 ActionScript | 📅 2013-05-21).
* [Kinect-Gestures](https://github.com/tonybeltramelli/Air-Kinect-Gesture-Lib) ⭐ 53 | 🐛 1 | 🌐 ActionScript | 📅 2014-06-27 - AIR Kinect Gesture Library.
* [AS3-arduino](https://github.com/quetwo/as3-arduino-connector) ⭐ 48 | 🐛 15 | 🌐 C | 📅 2015-03-22 - Connecting Arduino Prototyping board to Adobe AIR.
* [KinectGate](https://github.com/cleoag/KinectGate) ⭐ 14 | 🐛 0 | 🌐 ActionScript | 📅 2011-09-03 - KinectSDK to AS3 socket gate.
* [AS3midilib](https://github.com/heyfrench/as3midilib) ⭐ 8 | 🐛 4 | 🌐 ActionScript | 📅 2015-07-13 - Work with MIDI files and MIDI input/output devices.
* [AS3glue](https://code.google.com/archive/p/as3glue/) - Communication for Arduino boards.

#### Servers

* [AIR-Server](https://github.com/wouterverweirder/AIR-Server) ⭐ 47 | 🐛 1 | 🌐 ActionScript | 📅 2013-03-14 - Socket Server library for Adobe AIR.
* [AIRhttp](https://github.com/leopoldodonnell/airhttp) ⭐ 27 | 🐛 0 | 🌐 ActionScript | 📅 2013-04-03 - HTTP Server for Adobe AIR.

#### OAuth

* [Actionscript-oauth2](https://github.com/charlesbihis/actionscript-oauth2) ⭐ 109 | 🐛 2 | 🌐 ActionScript | 📅 2022-03-17 - Interfacing with OAuth 2.0 services.
* [oauth-flex](https://github.com/oauth-io/oauth-flex) ⭐ 7 | 🐛 0 | 🌐 ActionScript | 📅 2013-11-26 - OAuth.io plugin for Apache Flex/ActionScript.
* [oauth-as3](https://github.com/mlepicki/oauth-as3) - Mavenized, RSL version of oauth-as3 library - OAuth for ActionScript 3.

#### HTTP

* [AS3httpclient](https://github.com/gabriel/as3httpclient) ⭐ 243 | 🐛 11 | 🌐 ActionScript | 📅 2021-11-03 - HTTP client implementation.
* [Amazon Web Services](https://github.com/satoshi7/ActionScript-API-for-AWS-Amazon-Web-Services-) ⭐ 25 | 🐛 2 | 🌐 ActionScript | 📅 2019-11-03 - AS3 API for AWS.
* [Hendrix-HTTP](https://github.com/HendrixString/Hendrix-HttP-AiR) ⭐ 12 | 🐛 0 | 🌐 ActionScript | 📅 2016-02-22 - Lightweight HTTP library for ActionScript 3 (as3) inspired by Square's OkHttp.
* [AS3httpclient](https://github.com/abdul/as3httpclient) ⭐ 6 | 🐛 0 | 🌐 ActionScript | 📅 2015-02-22 - HTTP client implementation.
* [HTTPForm](https://github.com/dv/HTTPForm) ⭐ 5 | 🐛 0 | 🌐 ActionScript | 📅 2012-04-26 - Emulate a multipart/form-data HTML form submission request, including file upload.

#### P2P

* [ArcusNode](https://github.com/OpenRTMFP/ArcusNode) ⭐ 174 | 🐛 10 | 🌐 ActionScript | 📅 2017-07-08 - RTMFP Rendevouz Service For Peer Assisted Networking With Adobe Flash on Node JS.
* [HydraP2P](https://github.com/devboy/HydraP2P) ⭐ 92 | 🐛 1 | 🌐 ActionScript | 📅 2011-04-18 - Simplifies the peer-to-peer API introduced in Flash Player 10.1.
* [HLS-P2P](https://github.com/lava-tech/hls-p2p) ⭐ 89 | 🐛 1 | 🌐 ActionScript | 📅 2016-05-06 - Flash OSMF based hybrid cdn\&p2p hls solution.
* [NetGrouper](https://github.com/walpolea/NetGrouper) ⭐ 26 | 🐛 0 | 🌐 ActionScript | 📅 2013-02-27 - Wrapper for NetGroup and RTMFP Multicasting abilities to create quick P2P multiplayer games over local networks or Adobe Cirrus.
* [P2Plocal](https://github.com/palkan/as3_p2plocal) ⭐ 25 | 🐛 0 | 🌐 ActionScript | 📅 2018-05-07 - Local RTMFP connections.
* [Android-Flash-P2P](https://github.com/beautifycode/Android-Flash-P2P) ⭐ 16 | 🐛 0 | 🌐 ActionScript | 📅 2010-09-12 - P2P Communication between a Client.swf and an Android Device with AIR.
* [GroupP2P](https://github.com/oohazard/GroupP2P) ⭐ 2 | 🐛 0 | 🌐 ActionScript | 📅 2010-11-21 - P2P-based netgroup.
* [P2Pmessaging](https://github.com/dreamsocket/actionscript-p2p_messaging) ⭐ 1 | 🐛 0 | 🌐 ActionScript | 📅 2012-04-03 - Simple messaging framework for doing P2P in Flash.

#### Sockets

* [AS3WebSocket](https://github.com/theturtle32/AS3WebSocket) ⭐ 251 | 🐛 8 | 🌐 ActionScript | 📅 2016-09-22 - WebSocket client implementation for the final WebSocket Draft RFC6455.
* [FlashSocket.IO](https://github.com/simb/FlashSocket.IO) ⭐ 210 | 🐛 13 | 🌐 ActionScript | 📅 2016-09-22 - Clients connect to Socket.IO servers from AS3/AIR clients.
* [Socket.io-flash](https://github.com/sinnus/socket.io-flash) ⭐ 45 | 🐛 4 | 🌐 ActionScript | 📅 2013-08-23 - Communication to Socket.IO v.0.8+ servers.
* [Socket.io](https://github.com/ascorbic/socket-io-actionscript) ⭐ 35 | 🐛 0 | 🌐 ActionScript | 📅 2010-12-02 - Socket.IO Actionscript 3 client.
* [SmartSocket](https://github.com/XaeroDegreaz/SmartSocket) ⭐ 15 | 🐛 1 | 🌐 ActionScript | 📅 2012-05-26 - SmartSocket is a Java and PHP socket server engine, to make creating multi-user applications quick and painless.
* [AMFsocket](https://github.com/chadrem/amf_socket) ⭐ 11 | 🐛 0 | 🌐 ActionScript | 📅 2015-03-31 - Bi-directional RPC library for high performance network communication.
* [Sockpuppet](https://github.com/rjungemann/sockpuppet) - Complete Ruby/ActionScript socket client/server with AMF.
* [ws-flash-client](https://github.com/youurayy/ws-flash-client) - Reliable minimalistic WebSocket client (uses Adobe Flash where native WebSocket is not available).

#### Protocols

* [AMQP](https://github.com/0x6e6562/as3-amqp) ⭐ 42 | 🐛 4 | 🌐 ActionScript | 📅 2015-08-27 - Client-side implementation of the 0-8 version of AMQP.
* [BDD Cucumber](https://github.com/flashquartermaster/Cuke4AS3) ⭐ 25 | 🐛 0 | 🌐 ActionScript | 📅 2016-07-08 - A BDD Cucumber wire protocol implementation for Flash ActionScript.
* [AIRplay](https://github.com/mikkoh/AS3-Airplay) ⭐ 19 | 🐛 1 | 🌐 ActionScript | 📅 2012-04-23 - Client-side implementation of Apple's Airplay.
* [TeaTime](https://github.com/aemoncannon/croqodile) ⭐ 14 | 🐛 0 | 🌐 ActionScript | 📅 2009-04-17 - AS3/Erlang implementation of the Croquet project's TeaTime protocol.
* [XMPP](https://github.com/lyokato/as3xmppclient) ⭐ 8 | 🐛 2 | 🌐 ActionScript | 📅 2010-04-27 - Client-side implementation of XMPP library.
* [GIT](https://github.com/nexussays/git-as3) ⚠️ Archived - Client-side implementation of Git.
* [NTP](https://github.com/charlespalen/AS3-NTP-Implementation) ⭐ 6 | 🐛 1 | 🌐 ActionScript | 📅 2013-07-24 - Client-side implementation of NTP Client (Network Time Protocol).
* [XMPP](https://github.com/bluef/kuching) ⭐ 2 | 🐛 0 | 🌐 ActionScript | 📅 2010-01-09 - Lightweight implementation of XMPP library.
* [FUDI](https://github.com/matthiasbreuer/FUDI-as3) ⭐ 1 | 🐛 0 | 🌐 ActionScript | 📅 2010-02-23 - Client-side implementation of the Puredata FUDI protocol.

#### Email

* [AS3Mailer](https://github.com/Matan/AS3Mailer) ⭐ 9 | 🐛 1 | 🌐 ActionScript | 📅 2011-08-27 - Sends email using server script or invokes a mailto.
* [AIRXMail](https://github.com/hgupta9/AirXMail) ⭐ 5 | 🐛 1 | 🌐 ActionScript | 📅 2016-11-12 - Complete client-side email library supporting SMTP, POP3 and IMAP4.

## Utilities

#### Artificial Intelligence

* [Godmode-as3](https://github.com/tconkling/godmode-as3) ⭐ 27 | 🐛 4 | 🌐 ActionScript | 📅 2014-05-05 - Behavior tree implementation (artificial intelligence).
* [N-GramPredictor](https://github.com/pzUH/N-GramPredictor) ⭐ 4 | 🐛 0 | 🌐 ActionScript | 📅 2012-08-04 - n-Gram predictor for AI bot/agent.
* [FiniteStateMachine](https://github.com/pzUH/FiniteStateMachine) ⭐ 3 | 🐛 0 | 🌐 ActionScript | 📅 2012-07-21 - Finite State Machine for AI bot/agent.
* [DecisionTree](https://github.com/pzUH/DecisionTree) ⭐ 3 | 🐛 0 | 🌐 ActionScript | 📅 2012-04-19 - Binary decision tree for AI bot/agent.
* [Naive-BayesPredictor](https://github.com/pzUH/Naive-BayesPredictor) ⭐ 2 | 🐛 0 | 🌐 ActionScript | 📅 2012-04-19 - Naive-Bayes predictor for AI bot/agent.
* [HierarchicalStateMachine](https://github.com/pzUH/HierarchicalStateMachine) ⭐ 2 | 🐛 0 | 🌐 ActionScript | 📅 2012-07-21 - Hierarchical State Machine for AI bot/agent.
* [FuzzyStateMachine](https://github.com/pzUH/FuzzyStateMachine) ⭐ 2 | 🐛 0 | 🌐 ActionScript | 📅 2012-08-09 - Fuzzy State Machine (FuSM) for AI bot/agent.
* [SmartKid](https://github.com/skyfeiyun/SmartKid) - Powerful AI engine for 2D & 3D games.

#### Async

* [EasyAS-Worker](https://github.com/myflashlab/easyAS-Worker) ⭐ 47 | 🐛 5 | 🌐 ActionScript | 📅 2017-06-19 - Simplified wrapper for AIR Workers.
* [Worker-from-class](https://github.com/bortsen/worker-from-class) - Create Workers from Class definitions.

#### Crypto

* [AS3corelib](https://github.com/mikechambers/as3corelib) ⭐ 1,505 | 🐛 122 | 🌐 ActionScript | 📅 2024-08-18 -  MD5 and SHA1 hashing, Image encoders, and JSON serialization.
* [AS3Crypto](https://github.com/timkurvers/as3-crypto) ⚠️ Archived - Fork of Henri Torgemane's excellent cryptography library ([patched](https://github.com/lyokato/as3crypto_patched) ⭐ 16 | 🐛 0 | 🌐 ActionScript | 📅 2011-03-28).
* [BlooddyCrypto](https://github.com/blooddy/blooddy_crypto) ⭐ 94 | 🐛 15 | 🌐 ActionScript | 📅 2022-02-25 - High-performance library for processing binary data. This library contains MD5, SHA-1, SHA-2, Base64, CRC32, JSON, PNG/JPEG encoders.
* [ASCrypt](https://github.com/Meychi/ASCrypt) ⭐ 47 | 🐛 3 | 🌐 ActionScript | 📅 2015-02-07 - Crypto library with a similar API for multiple languages.
* [Nexuslib](https://github.com/nexussays/nexuslib-as3) ⚠️ Archived - Reflection, serialization, seeded random number generation, cryptography, networking, and more.
* [XXTEA-AS3](https://github.com/xxtea/xxtea-as3) ⭐ 5 | 🐛 0 | 🌐 ActionScript | 📅 2016-02-08 - XXTEA encryption algorithm library for ActionScript 3.
* [Hashlib](https://github.com/Corsaair/hashlib) ⭐ 1 | 🐛 1 | 🌐 ActionScript | 📅 2015-10-20 - Over 30 different hashing functions.
* [Gibberish-AES](https://github.com/NordMike/gibberish-aes-as3) ⭐ 0 | 🐛 0 | 🌐 ActionScript | 📅 2013-07-29 - A fully OpenSSL compliant ActionScript 3 library for AES encryption.

#### Data

* [AS3Commons Collections](https://github.com/AS3Commons/as3commons-collections) ⭐ 105 | 🐛 3 | 🌐 ActionScript | 📅 2011-09-19 - Sophisticated and high-performance collections & iterators for AS3.

#### Geometry

* [AS3geometry](https://github.com/alecmce/as3geometry) ⭐ 74 | 🐛 0 | 🌐 ActionScript | 📅 2011-10-27 - Primitives, Polygons, Intersections, etc.
* [Coral](https://github.com/richardlord/Coral) ⭐ 44 | 🐛 2 | 🌐 ActionScript | 📅 2017-04-16 - High-performance classes for 3D mathematics (Point, Vector, Matrix, Quaternion).
* [AS3GeomAlgo](https://github.com/azrafe7/as3GeomAlgo) ⭐ 43 | 🐛 1 | 🌐 ActionScript | 📅 2014-05-05 - Collection of geometry algorithms. Port of hxGeomAlgo.
* [AS3AStar](https://github.com/tomnewton/AS3AStar) ⭐ 22 | 🐛 1 | 🌐 ActionScript | 📅 2011-03-27 - Fast A-Star pathfinding algorithm.
* [As3Pathfinder](https://github.com/azakhary/As3Pathfinder) ⭐ 17 | 🐛 0 | 🌐 ActionScript | 📅 2017-07-02 - Grid Path finding Library written using Dijkstra's algorithm.
* [Csg.as](https://github.com/timknip/csg.as) ⭐ 8 | 🐛 0 | 🌐 ActionScript | 📅 2012-07-23 - Constructive Solid Geometry on 3D meshes.
* [A-star\_pathfinder](https://github.com/kevhiggins/a-star_pathfinder) ⭐ 3 | 🐛 0 | 🌐 ActionScript | 📅 2011-04-14 - A-Star pathfinding interface for tile based maps.
* [Hilbert](https://github.com/nodename/Hilbert) ⭐ 1 | 🐛 0 | 🌐 ActionScript | 📅 2011-07-13 - Port of Hilbert curve from cortesi/scurve.
* [PathUtils](https://github.com/alinakipoglu/Actionscript-PathUtils) - Working with quadratic, bezier and line sequences.

#### Math

* [FlashFormulaEditor](https://github.com/zasdfgbnm/FlashFormulaEditor) ⚠️ Archived - Formula editor made in Adobe Flex.
* [AS3eval](http://eval.hurlant.com/) - Packages the Tamarin ESC compiler to work within Flash Player. ([alternate](https://github.com/SimonRichardson/as3-eval) ⚠️ Archived).
* [AS3LinAlg](https://github.com/inspirit/AS3LinAlg) ⭐ 13 | 🐛 0 | 🌐 ActionScript | 📅 2012-10-29 - Linear Algebra library (Jacobi SVD, Eigen Vectors/Values, Cholesky LU, etc).
* [Zexpression](https://github.com/Xorcerer/zexpression) ⭐ 10 | 🐛 0 | 🌐 ActionScript | 📅 2014-03-04 - Parse and evalate math expressions with functions and variables.
* [FlexibleMatrix](https://github.com/Lukx/FlexibleMatrix) ⭐ 3 | 🐛 0 | 🌐 ActionScript | 📅 2010-10-02 - A multi purpose Matrix class.
* [AS3Units](https://github.com/erussell/AS3Units) ⭐ 1 | 🐛 0 | 🌐 ActionScript | 📅 2012-10-31 - Port of NGUnits. Parsing, formatting, and converting between units of measure.
* [Performance Primitives](https://github.com/martinkallman/performance-as3) - High-performance math modeled on the Intel Performance Primitives.

#### Text

* [Linkify-as3](https://github.com/CodeCatalyst/linkify-as3) ⚠️ Archived - Convert URLs, e-mail addresses, phone numbers, into clickable links.
* [AS3hyphenation](https://github.com/gka/as3hyphenation) ⭐ 1 | 🐛 1 | 🌐 ActionScript | 📅 2011-09-07 - Port of the Javascript text hyphenation library Hyphenator.js.

## Runtimes

#### Emulators

* [NES Emulator](https://github.com/nesbox/emulator) ⭐ 654 | 🐛 91 | 🌐 ActionScript | 📅 2015-08-02 - Emulator of NES, Super Nintendo, Sega Mega Drive, GameBoy video consoles.
* [Commodore 64 Emulator](https://github.com/claus/fc64) ⚠️ Archived - A low level Commodore 64 emulator written in Actionscript 3.
* [8080 Emulator](https://github.com/ozipi/As3_SpaceInvaders_Emulator) ⭐ 7 | 🐛 0 | 🌐 ActionScript | 📅 2009-12-08 - An actionscript 3 space invaders emulator based on the intel 8080 processor.
* [8-bit VM](https://github.com/OutOfTheVoid/AS3-8-bit-VM) ⭐ 6 | 🐛 0 | 🌐 ActionScript | 📅 2012-11-22 - An eight bit virtual machine written in actionscript.

#### Interpreters

* [Lisp Compiler](https://github.com/aemoncannon/las3r) ⭐ 94 | 🐛 9 | 🌐 ActionScript | 📅 2011-01-29 - A lisp compiler for the AVM2.
* [Simple JS](https://github.com/sixsided/Simplified-JavaScript-Interpreter) ⭐ 20 | 🐛 0 | 🌐 ActionScript | 📅 2014-02-27 - AS3-based Javascript interpreter.
* [JS](https://github.com/theturtle32/RhinoAS3) ⚠️ Archived - RhinoJS, Port of Mozilla's Rhino JavaScript interpreter.
* [CannonML](https://github.com/abiyasa/cannonml_as3) ⭐ 3 | 🐛 0 | 🌐 ActionScript | 📅 2012-04-20 - keim's CannonML (shmup scripting language) interpreter.
* [MIL](https://github.com/ser1zw/MIL) ⭐ 2 | 🐛 0 | 🌐 ActionScript | 📅 2010-07-27 - A MIL language VM and interpreter written in ActionScript.
* [TALES](https://github.com/oaubert/tales4as) ⭐ 2 | 🐛 0 | 🌐 ActionScript | 📅 2012-01-20 - TALES interpreter for ActionScript.
* [Scheme](https://github.com/hrundik/fScheme) ⭐ 1 | 🐛 0 | 🌐 ActionScript | 📅 2011-05-07 - Scheme interpreter in ActionScript.
* [Lisp](https://github.com/rzubek/as_lisp) ⭐ 1 | 🐛 0 | 🌐 ActionScript | 📅 2013-11-25 - Lisp dialect written in Actionscript, with compiler and bytecode interpreter.

## AIR Native Extensions

#### Audio ANE

* [SystemVolume](https://github.com/nweber/SystemVolumeNativeExtension) ⭐ 55 | 🐛 8 | 🌐 ActionScript | 📅 2012-08-03 - Interact with the system volume for iOS and Android devices.
* [SilentSwitch](https://github.com/StickSports/ANE-Silent-Switch) ⭐ 36 | 🐛 9 | 🌐 ActionScript | 📅 2017-06-05 - ANE for iOS to mute sounds if the hardware silent switch is on.
* [SongPicker](https://github.com/richpixel/SongPickerANE) ⭐ 26 | 🐛 11 | 🌐 ActionScript | 📅 2015-09-11 - A song picker/player ANE for iOS and Android.
* [VolumePro](https://github.com/myflashlab/VolumePro-ANE) ⚠️ Archived - Control native music stream volume and you can listen to the volume changes.

#### Multimedia ANE

* [WebView (Tuarua)](https://github.com/tuarua/WebViewANE) ⭐ 189 | 🐛 10 | 🌐 ActionScript | 📅 2026-07-01 - Modern WebView for OSX 10.10+, Windows Desktop, iOS 9.0+ and Android 21+. Uses CEF (Chromium Embedded Framework) on Windows, WKWebView on iOS/OSX, and WebView on Android.
* [QR-zbar](https://github.com/saumitrabhave/qr-zbar-ane) ⭐ 84 | 🐛 14 | 🌐 ActionScript | 📅 2020-07-24 - ANE for QR Code Reader.
* [AVANE](https://github.com/tuarua/AVANE) ⚠️ Archived - For building video encoding applications using FFmpeg.
* [WebView (FlashLab)](https://github.com/myflashlab/webView-ANE) ⚠️ Archived - Replacement for StageWebView, allows calling Javascript functions from AIR.
* [MyAR](https://github.com/myflashlab/AR-ANE-Samples) ⚠️ Archived - AR ANE supporting Android and iOS 64-bit based on Metaio's SDK.
* [Bullet](https://github.com/mziwisky/bullet-ane) ⭐ 40 | 🐛 1 | 🌐 ActionScript | 📅 2015-08-25 - Bullet physics simulation library.
* [VideoPlayer](https://github.com/myflashlab/videoPlayer-ANE) ⚠️ Archived - Play video files in Android or iOS native video player.
* [Barcode](https://github.com/myflashlab/barcode-ANE) ⚠️ Archived - Scan almost any barcode type with this super fast barcode scanner ANE.
* [Speech](https://github.com/myflashlab/speech-ANE) ⚠️ Archived - Convert strings to voice files and vice versa fully in the background.
* [SurfaceVideoPlayer](https://github.com/myflashlab/surfaceVideoPlayer-ANE) ⚠️ Archived - SurfacePlayer ANE helps you play video files inside your air mobile projects.
* [PDF](https://github.com/myflashlab/PDF-ANE) ⚠️ Archived - Lets you open PDF files from your AIR mobile apps. Supported on Android and iOS.

#### File System ANE

* [FileChooser](https://github.com/myflashlab/fileChooser-ANE) ⚠️ Archived - Enable users to select a file from the device filesystem.
* [ZipManager](https://github.com/myflashlab/zipManager-ANE) ⚠️ Archived - Zip or unzip large zip archives super fast using native process on Android and iOS.
* [Spotlight](https://github.com/myflashlab/Spotlight-ANE) ⚠️ Archived - Integrate with iOS 9 Spotlight Search, to index search items and user generated content.

#### Networking ANE

* [Firebase](https://github.com/myflashlab/Firebase-ANE) ⚠️ Archived - API for Google Firebase on Android and iOS with 100% identical ActionScript API.
* [BitTorrent](https://github.com/tuarua/BitTorrentANE) ⭐ 20 | 🐛 0 | 🌐 C++ | 📅 2023-10-04 - For building BitTorrent enabled applications.
* [DownloadManager](https://github.com/myflashlab/downloadManager-ANE) ⚠️ Archived - Download large data files with pause/resume support.

#### Hardware ANE

* [LeapMotionAS3](https://github.com/logotype/LeapMotionAS3) ⭐ 308 | 🐛 5 | 📅 2021-07-18 - ANE for LeapMotion sensor (provides Gestures, Image, Skeleton/Bone @ 210 FPS).
* [AIRKinectv2](https://github.com/Tastenkunst/AIRKinectv2) ⭐ 53 | 🐛 5 | 🌐 ActionScript | 📅 2015-05-06 - ANE for Microsoft Kinect v2 for Windows SDK.
* [Serial/MIDI/DMX](https://github.com/benkuper/AIR-NativeExtensions) ⭐ 49 | 🐛 0 | 🌐 ActionScript | 📅 2020-07-03 - AIRBonjour, NativeSerial, NativeDMXController, NativeMIDI, VirtualMIDI, ExtendedMouse.
* [AIROUYAController](https://github.com/gaslightgames/AIROUYAController) ⚠️ Archived - ANE for the OUYA Controller.
* [Joystick-ANE](https://github.com/StackAndHeap/joystick-ane) ⭐ 18 | 🐛 2 | 🌐 ActionScript | 📅 2013-02-10 - ANE Joystick Library.
* [AIRControl](https://github.com/AlexanderOMara/AIRControl) ⭐ 17 | 🐛 0 | 🌐 ActionScript | 📅 2013-07-23 - Adobe AIR Game Controller ANE.
* [GoogleVR](https://github.com/myflashlab/GoogleVR-ANE) ⚠️ Archived - Google Virtual Reality SDK available to AIR developers.
* [GPS](https://github.com/myflashlab/GPS-ANE) ⚠️ Archived - Get current device GPS location as fast as possible by automatically checking the best available provider.
* [Bluetooth](https://github.com/myflashlab/bluetooth-ANE) ⚠️ Archived - Scan for other devices, connect to and pair with them and transfer data between them.

#### System ANE

* [Can-Open-URL](https://github.com/StickSports/ANE-Can-Open-URL) ⭐ 36 | 🐛 3 | 🌐 ActionScript | 📅 2017-04-24 - ANE for iOS to detect whether an app is installed to handle a specific URL scheme.
* [DesktopToast](https://github.com/tuarua/DesktopToastANE) ⭐ 28 | 🐛 0 | 🌐 C++ | 📅 2023-03-04 - Display interactive toast notifications in Windows 8/10 and OSX.
* [InAppPayments](https://github.com/myflashlab/inAppPayments-ANE) ⚠️ Archived - Identical in-app-billing and in-app-purchase ANE for Android and iOS.
* [TaskbarProgress](https://github.com/tuarua/TaskbarProgressANE) ⭐ 13 | 🐛 0 | 🌐 Shell | 📅 2023-03-04 - Display taskbar progress on OSX & Windows 7/8/10 .
* [PermissionCheck](https://github.com/myflashlab/PermissionCheck-ANE) ⚠️ Archived - Check and request for permissions in your Adobe Air app.
* [RateMe](https://github.com/myflashlab/RateMe-ANE) ⚠️ Archived - Ask your users to rate your app in the most efficient way.
* [AlarmManager](https://github.com/myflashlab/alarmManager-ANE) ⚠️ Archived - Run a scheduled task even if your AIR app is closed.
* [Statusbar](https://github.com/myflashlab/Statusbar-ANE) ⚠️ Archived - Control the Statusbar in your AIR apps in runtime.
* [Badge](https://github.com/myflashlab/Badge-ANE) ⚠️ Archived - Control the iOS badge value.
* [WinDebug](http://www.henke37.cjb.net/windebug/) - Windows ANE to control applications, windows, memory, breakpoints, metadata, registry, etc.

#### Social ANE

* [Facebook](https://github.com/myflashlab/facebook-ANE) ⚠️ Archived - Integrate Facebook SDK into your AIR apps.
* [GCM](https://github.com/myflashlab/GCM-ANE) ⚠️ Archived - Use Google Cloud messaging on Android and iOS. .
* [Baidu](https://github.com/lilili87222/baidu-ane-for-ios-and-android) - Baidu ANE for for iOS and Android.

#### Analytics ANE

* [Chartboost](https://github.com/ChartBoost/air) ⭐ 42 | 🐛 2 | 🌐 ActionScript | 📅 2015-07-29 - ANE for the Chartboost SDK with compile scripts.
* [Testflight](https://github.com/jlopez/ane-testflight) ⭐ 25 | 🐛 5 | 🌐 ActionScript | 📅 2012-12-03 - Apple TestFlight ANE.
* [Admob](https://github.com/myflashlab/Admob-ANE) ⚠️ Archived - Admob ANE.
* [UMAnalytics](https://github.com/ColerYu/ANE-UMAnalytics) ⭐ 11 | 🐛 3 | 🌐 ActionScript | 📅 2015-01-17 - ANE for UMAnalytics SDK (iOS and Android).
* [Localytics](https://github.com/randori/ANE-Localytics) ⭐ 10 | 🐛 4 | 🌐 ActionScript | 📅 2012-06-22 - Localytics analytics for mobile Adobe AIR applications (iOS & Android).
* [Devtodev](https://github.com/devtodev-analytics/air-sdk) ⭐ 6 | 🐛 0 | 📅 2020-08-24 - A full-cycle analytics solution for game developers.
* [GameServices](https://github.com/myflashlab/GameServices-ANE) ⚠️ Archived - Google Game Services for Android+iOS.
* [HockeyApp](https://github.com/airext/hockeyapp) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2021-08-27 - ANE for the Hockeyapp testing & distribute platform.
* [MoPub](https://github.com/StickSports/MoPub-ANE) - ANE for MoPub advertising.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-14._
