# Chip-8-Emulator
Chip-8 emulator I wrote in rust using aquova's tutorial https://github.com/aquova/chip8-book.
I wrote this to introduce myself to rust and systems programming. \
I believe I learned a fair amount with this project, and would like to improve upon it at some point in the future.\
This project does not currently have audio emulation functionality, but is something I would like to work on later.\
It shouldn't be necessary as i've included it as a bundle within the cargo.toml, but you may need to download sdl2 in order to run this properly.  
I've added a few games as examples you can play to see how the emulator runs. \
To run a game, the easiest way would be to use cargo run and then the address of the game, \rustEmulator\c8games\PONG2 for example.\
The controls should be 1234 qwer asdf zcxv respectively, which is a lot of buttons.
