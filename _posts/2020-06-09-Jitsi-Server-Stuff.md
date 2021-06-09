---
layout: post
title: Jitsi Server Stuff
---
## Adding Moderators
```bash
sudo prosodyctl register USERNAME auth.video.redbib
lica.org
```

### how I achieved this
The reason I had to add moderators was because 

Jochen Kirstätter has a simple walk-through here:
https://jochen.kirstaetter.name/authentication-jitsi-meet/

### Troubleshoot
if you get this error:
```bash

**************************
Prosody was unable to find the configuration file.
We looked for: /etc/prosody/prosody.cfg.lua
A sample config file is included in the Prosody download calle
d prosody.cfg.lua.dist
Copy or rename it to prosody.cfg.lua and edit as necessary.
More help on configuring Prosody can be found at https://proso
dy.im/doc/configure
Good luck!
**************************
```
You are probably running into permissions problem.