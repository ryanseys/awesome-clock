awesome-clock
=============

Awesome Clock watchface for Pebble Watch

## How To Use

1. Put this repo folder in pebble sdk folder (own folder of /awesome-clock)
2. Run `../tools/create_pebble_project.py --symlink-only ../sdk/ awesome-clock`
3. Run `cd awesome-clock/` to navigate to awesome-clock
4. Run `./waf configure build` to build
5. Run `python -m SimpleHTTPServer 8000` to serve folder locally.
6. Open the {{ computer IP }}:8000 on your phone.
7. Navigate to the awesomeclock.pbw and open to install on watch! :D
8. Be (even more) awesome!
