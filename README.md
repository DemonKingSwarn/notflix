<h1 align="center">NOTFLIX</h1>
<p align="center">f@#k netflix use notflix a tool which search magnet links and stream it with peerflix</p>

> Watch this video to understand - [bugswriter's notflix](https://youtu.be/FbE19_omaWY)

### How does this work?

This is a shell script. It scape 1337x and get the magnet link.
After this it use [peerflix](https://github.com/mafintosh/peerflix) to stream the video from magnet link.
For scraping script use simple gnu utils like sed, awk, paste, cut.

## Requirements

* [peerflix](https://github.com/mafintosh/peerflix) - A tool to stream torrent. `sudo npm install peerflix -g`
* [fzf](https://github.com/junegunn/fzf) - For selection screen.

## Installation

### cURL
cURL **notflix** to your **$PATH** and give execute permissions.

```sh
$ curl -sL "https://raw.githubusercontent.com/demonkingswarn/notflix/master/notflix" > $HOME/.local/bin/notflix
$ chmod +x $HOME/.local/bin/notflix
```
- To update, just do `curl` again, no need to `chmod` anymore.
- To uninstall, simply remove `notflix` from your **$PATH**, for example `rm -f $HOME/.local/bin/notflix`.

## License
This project is licensed under [GPL-3.0](https://raw.githubusercontent.com/Illumina/licenses/master/gpl-3.0.txt).

