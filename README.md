# NTSC VIDEO BOARD FOR DRAGON 32 RECREATION Rev 3 #

To further improve video quality on the Dragon 32 this
board completely isolates the video circuits from the rest
of the Dragon by making it a plugin. This also means that
only a single version of the Dragon rev 3 board is needed to
provide a PAL or NTSC solution.

## Progress ##

This is a complete first hack at the design, based on the
reference design in the 6847 datasheet with supporting
information from the MC1372 datasheet.

The generator and amplifier circuits are isolated and
*should* be good for a clean video signal.

## Note ##

Given most modern TVs work with NTSC **and** PAL, switching
automatically, this slimline video board (compared to the PAL
version of the board) should be a cheaper and more attractive
option. The component count is *much* lower and the harder to
find analogue multiplexer is not needed.
