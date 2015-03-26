# Mezzo
Old (circa 2004), probably defunct, experimental code.  Mezzo was intended as a new base library for the audio parts of Audacity.  These files are of historic interest, and also of interest from a design perspective.  We would like to separate the audio and GUI parts of Audacity better. This was the beginning of an attempt at doing so.

Mezzo was designed with both efficiency and flexibility in mind.  

* Not tied to any GUI system. 
* As few dependencies (on libraries) as possible.
* Independently useful components.
* Clear memory semantics.

The code written up to when mezzo was abandoned supports Audacity's block file model (many small files for storing audio sequence) and provides an abstraction to allow other methods too.

More information about mezzo can be found at http://wiki.audacityteam.org/index.php?title=Mezzo
