# csgo-config

#Lauch options:
-console -novid -nojoy -high -processheap -fullscreen -language english -no-browser -nod3d9ex1 +mat_queue_mode 2 +cl_forcepreload 1 -refresh 60 -tickrate 64 -thread 4

clean: 
- path: "C:\Program Files (x86)\Steam\userdata\430607874\730\local\cfg"

#extra:
- path default: "C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg"
- command line in game: exec [file_name]
