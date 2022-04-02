# MC Server Installer Script

## How do it:
Run This Script:
```bash
bash <(curl -s https://imaged.ml/mcinstallweb.sh)
```
## After you have run the script follow this steps:
Change The Folder:
```run9
$ cd minecraft
```


Make Access to the file:
```run9
$ chmod +x start.sh
```


Run The Server:
```run1
$ java -Xmx1024M -Xms1024M -jar server.jar nogui
```

Change The Eula:
```run2
$ sudo nano eula.txt
```

Change eula=false to eula=true :
```run3
#By changing the setting below to TRUE you are indicating your agreement to our EULA (https://account.mojang.com/documents/minecraft_eula).
"eula=false" To "eula=true"
```

Create a screen instance for the server:
```run4
$ sudo screen -S "Minecraft Server"
```

Start your server script:
```run5
$ ./start.sh
```

To exit the screen session, press CTRL + A then D. To resume the screen session, run:
```run6
$ sudo screen -R
```


## Help and support

For help and support you can join the [Discord Server](https://BigheartedGiantNumericalanalysis.adrianleanderle.repl.co/discord).

