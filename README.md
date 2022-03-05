Node-Red setup
===========

1) stop  node-red  (  node-red-stop  ).
2) in the folder:  usr/lib/node_modules/node-red
replace these files with these from this repo

flows.json

flows_cred.json

package.json


3) unzip node_modules.rar and replace the node_modules dir  (these are the nodes packages).

4) Restart node-red (  node-red-start  ).


Your node red flows workspace is at {yourIP address};1880

Your web dashboard is at {yourIP address};1880/ui

The MQTT nodes need to have the correct config for connect to the Mosquitto broker (IP address, etc)


Only use this settings.js if you need to enable password/project mode etc




