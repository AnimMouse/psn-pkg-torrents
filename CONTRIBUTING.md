## Contributing
If you want to create a torrent to help our list of games, feel free to make a pull request.

Or use our [torrent creator](https://github.com/AnimMouse/torrent-webseed-creator) by forking this repository and using the provided GitHub Action in this repository to create a torrent and create a pull request.

### Torrent Format

Torrent file name format if region is US: \<Game Name> \<Console>\
Torrent file name format if region is different than US: \<Game Name> \<Region> \<Console>

Example file name:\
Grand Theft Auto V PS3.torrent\
Top Spin 4 EU PS3.torrent

Torrent comment field format: \<Game Name> \<Region> \<Console> PSN PKG \<Where the link came from> by \<Username>

Example comment:\
Grand Theft Auto V US PS3 PSN PKG NPS by AnimMouse\
Pro Evolution Soccer 2019 US PS4 PSN PKG PSNDL by AnimMouse

Source should be set at "psn-pkg-torrents"

Piece size should be set at "auto"

#### BitTorrent v2 and hybrid
For v2 and hybrid torrents, append the BitTorrent protocol version used at the end of the file name.

Example v2 file name: Grand Theft Auto V PS3 v2.torrent

Example hybrid file name: Gravity Rush PSVita.torrent