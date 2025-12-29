# Awesome Uxn [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Curated list of awesome Uxn projects from the community.

The [Uxn](https://100r.co/site/uxn.html) ecosystem is a personal computing playground, created to host small tools and games, programmable in its own unique assembly language.

## Learning

- [Learn Uxntal in Y minutes](https://learnxinyminutes.com/docs/uxntal/) - Language overview for when you're in a hurry.
- [Uxn Guide by Compudanzas](https://compudanzas.net/uxn_tutorial.html) - Tutorial guide which covers the basics of Uxn programming.
- [Uxn Video by Compudanzas](https://www.youtube.com/watch?v=LrNuq_JgaOA) - Video workshop which covers the basics of Uxn programming.
- [macOS installation](https://eli.li/how-to-install-uxn-on-macos)
- [Windows installation](https://itch.io/t/1605965/a-quick-guide-to-running-this-software)
- [Android installation](https://llllllll.co/t/uxn-virtual-computer/46103/253) - Through Termux.
- [HaikuOS installation](https://discuss.haiku-os.org/t/uxn-ecosystem-on-haiku/12209) - Forum thread for the Haiku operating system.
- [Learn-uxn](https://metasyn.srht.site/learn-uxn/) - A web-based learning environment with a text editor and graphics.
- [UxnREPL](https://wiki.xxiivv.com/etc/uxnrepl/) - A web-based learning with examples.

## Documentation

- [Uxntal](https://wiki.xxiivv.com/site/uxntal.html) - Uxntal language reference manual.
- [Varvara](https://wiki.xxiivv.com/site/varvara.html) - Technical documentation of the Varvara computer and a list of all its devices.
- [Opcodes](https://wiki.xxiivv.com/site/uxntal_reference.html) - List of Uxntal opcodes and their effects.
- [Uxntal Cheatsheet](https://github.com/weeble/uxn-cheatsheet) - Opcode Cheatsheet.
- [RosettaCode](https://rosettacode.org/wiki/Category:Uxntal) - Uxntal programming chrestomathy.

## File Formats

- [Sprite format](https://wiki.xxiivv.com/site/chr_format.html) - `.chr` file format description.
- [Font format](https://wiki.xxiivv.com/site/ufx_format.html) - `.ufx` file format description.
- [Compression format](https://wiki.xxiivv.com/site/ulz_format.html) - `.ulz` file format description.

## Emulators

### Desktop

- **Recommended for Linux**: [Uxn2](https://git.sr.ht/~rabbits/uxn2) - Cross-platform emulator, written in C(SDL2).
- **Recommended for Windows**: [Uxn32](https://github.com/randrew/uxn32) - Windows emulator, written in C.
- **Recommended for Mac**: [Raven](https://github.com/mkeeter/raven) - Cross-platform emulator, written in Rust.
- [Uxn38](http://zzo38computer.org/fossil/uxn.ui) - Emulator written in C with SDL1.
- [Nux](https://github.com/nf/nux) - Emulator written in Go.
- [Uxn11](https://git.sr.ht/~rabbits/uxn11) - Linux emulator, written in C.
- [uxn9](https://github.com/krzysckh/uxn9) - Native emulator for 9front. (no audio support)
- [uxn5](https://git.sr.ht/~rabbits/uxn5) - Javascript implementation.
- [buxn](https://github.com/bullno1/buxn) - Multi platform emulator, written in C.
- [ruxn](https://codeberg.org/mra/ruxn) - A Uxn library written in Rust, intended to make defining new Uxn-based systems easy.
- [zuxn](https://github.com/chmod222/zuxn) - A Uxn library, emulator and assembler written in Zig.
- [UxnFb](https://git.badd10de.dev/uxnfb) - Linux framebuffer emulator, written in C.
- [uxnfloppy](https://git.sr.ht/~gustav/uxnfloppy) - Bootable emulator for BIOS, written in 16bit x86 assembly. (no keyboard/gamepad/audio/file support)
- [UxnRPI](https://git.badd10de.dev/uxnrpi) - RaspberryPi framebuffer emulator, written in C. (no input support)
- [UxnJulia](https://github.com/Ismael-VC/Varvara.jl) - Cross-platform emulator and assembler, written in Julia.
- [UxnLua](https://github.com/DeltaF1/uxn-lua) - Cross-platform emulator, written in Lua(Love2d).
- [uxn-rs](https://github.com/Liorst4/uxn-rs) - Emulator written in Rust.

### Other systems

- [FPGA](https://github.com/tsalvo/openfpga-varvara) - Nearly Complete.
- [RPi](https://github.com/ar-nelson/uxnpi) - Nearly Complete.
- [Game Boy Advance](https://git.badd10de.dev/uxngba) - Complete.
- [Nintendo 64](https://git.badd10de.dev/uxn64) - Complete.
- [Nintendo DS](https://github.com/asiekierka/uxnds) - Complete.
- [Playdate](https://git.sr.ht/~rabbits/uxn-playdate) - Complete.
- [Nook eReader](https://git.badd10de.dev/uxnnst/) - Complete.
- [Game Boy](https://github.com/tbsp/uxngb) - Experimental.
- [DOS](https://git.sr.ht/~rabbits/uxn-vga) - Implemented: Core, Screen, Mouse, Controller.
- [Teletype](https://github.com/csboling/teluxn) - Incomplete.
- [ESP32](https://github.com/max22-/uxn-esp32) - Incomplete.
- [iOS](https://github.com/paiv/uxn-ios) - Nearly Complete (missing midi and controller).
- [iOS](https://github.com/kylestew/UxniOS) - Incomplete.
- [STM32duino](https://github.com/cassvs/arduxno-demo) - Incomplete.
- [IBM PC](https://github.com/cr1901/pcuxn) - Incomplete.
- [PlayStation Vita](https://github.com/ivodopiviz/uxnvita) - Incomplete.
- [PlayStation Portable](https://codeberg.org/tbsp/VarvaraPSP) - Nearly Complete (missing keyboard).
- [Atari ST](https://framagit.org/Bartitsu59/stuxn) - Incomplete.
- [Android](https://github.com/bullno1/buxn) - Complete.
- [Pebble OS](https://git.sr.ht/~angelwood/uxn-pebble) - Experimental.
- [Adafruit PyBadge](https://git.sr.ht/~poyu/uxn-pybadge) - Implemented: Core, Console, Screen, Controller.
- [Logisim](https://github.com/DeltaF1/uxn-logisim) - Incomplete.
- [auxn](https://github.com/saucesaft/auxn) - uxn running inside of an audio plugin (standalone mode included)

### Web

- [UxnWasm](https://github.com/remko/uxn.wasm) - WebAssembly implementation of the Uxn core.
- [Webuxn](https://github.com/aduros/webuxn) - Lightweight port of the Uxn virtual machine to the web via WebAssembly.

### Cores

- [uxnbot](https://git.sr.ht/~rabbits/uxnbot) - a REPL.
- [uxn.py](https://github.com/max22-/uxnemu.py) - Python implementation of the VM.
- [Uxncli](https://git.sr.ht/~rabbits/uxncli) - System, console and file devices only.
- [Uxnmin](https://git.sr.ht/~rabbits/uxnmin) - Console only.

## Applications

### Creative

- [Left](https://wiki.xxiivv.com/site/left.html) - Graphical text-editor with Uxntal syntax highlight.
- [Nasu](https://wiki.xxiivv.com/site/nasu.html) - Spritesheet editor.
- [Noodle](https://wiki.xxiivv.com/site/noodle.html) - Drawing tool.
- [Turye](https://wiki.xxiivv.com/site/turye.html) - Font editor.
- [Orca](https://wiki.xxiivv.com/site/orca.html) - Livecoding IDE.
- [uxn-harp](https://github.com/lynn/uxn-harp) - Chordal musical toy.

### Utilities

- [Notepad](https://wiki.xxiivv.com/site/notepad.html) - Notepad.
- [Calendar](https://wiki.xxiivv.com/site/calendar.html) - Calendar.
- [Theme](https://wiki.xxiivv.com/site/theme.html) - Theme editor.
- [Dexe](https://wiki.xxiivv.com/site/dexe.html) - Graphical hex editor.
- [CCCC](https://wiki.xxiivv.com/site/cccc.html) - Graphical calculator.
- [Nebu](https://wiki.xxiivv.com/site/nebu.html) - Spreadsheet calculator.
- [Starling](https://git.sr.ht/~cabrendan/starling) - Spreadsheet application.
- [Beetbug](https://git.sr.ht/~rabbits/beetbug) - Step debugger.
- [Varaboy](https://github.com/tbsp/varaboy) - Gameboy Emulator.

### Games

- [Oquonie](https://hundredrabbits.itch.io/oquonie) - Puzzle adventure game.
- [Niju](https://hundredrabbits.itch.io/niju) - Hiragana and katakana learning game.
- [Donsol](https://hundredrabbits.itch.io/donsol) - Card game about exploring a dungeon made of a standard 54 poker card set.
- [Flappy](https://github.com/keijiro/uxn-sketches/blob/main/flappy.tal) - Implementation of a Flappy Bird-like game.
- [Pong](https://compudanzas.net/uxn_tutorial_day_6.html) - Recreation of the classic Pong game.
- [Cat Cubes](https://pup.town/catcubes.html) - Puzzle game about matching and clearing tiles from a board.
- [Minesweeper](https://codeberg.org/yorshex/minesweeper-uxn) - Minesweeper port for Varvara.
- [XO](https://garden.bouncepaw.com/hypha/xo.tal) - TicTacToe for Varvara.
- [Fourtette](https://github.com/nf/fourtette) - Tetris for Varvara.
- [Shanghai](https://github.com/lynn/shanghai) - Mahjong Solitaire for Varvara.
- [Pinkie Run](https://github.com/Jaezmien/pinkie-run) - Pony-themed Endless Runner for Varvara.
- [oneko-uxn](https://github.com/hikari-no-yume/oneko-uxn) - A version of “Neko”, the classic desktop pet cat, with several characters.
- [Lights Out](https://github.com/origedit/lights-out) - Puzzle game for Varvara.
- [Worm](https://github.com/origedit/worm) - Dune themed snake game for Varvara.
- [Kodiak](https://git.phial.org/d6/kodiak) - Klondike solitaire with music and bears.
- [Tile Garden](https://kylep.itch.io/tile-garden) - Idle game where you place tiles to make plants.
- [Polycat](https://hundredrabbits.itch.io/polycat) - Platformer game.

### Operating systems/REPLs

- [UF](http://www.call-with-current-continuation.org/uf/uf.html) - A traditional Forth system for Varvara.
- [PotatoOS](http://wiki.xxiivv.com/site/potato.html) - A little desktop environment.
- [CollapseOS](https://github.com/schierlm/collapseos-uxn) - Forth-based [operating system](http://collapseos.org/) for Varvara.
- [Uxnfth](https://git.sr.ht/~binarycat/uxnfth) - Uxn-native forth.
- [TalOS](https://github.com/UxnTalOS/talos) - A small Uxntal REPL and System Monitor/OS written in Uxntal.

### Demos

- [Bad Apple!!](http://167.235.19.20/bad-apple-uxn/) - An arrangement of the Bad Apple!! music video.
- [tiles](https://codeberg.org/kira/uxn-demos/src/branch/master/tiles.tal) - A scrolling tile-map renderer.
- [svitlyna](https://github.com/gardenappl/svitlyna) - A "full-color" image viewer.
- [Bunnymark](https://git.sr.ht/~rabbits/uxn-games/tree/main/item/bunnymark/src/bunnymark.tal) - Render performance benchmark.

### Libraries

- [math32](https://git.phial.org/d6/nxu/raw/branch/main/math32.tal) - Unsigned 32-bit integers
- [regex](https://git.phial.org/d6/nxu/raw/branch/main/regex.tal) - Regex parsing and matching ([repl](https://git.phial.org/d6/nxu/raw/branch/main/repl-regex.tal))
- [fix16](https://git.phial.org/d6/nxu/raw/branch/main/fix16.tal) - Signed 16-bit fixed point numbers (8.8)
- [alloc](https://git.phial.org/d6/nxu/raw/branch/main/alloc.tal) - Arena-based memory allocator
- [arg](https://git.phial.org/d6/nxu/raw/branch/main/arg.tal) - Command-line argument parsing ([demo](https://git.phial.org/d6/nxu/raw/branch/main/arg-demo.tal))

### Terminal / Command-line

- [femto](https://git.phial.org/d6/nxu/raw/branch/main/femto.tal) - nano-like text editor ([about](https://git.phial.org/d6/nxu/raw/branch/main/femto.txt) / [launcher](https://git.phial.org/d6/nxu/raw/branch/main/femto) / [rom](http://plastic-idolatry.com/erik/nxu/femto.rom))
- [grep](https://git.phial.org/d6/nxu/raw/branch/main/grep.tal) - minimal grep-like tool (uses regex.tal)

### Networking

- [Xrxs](https://nilfm.cc/git/xrxs/about/) - Experimental game server using the Plan 9 protocol 9p.

## Development tools

### Assemblers, compilers & disassemblers

- **Recommended**: [Drifblim](https://wiki.xxiivv.com/site/drifblim.html) - Uxntal Assembler, written in Uxntal.
- [uxndis](https://git.sr.ht/~rabbits/uxndis) - a disassembler for rom and sym files.
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
- [Finwë](https://github.com/kiedtl/finwe) - A high-level, stack-based language that compiles to Uxn bytecode.
- [Yaku](https://codeberg.org/wimvanderbauwhede/yaku) - An Uxntal assembler and interpreter.
- [B](https://github.com/tsoding/b) - Compiler for the B Programming Language implemented in Crust, has support for uxn target.
- [niënor](https://github.com/krzysckh/nienor) - Optimizing compiler for a Lisp dialect.
- [SUPERFLY](https://codeberg.org/Bunny351/superfly) - Concatenative array language.
- [buxn-asm](https://github.com/bullno1/buxn) - Uxntal assembler with a type checker.
- [buxn-dbg](https://github.com/bullno1/buxn-dbg) - Uxntal step debugger.
- [Callisto](https://github.com/callisto-lang/compiler) - Low level compiled programming language with a uxn backend
- [uxnfor](https://git.sr.ht/~rabbits/uxnfor) - a formatter for tal files.

### Uxntal language support

- [Atom language package](https://atom.io/packages/language-uxntal)
- [Emacs mode](https://github.com/non/uxntal-mode) ([alt 1](https://github.com/xaderfos/uxntal-mode) [alt 2](https://github.com/rafapaezbas/uxntal-mode))
- [Kakoune plugin](https://git.sr.ht/~athorp96/uxntal.kak)
- [Lite XL plugin](https://raw.githubusercontent.com/lite-xl/lite-xl-plugins/master/plugins/language_tal.lua)
- [Vim plugin](https://github.com/karolbelina/uxntal.vim)
- [Visual Studio Code extension](https://marketplace.visualstudio.com/items?itemName=karolbelina.uxntal)
- [Language server](https://github.com/bullno1/buxn-ls)
- [Kate syntax](https://github.com/pfych/uxntal-kate-syntax)
- [Sublime syntax](https://git.sr.ht/~rabbits/uxn-utils/tree/main/item/etc/tal.sublime-syntax)
- [Nano syntax](https://git.sr.ht/~rabbits/uxn-utils/tree/main/item/etc/tal.nanorc)
- [Micro syntax](https://hacklab.nilfm.cc/dotfiles/blob/main/micro/syntax/uxn.yaml)
- [Nano syntax](https://git.phial.org/d6/nxu/src/branch/main/tal.nanorc) ([alt 1](https://codeberg.org/sejo/uxntal.nanorc) [alt 2](https://git.sr.ht/~cassvs/uxntal-nano))

## Community

- [Forum](https://llllllll.co/t/uxn-virtual-computer/46103)
- [#uxn on irc.libera.net](https://web.libera.chat/gamja/?channels=%23uxn)
- [#uxn on Merveilles](https://merveilles.town/tags/uxn)

