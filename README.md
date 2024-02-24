Drag and drop the resource into your fivem "resources" folder

Ensure the resource by opening your server.cfg then go to the line that should look like this:

# These resources will start by default.
ensure mapmanager
ensure chat
ensure spawnmanager
ensure sessionmanager
ensure basic-gamemode
ensure hardcap
ensure baseevents
ensure             <-- Add the resource name here

should look like this:

# These resources will start by default.
ensure mapmanager
ensure chat
ensure spawnmanager
ensure sessionmanager
ensure basic-gamemode
ensure hardcap
ensure baseevents
ensure disableproploss
