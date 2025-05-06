![EasyABC logo](img/abclogo.png "EasyABCLite")

# EasyABCLite

An open source ABC editor for Windows, OSX and Linux based on EasyABC. It is published under the GNU Public License.

## Features

- Good ABC standard coverage thanks to internal use of abcm2ps and abc2midi
- Syntax highlighting
- Zoom support
- Export to MIDI, SVG, PDF (single tune or whole tune book).
- Select notes by clicking on them and add music symbols by using drop-down menus in the toolbar.
- Play the active tune as midi
- See which notes are currently playing (Follow score)
- Contextual guidance (ABC Assist)
- The musical score is automatically updated as you type in ABC code.
- Support for unicode (utf-8) and other encodings.
- Transpose and halve/double note length functionality (using abc2abc)
- An abcm2ps format file can easily be specified in the settings.
- ABC fields in the file header are applied to every single tune in a tune book.
- Automatic alignment of bars on different lines
- Functions to sort tunes and renumber X: fields.
- Musical search function - search for note sequences irrespectively of key, etc.

## Credits - software components used by EasyABCLite

- abcm2ps for converting ABC code to note images (developed/maintained by Jean-François Moine)
- abc2midi for converting ABC code to midi (by James Allwright, maintained by Seymour Shlien)
- wxPython cross-platform user-interface framework
- scintilla for the text editor used for ABC code
- python midi package for the initial parsing of midi files to be imported
- pygame (which wraps portmidi) for real-time midi input

## Links

- [abcnotation.com](https://abcnotation.com)
- [abcplus.sourceforge.net](https://abcplus.sourceforge.net)

