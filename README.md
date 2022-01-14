## ASCII Art Images for Neofetch (and Beyond) ##

* Install https://github.com/dylanaraps/neofetch/ *or* [one of the alternatives](https://github.com/topics/neofetch)
* Clone this repo *or* download individual `neofetch/*.txt` files
* Run Neofetch with arguments (see below) *or* modify your `~/.config/neofetch/config.conf` to make changes permanent

### IBM ThinkPad Classic Logo (vertical) ###
	neofetch --ascii --source "/path/to/ibm-tp-v.txt" --ascii_colors '7' '1' '2' '4'
![Neofetch with IBM ThinkPad classic logo (vertical)](https://github.com/roadkell/ascii-art/blob/main/screenshots/ibm-tp-v-neofetch.png?raw=true)

### IBM ThinkPad Classic Logo (horizontal) ###
	neofetch --ascii --source "/path/to/ibm-tp-h.txt" --ascii_colors '7' '1' '2' '4'
![IBM ThinkPad classic logo (horizontal)](https://github.com/roadkell/ascii-art/blob/main/screenshots/ibm-tp-h.png?raw=true)

### ThinkPad Modern Logo ###
	neofetch --ascii --source "/path/to/thinkpad-v.txt" --ascii_colors '7' '1'
	neofetch --ascii --source "/path/to/thinkpad-h.txt" --ascii_colors '7' '1'
![ThinkPad modern logo (vertical)](https://github.com/roadkell/ascii-art/blob/main/screenshots/thinkpad-v.png?raw=true)
![ThinkPad modern logo (horizontal)](https://github.com/roadkell/ascii-art/blob/main/screenshots/thinkpad-h.png?raw=true)

### ThinkPad Modern Logo (half-size, horizontal) ###
	neofetch --ascii --source "/path/to/thinkpad-halfsize-h.txt" --ascii_colors '7' '1'
![ThinkPad modern logo (half-size, horizontal)](https://github.com/roadkell/ascii-art/blob/main/screenshots/thinkpad-halfsize-h.png?raw=true)

### Lenovo Modern Logo (horizontal) ###
	neofetch --ascii --source "/path/to/lenovo-h.txt" --ascii_colors '1'
![Lenovo modern logo (horizontal)](https://github.com/roadkell/ascii-art/blob/main/screenshots/lenovo-h.png?raw=true)

### Trans Rights 🏳️‍⚧️ ###
	neofetch --ascii --source "/path/to/ibm-transpad-v.txt" --ascii_colors '15' '14' '9'
	neofetch --ascii --source "/path/to/ibm-transpad-h.txt" --ascii_colors '15' '14' '9'
![IBM TransPad logo (vertical)](https://github.com/roadkell/ascii-art/blob/main/screenshots/ibm-transpad-v.png?raw=true)
![IBM TransPad logo (horizontal)](https://github.com/roadkell/ascii-art/blob/main/screenshots/ibm-transpad-h.png?raw=true)


### Notes ###
* There are Unicode symbols in use beyond the classic charset of ASCII codepage 437 (notably, [Block Elements](https://en.wikipedia.org/wiki/Block_Elements) and [Symbols for Legacy Computing](https://en.wikipedia.org/wiki/Symbols_for_Legacy_Computing)), so make sure your terminal emulator and font support Unicode version 13.0 or later. If images look distorted, try `*-lowres.txt` versions - they only use symbols from Unicode 1.0-3.2 which are likely supported ubiquitously.
* These are not proper ANSI colors, they use [Neofetch ASCII file format](https://github.com/dylanaraps/neofetch/wiki/Custom-Ascii-art-file-format) which is quite color-limited. This will change when Neofetch [implements](https://github.com/dylanaraps/neofetch/issues/1699) [ANSI escape codes](https://en.wikipedia.org/wiki/ANSI_escape_code#24-bit). Also, colorless versions are available in `monochrome` folder. Enjoy!


### To Do ###
* Make low-res versions restricted to the charset of ASCII CP437


### Legal Disclaimer ###
* I am not affiliated with IBM or Lenovo. All trademarks, logos and brand names are the property of their respective owners. Use of these names, trademarks and brands does not imply endorsement.
* For guidelines on the permitted uses of the IBM logo, refer to <https://www.ibm.com/design/language/ibm-logos/8-bar/>.
* For guidelines on the permitted uses of the Lenovo and ThinkPad logos, refer to <https://www.lenovo.com/us/en/legal/copytrade/>.
