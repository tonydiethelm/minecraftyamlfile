# minecraftyamlfile
This is the yaml file I use to start up minecraft servers with docker-compose


## How this works

I make a directory..... Minecraft.blah
I put this yaml file in there and change what needs changing.
    - image name
    - Port number, remember outside:inside
    - directory name in the volume mounting section to Minecraft.blah

I start it up with `sudo docker-compose up -d`. 

Bingo Bango Bongo. It should start up. 
You'll further need to add folks to the whitelist and OP files. 
And change the MOTD in the server.properties file. 