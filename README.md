# ![Awesome Löve](logo.png) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A categorized community-driven collection of high-quality, awesome [LÖVE](http://love2d.org) libraries, projects, and resources.

## Table of contents

* [3D](#3d)
* [AI](#ai)
* [Animation](#animation)
* [Camera](#camera)
* [Development](#development)
* [Drawing](#drawing)
* [Entity](#entity)
* [Helper Libraries](#helper)
* [Input](#input)
* [Lighting](#lighting)
* [Math](#math)
* [Music](#music)
* [Networking](#networking)
* [Object Orientation](#object)
* [Performance](#performance)
* [Physics](#physics)
* [Platforms](#platforms)
* [Publishing](#publishing)
* [Serialization](#serialization)
* [Shaders](#shaders)
* [Testing](#testing)
* [Tweening](#tweening)
* [UI](#ui)
* [Utilities](#utilities)
* [Tutorials](#tutorials)
* [IDEs](#ides)

## 3D
*3D-centric Libraries*

* [anim9](https://github.com/excessive/anim9) - 3D skeletal animation library (design to be used with IQM and IQE)
* [IQE](https://github.com/excessive/iqe) - Inter-Quake Export loader (text)
* [IQM](https://github.com/excessive/iqm) - Inter-Quake Model loader (binary)
* [LÖVE3D](https://github.com/excessive/love3d) - 3D extensions to LÖVE
* [Lovox](https://github.com/tjakka5/Lovox) - Pseudo-3D library for working with voxels

## AI
*Navigation, Decision-Making and AI Libraries*

* [Jumper](https://github.com/Yonaba/Jumper) - Grid-based pathfinding library

## Animation
*Animation & Frame-Managing Libraries*

* [anim8](https://github.com/kikito/anim8) - Animation library
* [chiro](https://github.com/bjornbytes/chiro) - Convenience wrapper around [Spine](http://esotericsoftware.com)
* [skeletor](https://github.com/pelevesque/skeletor) - 2D skeletal animation system
* [Sodapop](https://github.com/tesselode/sodapop) - Sprite and animation library
* [Walt](https://github.com/davisdude/Walt) - Animation library
* [Lump](https://github.com/sixFingers/lump) - Adobe Flash animation runtime

## Camera
*Viewport & Camera Libraries*

* [Brady](https://github.com/davisdude/Brady) - Camera library with parallax scrolling
* [Editgrid](https://github.com/bakpakin/Editgrid) - Gamera and HUMP compatible scaling grid
* [gamera](https://github.com/kikito/gamera) - Camera system
* [hump.camera](http://hump.readthedocs.io/en/latest/camera.html) - Camera library with window locking and smooth camera movement interpolation

## Development
*Development assisting Libraries, that enrich your development experience*

* [FPSGraph](https://github.com/icrawler/FPSGraph) - Small FPS graphing utility
* [debugGraph](https://github.com/Mechazawa/Love-Debug-Graph) - Small OO FPS graphing utillity based on FPSGraph
* [Lovebird](https://github.com/rxi/lovebird) - Browser-based debug console
* [Lovecat](https://github.com/CoffeeKitty/lovecat) - Edit your game parameters in a browser and see the changes in the running game in real time
* [LoveDebug](https://github.com/Ranguna/LOVEDEBUG) - Inline console-like debugger utility
* [lurker](https://github.com/rxi/lurker) - Auto-swaps changed Lua files in a running game
* [LÖVE API](https://github.com/love2d-community/love-api) - The complete API documentation of LÖVE in a Lua table

## Drawing
*Drawing specific Libraries, that simplify the Drawing process*

* [draft](https://github.com/pelevesque/draft) - A module for drawing complex shapes
* [Artal](https://github.com/unXedDani/Artal) - A .PSD parsing library for LÖVE
* [Autobatch](https://github.com/rxi/autobatch) - Small LÖVE module to automate the use of SpriteBatches
* [Maid64](https://github.com/adekto/maid64) - Low resolution scaler for LÖVE
* [renderplanet](https://github.com/meric/renderplanet/) - realistic orthographic planet rendering
* [Sölar](https://github.com/JanWerder/soelar) - a fairly simple solar system simulator
* [svglover](https://github.com/globalcitizen/svglover) - Library to import and display simple SVGs in LÖVE

## Entity
*Entity and Gameobject Managing Libraries*

* [adorbs](https://github.com/JosephShering/adorbs) - Minimal, Functional Entity Component System
* [knife.system](https://github.com/airstruck/knife/blob/master/readme/system.md) - Minimalist functional ECS
* [tiny-ecs](https://github.com/bakpakin/tiny-ecs) - Entity Component System for Lua that's simple, flexible, and useful

## <a name="helper"></a>Helper Libraries
*Game specific Library bundles, that provide reuseable functions*

* [astray](https://github.com/SiENcE/astray) - Astray is a lua based maze, room and dungeon generation library for dungeon crawlers and rougelike video games
* [hump](https://github.com/vrld/hump) - Collection of tools for developing games with LÖVE (Gamestates, Timers/Tweens, Vectors, Classes, Signals, Cameras)
* [knife](https://github.com/airstruck/knife) - Collection of useful micro-modules for Lua (Class, State Machines, Bind, Chain, Coroutines, Event, Memoize, Entity, Tests, Timer)
* [lue](https://github.com/Ulydev/lue) - lue is a LÖVE library that allows you to display hue color effects in your game
* [lume](https://github.com/rxi/lume/) - Collection of functions for Lua, geared towards game development
* [rotLove](https://github.com/paulofmandown/rotLove) - Roguelike Toolkit in Love. A Love2D/lua port of rot.js
* [ScreenManager](https://github.com/rm-code/screenmanager) - Screen/State Management for the LÖVE framework
* [shack](https://github.com/Ulydev/shack) - shack is a LÖVE library that lets you easily add screen effects such as shake and rotation
* [Simple Tiled Implementation](https://github.com/karai17/Simple-Tiled-Implementation) - Tiled map loader and renderer
* [Vivid](https://github.com/WetDesertRock/vivid) - Color math, manipulation and conversion library

## Input
*Input & Binding Libraries*

* [baton](https://github.com/tesselode/baton) -  Input library for LÖVE that bridges the gap between keyboard and gamepad controls
* [boipushy](https://github.com/adonaac/boipushy) - A simple and easy to use input handler
* [love-microphone](https://github.com/LPGhatguy/love-microphone) - Simple microphone support for LÖVE
* [tactile](https://github.com/tesselode/tactile) - A straightforward and flexible input library

## Lighting
*Lighting & Shadow Libraries*

* [Light World](https://github.com/tanema/light_world.lua) - A lighting model

## Math
*Math specific Libraries*

* [Cirno's Perfect Math Library](https://github.com/excessive/cpml) - Math/intersection library designed for games
* [delaunay](https://github.com/Yonaba/delaunay) - Delaunay triangulation for convex polygons
* [MLib](https://github.com/davisdude/mlib) - Math and shape-intersection detection library written in Lua. It's aim is to be robust and easy to use
* [hump.vector](http://hump.readthedocs.io/en/latest/vector.html) - Powerful 2D vector class
* [Bresenham](https://github.com/rm-code/Bresenham) - Bresenham's line algorithm written in Lua

## Music
*Music related libraries*

* [ripple](https://github.com/tesselode/ripple) - An audio library for sound effects and music
* [wave](https://github.com/Ulydev/wave) - A sound manager with audio parsing and rhythm functionalities
* [denver](https://github.com/superzazu/denver.lua) - A Löve custom waveform generation library

## Networking
*Networking & Online-Play Libraries*

* [Grease](https://github.com/bartbes/love-misc-libs/tree/master/grease) - Networking library intended to make networking easy for lovers (TCP, UDP, Enet)
* [NoobHub](https://github.com/Overtorment/NoobHub) - OpenSource multiplayer and network messaging
* [Sock.lua](https://github.com/camchenry/sock.lua) - A Lua networking library for LÖVE games

## <a name="object"></a>Object Orientation
*Object Orientation Libraries that support [Class-Commons](https://github.com/bartbes/Class-Commons)*

* [30log](https://github.com/Yonaba/30log) - Minified framework for object-orientation in Lua. It features named (and unnamed) classes, single inheritance and a basic support for mixins
* [classic](https://github.com/rxi/classic/) - Tiny class module for Lua. Attempts to stay simple and provide decent performance by avoiding unnecessary over-abstraction
* [hump.class](http://hump.readthedocs.io/en/latest/class.html) - Small, fast class/prototype implementation with multiple inheritance (class-commons)
* [knife.base](https://github.com/airstruck/knife/blob/master/readme/base.md) - Extremely minimal base class providing single inheritance and constructors.
* [middleclass](https://github.com/kikito/middleclass) - Simple OOP library for Lua; has inheritance, metamethods (operators), class variables and weak mixin support (class-commons)

## Performance
*Performance measurement tools*

* [Piefiller](https://github.com/Polynominal/Piefiller) - Graphical profiler for LÖVE
* [profile.lua](https://bitbucket.org/itraykov/profile.lua/src/) - Profile.lua is a small, non-intrusive module for finding bottlenecks in your Lua code
* [ProFi](https://gist.github.com/rm-code/383c98a6af04652ed9f39b7ae536bcc5) - A simple lua profiler that works with LuaJIT and prints a pretty report file in columns

## Physics
*Collision Detection & Physics Wrappers*

* [Bump](https://github.com/kikito/bump.lua) - Collision detection library for Lua
* [HC](http://vrld.github.io/HardonCollider/) - Collision detection with arbitrary polygons; allows rotation of objects

##Platforms
*Ports for Platforms other than Windows, Mac and Linux*

* [LoveDos](https://github.com/rxi/lovedos) - A Lua framework for 2D DOS games, implementing a subset of the LÖVE API
* [LoveFTW](https://bitbucket.org/T-BoneISS/l-veftw) - Work-in-progress port to Windows phone 8.1
* [LovePotion](https://github.com/VideahGams/LovePotion) - Unofficial work-in-progress implementation of the LÖVE API for 3DS Homebrew
* [Love.js](https://github.com/TannerRogalsky/love.js) - LÖVE ported to the web using Emscripten

## Publishing
*Guides to distributing LÖVE games in 3rd party stores*

* [Love-Snap-Template](https://github.com/popey/love-snap-template) - A template for packaging LÖVE games for distribution in the Snappy Store

## Serialization
*Save Game & Storage Libraries*

* [binser](https://github.com/bakpakin/binser) - Customizable Lua Serializer
* [cdata](https://github.com/excessive/cdata) - Serialize between Lua data and C data using LuaJIT's FFI
* [knife.serialize](https://github.com/airstruck/knife/blob/master/readme/serialize.md) - Serialize data as a Lua script
* [Lady](https://github.com/gvx/Lady) - Saving and loading savegames; based on Ser
* [Ser](https://github.com/gvx/Ser) - Fast, robust, richly-featured table serialization library for Lua
* [Smallfolk](https://github.com/gvx/Smallfolk) - A fast, robust, secure, richly-featured table serialization library for Lua
* [trickle](https://github.com/bjornbytes/trickle) - A bitstream library focused on high compression for use in networking

## Shaders
*GLSL related Libraries*

* [LoveShaderConverter](https://github.com/tsteinholz/LoveShaderConverter) - Convert Shadertoy Shader files to LÖVE GLSL Files with handy utilities for infinite purposes
* [Shadertoy viewer](http://love2d.org/forums/viewtopic.php?f=5&t=80885) - Run code copied from shadertoy directly or output the converted code to a LÖVE shader
* [shine](https://github.com/vrld/shine) - Repository of common post-processing effects like blur, vignette, color-grading, etc.

## Testing
*Libraries and Tools for Unit Testing*

* [busted](http://olivinelabs.com/busted/) - Simple unit-testing framework with customizable assertions
* [knife.test](https://github.com/airstruck/knife/blob/master/readme/test.md) - Fixture-free test framework
* [Luassert](https://github.com/Olivine-Labs/luassert) - Extends `assert()` with additional, customizable tests
* [lua-TestMore](http://fperrad.github.io/lua-TestMore/) - Port of Perl's `Test::More` package
* [Lunatest](https://github.com/silentbicycle/lunatest) - xUnit-style randomized unit testing framework
* [lust](https://github.com/bjornbytes/lust) - Minimal test framework
* [Specl](http://gvvaughan.github.io/specl/) - Behavior Driven Development (BDD) tool
* [Telescope](http://norman.github.io/telescope/) - Highly-customizable BDD-style testing library

## Tweening
*Smoothing & Timer Libraries*

* [Flux](https://github.com/rxi/flux) - A fast, lightweight tweening library for Lua
* [hump.timer](http://hump.readthedocs.io/en/latest/timer.html) - Timer and tweening library with flexible tweening methods
* [knife.timer](https://github.com/airstruck/knife/blob/master/readme/timer.md) - Create timers and tweens with ease.
* [tween.lua](https://github.com/kikito/tween.lua) - Tweening/Easing/Interpolating functions for Lua inspired on jQuery's animate method

## UI
*User Interface Libraries*

* [CatUI](https://github.com/wilhantian/catui) - A very light-weight GUI library for LÖVE
* [GOOi](https://github.com/tavuntu/gooi) - Android-oriented GUI library
* [Gspöt](https://github.com/pgimeno/Gspot) - A stateful GUI lib for LÖVE
* [LoveFrames Fork](https://github.com/unek/LoveFrames/commits/master) - 0.10 Fork of a GUI library
* [Love Imgui](https://github.com/slages/love-imgui) - imgui module for the LÖVE game engine
* [Löve-Nuklear](https://github.com/keharriso/love-nuklear) - Lightweight immediate mode GUI for LÖVE games
* [Patchy](https://github.com/excessive/patchy) - 9patch library
* [Polywell](https://gitlab.com/technomancy/polywell) - A highly-configurable text editor / coding tool written in Lua that runs on the LÖVE game engine.
* [SafeWord](https://github.com/josefnpat/safeword) - An overscan detection library for LÖVE
* [SUIT](https://github.com/vrld/SUIT) - small immediate mode GUI library

## Utilities
*Non-Game specific Library bundles, that provide reuseable functions*

* [cargo](https://github.com/bjornbytes/cargo) - Asset manager
* [chance.lua](http://ejmr.github.io/chance.lua/) - Library for generating random data
* [GifCat](https://github.com/WetDesertRock/GifCat) - A simple module for saving gifs from LÖVE
* [i18n](https://github.com/excessive/i18n) - Internationalization library designed to help localize your game
* [log.lua](https://github.com/rxi/log.lua) - Library for configurable log output
* [love-loader](https://github.com/kikito/love-loader) - Threaded resource loading
* [love2d-assets-loader](https://github.com/Yonaba/love2d-assets-loader) - Assets Loader
* [Luvent](https://github.com/ejmr/Luvent) - Simple event-driven programming
* [splashy](https://github.com/VideahGams/splashy) - Splash Screen Library
* [Talkback](https://github.com/tesselode/talkback) - Observer pattern library with two-way communication
* [tick](https://github.com/bjornbytes/tick) - Useful timing tweaks for LÖVE's run loop

## Tutorials
*Blogs and tutorials*

* [adonaac's](https://github.com/adonaac/blog) - A blog by [adonaac](https://github.com/adonaac) with articles about game development using LÖVE
* [Using Tiled Maps in LÖVE](http://lua.space/gamedev/using-tiled-maps-in-love) - An article about using maps created with Tiled in your LÖVE game
* [Tutorial on making an Arkanoid-type game](https://github.com/noooway/love2d_arkanoid_tutorial/wiki) - A complete tutorial on how to make a breakout clone by nooowaay
* [Simple Game Tutorials](https://simplegametutorials.github.io/) - Tutorials for making simple games with LÖVE (Snake, Sokoban, Tetris, etc.)
* [How to LÖVE](http://sheepolution.com/learn/book/contents) - A book by Sheepolution teaching LÖVE from the ground up

## IDEs
*Integrated Development Enviroments and text editor plugins*

* [Atom](https://atom.io/) - A hackable text editor for the 21st Century
	* [Löve Atom](https://atom.io/packages/love-atom) - A lövely provider for Atom's autocomplete+ package
	* [Löve IDE](https://atom.io/packages/love-ide) - This package auto-installs several utilities for writing Love2D games in Atom
		* [Autocomplete Löve](https://atom.io/packages/autocomplete-love) - Auto-complete and snippets for LÖVE
		* [Hyperclick Löve](https://atom.io/packages/hyperclick-love) - A Hyperclick provider for LÖVE which shows the wiki
	* [Löve Launcher](https://atom.io/packages/love-launcher) - Launch LÖVE 2D for the current project without having to leave Atom
	* [language-lua](https://github.com/FireZenk/language-lua) - Lua language support in Atom
	* [linter-luacheck](https://github.com/AtomLinter/linter-luacheck) - Lint Lua on the fly, using luacheck
* [Brackets](https://brackets.io/) - A modern, open source text editor by Adobe
	* [Lua Syntax Highlighter](https://github.com/ForbesLindesay/brackets-language-extensions) - Add Lua syntax highlighting in Brackets
	* [LÖVE Hints for Brackets.io](https://gitlab.com/sdonalcreative/brackets-love-hints/) - Provides LÖVE code hints
	* [Run LÖVE](https://github.com/instilledbee/run-love2d) - Run LÖVE projects with a hotkey.
* [ZeroBrane Studio](https://studio.zerobrane.com/) - ZeroBrane Studio is a lightweight Lua IDE with code completion, syntax highlighting, live coding, code analyzer, and debugging support
* [LÖVE IDEA](https://github.com/rm-code/love-IDEA-plugin) - Snippets and code completion for [IntelliJ IDEA](https://www.jetbrains.com/idea/)
* [Vim LOVE Docs](https://github.com/davisdude/vim-love-docs) - Syntax highlighting for [Vim](http://www.vim.org)
* [LÖVE API for Notepad++](https://github.com/dail8859/love-api-npp) - Code completion and documentation for [Notepad++](https://notepad-plus-plus.org/)
* [Visual Studio Code LÖVE Launcher](https://marketplace.visualstudio.com/items?itemName=JanW.love-launcher) - A Löve Launcher Extension for Visual Studio Code

# Contributing

Please see [CONTRIBUTING](https://github.com/love2d-community/awesome-love2d/blob/master/CONTRIBUTING.md) for details.

# Other Awesome Lists

* [awesome-lua](https://github.com/LewisJEllis/awesome-lua) - A list like this one, but more general and encompassing all of Lua's uses
* [awesome-love-shaders](https://github.com/karai17/awesome-love-shaders) - A collection of shaders designed to work in LÖVE
* [awesome-pico8](https://github.com/felipebueno/awesome-PICO-8) - A curated list of PICO-8 resources, tutorials, tools and more

Other awesome lists can be found in the [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) list.
