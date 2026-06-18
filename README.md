# Final Fantasy V GBA Script Port - Legend of the Crystals Font Edit
Untested. Work in progress.

Using the Legend of the Crystals patch's assets as a basis, I:
 - recreated the GBA script port's special characters and ligatures with the LotC font table,
 - adjusted the variable width definitions, 
 - and began the painstaking process of reformatting the entire game's scripts to fit with this new font width,
all done with noisecross's fantastic [FF5e Text Editor](https://github.com/noisecross/FF5e_Text_Editor).

Taking some inspiration from xJ4cks's [Bigger Font patch](https://www.romhacking.net/hacks/9389/) for the GBA script port, I also went and formatted the text to follow the convention of adding spaces after linebreaks in dialogue with character names.

I also had to pare down the GBA script's battle messages to fit within a single line, trying my hardest to keep the character voice and occasionally taking inspiration from how RPGe/LotC rendered their lines. 

Additionally, I undid the GBA script port's squared off menu/dialogue box frames in favor of the vanilla game's rounded corners.

## What to do if you find any typos, bugs, etc.

Please report them here in the issues tab! If you're savvy enough, I accept pull requests too. All of the extracted game files are in common formats, so feel free to tinker for yourself.

## Tools used

[FF5e Text Editor](https://github.com/noisecross/FF5e_Text_Editor) (text extraction/insertion, VWF table adjustment)

[Notepad++](https://notepad-plus-plus.org/) (find+replace operations on extracted text, comparing multiple text dumps)

[ImHex](https://imhex.werwolv.net/) (GBA script port analysis, i.e. the new BattleSpeech offset)

[Paint.net](https://paint.net) (1bpp image editing)

Adobe Photoshop (2bpp/4bpp image editing, as editing indexed color PNGs was more convenient with it)

__And zero AI involvement.__
