# melodies.lmms
Melodies that are re-generatable in [LMMS](https://lmms.io/) software ([GitHub Project](https://github.com/LMMS/lmms)), with source file.

## Project files structure
* `lyrics/*.txt`, `*.lrc`: lyrics file
* `notations/*.txt`: (स्वर लिपी) Sargam or English scale notes eg. notations-sargams.txt formatted in Bhatkhande Style.
* `output/*.ogg`: Raw audio output eg. 01.ogg
* `project/*.mmpz`: Actual DAW file for LMMS eg. project.mmpz
* `youtube.txt`: Collection of video links around a project

## swar converter
The notations files are made compatible with my other project: [swar.lmms](https://github.com/anytizer/swar.lmms/) application.
That project can produce .xpt XML Pattern files from sargam notations, for importing them directly into LMMS's piano editor.
This makes data entry easier, faster and accurate.

### Basic conversion chart
Representation↓ Keys →| C | C# | D | D# | E | F | F# | G | G# | A | A# | B
-- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | --
English | C | C# | D | D# | E | F | F# | G | G# | A | A# | B
Roman Short Form | S | S' | R | R' | G | M | M' | P | P' | D | D' | N
North Indian | सा | सा' | रे | रे' | ग | म | म' | प | प' | ध | ध' | नि

If you see project.mmpz file, the data entry has been already done for you.
Supplied .mmpz file does not contain enough instrumental presets.
They are for melodies only.

## Did you improve?
Let me know back if you improved any of these melodies.

## Disclaimers
It is a collaborative project; my work is free; but the melody or other collaborator's work may not be.
Collaborators may retain their authorship.

### Samples - Disclaimer
The tiny sound clips and audio instruments are default to LMMS 1.3 version, or otherwise:
* recorded by the author
* or, assumed free for at least tutotrial purpose (non commercial use)
* If you think they should be removed, please mention your issue to @anytizer.

### .ogg Disclaimer
This is a default audio output format I chose. It should NOT be cosndiered as the final version of the project.
The .ogg file is attached with the project considering that some users may want to listen or preview the audio before checking out the complete project folder.

Since I do not know enough mixing and mastering, the provided audio is for a reference only.
It does not carry enough instrumental presets.

Compile / regenerate / improve your own beats!

### Melody Disclaimer
Melodies are picked up for relevance, age, popularity, availability of public tutorials and many other aspects.
Neither I nor the collaborators may always claim that they fully own it.

I seek the orignal contributor to credit them properly. See *credits.txt* file where applicable.
Credits may exist in .txt files as well.

These are **melodies** only, not a full audio compilation.

# Mind your speakers
These LMMS files are made comatible on cup-foamed gaming headphones experience.
Mind your speakers, if you are playing too loud.

# Research | Experiement | Develop | Collaborate
A lot of researches are made, experimentations done, data entries made, and applications developed to raise this project.
If you make use of any of the materials in this project, please consider backlinking this project in your derivatives.

Also, please duplicate the melody's copyright information (generally, credits.txt file) within your work too.

Thank you! Enjoy the raw beats!

# Copyrights?

Yes, there could be. These melodies may not be free.

I have tried to collborate the collection of melodies in order to preseve them.
It takes several days to improve a melody, and I tend to supply as much information as possible.
This includes source of melody (original websites, tutorials, videos), author's contact information, improviser's views, and some stories behind the original work.

So copyrights may still remain with known or unknown team of original workers for their contributions, even if the team mate has been decesead.

Primary purpose is to preserve and tutor the melody; but please respect individual item's copyright information if you are using them commercially.

# Notations Formatting

The notations formatting is __similar__ to the [Bhatkhande style](https://archive.org/search.php?query=bhatkhande).
Parsing logic has been included for the following:

* Hash '#' means a comment line.
* Pipe '|' is a division separator - Bar, or [Vibhag](https://en.wikipedia.org/wiki/Vibhag).
* Comma ',' is a group of notes played together within the same beat. eg: `sa,re re,ga` (meed, gamak, khitkaa, kan)
* '#//' is a block separator, eg. Melody/Music/Prelude/Stanza separator.
* Apostrophe ''' means a sharp note. eg: `ma'`
* Asterisk '*' means higher octave note. eg: `sa*`
* Dot '.' means lower octave note. eg: `dha.`
* Dash '-' means continuation of a note. eg: `sa - - -`
* X mark 'x' means slicence during its timing. eg: `sa - - x`

# Creating special notes:
Timing is divided using comma in a beat:
* 1 comma: 50%,50% timing
* 2 comma: 33%,33%,33% timing - might produce a glitch
* 3 comma: 25%,25%,25%,25% timing eg, in flutes
* `re,x,x,x` termimates with a very short `re`.
* `re,-,x,x` may be similar to `re,x`
* `re,re` and `re,-` are different.
