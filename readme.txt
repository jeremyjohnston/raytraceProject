RayTrace Project
---

This directory contains the program explained at:

http://fabiensanglard.net/rayTracing_back_of_business_card/index.php

The program will render a simple scene with initials, and do so with
source code that can "fit on the back of a business card".

No clue yet if it will work on cygwin but it should work on *nix systems
as the article described.

Compile with (in cygwin or linux): >c++ -O3 -o card card.cpp
Run with: >./card > card.ppm

Wait about 30s for it to finish...

Then open card.ppm in gimp to view!