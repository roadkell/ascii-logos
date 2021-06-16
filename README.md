# ASCII/ANSI art images for Neofetch and beyond

* Install https://github.com/dylanaraps/neofetch/
* Download `*-neofetch.txt` files from this repo
* Run Neofetch with arguments (see below)

  *or*

* Modify your `~/.config/neofetch/config.conf` to make the changes permanent

### IBM ThinkPad classic logo (vertical) ###
    neofetch --ascii --source "/path/to/ibm-tp-v-neofetch.txt" --ascii_colors '7' '1' '2' '4'
![Neofetch with IBM ThinkPad logo (vertical)](https://user-images.githubusercontent.com/4406611/122239502-6ce3e880-ceda-11eb-8824-73bc19586f62.png)

### IBM ThinkPad classic logo (horizontal) ###
    neofetch --ascii --source "/path/to/ibm-tp-h-neofetch.txt" --ascii_colors '7' '1' '2' '4'
![Neofetch with IBM ThinkPad logo (horizontal)](https://user-images.githubusercontent.com/4406611/122252190-99046700-cee4-11eb-9d42-5bcacb9fead7.png)


Notes:
* There are some Unicode symbols in use beyond the classic 8-bit ASCII code page (notably, [Block Elements](https://en.wikipedia.org/wiki/Block_Elements)), so make sure your terminal and font support Unicode (I use [kitty](https://github.com/kovidgoyal/kitty/) and [MesloLGS NF](https://github.com/romkatv/powerlevel10k#meslo-nerd-font-patched-for-powerlevel10k)).
* These are not proper ANSI images, they use ![Neofetch ASCII file format](https://github.com/dylanaraps/neofetch/wiki/Custom-Ascii-art-file-format) which is quite color-limited. This will change when Neofetch [implements](https://github.com/dylanaraps/neofetch/issues/1699) [ANSI escape codes](https://en.wikipedia.org/wiki/ANSI_escape_code#24-bit).
