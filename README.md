# YouTube Music (Music Player)
Download [Scoop](https://github.com/BosEriko/scoop) as your package manager then install [Spotify](https://scoop.sh/#/apps?q=youtube-music).

## Install YouTube Music
```sh
scoop bucket add extras
scoop install extras/youtube-music
```

## Sync your settings
Go to the folder where you want to put your YouTube Music files and run the following script.
```sh
curl -fsSL https://raw.githubusercontent.com/BosEriko/youtube-music/HEAD/install.sh | sh
```

## Enable Custom Theme
Enable the [custom theme](custom.css) by going to `Options` > `Visual Tweaks` > `Theme` > `Import cusom css file`.