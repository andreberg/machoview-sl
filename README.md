# MachOView for Snow Leopard

Peter Saghelyi created this fantastic macho-o executable viewer/browser over on [Sourceforge](http://sourceforge.net/projects/machoview/ "Sourceforge project home").

Since I couldn't find a version for Snow Leopard I decided to try and check out the 
latest SF source code version that looked promising enough to try and revert it back 
to a state that would let it compile and link on Snow Leopard. 

- This meant getting rid of ARC and going back to GC.
- This also means there's probably gonna be memory bugs. 
- Functionality-wise everything's there though. 
  Watching the console when loading binaries produces all the right 
  output and no error messages like wrong selectors etc.
- Based on r218 from Peter's Sourceforge SVN repository. 

I included a dmg with a precompiled binary in the `dist` folder.

Have fun!

_PS: the original README included with the project has been renamed to README.orig_

