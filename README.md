sublime url protocol for mac os x
========================

## Installation

- Download the [latest release](https://github.com/saetia/sublime-url-protocol-mac/archive/master.zip) and unzip
- Drag "Sublime Protocol.app" to your /Applications directory
- Double-click the app once to register it as the protocol handler

Note: It will close instantly; this is the expected behaviour.


Supports opening subl:// urls from "better errors" on rails and "whoops!" on php

![http://i.imgur.com/vtzf2FZ.png](http://i.imgur.com/vtzf2FZ.png)
subl://open?url=file:///Users/Joel/.rvm/gems/ruby-2.0.0-p247/gems/actionpack-4.0.0/lib/action_dispatch/routing/route_set.rb&line=69

![http://i.imgur.com/C8QKIOo.png](http://i.imgur.com/C8QKIOo.png)
subl://open?url=file:///Users/Joel/Sites/skeleton/httpdocs/doc/index.php&line=41

---

This only works for Sublime Text 3, to make this work with Sublime Text 2 - alter the */Sublime\ Protocol.app/Contents/Resources/Scripts/main.scpt* file
