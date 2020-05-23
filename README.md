# How to Run: Virtual Cubes C-Code Practice Build
- Download the "Virtual Cubes RTS.zip" zip folder to your computer. (Do not mistake it for this master branch zip!)
- Extract its contents wherever you like.
- Open folder
- Run "Virtual Cubes" application
- Windows will warn you that it is an Executable with no publisher. If you trust this download prompt it to run anyway.

Path: \Virtual Cubes RTS\Virtual Cubes.application

The program should start immediately and needs no assembly.

# Description
Build for a small RTS project. Used to practice C++/C# code skills.

# Basic Controls

**W Key** - Pans screen up

**A Key** - Pans screen left

**S Key** - Pans screen down

**D Key** - Pans screen right

**Mouse Wheel Up** - Zooms the screen in

**Mouse Wheel Down** - Zooms the screen out

**SPACE Key** - Resets screen to the middle of the level.

**R Key** - Restarts Game

**ESC Key** - Exits Program

**Pushing the edge of the screen with the mouse cursor** - Moves screen in the pushed direction

# Player Unit Controls
## Units are small colored cylinders positioned on the map. The Purple cylinders belong to you, the Yellow cylinders are enemies! Selecting a unit turns it pink!

**Left-Click (On Your Units)** - Selects the unit so you can control it.

**Left-Shift + Left-Click (On Your Units)** - Adds the clicked unit to selection group.

**Left-Click (Anywhere on Map)** - Deselects all units.


**Right-Click (Anywhere on Map)** - Sends selected units to clicked location.

**Left-Shift + Right-Click (Anywhere on Map)** - Waypoints selected units to clicked location after current waypoints are finished.

**Right-Click (On enemy unit)** - Sends selected units to attack enemy unit.

**Left-Shift + Right-Click (On enemy unit)** - Queues selected units to attack enemy unit after they have finished killing other queued enemies.

```diff
- Box drag-select feature has been developed yet! Shift click selections are only way to select multiple units in this version!
```

Author(s): Doctor Laplace (Jacob Halaweh)



