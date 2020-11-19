# DND-Initiative-Tracker
This is an app that helps DMs and Players alike track initiative in combat in Dungeons &amp; Dragons!

## Dev Notes

I'm mostly just making this to get into the habit of working on software software dev at least once a day. I need to keep my skills sharp and get back into my career now more than ever, so what better way than by creating a portfolio?

### Main Features
The idea of this application is pretty simple. I aim to allow users:

1. to create entries in a list.
2. to assign "Initiative" values to each entry.
3. to order their initiative list in descending order (i.e. 20, 15, 13, 10, 3, 0, -2)
4. to see what entry is currently active in the initiative order (either using a pointer in the UI or cycling the menu to show the "active" entry at the top)

I would also like to build this with a pretty cohesive GUI that is easily readable, since that's something I've only ever experimented with on occasion. It could be cool to make something that my friends can use!

### Some bonus features I might want to add later on:
- Perhaps a way to track each entry's actions/movement actions/bonus actions/reactions per combat?
- Maybe create a way to save individual entries (i.e. player characters, recurring NPCs, generic monsters, etc.) for later use
  - Might go even further and add a way to save an initiative tracker, so if a game ends mid-combat, everyone can come right back to it
- If I add the entry/order saving options, I would like to look into adding images to each entry as well. Assigning a character with a character portrait would be nice! (Maybe just a little 35x35px square for each entry?)

### Ideas From Friends
- HP tracker
- - Select die/dice to be rolled
- - - Should I add a console that displays what was rolled?
- - Enter custom modifier (default = 0)
- - Click either a "Harm" or "Heal" button
- - Target's HP is modified as a result
- Individual Action Tracking
- - A Fighter's "Attack" action has a number of attacks based on their Fighter level
- - Casting a spell/cantrip takes 1 Action (unless it says otherwise)
