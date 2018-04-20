# SSDVR
Super Simple DVR Solution

I like to record my favorite shows, and my current DVR software pisses me off because it doesn't get all of them, does not gracefully recover from errors, and tends to screw up around live sports.  
It also seems to be overly complicated.

This solution has a very simple DVR recorder, currently supporting the HD Homerun line of products - specifically the Prime, because that's what I have.
Creates a simple webserver for administration.
Uses MongoDB for data persistence.
Will probably use some sort of TV Metadata services to pull down series information.
Will probably support schedules direct for scheduling information.
Supports recording via manual schedules, guide information, regular expressions, and maybe others (Alexa / Google Home).
Works with Plex to identify previously recorded shows.
Uses Handbrake to transcode.  Does not do live transcoding, but does it after the fact.
Please note this software only records and transcodes, there is no media server or player included.  Download Plex, FFS.  If there is interest, I may write a media server for it.

If people actually use this and express interest, I will see about getting a license for DTCP so that it will work with encrypted channels.  It's not super cheap ($14K/year + certificates), but it would be doable with a reasonable community size.

Written in C# targeting .NET Core, so it theoretically works everywhere.

May contain various not my trademarks, proceed at your own risk.
Not my code is covered by not my license, proceed at your own risk.
