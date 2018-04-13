# collab
A Collaborative Writing Game

Collab is a social network implemented entirely with text files. No database. I am running this test version of Collab here.

http://hairylarry.sdf.org/collab

This version has no user management like create account, change password, etc. so users have to be created manually. 

In the directory usernames we need a file username.txt like this.

000001
username@example.com
12345
username

In the directory userids we need a file userid.txt (000001.txt) like this

username

then we need to make a directory for that user

mkdir 000001

In that directory we need an empty file called profile.txt.

All this will be done automatically through a Create Account page that will have email confirm and encrypt the paswords. I have a few more things to do to this test version while it is being tested before I concentrate on the user account module.

If you want to help test Collab or help in any other way email hairylarry@deltaboogie.com.
