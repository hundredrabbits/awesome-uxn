# Awesome Uxn [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Curated list of awesome Uxn projects from the community.

The [Uxn](https://100r.co/site/uxn.html) ecosystem is a personal computing playground, created to host small tools and games, programmable in its own unique assembly language.

## Documentation

- [Varvara](https://wiki.xxiivv.com/site/varvara.html) - Technical documentation of the Varvara computer and a list of all its devices.
- [Uxntal](https://wiki.xxiivv.com/site/uxntal.html) - Uxntal language reference manual.
- [Uxntal opcode manual](https://wiki.xxiivv.com/site/uxntal_reference.html) - List of Uxntal opcodes and their effects.
- [Sprite format](https://wiki.xxiivv.com/site/chr_format.html) - `.chr` file format description.

## Tutorials

- [Uxn Tutorial by Compudanzas](https://compudanzas.net/uxn_tutorial.html) - Beginner-friendly tutorial guide which covers the basics of Uxn programming.
- [Uxn Tutorial by Compudanzas(video)](https://www.youtube.com/watch?v=LrNuq_JgaOA) - Beginner-friendly video workshop which covers the basics of Uxn programming.
- [Learn Uxntal in Y minutes](https://learnxinyminutes.com/docs/uxntal/) - Quick Uxntal guide.
- [Uxn implementation guide](https://github.com/DeltaF1/uxn-impl-guide) - Notes on how to implement the Uxn/Varvara virtual machine specification.
- [macOS installation](https://eli.li/2021/09/27/how-to-install-uxn-on-macos)
- [Windows installation](https://itch.io/t/1605965/a-quick-guide-to-running-this-software)
- [Android installation](https://llllllll.co/t/uxn-virtual-computer/46103/253) - Guide for running Uxn on the Android operating system through Termux.

## Emulators

* Desktop

  - [Uxn](https://git.sr.ht/~rabbits/uxn) - Cross-platform emulator and assembler, written in C(SDL2).
  - [Uxn32](https://github.com/randrew/uxn32) - Windows emulator, written in C.
  - [Uxn11](https://git.sr.ht/~rabbits/uxn11) - Linux emulator, written in C.
  - [UxnFb](https://git.badd10de.dev/uxn-linuxfb/) - Linux framebuffer emulator, written in C.
  - [UxnEssence](https://gitlab.com/nakst/essence/-/tree/master/ports/uxn) - [Essence](https://gitlab.com/nakst/essence) emulator, written in C.
  - [UxnJulia](https://github.com/Ismael-VC/Varvara.jl) - Cross-platform emulator and assembler, written in Julia.
  - [UxnLua](https://github.com/DeltaF1/uxn-lua) - Cross-platform emulator, written in Lua(Love2d).

* Other systems

  - [Game Boy Advance](https://git.badd10de.dev/uxngba/about/) - Complete.
  - [Nintendo DS](https://github.com/asiekierka/uxnds) - Complete.
  - [Playdate](https://git.sr.ht/~rabbits/uxn-playdate) - Complete.
  - [DOS](https://git.sr.ht/~rabbits/uxn-vga) - Implemented: Core, Screen, Mouse, Controller.
  - [PlayStation Vita](https://github.com/ivodopiviz/uxnvita) - Incomplete.
  - [Raspberry Pi Pico](https://git.sr.ht/~alderwick/pico-uxn) - Implemented: Core, Screen.
  - [Teletype](https://github.com/csboling/teluxn) - Incomplete.
  - [ESP32](https://github.com/max22-/uxn-esp32) - Incomplete.
  - [iOS](https://github.com/kylestew/UxniOS) - Incomplete.
  - [STM32](https://github.com/kylestew/armuxn) - Incomplete.
  - [STM32duino](https://github.com/cassvs/arduxno-demo) - Incomplete.
  - [IBM PC](https://github.com/cr1901/pcuxn) - Incomplete.

* Misc

  - [Libretro port](https://github.com/kivutar/uxn) - [Libretro](https://www.libretro.com/) emulation layer.
  - [LearnUxn](https://github.com/metasyn/learn-uxn/) - Web assembler and emulator.
  - [Grid](https://tildegit.org/nihilazo/grid-uxn) - Incomplete.
  - [Rockbox](https://tilde.town/~nihilazo/varvara_rockbox.html) - Implemented: Core, Screen.
  - [Logisim](https://github.com/DeltaF1/uxn-logisim) - Incomplete.
  - [Adafruit PyBadge](https://git.sr.ht/~poyu/uxn-pybadge) - Implemented: Core, Console, Screen, Controller.
  - [Webuxn](https://github.com/aduros/webuxn) - Lightweight port of the Uxn virtual machine to the web via WebAssembly.

* Simulator

  - [uxn.py](https://github.com/max22-/uxnemu.py) - Python implementation of the VM.
  - [Uxn5](https://git.sr.ht/~rabbits/uxn5) - Javascript implementation of the VM.

## Applications

* Creative

  - [Left](https://wiki.xxiivv.com/site/left.html) - Graphical plain-text editor with proportional fonts and Uxntal syntax highlight.
  - [Nasu](https://wiki.xxiivv.com/site/nasu.html) - Spritesheet editor.
  - [Noodle](https://wiki.xxiivv.com/site/noodle.html) - Drawing tool.
  - [Turye](https://wiki.xxiivv.com/site/turye.html) - Font editor.
  - [Orca](https://wiki.xxiivv.com/site/orca.html) - Livecoding IDE.

* Utilities

  - [Dexe](https://wiki.xxiivv.com/site/dexe.html) - Graphical hex editor.
  - [Calc](https://git.sr.ht/~rabbits/uxn/tree/main/item/projects/software/calc.tal) - Graphical hexadecimal calculator.
  - [Clock](https://git.sr.ht/~rabbits/uxn/tree/main/item/projects/examples/devices/datetime.tal) - Graphical clock.
  - [Starling](https://git.sr.ht/~cabrendan/starling) - Spreadsheet application.

* Games

  - [Niju](https://hundredrabbits.itch.io/niju) - Hiragana and katakana learning game.
  - [Donsol](https://hundredrabbits.itch.io/donsol) - Card game about exploring a dungeon made of a standard 54 poker card set.
  - [Flappy](https://github.com/keijiro/uxn-sketches/blob/main/flappy.tal) - Implementation of a Flappy Bird-like game.
  - [Pong](https://compudanzas.net/uxn_tutorial_day_6.html) - Recreation of the classic Pong game.
  - [Snake](https://git.sr.ht/~rabbits/uxn/tree/main/item/projects/examples/demos/snake.tal) - Classic Snake game implementation.
  - [Cat Cubes](https://pup.town/catcubes.html) - Puzzle game about matching and clearing tiles from a board.
  - [Minesweeper](https://git.sr.ht/~rabbits/minesweeper) - Minesweeper port for Varavara.

* Networking

  - [Xrxs](https://nilfm.cc/git/xrxs/about/) - Experimental game server using the Plan 9 protocol 9p.
  - [Uxnyap](https://github.com/klardotsh/uxnyap) - Helper binary for generic abstract networking.

* Operating systems/REPLs

  - [Collapse OS](https://collapseos.org/download.html) - Experimental Uxn port of Collapse OS.
  - [Uxnfth](https://git.sr.ht/~binarycat/uxnfth) - Uxn-native forth.

* Demos

  - [Bad-apple-uxn](https://github.com/karolbelina/bad-apple-uxn) - Bad Apple!! video on a single Uxn ROM.

* Libraries

  - [regex](https://gist.github.com/non/4d9060b7a0b9aba0bddadfc6ba3e3442) - Regex parsing in uxn

## Development tools

* IDEs

  - [Learn-uxn](https://metasyn.github.io/learn-uxn/) - A web-based development environment with a text editor and up-to-date versions of Uxnasm and Uxnemu.

* Assemblers, compilers & disassemblers

  - [Uxnasm](https://git.sr.ht/~rabbits/uxn/tree/main/item/src/uxnasm.c) - The original implementation of the Uxntal assembler in about 400 lines of ANSI C.
  - [Asma](https://git.sr.ht/~rabbits/uxn/tree/main/item/projects/software/asma.tal) - Uxntal assembler, written in Uxntal.
  - [Drifblim](https://wiki.xxiivv.com/site/drifblim.html) - Uxntal Assembler, written in Uxntal.
  - [Ruxnasm](https://github.com/karolbelina/ruxnasm) - Uxntal assembler focused on error reporting.
  - [Uxncle](https://github.com/CPunch/Uxncle) - Compiler for a small subset of C to Uxn bytecode.
  - [Pyuxncle](https://github.com/CPunch/Pyuxncle) - Python implementation of Uxncle.
  - [Conch](https://github.com/Armael/conch) - Compiler for a C-like language with Lisp-like syntax to Uxn bytecode.
  - [Uxn-ng](https://git.sr.ht/~tenshi/uxn-ng) - Uxntal assembler with bytecode annotating.
  - [Uxnbruteforce](https://github.com/max22-/uxnbruteforce) - Tool for optimizing little pieces of Uxntal code.
  - [Uxnlin](https://git.sr.ht/~rabbits/uxnlin) - Linter for Uxntal.
  - [Uxnbot](https://git.sr.ht/~alderwick/uxnbot) - IRC bot for assembling and running small Uxntal snippets.
  - [Pyuxntaldisasm](https://github.com/DeltaF1/pyuxntaldisasm) - Very basic disassembler for Uxn ROMs.
  - [Uxnasm-js](https://github.com/rafapaezbas/uxnasm-js) - Uxntal assembler written in JavaScript.

* Uxntal language support

  - [Atom language package](https://atom.io/packages/language-uxntal)
  - [Emacs mode](https://github.com/non/tal-mode) ([alt 1](https://github.com/xaderfos/uxntal-mode) [alt 2](https://github.com/rafapaezbas/uxntal-mode))
  - [Kakoune plugin](https://git.sr.ht/~athorp96/uxntal.kak)
  - [Micro syntax](https://nilfm.cc/git/dotfiles/tree/micro/syntax/uxn.yaml)
  - [Nano syntax](https://codeberg.org/sejo/uxntal.nanorc) ([mirror](https://git.sr.ht/~rabbits/uxn/tree/main/item/etc/syntax-highlight/tal.nanorc))
  - [Sublime syntax](https://git.sr.ht/~rabbits/uxn/tree/main/item/etc/tal.sublime-syntax)
  - [Vim plugin](https://github.com/karolbelina/uxntal.vim)
  - [Visual Studio Code extension](https://marketplace.visualstudio.com/items?itemName=karolbelina.uxntal)

## Metadevelopment tools

* Testing

  - [Uxn-instruction-tests](https://github.com/DeltaF1/uxn-instruction-tests) - Test suite for the Uxn CPU instruction set.
  - [Uxntal-test-suite](https://github.com/karolbelina/uxntal-test-suite) - Test suite for Uxntal.

* Benchmarking

  - [Bunnymark](https://codeberg.org/kira/bunnymark) - Render performance benchmark.

## Community

- [Lines](https://llllllll.co/t/uxn-virtual-computer/46103)
- [#uxn on irc.esper.net](https://webchat.esper.net/?channels=uxn)
- [#uxn on Merveilles](https://merveilles.town/tags/uxn)
