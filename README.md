NOTE: This was found by me, not made by me. Threw it on github to give it some more exposure.

-----------------

I have written a script to take all the time and effort out of setting up a seedbox. My script will do many things....

I have a sourceforge page: http://sourceforge.net/projects/flizbox/

flizbox version 7 (seedbox install script)

Lighttpd web server | rtorrent 0.9.3 | libtorrent 0.13.3 | RuTorrent 3.5 + all official plugins | autodl-irrsi with plugin for RuTorrent | vsftpd (very secure ftp using ssl) | mktorrent 1.0 | all required dependancies | a unique ssl cetificate for each weblink needed to your server (vsftp, rutorrent, deluge etc).

Option to install Deluge 1.3.5, ZNC 1.0 and Webmin (deluge option does not replace the rutorrent installation).

Tested 100% working on 64-bit versions of:-

- Debian 6
- Ubuntu 12.10 Server
- Ubuntu 12.04 Server
- Ubuntu 11.10 Server
- Ubuntu 11.04 Server
- Ubuntu 10.04 Server

This script is for a single seedbox user only.

How to use:-

After a fresh Linux install, log in as the ROOT USER using the password they give you into SSH and paste the following lines in turn:-

wget http://sourceforge.net/projects/flizbox/files/flizbox-v7.sh
bash flizbox-v7.sh

Any questions or suggestions contact axoree@gmail.com


