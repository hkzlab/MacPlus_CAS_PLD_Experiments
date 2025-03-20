# MacPlus CAS PLD Experiments

**WARNING**: Work in progress, do not use unless you know what you're doing! :)

## Introduction

As far as I know, the dumps for the CAS PLD (a PAL 20L8) on the Macintosh Plus that are floating around the net are problematic with some memory configurations.

I fiddled with the equations without having an PLD on hand, to try and get all the memory configurations working (4x 256KB, 2x 1MB, 2x 1MB + 2x 256KB, 4x 1MB),
I then got hold of an original Macintosh Plus motherboard, desoldered the CAS IC and manually checked the behavior of CAS lines.

The JEDs found in this repository are the current result of such work. They are working fine for me in a Macintosh Plus clone, with all supported memory configurations, using both original ROMs and UNITRON ROMs.

Testing by others is pending.
