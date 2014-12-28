XBMC-Remote
===========
The official XBMC Remote app on Google Play store does not seem to be maintained by the team any longer. I am
currently working on an Android app to control my Karaoke server using XBMC/Kodi as a Media Player and needing
to use a tool similar to XMBC Remote to debug JSON RPC 2.0 protocol. The official remote seems to "crash" a lot
so I decided to spend some time to fix it up. It has no new feature -- It just works the way the it was supposed
to.

This is a fork from the official XBMC Remote v1.09 Project to fix a number of bugs:
  1. Null pointer exception at several places
  2. Fix add/play/remove media items to playlist
  3. For new devices without a permanent menu button, the XBMC icon at the bottom left of the Home screen will
     bring up the setting option menu.
  4. Touching the title bar of the nowplaying, playlist, media browsing list will bring up the option menu for that
     activity/controller

