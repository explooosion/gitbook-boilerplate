# Gitbook Boilerplate

[![forthebadge](https://forthebadge.com/images/badges/fuck-it-ship-it.svg)](https://github.com/explooosion/gitbook-boilerplate)
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://github.com/explooosion/gitbook-boilerplate)
[![forthebadge](https://forthebadge.com/images/badges/makes-people-smile.svg)](https://github.com/explooosion/gitbook-boilerplate)

### Documentation

👉 [Start Reading](https://github.com/explooosion/gitbook-boilerplate)

### Global Installation

Installation is done using the
[`npm install` command](https://docs.npmjs.com/getting-started/installing-npm-packages-locally):

```bash
npm install -g gitbook-cli
```

```bash
gitbook install
```

### Run Gitbook

#### View

Using `dev` to run local [http://192.168.0.100:8080](http://192.168.0.100:8080)

```bash
npm run dev
```

If you want to watch files, please remove the folder `_book` after running the script `dev`.

> from [git serve can't restart when file changes #1379](https://github.com/GitbookIO/gitbook/issues/1379)    

#### Image

You can put images to [imgur](https://imgur.com/), please install [vscode-imgur](https://github.com/MaxfieldWalker/vscode-imgur).
> Add your imgur key to `.vscode` / `settings.json`

> Hotkey `Ctrl` + `Alt` + `V`

### Build To HTML

Using `build` to compile the files into `docs`.

```bash
npm run build
```

### Convert To PDF

Using `pdf` to export the PDF format.

```bash
npm run pdf
```
> If your OS is Windows, please download [Calibre](https://calibre-ebook.com/download_windows).

### Use Disqus

Input your shortname into `book.json`,
then you can use the [disqus](https://disqus.com/) plugin.