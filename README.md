# Activity_Tracker 0.15h
Aardwolf MUSHCLIENT plugin to track group activity
```
acti help
acti report -> report tracked data
acti reset -> reset data (not loop data)
acti remove <member> -> remove member from data, if they have left the group (case sensitive)
acti next/prev -> scroll through window data options (or use right-click menu)
acti <spellchants/groupcombat> -> toggle gagging spellchants/groupcombat

acti loop new -> begin recording a new loop, ends and saves one if in progress
acti loop end -> ends recording and saves the current loop without starting a new one
acti loop discard -> ends recording and discards the current loop
acti loop reset -> ends recording and deletes all loop data
acti loop report -> reports total saved loop performance to this point

acti test -> toggle displaying test messages (very spammy)
```
### Miniwindow usage:
- Left-click top bar (<-Attacks->, <-Casts->, etc.) to drag window, right-click top bar for menu
- Click on a player's name to show details, click again to go back to the player list

### Currently tracks:
- Attacks
- Casts
- Rescues
- Quaffs
- Deaths (timestamp, killer)
- Quests (timestamp, elapsed time)
- Genie loops

### Known issues:
- Silent rooms
- Self casting does not spellchant
- Group members appearing in loop data after loops are done
- Report columns are misaligned
- Pills not tracked

### Todo:
- Report and miniwindow formatting
- Party heal and dampen+dispel columns
- Filter out damage spells and spellups from spellchant cast data
- Separate attacks and spells/skills
- Player details
- Reciting capture
- Healing capture
- Damage taken capture
- Track who is applying debuffs? (poison, disease, hydra, etc)
- Rounds/target metric?
- Timestamp damage taken for death summary reports? Time to return after death?
- Vorpal/death blow tracking
- Damage tracking

### Updates:
0.15h - Quest timer hotfix for table creation while player is already on quest\
0.15 - Miniwindow update - click player for details, quest timer, death timestamps\
0.14 - Group misses/immune gagged, spellchant blank lines gagged\
0.13 - Report loop number(s), spellchant and group combat gag options, acti next/prev now scrolls through all data options, window and other variables saved, death capture\
0.12 - Quest now also reports to mud output\
0.11 - Fixed spellchant pretitle capture and Genie 'blizzard of sand' attack capture
