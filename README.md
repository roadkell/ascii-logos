## ASCII (actually, Unicode) logos for Neofetch (and beyond) ##

* Install [Neofetch](https://github.com/dylanaraps/neofetch) *or* [one of the alternatives](https://github.com/topics/neofetch) (for example, [HyFetch](https://github.com/hykilpikonna/hyfetch) is an updated fork).
* Clone this repo *or* download individual `neofetch/*.txt` files.
* Run Neofetch with arguments (see below) *or* modify your `~/.config/neofetch/config.conf` to make changes permanent.
* Also check out LGBTQ+ pride flag-colored versions [here](https://github.com/roadkell/ascii-logos-uwu) <3

### IBM ThinkPad classic logo (vertical) ###
	neofetch --ascii --source "/path/to/ibm-tp-v.txt" --ascii_colors '7' '1' '2' '4'
![Neofetch with IBM ThinkPad classic logo (vertical)](./screenshots/ibm-tp-v-neofetch.png?raw=true)

### IBM ThinkPad classic logo (horizontal) ###
	neofetch --ascii --source "/path/to/ibm-tp-h.txt" --ascii_colors '7' '1' '2' '4'
![IBM ThinkPad classic logo (horizontal)](./screenshots/ibm-tp-h.png?raw=true)

### ThinkPad modern logo ###
	neofetch --ascii --source "/path/to/thinkpad-v.txt" --ascii_colors '7' '1'
	neofetch --ascii --source "/path/to/thinkpad-h.txt" --ascii_colors '7' '1'
![ThinkPad modern logo (vertical)](./screenshots/thinkpad-v.png?raw=true)
![ThinkPad modern logo (horizontal)](./screenshots/thinkpad-h.png?raw=true)

### ThinkPad modern logo (half-size, horizontal) ###
	neofetch --ascii --source "/path/to/thinkpad-halfsize-h.txt" --ascii_colors '7' '1'
![ThinkPad modern logo (half-size, horizontal)](./screenshots/thinkpad-halfsize-h.png?raw=true)

### Lenovo modern logo (horizontal) ###
	neofetch --ascii --source "/path/to/lenovo-h.txt" --ascii_colors '1'
![Lenovo modern logo (horizontal)](./screenshots/lenovo-h.png?raw=true)

### ThinkServer & ThinkCentre logo (vertical) ###
	neofetch --ascii --source "/path/to/thinkserver-v.txt" --ascii_colors '7' '1'
	neofetch --ascii --source "/path/to/thinkcentre-v.txt" --ascii_colors '7' '1'
![ThinkServer logo (vertical)](./screenshots/thinkserver-v.png?raw=true)
![ThinkCentre logo (vertical)](./screenshots/thinkcentre-v.png?raw=true)

### Notes ###

* There are Unicode symbols in use beyond the classic charset of ASCII codepage 437 (notably, [Block Elements](https://en.wikipedia.org/wiki/Block_Elements) and [Symbols for Legacy Computing](https://en.wikipedia.org/wiki/Symbols_for_Legacy_Computing)), so make sure your terminal emulator and font support them. For example, [Unifont Upper](https://unifoundry.com/unifont/index.html) (`fonts-unifont` package in Ubuntu, `font-gnu-unifont` in Homebrew) and [Code2001](https://www.code2001.com/code2001.htm) fonts have the necessary glyphs. If images look distorted, try `*-lowres.txt` versions — they only use symbols from Unicode 1.0-3.2 which are likely supported ubiquitously.
* These are not proper ANSI colors, they use [Neofetch ASCII file format](https://github.com/dylanaraps/neofetch/wiki/Custom-Ascii-art-file-format) which is quite color-limited. This will change when Neofetch [implements](https://github.com/dylanaraps/neofetch/issues/1699) [ANSI escape codes](https://en.wikipedia.org/wiki/ANSI_escape_code#24-bit). Also, colorless versions are available in `bw` folder.
* Enjoy!

### To do ###

* Make low-res versions restricted to the charset of ASCII CP437.

### Legal disclaimer ###

* I am not affiliated with IBM or Lenovo. All trademarks, logos and brand names are the property of their respective owners. Use of these names, trademarks and brands does not imply endorsement.
* For guidelines on the permitted uses of the IBM logo, refer to <https://www.ibm.com/design/language/ibm-logos/8-bar/>.
* For guidelines on the permitted uses of the Lenovo and ThinkPad logos, refer to <https://www.lenovo.com/us/en/legal/copytrade/>.

### Important ###
[Queer Svit](https://queersvit.taplink.ws/) is an organization that helps queer and BAME people impacted by the war in Ukraine, and those whose lives are threated by rising authoritarianism in Russia and Belarus. We are a group of volunteers, providing financial assistance, housing, and transportation to LGBTQ+ and BAME people in need, along with guidance and connections to further resources.
Any donation helps, and we are always grateful to people who spread the word about our cause. Thank you!
