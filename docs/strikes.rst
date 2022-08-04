#######
Strikes
#######
Every time a person gets their message deleted, they will receive a "strike". A strike is a way to keep track of how many times a person said a blacklisted item.

==============
Command syntax
==============

``b-str (set|view) (role mention here)``

===============
Viewing Strikes
===============
Use the ``view`` option to view your or someone else's strikes. 

View your own strikes (mod role not needed): ``b-str view @YourMentionHere``

View someone else's strikes: ``b-str view @MemberMention``

===============
Setting Strikes
===============
You can set the strikes of someone else, or yours, with ``b-str set``. Example:

**Setting 5 strikes on a member:** ``b-str set 1 @MemberMention``