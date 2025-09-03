# FPGA_PACMAN
A FPGA-based Pac-Man implementation with a MicroBlaze soft processor, GPIO peripherals for keyboard input, and BRAM for graphical storage. The game is designed using a maze constructed of 8x8 tiles, custom FontROM graphics, and real-time movement logic.

Features Included:
* Keyboard Input via USB (MAX3241E): Controls Pac-Man’s movement.
* Ghost AI: Three ghosts with unique movement patterns that chase Pac-Man.
* Power Pellets: Temporarily enable Pac-Man to eat ghosts.
* Score & Collision System: Tracks pellet consumption, ghost interactions, and win/loss conditions.
* Custom VGA Display: Rendered using a BRAM-based background and sprite animations.

Built as a final project for ECE 385 at UIUC, integrating hardware-accelerated game logic with efficient memory management.

Live Game Demo:
<video src="./PACMAN.mp4" width="320" height="240" controls></video>



This repo only contains code that I wrote. All Vivado / Univeristy sources inlcuding Micoblaze block are not included.
