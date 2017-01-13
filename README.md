# Outlook2016_Database_Rebuild
Force a rebuild of SQLite database used by Outlook 2016 for Mac
Our facility must sometimes 'clean' a system when data that's not supposed to be in the open, ends up in the open and on a system. The usual avenue for this data finding it's way onto a system is email and we must purge the targeted email in conducting the 'cleaning' of the system. This also means rebuilding the email database to ensure the deleted emails CAN'T be recovered.

Under Outlook 2011 Mac, this was performed simply by holding the option key during launch and rebuilding the mail database. Outlook 2016 has removed this feature and the official support from Microsoft is that Outlook will determine when a database needs rebuilt and users shouldn't do this anyway. Well, we still need to do this when cleaning a system.

Luckily someone made a post on how to do this on a SQLite database which Outlook 2016 uses. Post Here: http://www.cortig.net/wordpress/2016/04/25/outlook-2016-sqlite-database-commands/ I tried making this a little easier for our field technicians and wrapped it into an AppleScript App. Feel free to use, it seems to be working for us. 
