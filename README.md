MACHINE
Sudo is mike, password is the standard linux password

PATCH
Pd patch directory/path: /home/mike/Desktop/MECA.pd

MEDIA
MEDIA-MECA directory/path: /home/media/mike/MECA-MEDIA
The media file (MAIN.WAV) is located on a flashdrive (MECA-MEDIA)
To update the file, simply put another 44.1/16 4 channels MAIN.WAV
on the MECA-MEDIA flashdrive

UPDATE
The patch can be updated via SSH or desktop

AUTOSTART
Autostart directory/path: /home/mike/.config/autostart/MECA.desktop
The autostart is a .desktop file, and is executed using pd

---------------
[Desktop Entry]
Type=Application
Name=MECA
Exec=pd /home/mike/Desktop/MECA.pd
---------------

If the name of the patch is changed during an update,
it must be changed in the autostart file as well. Example:
Exec= pd /home/mike/Desktop/newPatch.pd
