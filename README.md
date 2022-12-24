# Node-red-inputs-emulators
DHT sensor and button emulators for Node-red

1) In a Linux environment, unzip button-emu.zip and dht-emu.zip onto your Desktop. 
2) Now, you should have the folders “button-emu” and “dht-emu” on your Desktop. Make sure node-red is not running at the back.
  a. Open a Terminal, type 
  
    i.) ```cd .node-red/```
  
    ii.) ```npm install ~/Desktop/dht-emu```
    
    iii.) ```npm install ~/Desktop/button-emu```
    
  b. Type `node-red`, now you should see the emulators.

The DHT sensor emulator is modified from http://www.airspayce.com/mikem/bcm2835/bcm2835-1.60.tar.gz by replacing the data sampling loop with random numbers. For more details, please refer to http://www.airspayce.com/mikem/bcm2835/index.html.
