# Teko

Teko is an open source typeface that currently supports the Devanagari and Latin scripts. This font family has been created for use in headlines and other display-sized text on screen. Five font styles make up the initial release.

Display families with extensive character sets are rare for any script. With Indian typefaces, however, large character sets are even less common. ITF’s designs are an exception. The Teko typeface features letterforms with low stroke contrast, square proportions and a structure that appears visually simple.

The Regular, Medium and Semibold fonts are recommended for use in long headlines, while Bold is intended primarily for setting just one or two words. The Light is a beautiful variant that may be put to exceptionally good use in large headlines on websites. At display sizes, Teko works equally well on screen or in print. Each font contains 1090 glyphs, offering full support for the conjuncts and ligatures required by languages written with the Devanagari script. Teko is an excellent choice for use in advertising or for news tickers on television screens (breaking news, etc.)

Manushi Parikh designed the Teko typeface for the Indian Type Foundry, who published it in 2014.

## Code base

This working directory is forked from the common code base, [ITF Base Devanagari (for Google Fonts)](https://github.com/itfoundry/base-devanagari-gf).

## Dependencies

- [Adobe Font Development Kit for OpenType](http://www.adobe.com/devnet/opentype/afdko.html) (AFDKO), version 2.5 build 63209 (Sep 18 2014) or newer.
- A script [`UFOInstanceGenerator.py`](https://github.com/adobe-type-tools/python-scripts/blob/master/FDK%20Extras/UFOInstanceGenerator.py) (to be placed in AFDKO’s directory `FDK/Tools/osx`) and two [modules](https://github.com/adobe-type-tools/python-modules) (to be placed in Python’s `site-packages` directory) from Adobe.
