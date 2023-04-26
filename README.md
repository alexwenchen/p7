# p7 - NES Emulator
C S 429H Computer Architecture's final project by David Li, Yifan Ma, Yu Lim, Wen Chen.

# How to Run
- As of right now, the program can only be run on a Windows machine with g++ and SDL installed.
- The reason for this is because we only got SDL working on Windows as of right now.
- To run our project, compile and run with the command ```make;.//main```.
- You should see the sprite table of the NES game Donkey Kong, which is as far as we got for the graphics by Tuesday night.
- On the other hand, the NES CPU (based on the MOS Technology 6502) and instruction set are fully emulated.
- All CPU instructions that ran should print in the console as a way to visualize the program running.

# Sources Cited 
- https://www.youtube.com/playlist?list=PLrOv9FMX8xJHqMvSGB_9G9nZZ_4IgteYf
  - This project is built off of javidx9 (OneLoneCoder)'s NES emulator tutorial.
  - We followed his tutorial and used his template for the skeletal code structure.
- https://www.nesdev.org/wiki/Nesdev_Wiki
  - The Nesdev Wiki provided the table for the CPU instruction set.
  - The wiki contained majority of the information we needed to implement the CPU, mappers, PPU, and etc.
- http://archive.6502.org/datasheets/rockwell_r650x_r651x.pdf
  - MOS 6502 Manual
- https://www.princeton.edu/~mae412/HANDOUTS/Datasheets/6502.pdf
  - MOS 6502 Manual 2
- http://www.emulator101.com/6502-addressing-modes.html
  - Blog post the explained the addressing modes in good detail.
- http://www.6502.org/
  - 6502 Central Hub
- https://yizhang82.dev/blog/nes/
  - Blog post with roadmap
- https://www.libsdl.org/
  - Simple DirectMedia Layer Official Website
