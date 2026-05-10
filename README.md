# Kerbal Star Frontiers
## A planet pack with potentially interesting worlds and in the future, multiple stars
## Work in progress!


## Novus System
* Novus, a large blue-white star that's the result of a stellar merger, wrecking chaos in the system
* Ardor, a large hot super-joolian world being baked by Novus, with a singular surviving moon and a beautiful planetary disk that at the moment doesn't exist
    * Adaris, a shattered lava moon scarily close to Ardor, bombarded by Ardor's disk and charred by Novus
* Mirage, habitable paradise turned desert world. Sorta breathable, though the temperature would kill a Kerbal under the sun. Unstable climate and weather.
* Helia, a sterile, hot and humid dried-up hycean world, ocean floor flats with highly oxygenated water that may have simplistic life
    * Cairn, a lonely jagged cold moon containing jagged highlands and odd eroded valleys and flats. Can provide gravity assists/capture for Helia 
* Khion, a lonely cold white-blue ice giant which is heating up slightly
    * Boreas, a Vall clone with an atmosphere and strange weather. A slick melting ice ball with polar snow storms and sparse lakes
* Nimis, a highly elliptical gilly-sized comet with an immense tail

## Todo
* Wet surface configs
* Fix polar "keyhole" anomalies on some worlds. Byproduct of heightmap process :/ (I may not do for a while! Would require redoing height, and normal and parallax min/max)
* Optimize Nimis's tail
* Mirage's and Ardor's rings
* Fix Boreas's ocean node
* Helia revamp

## Implemented at a later date
* Use my procedural rings thingy once I get it working
* Optimization:
    * Downscaling some textures
    * DDS of EVE core textures
    * Not a priority
* Misc stuff like science defs
* Pretty readme/perhaps wiki with screenshots
* Second star system focusing on PDS70 style planetary disk

## Requirements
* Kopernicus obviously
* Parallax Continued
* VertexColormapEmissive and VertexMitchellNetravaliHeightMap
* V5 scatterer and volumetrics
    * In the far future I might add 2D cloud support for EVE-Redux and make parallax continued optional. V3 scatterer **may** be compatible, though I never tested it
## Optional
* BurstPQS: __This pack uses a lot of complicated PQS/terrain setups that are very costly on low-end hardware, I would *highly* recommend this__
* Scaled Decorator, presently just used for Nimis's tail
* My procedural ring mod once I release it eventually

`This project is licensed under GPLv3, with some exceptions. See LICENSE.md and LICENSEINFO.md`