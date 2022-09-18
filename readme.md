# A Jellyfin startup script

Run this script to create a Jellyfin docker instance

Requirements:
[docker](https://www.docker.com/)
[docker compose](https://docs.docker.com/compose/install/)

To run use:
```
  chmod +x ./Jellyfin
  ./jellyfin
```

Move your files to `$HOME/jellyfin-medias/media/` to list on platform

You can use the start and stop scripts too. To use this do:
```
chmod +x start_jellyfin
chmod +x stop_jellyfin
```

then add this folder to your $PATH `PATH=/path/to/this/folder:$PATH`


