# Thing

This 3D "thing" is a FreeCAD 0.16R model of a part produced
by following along with a
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

* Apparently Freecad 0.12 had trouble with units. I followed
  the book drawing and used inches for everything. Seemed to
  work fine.

* The construction of the slot in the base should really be
  explicitly such that the center of the slot hits the
  center of the hole. I fixed this in my version.

* The construction of the fillet in the 

* It is not obvious from the book drawing how the top of the
  flange piece should be shaped. I followed the tutorial's
  suggestion here, but there seem to be many possibilities.

* The process of hand-calculating how the base and flange
  piece fit together is tedious and error-prone. I suspect
  that this can be fixed in FreeCAD with judicious use of
  face sketches and imported edges, although this is also
  fiddly and error-prone in FreeCAD.
