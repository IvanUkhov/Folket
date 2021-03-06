# Folket

Folket is a Swedish–English dictionary for macOS.

![Dictionary](dictionary.png)

## Installation

1. [Download][archive] an archive with the latest version of the dictionary.
2. Unzip the archive and copy `Folket.dictionary` to `~/Library/Dictionaries`.
3. Open the Dictionary app and activate the Folket dictionary in the
   preferences.

## Usage

* Tap a word with three fingers on the trackpad.
* Hover the cursor over a word and press ⌃⌘D.
* Open the Dictionary app and type a word.

## Compilation

1. Clone the repository.
2. [Download](kit) the “Additional Tools for Xcode” package.
3. Move the “Dictionary Development Kit” directory from the “Utilities”
   directory found in the package to the directory of the repository.
4. Run `make install`.

## License

Folket is based on the [People’s Dictionary][folkets-index] (Folkets lexikon).
The People’s Dictionary is free. Both the English–Swedish and Swedish–English
dictionaries can be [downloaded][folkets-about] for use under the terms of the
[Creative Commons Attribution-Share Alike 2.5 Generic][license] license. Folket
is distributed under the same terms.

## Acknowledgments

The project is a fork of [MacFolket][macfolket], which is developed by
[Christopher Loessl][loessl].

[archive]: https://github.com/svenskan/folket/raw/gh-pages/Folket.zip
[kit]: https://developer.apple.com/downloads

[folkets-index]: http://folkets-lexikon.csc.kth.se/folkets/folkets.en.html
[folkets-about]: http://folkets-lexikon.csc.kth.se/folkets/om.en.html
[license]: http://creativecommons.org/licenses/by-sa/2.5

[macfolket]: https://github.com/hashier/MacFolket
[loessl]: http://loessl.org
