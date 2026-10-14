# Activity_Tracker 0.14
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
### Currently tracks:
- Attacks
- Casts
- Rescues
- Quaffs
- Deaths
- Quests
- Genie loops

### Known issues:
- Silent rooms
- Self casting does not spellchant
- Group members appearing in loop data after loops are done
- Sand attacks not tracking/outputting properly in loop data
- Report columns are misaligned
- 12h time but formatted like 24h
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
0.14 - Group misses/immune gagged, spellchant blank lines gagged
0.13 - Report loop number(s), spellchant and group combat gag options, acti next/prev now scrolls through all data options, window and other variables saved, death capture\
0.12 - Quest now also reports to mud output\
0.11 - Fixed spellchant pretitle capture and Genie 'blizzard of sand' attack capture
