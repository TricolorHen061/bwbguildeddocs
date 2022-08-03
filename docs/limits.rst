######
Limits
######
In the last section, strikes were introduced. Just keeping track of strikes isn't very useful. Strikes were created for use with "limits".

Limits are a way to put a "cap" on the amount of times a person can say a blacklisted item. For exmaple, you could create a limit: If a member reaches 5 strikes, they get banned.

==============
Command Syntax
==============
``b-limits (add|remove|view) (amount goes here) (kick|ban)``

==============
Viewing Limits
==============
To view existing limits, run ``b-limits view``.

======================
Adding/removing limits
======================
To add a limit, use the ``add`` option, followed by the amount and action.

**Adding a limit of a kick upon receiving 2 strikes:** ``b-limits add 2 kick``

**Adding a limit of a ban upon receiving 4 strikes:** ``b-limits add 4 ban``

To remove a limit, use the ``remove`` option, followed by the amount.

**Removing an existing limit of kick on 2 strikes:** ``b-limits remove 2``

**Removing an existing limit of ban on 4 strikes:** ``b-limits remove 4``
