# Simple Slide by Marp App

## Install

- Install Marp-Cli

  ```sh
  npm install -g @marp-team/marp-cli
  ```

- Install Marp for VS Code

  see [Link](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)

---

## Start Server to view in HTML

```sh
marp . --server
```

Start server listened at [http://localhost:8080/](http://localhost:8080/) ...

---

## Generate PDF Slide

```sh
marp --pdf -o simple-slide.pdf --allow-local-files  simple-slide.md 
```

Marp provide some nice built-in themes in Marp Core. You can choose a favorite theme by using Marpit theme directive in your Markdown. But I don't need to include theme info in my markdown. please run command with `--theme` for specific required theme.

### Theme gaia

```sh
marp --theme gaia --pdf -o simple-slide-gaia.pdf --allow-local-files  simple-slide.md
```

### Theme uncover

```sh
marp --theme uncover --pdf -o simple-slide-uncover.pdf --allow-local-files  simple-slide.md
```

---

## Deckset Help

[https://docs.deckset.com/English.lproj/getting-started.html](https://docs.deckset.com/English.lproj/getting-started.html)

---

## Reference

- [@marp-team/marp-cli](https://github.com/marp-team/marp-cli#install)
- [yhatt/marp.md](https://gist.github.com/yhatt/a7d33a306a87ff634df7bb96aab058b5)
- [Marpit Markdown](https://marpit.marp.app/markdown)
- [Marp Core built-in themes](https://github.com/marp-team/marp-core/tree/main/themes)
- [@marp-team/marp-core](https://github.com/marp-team/marp-core)
- [Marpit API](https://marpit-api.marp.app)
