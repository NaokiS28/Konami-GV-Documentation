# Konami GV/ZV610 Schematics

A (currently skeleton) schematics in KiCad 10.0 format for the Konami GV arcade main board.

The Konami GV could be considered a precursor to the [https://github.com/NaokiS28/Konami-System-573-Docs](Konami System 573), in that is is a Sony PlayStation based arcade board but is much simpler:

* The CD-ROM drive uses Narrow SCSI instead of ATAPI/IDE
* The GV uses a revision 0 GPU (CXD8514Q), which has some quirks compared to the later GPUs.
* Security is almost entirely done with a 128 byte EEPROM at position 25C.
* There are headers for players 3 & 4.
* Some (but almost all did not) have 28F400 NOR flash ROM soldered on board.
* Only JAMMA is a connection option.
