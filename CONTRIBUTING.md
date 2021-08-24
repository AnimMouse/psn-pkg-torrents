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

Game names with illegal characters like : (colon) should be removed.

Example file name for Red Dead Redemption: Undead Nightmare:\
Red Dead Redemption Undead Nightmare.torrent

#### Multipart PKGs
For Multipart PKGs, create a folder and put torrents there.

Folder name format if region is US: \<Game Name> \<Console>\
Folder name format if region is different than US: \<Game Name> \<Region> \<Console>

Example folder name:\
Yakuza 5 PS3\
Grand Theft Auto V EU PS4

Torrent file name format if region is US: \<Game Name> \<Console> \<Part Number>\
Torrent file name format if region is different than US: \<Game Name> \<Region> \<Console> \<Part Number>

Example file name:\
Yakuza 5 PS3 1.torrent\
Grand Theft Auto V EU PS4 1.torrent

Torrent comment field format: \<Game Name> \<Part Number> \<Region> \<Console> PSN PKG \<Where the link came from> by \<Username>

Example comment:\
Grand Theft Auto V 1 US PS4 PSN PKG NPS by AnimMouse\
Gravity Rush 2 1 US PS4 PSN PKG NPS by AnimMouse

#### Downloadable content (DLCs)
Put DLCs inside the DLC folder.

Torrent file name format if region is US: \<Game Name> \<Console> DLC\
Torrent file name format if region is different than US: \<Game Name> \<Region> \<Console> DLC

Example file name:\
Grand Theft Auto IV - The Ballad of Gay Tony PS3 DLC.torrent\
Grand Theft Auto IV - The Lost and the Damned PS3 DLC.torrent

Torrent comment field format: \<Game Name> \<Region> \<Console> DLC PSN PKG \<Where the link came from> by \<Username>

Example comment:\
Grand Theft Auto IV - The Ballad of Gay Tony US PS3 DLC PSN PKG NPS by AnimMouse\
Grand Theft Auto IV - The Lost and the Damned US PS3 DLC PSN PKG NPS by AnimMouse

#### BitTorrent v2 and hybrid
For v2 and hybrid torrents, append the BitTorrent protocol version used at the end of the file name.

Example v2 file name: Grand Theft Auto V PS3 v2.torrent

Example hybrid file name: Gravity Rush PSVita hybrid.torrent