# Awesome Uxn [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Curated list of awesome Uxn projects from the community.

The [Uxn](https://100r.co/site/uxn.html) ecosystem is a personal computing playground, created to host small tools and games, programmable in its own unique assembly language.

## Documentation

- [Varvara](https://wiki.xxiivv.com/site/varvara.html) - Technical documentation of the Varvara computer and a list of all its devices.
- [Uxntal](https://wiki.xxiivv.com/site/uxntal.html) - Uxntal language reference manual.
- [Uxntal opcode manual](https://wiki.xxiivv.com/site/uxntal_reference.html) - List of Uxntal opcodes and their effects.
- [Sprite format](https://wiki.xxiivv.com/site/chr_format.html) - `.chr` file format description.
- [Font format](https://wiki.xxiivv.com/site/ufx_format.html) - `.ufx` file format description.
- [Uxntal Cheatsheet](https://github.com/weeble/uxn-cheatsheet) - Opcode Cheatsheet.

## Tutorials

- [Uxn Tutorial by Compudanzas](https://compudanzas.net/uxn_tutorial.html) - Beginner-friendly tutorial guide which covers the basics of Uxn programming.
- [Uxn Tutorial by Compudanzas(video)](https://www.youtube.com/watch?v=LrNuq_JgaOA) - Beginner-friendly video workshop which covers the basics of Uxn programming.
- [Learn Uxntal in Y minutes](https://learnxinyminutes.com/docs/uxntal/) - Quick Uxntal guide.
- [Uxn implementation guide](https://github.com/DeltaF1/uxn-impl-guide) - Notes on how to implement the Uxn/Varvara virtual machine specification.
- [macOS installation](https://eli.li/2021/09/27/how-to-install-uxn-on-macos)
- [Windows installation](https://itch.io/t/1605965/a-quick-guide-to-running-this-software)
- [Android installation](https://llllllll.co/t/uxn-virtual-computer/46103/253) - Guide for running Uxn on the Android operating system through Termux.
- [HaikuOS](https://discuss.haiku-os.org/t/uxn-ecosystem-on-haiku/12209) - Forum thread for the Haiku operating system.

## Emulators

* Desktop

  - [Uxn](https://git.sr.ht/~rabbits/uxn) - Cross-platform emulator and assembler, written in C(SDL2).
  - [Uxn32](https://github.com/randrew/uxn32) - Windows emulator, written in C.
  - [Uxn11](https://git.sr.ht/~rabbits/uxn11) - Linux emulator, written in C.
  - [UxnFb](https://git.badd10de.dev/uxnfb) - Linux framebuffer emulator, written in C.
  - [UxnRPI](https://git.badd10de.dev/uxnrpi) - RaspberryPi framebuffer emulator, written in C. (no input support)
  - [UxnAmiga](https://code.mathr.co.uk/uxn-amiga) - AmigaOS emulator, written in C. (no keyboard or joystick input, no audio support)
  - [UxnEssence](https://gitlab.com/nakst/essence/-/tree/master/ports/uxn) - [Essence](https://gitlab.com/nakst/essence) emulator, written in C.
  - [UxnJulia](https://github.com/Ismael-VC/Varvara.jl) - Cross-platform emulator and assembler, written in Julia.
  - [UxnLua](https://github.com/DeltaF1/uxn-lua) - Cross-platform emulator, written in Lua(Love2d).
  - [Uxn38](http://zzo38computer.org/fossil/uxn.ui) - Emulator written in C with SDL1.
  - [Nux](https://github.com/nf/nux) - Emulator written in Go.
  - [uxn-rs](https://github.com/Liorst4/uxn-rs) - Emulator written in Rust.
  - [ruxn](https://github.com/CrashAndSideburns/ruxn) - A Uxn library written in Rust, intended to make defining new Uxn-based systems easy.
  - [zuxn](https://github.com/chmod222/zuxn) - A Uxn library, emulator and assembler written in Zig.

* Other systems

  - [FPGA](https://github.com/tsalvo/uxn-fpga) - Nearly Complete.
  - [RPi](https://github.com/ar-nelson/uxnpi) - Nearly Complete.
  - [Game Boy Advance](https://git.badd10de.dev/uxngba) - Complete.
  - [Nintendo 64](https://git.badd10de.dev/uxn64) - Complete.
  - [Nintendo DS](https://github.com/asiekierka/uxnds) - Complete.
  - [Playdate](https://git.sr.ht/~rabbits/uxn-playdate) - Complete.
  - [Nook eReader](https://git.badd10de.dev/uxnnst/) - Complete.
  - [Nokia N900](https://git.sr.ht/~foura/uxn900) - Partial.
  - [Game Boy](https://github.com/tbsp/uxngb) - Experimental.
  - [DOS](https://git.sr.ht/~rabbits/uxn-vga) - Implemented: Core, Screen, Mouse, Controller.
  - [Teletype](https://github.com/csboling/teluxn) - Incomplete.
  - [ESP32](https://github.com/max22-/uxn-esp32) - Incomplete.
  - [iOS](https://github.com/paiv/uxn-ios) - Nearly Complete (missing midi and controller).
  - [iOS](https://github.com/kylestew/UxniOS) - Incomplete.
  - [STM32](https://github.com/kylestew/armuxn) - Incomplete.
  - [STM32duino](https://github.com/cassvs/arduxno-demo) - Incomplete.
  - [IBM PC](https://github.com/cr1901/pcuxn) - Incomplete.
  - [PlayStation Vita](https://github.com/ivodopiviz/uxnvita) - Incomplete.
  - [PlayStation Portable](https://codeberg.org/tbsp/VarvaraPSP) - Nearly Complete (missing keyboard).
  - [Atari ST](https://framagit.org/Bartitsu59/stuxn) - Incomplete.

* Misc

  - [Libretro port](https://github.com/kivutar/uxn) - [Libretro](https://www.libretro.com/) emulation layer.
  - [LearnUxn](https://git.sr.ht/~metasyn/learn-uxn/) - Web assembler and emulator.
  - [Grid](https://tildegit.org/nihilazo/grid-uxn) - Incomplete.
  - [Rockbox](https://tilde.town/~nihilazo/varvara_rockbox.html) - Implemented: Core, Screen.
  - [Logisim](https://github.com/DeltaF1/uxn-logisim) - Incomplete.
  - [Adafruit PyBadge](https://git.sr.ht/~poyu/uxn-pybadge) - Implemented: Core, Console, Screen, Controller.
  - [Webuxn](https://github.com/aduros/webuxn) - Lightweight port of the Uxn virtual machine to the web via WebAssembly.
  - [auxn](https://github.com/saucesaft/auxn) - uxn running inside of an audio plugin (standalone mode included)
  - [UxnWasm](https://github.com/remko/uxn.wasm) - WebAssembly implementation of the Uxn core.

* Simulator

  - [uxn.py](https://github.com/max22-/uxnemu.py) - Python implementation of the VM.
  - [uxn.js](https://git.sr.ht/~rabbits/uxn5) - Javascript implementation of the VM.

## Applications

* Creative

  - [Left](https://wiki.xxiivv.com/site/left.html) - Graphical plain-text editor with proportional fonts and Uxntal syntax highlight.
  - [Nasu](https://wiki.xxiivv.com/site/nasu.html) - Spritesheet editor.
  - [Noodle](https://wiki.xxiivv.com/site/noodle.html) - Drawing tool.
  - [Turye](https://wiki.xxiivv.com/site/turye.html) - Font editor.
  - [Orca](https://wiki.xxiivv.com/site/orca.html) - Livecoding IDE.
  - [uxn-harp](https://github.com/lynn/uxn-harp) - Chordal musical toy.

* Utilities

  - [Dexe](https://wiki.xxiivv.com/site/dexe.html) - Graphical hex editor.
  - [Calc](https://git.sr.ht/~rabbits/uxn/tree/main/item/projects/software/calc.tal) - Graphical hexadecimal calculator.
  - [Clock](https://git.sr.ht/~rabbits/uxn/tree/main/item/projects/examples/devices/datetime.tal) - Graphical clock.
  - [Starling](https://git.sr.ht/~cabrendan/starling) - Spreadsheet application.
  - [Beetbug](https://git.sr.ht/~rabbits/beetbug) - Step debugger.

* Games

  - [Niju](https://hundredrabbits.itch.io/niju) - Hiragana and katakana learning game.
  - [Donsol](https://hundredrabbits.itch.io/donsol) - Card game about exploring a dungeon made of a standard 54 poker card set.
  - [Flappy](https://github.com/keijiro/uxn-sketches/blob/main/flappy.tal) - Implementation of a Flappy Bird-like game.
  - [Pong](https://compudanzas.net/uxn_tutorial_day_6.html) - Recreation of the classic Pong game.
  - [Snake](https://git.sr.ht/~rabbits/uxn/tree/main/item/projects/examples/demos/snake.tal) - Classic Snake game implementation.
  - [Cat Cubes](https://pup.town/catcubes.html) - Puzzle game about matching and clearing tiles from a board.
  - [Minesweeper](https://git.sr.ht/~rabbits/minesweeper) - Minesweeper port for Varvara.
  - [XO](https://garden.bouncepaw.com/hypha/xo.tal) - TicTacToe for Varvara.
  - [Fourtette](https://github.com/nf/fourtette) - Tetris for Varvara.
  - [Shanghai](https://github.com/lynn/shanghai) - Mahjong Solitaire for Varvara.
  - [Pinkie Run](https://github.com/Jaezmien/pinkie-run) - Pony-themed Endless Runner for Varvara.
  - [oneko-uxn](https://github.com/hikari-no-yume/oneko-uxn) - A version of “Neko”, the classic desktop pet cat, with several characters.
  - [Lights Out](https://github.com/origedit/lights-out) - Puzzle game for Varvara.
  - [Worm](https://github.com/origedit/worm) - Dune themed snake game for Varvara.

* Networking

  - [Xrxs](https://nilfm.cc/git/xrxs/about/) - Experimental game server using the Plan 9 protocol 9p.

* Operating systems/REPLs

  - [UF](http://www.call-with-current-continuation.org/uf/uf.html) - A traditional Forth system for Varvara.
  - [CollapseOS](https://github.com/schierlm/collapseos-uxn) - Forth-based [operating system](http://collapseos.org/) for Varvara.
  - [Uxnfth](https://git.sr.ht/~binarycat/uxnfth) - Uxn-native forth.
  - [PotatoOS](http://wiki.xxiivv.com/site/potato.html) - A little desktop environment.
  - [Varaboy](https://github.com/tbsp/varaboy) - Gameboy Emulator.

* Demos

  - [Bad-apple-uxn](https://github.com/karolbelina/bad-apple-uxn) - Bad Apple!! video on a single Uxn ROM.
  - [tiles](https://codeberg.org/kira/uxn-demos/src/branch/master/tiles.tal) - A scrolling tile-map renderer.
  - [svitlyna](https://github.com/gardenappl/svitlyna) - A "full-color" image viewer.

* Libraries

  - [math32](http://plastic-idolatry.com/erik/nxu/math32.tal) - Unsigned 32-bit integers
  - [regex](http://plastic-idolatry.com/erik/nxu/regex.tal) - Regex parsing and matching ([repl](http://plastic-idolatry.com/erik/nxu/repl-regex.tal))
  - [fix16](http://plastic-idolatry.com/erik/nxu/fix16.tal) - Signed 16-bit fixed point numbers (8.8)
  - [alloc](http://plastic-idolatry.com/erik/nxu/alloc.tal) - Arena-based memory allocator
  - [arg](http://plastic-idolatry.com/erik/nxu/arg.tal) - Command-line argument parsing ([demo](http://plastic-idolatry.com/erik/nxu/alloc-demo.tal))

* Terminal / Command-line

  - [femto](http://plastic-idolatry.com/erik/nxu/femto.tal) - nano-like text editor ([about](http://plastic-idolatry.com/erik/nxu/femto.txt) / [launcher](http://plastic-idolatry.com/erik/nxu/femto) / [rom](http://plastic-idolatry.com/erik/nxu/femto.rom))
  - [grep](http://plastic-idolatry.com/erik/nxu/grep.tal) - minimal grep-like tool (uses regex.tal)

## Development tools

* IDEs

  - [Learn-uxn](https://metasyn.srht.site/learn-uxn/) - A web-based development environment with a text editor and up-to-date versions of Uxnasm and Uxnemu.

* Assemblers, compilers & disassemblers

  - [Uxnasm](https://git.sr.ht/~rabbits/uxn/tree/main/item/src/uxnasm.c) - The original implementation of the Uxntal assembler in about 400 lines of ANSI C.
  - [Asma](https://git.sr.ht/~rabbits/uxn/tree/main/item/projects/software/asma.tal) - Uxntal assembler, written in Uxntal.
  - [Drifblim](https://wiki.xxiivv.com/site/drifblim.html) - Uxntal Assembler, written in Uxntal.
  - [Uxncle](https://github.com/CPunch/Uxncle) - Compiler for a small subset of C to Uxn bytecode.
  - [Pyuxncle](https://github.com/CPunch/Pyuxncle) - Python implementation of Uxncle.
  - [Conch](https://github.com/Armael/conch) - Compiler for a C-like language with Lisp-like syntax to Uxn bytecode.
  - [Uxnbruteforce](https://github.com/max22-/uxnbruteforce) - Tool for optimizing little pieces of Uxntal code.
  - [Uxnlin](https://git.sr.ht/~rabbits/uxnlin) - Linter for Uxntal.
  - [Uxnbot](https://git.sr.ht/~alderwick/uxnbot) - IRC bot for assembling and running small Uxntal snippets.
  - [Pyuxntaldisasm](https://github.com/DeltaF1/pyuxntaldisasm) - Very basic disassembler for Uxn ROMs.
  - [Uxnasm-js](https://github.com/rafapaezbas/uxnasm-js) - Uxntal assembler written in JavaScript.
  - [Uxn-disassembler](https://github.com/Liorst4/uxn-disassembler) - A rom disassembler writen in Uxntal 
  - [Dotal](https://github.com/HParker/dotal) - A small language designed to compile to the Uxn virtual machine.
  - [lunas](https://github.com/ThaCuber/lunas) - An Uxntal assembler written in Lua.
  - [chibicc-uxn](https://github.com/lynn/chibicc) - A C compiler for Uxn, written in C.
  - [nito](https://codeberg.org/wimvanderbauwhede/nito) - A compiler from Uxntal to C, written in Raku. See also the [blog post](https://limited.systems/articles/uxntal-to-C/).
  - [funktal](https://codeberg.org/wimvanderbauwhede/funktal) - A small, statically typed, functional programming language that compiles to Uxntal. The compiler is written in Fortran. See also the [blog post](https://limited.systems/articles/funktal).

* Uxntal language support

  - [Atom language package](https://atom.io/packages/language-uxntal)
  - [Emacs mode](https://github.com/non/uxntal-mode) ([alt 1](https://github.com/xaderfos/uxntal-mode) [alt 2](https://github.com/rafapaezbas/uxntal-mode))
  - [Kakoune plugin](https://git.sr.ht/~athorp96/uxntal.kak)
  - [Lite XL plugin](https://raw.githubusercontent.com/lite-xl/lite-xl-plugins/master/plugins/language_tal.lua)
  - [Micro syntax](https://hacklab.nilfm.cc/dotfiles/blob/main/micro/syntax/uxn.yaml)
  - [Nano syntax](https://codeberg.org/sejo/uxntal.nanorc)
  - [Nano syntax(alt)](https://git.sr.ht/~cassvs/uxntal-nano)
  - [Sublime syntax](https://git.sr.ht/~rabbits/uxn/tree/main/item/etc/syntax-highlight/tal.sublime-syntax)
  - [Vim plugin](https://github.com/karolbelina/uxntal.vim)
  - [Visual Studio Code extension](https://marketplace.visualstudio.com/items?itemName=karolbelina.uxntal)

## Metadevelopment tools

* Testing
  - Reference test suite included in the `uxn-utils` repository: [opctest](https://git.sr.ht/~rabbits/uxn-utils/blob/main/cli/opctest/opctest.tal).
  - Others
    * [Uxn-instruction-tests](https://github.com/DeltaF1/uxn-instruction-tests) - Test suite for the Uxn CPU instruction set.

* Benchmarking

  - [Bunnymark](https://codeberg.org/kira/uxn-demos/src/branch/master/bunnymark.tal) - Render performance benchmark.

## Community

- [Lines](https://llllllll.co/t/uxn-virtual-computer/46103)
- [#uxn on irc.libera.net](https://web.libera.chat/gamja/?channels=%23uxn)
- [#uxn on Merveilles](https://merveilles.town/tags/uxn)
