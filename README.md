# Fork Info
This is a fork of ShaguScore that uses Pepopo's version of nampower at https://github.com/pepopo978/nampower
This allows ShaguScore to get the item levels of items that are not in the database

I also set this addon up so it can also collect itemlevel data that can eventually be added back to the main addon's database.

# How to help
- Play Turtle WoW
- add items you don't think should have a score to the blacklist with '/ssb itemlink' WHERE itemlink is the actual shift click link of the item.
    - Use the command again to remove item from blacklist
- After you've collected a few weeks of data share your 'WTF\Account\ 'YOURACCOUNT' \SavedVariables\ShaguScore.lua' in an issues post

# ShaguScore
This AddOn is a GearScore alike item rating. It includes a small database of the itemLevels of all items available in classic up to Naxxramas. Those values are are printed as score, similar to GearScore. Please don't take those values to serious, in vanilla the itemLevel is worth nothing.

![character](https://raw.githubusercontent.com/shagu/ShaguAddons/master/_img/ShaguScore/character.jpg)

## Installation
This fork requires Pepopo's version of nampower at https://github.com/pepopo978/nampower
1. Download 
2. Unpack the Zip file
3. Rename the folder "ShaguScore-master" to "ShaguScore"
4. Copy "ShaguScore" into Wow-Directory\Interface\AddOns
5. Restart Wow

## Older Versions

In older versions this addon did two things, it calculated the average color (rarity) of the player's equip and it aggregated a score of the overall equip.

The score value has been calculated as followed:

    Score = Rarity * ItemLevel * Bonus

**Rarity:**
<span style="color: #9d9d9d">Poor (0)</span>,
<span style="color: #000000">Common (1)</span>,
<span style="color: #1eff00">Uncommon (2)</span>,
<span style="color: #0080ff">Rare (3)</span>,
<span style="color: #b048f8">Epic (4)</span>,
<span style="color: #ff8000">Legendary (5)</span>,
<span style="color: #e6cc80">Artifact (6)</span>

**Bonus:** 
The Bonus is 2 when a TwoHand weapon is used, otherwise it will be 1