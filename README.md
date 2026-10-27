# Firebot Setups
Here's some of my Firebot setups I don't mind people using. All will be improved as time goes on of course

## FUNtoon Bot Guessing
Set of events that react to FUNtoon only
### Ceres Guessing
Will save previous best Ceres time and guess based on the last Ceres time. Maybe will do something with PB at some point
### Phantoon guessing
Will just guess slow mid fast assuming a 3 or 4 round Phantoon. Later on I'll let it store out what your usual phantoon 
rounds are
### Ridley Guessing
Similar to Ceres Guessing but with Ridley Room time instead

## Stream Notes
Simple set of commands to track notes between streams in bot. By default all are restrictd to stereamer and mods

### !addnote notetext
Adds a note
### !clearnote index
Removes a note, requires a 0-based index as parameter
Why 0 based? Because I like 0 based. I'll add an option for 1 based later
### !shownote index
Shows the specified note. Remember, 0 based index
### !shownotes
Shows all the notes. Due to Twitch Chat API limitations notes are displayed as separate chat messages

## Stream Shoutout Queue
Simply allows you to show your firebot shoutout widget while queuing up the official twitch /shoutout commands as twitch
limits usage to once every 2 minutes. There's a bit of an extra buffer as twitch's timing doesn't always line up 
as expected. Edit the firebot shoutout widget as you'd normally do