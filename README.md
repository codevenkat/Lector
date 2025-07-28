<p align="center"><img src="lector/resources/raw/logo/logotype_horizontal.svg" alt="Lector" height="90px"></p>

(this is a fork as the original project has been abandoned)

Qt based ebook reader

Currently supports:
* pdf
* epub
* djvu
* fb2
* mobi
* azw / azw3 / azw4
* cbr / cbz
* md

## Requirements
### Needed
Python 3.13, pip

### Building Instructions
Binary releases will be available soon. For now please compile the program using a Python installation.

* Clone the repository
* Create a virtualenv and activate it
* `pip install .`
* You can now run the program with `lector`

You can also at this step install optional support for more file extensions as extras. Currently available are `pdf`, `djvu`, `md`, `txt`. To get all of them, run
```shell
pip install '.[all]'
```

For `djvu` support make sure you have the required version of djvulibre available on your system. Note that as the `djvu` module [only supports linux](https://github.com/FriedrichFroebel/python-djvulibre?tab=readme-ov-file#about-this-fork) as of now, windows support for it is not possible.

## Support
When reporting issues:
* Make sure you're at the latest commit.
* Run with `$EXECUTABLEPATH debug`.
* Include the log `~/.local/share/Lector/Lector.log` AND terminal output.
* If you're having trouble with a book while the rest of the application / other books work, please link to a copy of the book itself.
* If nothing is working, please make sure the requirements mentioned above are all installed, and are at least at the version mentioned.

## Translations
1. There is a `SAMPLE.ts` file [here](https://github.com/BasioMeusPuga/Lector/tree/master/lector/resources/translations). Open it in `Qt Linguist`.
2. Pick the language you wish to translate to.
3. Translate relevant strings.
4. Try to resist the urge to include profanity.
5. Save the file as `Lector_<language>` and send it to me, preferably as a pull request.

Please keep the translations short. There's only so much space for UI elements.

## Screenshots

### Main window
![alt tag](https://i.imgur.com/516hRkS.png)

### Table view
![alt tag](https://i.imgur.com/o9An7AR.png)

### Book reading view
![alt tag](https://i.imgur.com/ITG63Fc.png)

### Distraction free view
![alt tag](https://i.imgur.com/g8Ltupy.png)

### Annotation support
![alt tag](https://i.imgur.com/gLK29F4.png)

### Comic reading view
![alt tag](https://i.imgur.com/rvvTQCM.png)

### Bookmark support
![alt tag](https://i.imgur.com/Y7qoU8m.png)

### View profiles
![alt tag](https://i.imgur.com/awE2q2K.png)

### Metadata editor
![alt tag](https://i.imgur.com/0CDpNO8.png)

### In program dictionary
![alt tag](https://i.imgur.com/RF72m2h.png)

### Settings window
![alt tag](https://i.imgur.com/l6zJXaH.png)

## Attributions
* [KindleUnpack](https://github.com/kevinhendricks/KindleUnpack)
* [rarfile](https://github.com/markokr/rarfile)
* [Papirus icon theme](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme)

## License
_Lector_ is released under the GNU General Public License v3.0 or any later version.
See the [LICENSE](LICENSE) file for details.
