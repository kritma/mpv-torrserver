# mpv Torrserver integration
sends torrent info to [TorrServer](https://github.com/YouROK/TorrServer) and gets playlist. Supports torrent files and magnet links

1. copy `mpv-torrserver.lua` into your `mpv/scripts`
2. Adjust `server` address in `mpv-torrserver.lua` or put `server=http://[TorrServer ip]:[port]` in `mpv/script-opts/mpv-torrserver.conf`

## Usage
Drag & Drop torrent into mpv

or

```sh
mpv <magent link or torrent file>
```

## Requirements
* curl
