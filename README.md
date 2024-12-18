# Pato-Netlists
WORK IN PROGRESS
To do:
- remove domains that are no longer needed
- Polishing.
- reformat for easy install. Only comments break it at the moment
- add hyperlinks to raw to the below
- Find an easy copy and paste way to update this.

personal privacy blocklists and whitelists, hopefully you'll find it useful. Made for Pi-Hole

The main lists will have all my settings, which you may not like. I created different lists for specific purposes that should make it easier to incorporate to a larger audience

Some of my whitelists are made assuming a strict network policy (so, .* regex blacklist). I personally never do this for every device, and never on a browser. I only encourage this on specific applications or devices such as WLED, OpenWRT, TVs, and consoles, while always excluding devices that need web browsing such as computers and cellphones.

You are encouraged to fork and make your own repo, since this is mainly a personal lists, so some issue reports could be disregarded.

# Whitelists.
Installation: Copy the domains from the text file, and add them to your domains tab. There is no way to enable auto updates.

Patopass: Meant for use on every device without a strict network policy. Helpful if you have a lot of blocklists, I whitelist false positives that break functionality on websites I use.

Firesticknicey: Allows only apps I like (SmartTube). Note: Main menu will be inaccessible, use app settings to open apps.

PS5Strict: Allows only what I need from PS5. FYI, I mostly play games offline. You are also able to stream on YT (only YT).

Facebook Casualties: Domains wrongfully removed by my AntiFacebook blocklist.

# Blocklists.
Installation: Just like any adlist, get the raw link and paste then

HateFacebook: Blocks any domain that could in any way be related to Facebook or Meta. I believe Facebook is the biggest crime when it comes to privacy infringement, so I never touch it. This will have many false positives, since any websites that has any word or acronym related to facebook will also be blocked. Should be used alongside my facebook casualties whitelist. This list is done thanks to looking at other blocklists that block facebook, among some speculative and not backed up assumptions I make. This is the strictest anti-facebook blocklist you will ever find.

NoPan: Domains not blocked by blocklists I use that I want to block. It's very small currently.
