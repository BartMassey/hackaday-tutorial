# Thing
Copyright (c) 2017 Bart Massey

This 3D "thing" is a FreeCAD 0.16R part model produced by
following a
[Hackaday 3D Printering Tutorial](http://hackaday.com/2014/02/05/3d-printering-making-a-thing-in-freecad-part-i/). The
part itself is from the book *A Manual of Engineering
Drawing for Students and Draftsmen* by Thomas Ewing
French, 1911. The second
[1918 edition](https://books.google.com/books?id=6R5DAAAAIAAJ)
is available online through Google Books , although I can't
find this drawing in there since the figures have all
changed.

The Hackaday tutorial is great overall. I had a few minor
quibbles:

* It would have been nice to have the book drawing enlarged
  and cleaned up so that it was more readable.

* Apparently Freecad 0.12 had trouble with units. With 0.16R
  I followed the book drawing and used inches for
  everything. Seemed to work fine.

* The construction of the slot in the base should really be
  explicitly such that the center of the slot hits the
  center of the hole. I fixed this in my version.

* The construction of the fillet between the washer and foot
  part of the base should really be explicit in the sketch,
  given that it is fairly explicit in the book drawing. I
  tried to reproduce it accurately.

* It is not obvious from the book drawing how the top of the
  flange piece should be shaped. After staring at it for a
  long time, I diverged from the drawing and made the sides
  of the flange vertical instead of sloped. To change this,
  remove the vertical constraint in the flange sketch and
  figure out how high you want the top of the flange to be.

* The tutorial handwaves some idea of making the base and
  flange pieces fit together by doing some math and
  adjusting sketch positions manually. I did this first, but
  didn't like it. I instead chose to go through the
  sometimes-painful process of making sure sketches were
  attached to appropriate faces and appropriate geometry was
  borrowed: as a result, things are more reliable and
  configurable.

I've included STL exported from the model, just for fun.

Anyway, have fun taking this apart, printing it,
whatever. Thanks again to the tutorial authors for an
interesting afternoon.

---

This work is licensed under the "MIT License". Please see
the file COPYING in this distribution for license terms.
