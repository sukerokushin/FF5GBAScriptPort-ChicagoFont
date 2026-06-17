# Final Fantasy V GBA Script Port - Legend of the Crystals Font Edit
Untested. Work in progress.

Using the Legend of the Crystals patch's assets as a basis, I recreated the GBA script port's special characters and ligatures with the LotC font table, adjusted the variable width definitions, and began the painstaking process of reformatting the entire game's scripts to fit with this new font width, all done with noisecross's fantastic [FF5e Text Editor](https://github.com/noisecross/FF5e_Text_Editor). Taking some inspiration from xJ4ck's own [Bigger Font patch](https://www.romhacking.net/hacks/9389/), I went and formatted the text to follow the official Chrono Trigger and the amazing FF4 Namingway/FF6 ROSE patches' conventions of adding spaces after linebreaks in dialogue with character names. I also had to pare down the GBA script's battle messages to fit, trying my hardest to keep the character voice and occasionally taking inspiration from how RPGe/LotC rendered their lines. The battle dialogue stuff is all very untested, however, so I would greatly appreciate reports in the issues tab, especially if you include saves/save states. This additionally undoes the translations' squared off menu/dialogue box frames in favor of the vanilla game's rounded corners.

tl;dr: Backported font commonly used in Square SNES RPGs and reformatted all GBA text to fit.
## Tools used

[FF5e Text Editor](https://github.com/noisecross/FF5e_Text_Editor) (text extraction/insertion, VWF table adjustment)

[Notepad++](https://notepad-plus-plus.org/) (find+replace operations on extracted text, comparing multiple text dumps)

[Paint.net](https://paint.net) (1bpp image editing)

Adobe Photoshop (2bpp/4bpp image editing, as editing indexed color PNGs was more convenient with it)

__And zero AI involvement.__
