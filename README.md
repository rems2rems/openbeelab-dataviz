# openbeelab-dataviz

## TODO : a public webapp for everyone to see a beehouse weight in real-time

for a specific beehouse, the (remote) weight measures JSON objects can be retrieved with view :

http://dev.openbeelab.org:5984/la_mine/_design/ + beehouse_name + /_view/weight_by_week

example:
http://dev.openbeelab.org:5984/la_mine/_design/ruche_01/_view/weight_by_week?group=true&limit=50";//&endkey=\"2014W20\"&startkey=\"2014W30\"";