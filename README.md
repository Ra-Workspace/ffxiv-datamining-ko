# ffxiv-datamining-ko
This repository is to serve as a place to share data mining information related to Final Fantasy XIV in Korean.

If you want to know datamining, go [viion/ffxiv-datamining](https://github.com/viion/ffxiv-datamining) and check docs.

### csv/

This repository keeps a record of CSV's extracted via [SaintCoinach](https://github.com/ufx/SaintCoinach/releases) using the command `rawexd`, this is so they can be easily linked and referenced when datamining, so we have a git history of changes and just to make life easier in some cases :)

### ex/

It contains an archive list of the [SaintCoinach ex.json](https://github.com/ufx/SaintCoinach/blob/master/SaintCoinach/ex.json) file, ths main point was to keep a `ex.json` file per Patch, then if you wanted to extract data from an older patch (such as Korean or Chinese clients) you can hot-swap the `ex.json` file and extract data in the correct format.
