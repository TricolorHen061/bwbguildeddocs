############
Blacklisting
############

Obviously, the bot is made for censoring messages containing bad words. phrases, and links. The blacklist allows you to acheive this.

==============
Command Syntax
==============
``b-blacklist (add|remove|view) (words|phrases|links) <items seperated by commas>``

Everything the bot blocks is organized into a "blacklist". You can access this blacklist using the ``blacklist`` command.

=====================
Viewing The Blacklist
=====================
To view the blacklist for your server, type ``b-blacklist view`` and send it in any channel. The bot will respond with a hidden message containing the blacklist.

=====================
Editing The Blacklist
=====================
The bot can block three types of items: words, phrases, and links. Use the ``add`` or ``remove`` options to add/remove items. Exmaples:

**Adding words example:** ``b-blacklist add words word1, word2, word3``

**Adding phrases example:** ``b-blacklist add phrases some phrase 1, some phrase 2, another phrase``

**Adding links example:** ``b-blacklist add links https://link1.com, https://link2.com, https://anotherlink.com``

**Removing words example:** ``b-blacklist remove words word1, word2, word3``

**Removing phrases example:** ``b-blacklist remove phrases some phrase 1, some phrase 2, another phrase``

**Removing links example:** ``b-blacklist remove links https://link1.com, https://link2.com, https://anotherlink.com``
