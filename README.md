## ThinkPad ASCII (actually, Unicode) logos for all your terminal needs ##

* Install [HyFetch](https://github.com/hykilpikonna/hyfetch) (an updated fork of the original [Neofetch](https://github.com/dylanaraps/neofetch) with 24-bit color support)
* Clone this repo *or* download individual files from the `color` subfolder
* Run `neowofetch` with desired arguments (see examples below) *or* modify your `~/.config/neofetch/config.conf` to make changes permanent
* Also check out LGBTQ+ pride flag-colored versions [here](https://github.com/roadkell/ascii-logos-uwu) <3

### IBM ThinkPad classic logo (vertical) ###
```
neowofetch --ascii 'color/ibm-tp-v.txt' --ascii_colors '#fd1813' '#0fa14c' '#1f70c1' '#ffffff'
```
![Neofetch with IBM ThinkPad classic logo (vertical)](./screenshots/ibm-tp-v-full.png?raw=true)

### IBM ThinkPad classic logo (horizontal) ###
```
neowofetch --ascii 'color/ibm-tp-h.txt' --ascii_colors '#fd1813' '#0fa14c' '#1f70c1' '#ffffff'
```
![IBM ThinkPad classic logo (horizontal)](./screenshots/ibm-tp-h.png?raw=true)

### ThinkPad modern logo ###
```
neowofetch --ascii 'color/thinkpad-v.txt' --ascii_colors '#e32726' '#ffffff'
neowofetch --ascii 'color/thinkpad-h.txt' --ascii_colors '#e32726' '#ffffff'
```
![ThinkPad modern logo (vertical)](./screenshots/thinkpad-v.png?raw=true)
![ThinkPad modern logo (horizontal)](./screenshots/thinkpad-h.png?raw=true)

### ThinkPad modern logo (half-size, horizontal) ###
```
neowofetch --ascii 'color/thinkpad-halfsize-h.txt' --ascii_colors '#e32726' '#ffffff'
```
![ThinkPad modern logo (half-size, horizontal)](./screenshots/thinkpad-halfsize-h.png?raw=true)

### Lenovo modern logo (horizontal) ###
```
neowofetch --ascii 'color/lenovo-h.txt' --ascii_colors '#e32726'
```
![Lenovo modern logo (horizontal)](./screenshots/lenovo-h.png?raw=true)

### ThinkServer & ThinkCentre logo (vertical) ###
```
neowofetch --ascii 'color/thinkserver-v.txt' --ascii_colors '#e32726' '#ffffff'
neowofetch --ascii 'color/thinkcentre-v.txt' --ascii_colors '#e32726' '#ffffff'
```
![ThinkServer logo (vertical)](./screenshots/thinkserver-v.png?raw=true)
![ThinkCentre logo (vertical)](./screenshots/thinkcentre-v.png?raw=true)

### ThinkPad Amiga-style line art logo (vertical) ###
```
neowofetch --ascii 'color/thinkpad-linear-v.txt' --ascii_colors '#e32726' '#ffffff'
```
![ThinkPad Amiga-style line art logo (vertical)](./screenshots/thinkpad-linear-v.png?raw=true)

### Notes ###

* If your terminal or your `*fetch` program doesn't support true color, try color indices like `--ascii_colors 1 2 4 15` for classic IBM ThinkPad logos and `--ascii_colors 1 15` for modern ones (result depends on your palette). Versions without color tags are available in `*-bw` subfolders.
* Default versions use Unicode characters beyond the charset of [code page 437](https://en.wikipedia.org/wiki/Code_page_437) (notably, [Block Elements](https://en.wikipedia.org/wiki/Block_Elements) and [Box Drawing](https://en.wikipedia.org/wiki/Box_Drawing)), so make sure your terminal emulator and font support them. For nostalgia purposes, `cp437-*` folders contain blockier versions restricted to the classic CP437 charset (though still coded in Unicode for compatibility).
* Enjoy!

### Important ###

[Queer Svit](https://queersvit.org/) is a black queer-run independent team of volunteers from all over the world. With your support we help LGBTQ+ and BAME people affected by the war and/or political repressions get to safety by providing consultations, purchasing tickets, finding free accommodation and providing humanitarian aid.

‌‌Just like any other catastrophe, war affects the most those who are most vulnerable, including LGBTQ+ and BAME people while at the same time their troubles are often rendered invisible. But because our own team comprises LGBTQ+ and BAME people we see the specific challenges our beneficiaries face and understand how to help them.

‌Your donations make a difference; Queer Svit is run in large part on small donations from individual donors. We are grateful for any and all help to continue our work — thank you!

### Legal disclaimer ###

I am not affiliated with IBM or Lenovo. All trademarks, logos and brand names are the property of their respective owners. Use of these names, trademarks and brands does not imply endorsement.

For guidelines on the permitted uses of the IBM logo, refer to <https://www.ibm.com/design/language/ibm-logos/8-bar/>.

For guidelines on the permitted uses of the Lenovo and ThinkPad logos, refer to <https://www.lenovo.com/us/en/legal/copytrade/>.
