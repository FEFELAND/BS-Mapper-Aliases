Just needed somewhere to place this file. A list that links a TwitchUser to a MapperName.
Mainly just for use with my own beat saber request thingy, but anyone's free to use this list too.
Feel free to open an issue here or message me on discord (@fefeland) if there is anything to update or add.

How I use this list in my bot implementation (trigger configured to within 7 days of a map releasing):
1) I check if twitch username and mapper name already match in any given request. If they do, bump their map to the top of queue.
2) If they don't match, the bot checks this list for aliases. If one is found, then it bumps the map to the top. (list supports multiple names in case of alt accounts per user)
3) If nothing matches, then nothing gets triggered of course and request goes through as normal.
