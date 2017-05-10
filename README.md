## TraktForVLC

>  This project is obselete !

Allow scrobbling VLC content to Trakt. Since VLC has no idea what you are watching the script will attempt to figure out if you are watching a TV show or a Movie based on the name of the video, and it's lenght for movies. So, the script can only work well if your files are named properly.

This script is based off of the TraktForBoxee script and works very similarily to it.

You can run the script through TraktForVLC.py.

The script will run until you kill the command.

*Installation*

Install Python 2.7.2 if you don't have it installed already

## Configuration

Setup config.ini
- Set the IP and Port that you entered into VLC. If you entered the above ip and port in VLC then the default are fine.
- Set your Trakt username and password

There are two ways to configure VLC remote control :

With VLC settings (ver.2)
Tools > Preferences > All > Interface > Main Interfaces > RC
- Check "Do not open a DOS command box interface"
- Input "localhost:4222" into the "TCP command input" box

With commande line
"vlc.exe" --extraintf=rc --rc-host=localhost:4222 --rc-quiet

