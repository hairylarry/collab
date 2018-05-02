# collab
A Collaborative Writing Game

Collab is a social network implemented entirely with text files. No database. I am running this test version of Collab here.

http://hairylarry.sdf.org/collab

The 2018-04-30 version has create story, continue story, user management, reading lists (follow), TOC, Writers Directory, Collab News,RSS, and Weekly Digest. Notifications are nearly complete. Major features yet to come are cloning a story and ending a story. 

In the directory usernames we need a file username.txt like this.

-----

000001 (user id)

username@example.com (contact email)

1!2@3D4v5% (encrypted password)

username

10000 (notification flags)

-----

In the directory userids we need a file userid.txt (000001.txt) like this

username

then we need to make a directory for that user

mkdir 000001

In that directory we need an empty file called profile.txt.

All this is done automatically through a Create Account page that will have email confirm and encrypt the paswords.

If you want to help test Collab or help in any other way email hairylarry@deltaboogie.com.
