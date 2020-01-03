# Dungeon-of-spells
Made by GameMaker Studio
In Dungeon of Spells, the player takes the role of two game devs who have become trapped in their own computer. They must fight a virus who has taken the forms of some characters from their games while other characters from finished and unfinished products alike help them. 

The dungeon of the computer takes the form of multiple rooms- combat rooms, healing rooms, and ally rooms.  

The first room will ask you to choose which two dev allies to start with. These dev allies cannot be found anywhere later in the game. At any time, you can hover over an ally to see what spells they can cast.

In a combat room, your two allies in the two leading position slots face off against an enemy. The combat is a is a turn-based system where turn order progresses from the first slot ally, to the enemy, to the second slot ally.

On the player’s turn, they can either cast a spell or switch positions. To attack the enemy, the player must click a spell. When a spell is chosen, they will be prompted to type in a casting word. If they type the word correctly in the specified time, they will deal damage. A spell typed quickly does 1.5x damage, and a spell typed slowly does 0.5x damage. Hover over a spell to see what the spell is and how much base damage it does. If you fail to type the word in the given time, your spell will miss and you will do no damage.

All spells have a type, which are color-coded for convenience. Physical spells use objects or physical attacks to hurt enemies. Elemental spells use the power of the elements to deal damage. Arcane spells encompass all other types of magic. Hover over a spell to see its type, read information about it, its casting time, and casting words, and see how much damage it will do.

Every enemy has a weakness and a resistance to either Arcane, Physical, or Elemental damage. Spells with the type the enemy is weak to will do more damage to them, but spells the enemy is resistant to will do less damage to them. Hover over an enemy to see its current weakness and resistance, as well as how much damage the enemy will do to the players.

There are also Healing spells, which don’t do damage but instead heal the other ally in the leading slot. The Producer also has one Special spell which ignores enemy resistances and weakness.

Some enemies have special behavior- for example, The Dragon will usually attack the player in the first position slot. You can read about each enemy’s special behavior by hovering over them.

If your lead allies get low on HP or don’t have useful spells, you can switch your ally’s position slot with another by clicking the “Switch” button. You can then switch with either ally in your back row, or the other ally in your front row.  Switching slot position will use that ally’s turn! If you try to switch an ally’s slot position with the slot position they’re currently in, they will pass their turn. Switch responsibly- when an ally’s HP reaches zero, they’re gone!

Lastly, the enemy will occasionally perform a Resistance Switch, which changes both its weakness and resistance randomly. Make sure to re-check the enemy description after each Resistance Switch.

Healing Rooms have a table with health potions. Click on the potions to begin a minigame of typing healing-related words. Each word typed will heal all of your allies for 4 HP. Type as many words as you can before time runs out to heal your party as much as possible.

Ally Rooms are similar to the starting room and will prompt you to choose a new ally if you wish. Hover over each potential ally to see what spells they can cast. You may skip picking a new ally, or, if you click on an ally to add to your team, the menu will ask you which ally to replace in your party. New allies will always join with full HP, even if they replace a member with little HP remaining. If you don’t have 4 allies in your party, you can click the “Add” button to simply let the new ally join your team.

Team balance is important- it’s very good to have a party with all 3 types of damaging spells represented.

IMPORTANT! If you are having trouble with the game’s difficulty, you can turn on an experimental Easy Mode by pressing the spacebar at the title screen of the game. If you do, the screen will briefly flash green and a sound effect will play. You may then press enter to continue the game in Easy Mode. Easy Mode adds two and a half seconds to every spell’s casting time, allowing for easier hits.

If you would like to test certain parts of the game, you may press the “end” key on your keyboard to reduce enemy HP to 1. As a testing tool, this feature may cause some bugs, and it would be removed in a final product.

Some things we would implement if we had more time:
Attack animations for every spell, ex. casting a lightning spell would show a lightning bolt on-screen. This would have been given priority for implementation if we had more artists.
More tested and fleshed-out difficulty modes.
More wings, spells, enemies, and allies. There are currently 9 allies (13 if you count the dev allies), 8 enemies, 3 wings, and 26 spells.
Player choice in how they would traverse the dungeon, ex. deciding to go to a healing or ally room first.
A mana system for casting spells that would consume party MP every time a spell is cast.
