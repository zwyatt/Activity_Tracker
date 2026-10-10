# Activity_Tracker 0.1
Aardwolf MUSHCLIENT plugin to track group activity
```
acti help
acti report -> report tracked data
acti reset -> reset data
acti remove <member> -> remove member from data, if they have left the group (case sensitive)
acti next/prev -> scroll through window data options (or use right-click menu)

acti loop new -> begin recording a new loop, ends and saves one if in progress
acti loop end -> ends recording and saves the current loop without starting a new one
acti loop discard -> ends recording and discards the current loop
acti loop reset -> ends recording and deletes all loop data
acti loop report -> reports total saved loop performance to this point

acti test <on/off> -> toggle displaying test messages (very spammy)
```
### Currently tracks:
- Attacks
- Casts
- Rescues
- Quaffs
- Deaths
- Quests
- Genie loop activity, attacks on sand (Satk)

### Todo:
- TESTING!
- Formatting, report, display cleanup
- Player details
- Reciting capture
- Healing capture (as much as can be, anyway)
- Damage taken capture
- Filter out damage spells and spellups from spellchant cast data, we want to know healing/dampen/reverse align/etc
- Separate attacks and spells/skills
- Track who is applying debuffs? (poison, disease, hydra, etc)
- Rounds/target metric?
- Timestamp damage taken for death summary reports? Time to return after death?
- Damage tracking, I guess? Low priority
