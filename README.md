# fixperms
Script to fix permissions of accounts

Written by: Vanessa Vasile 5/13/10<br/>
Written by: laudarch 10/16/22<br/>
http://thecpaneladmin.com<br/>

## Usage:
`./fixperms user1 user2 user3`

 You can also run a server-wide loop like this:

``for i in `ls -A /var/cpanel/users` ; do ./fixperms $i ; done``
