# Activity_Tracker
Aardwolf MUSHCLIENT plugin to track group activity
Alpha v0.1

acti help
acti report -> report tracked data
acti reset -> reset data
acti remove <member> -> remove member from data, if they have left the group (case sensitive)

Currently tracks:
- Spell casts
- Attacks on targets
- Quaffs
- Quests

Todo:
- Miniwindow display
- Add scroll recite capture
- Filter out damage spells and spellups from spellchant cast data, we want to know healing/dampen/reverse align/etc
- Separate attacks and spells/skills
- Track who is applying debuffs? (poison, disease, hydra, etc)
- Rounds/target metric? 
- Deaths? Timestamp damage taken for death summary reports? Time to return after death?
- Damage tracking, I guess? Low priority
