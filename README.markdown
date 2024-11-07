# About

Tekkub Stoutwrithe's World of Warcraft AddOn "Buffet".  It is a simple water/food managing addon inspired by:

- [BaudConsumables](http://wow.curse.com/downloads/details/5827/) and
- [Munchies](http://www.wowinterface.com/downloads/info8174-Munchies.html).

Unlike them, Buffet does not swap items on the action bar (the noise is bothersome).  Instead it edits macros on the fly (out of combat) to provide you with the best food, water, potions, stones, and bandages.

This is spiralofhope's fork from tekkub's repository from `1a96512f4b2e58aed7eaf1e0c04e17dedd194dbc`.

While it worked as-is, changes were made for Project Ascension.



# Usage

To make Buffet work, you must provide two macros, "AutoHP" and "AutoMP".  Drop these on your action bar like any other macro, Buffet will change the macros as needed to provide you with food and drink out of combat, potions and stones in combat, and bandages on shift (HP macro only, of course).  Buffet will always pick the smaller stack if equal-strength items are found.  Conjured items will always be preferred over permanent ones.
