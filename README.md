##### To Run Locally

Launch multiplayer server by running this command in your terminal:
```
java -Xms3036M -Xmx3036M -jar CanaryMod-1.2.0.jar
```

Note: If this is the first time you're running the server, it will quit and leave a file called eula.txt in that directory. You need to edit this and change the last line to be:
```
eula=true
```
Then the server will start successfully.

Now when you can connect to this server using Multiplayer -> Direct Connect -> 127.0.0.1

##### To Run Online

- Upload these files to your minecraft hosting provider.
- Somewhere your host will have a spot that specifies what .jar file is the server executable. Update that to the CanaryMod-1.2.0.jar
- If your provider has given you a specific port to host your server on (common for shared providers), you need to update that in this (config file)[https://github.com/teachthenet/TeachCraft-Server/blob/master/config/server.cfg#L77] (and uncomment the line).
- Restart your server 

##### This Server Setup
http://www.stuffaboutcode.com/2014/10/minecraft-raspberryjuice-and-canarymod.html
