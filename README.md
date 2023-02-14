# akufu36 

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC_BY--NC_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

A repository containing design files for akufu36 with some minor improvements
(see [Changelog](#changelog)).  Originally released by [NGM
Design](https://ngm-design.com/) ([@ngmdesign](https://twitter.com/ngmdesign))
under CC BY-NC 4.0.

## Source

Design files for v1.0, v1.5, and v2 are on Thingiverse and Printables.

- v1.0 - [Thingiverse](https://www.thingiverse.com/thing:4492963) // [Printables](https://www.printables.com/en/model/70202-akufu36-original-mechanical-keyboard-case-plate)
- v1.5 - [Thingiverse](https://www.thingiverse.com/thing:4593595) // [Printables](https://www.printables.com/en/model/70201-akufu36-ver15-original-mechanical-keyboard-case-pl)
- v2.0 - [Thingiverse](https://www.thingiverse.com/thing:4593582) // [Printables](https://www.printables.com/en/model/70200-akufu36-ver20-original-mechanical-keyboard-case-pl)


## Packaging

The source design files for each version were downloaded from Printables.
`*.stl` and `*.step` (v1.5 and v2 only) files were extracted and placed in
version specific repository subdirectories of this repository.  All other files
were deleted (e.g. packaging information from Printables). 

Each version can be packaged individually as follows:

```
zip -jr akufu36-v1.zip v1/
```

## Changelog

- Use https://stl-mirror.beekeeb.com/ to reflect included top, bottom, and
  switch plate files. Relabel `l` (original) and `r` (generated).
