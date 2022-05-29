# NeoDS
Neo DS is a Vulkan DSI/DS (at least it will be) emulator with support for GB, GB color, and GBA ROMS. Support for camera and printer periperals is planned. Along with Networking via SteamWorks and Asio.

# Main Emulator

--Done <br>

--To Do
  - Main Interface for going through ROMs and playing games. Will be based off the DS menu

  -Main and secondary display. Main Display would be used for input polling and act as the bottom screen in DS/DSI mode.
  -Hardware layer for managing system camera, system clock, system microphone, link cable, gyro-carts, infered-carts, other hardware
  -Input layer for key remaping per console, touch input
  -Network Driver, the Network Driver manages WIFI functionality and is used in place of a link cable
  
  -ROM based disassembler
  
  -Descriptor Pool Manager
  -Dedicated 2D batch GPU based renderer
  -Dedicated 3D batch GPU based renderer
  -Main 2D pipeline
  -Main 3D pipeline
  -Runtime Pipeline recreation as secondary pipeline
  -Per screen render pass
  
  -Built in sqr that uses the Quake 3 algorathem
  
  -Opcode function table
  -Opcode ROM mapping and recompalation to condensed commands
  -Runtime memory inspecton and modification

  -Save states
  -Speed up

# GB (Color)

--Done

--To Do
  -Color option to enabled and disabled
  -ROM loading

  -Link Cable support via networking

# GBA

--Done

--To Do
  -ROM loading

  -Link Cable support via networking


# DS

--Done

--To Do

  -screen touch

  -Create in emulator rooms and be able to invite others
  -Replace Nintendo Server with local host Network call
  -Download play

# DSI

--Done

--To Do

-Support pressure and temp touch
-Camera

# Building
