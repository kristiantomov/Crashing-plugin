Crashing-plugin
===============
[12:59:54] [Server thread/INFO]: Starting minecraft server version 1.7.2
[12:59:54] [Server thread/INFO]: Loading properties
[12:59:54] [Server thread/INFO]: Default game type: SURVIVAL
[12:59:54] [Server thread/INFO]: Generating keypair
[12:59:54] [Server thread/INFO]: Starting Minecraft server on *:25565
[12:59:55] [Server thread/INFO]: This server is running CraftBukkit version git-Bukkit-1.7.2-R0.2-b2974jnks (MC: 1.7.2) (Implementing API version 1.7.2-R0.2)
[12:59:55] [Server thread/INFO]: [CalebCurrency] Loading CalebCurrency v1.0.0
[12:59:55] [Server thread/INFO]: [Essentials] Loading Essentials v2.12.2
[12:59:55] [Server thread/INFO]: [EssentialsChat] Loading EssentialsChat v2.12.2
[12:59:55] [Server thread/INFO]: [EssentialsProtect] Loading EssentialsProtect v2.12.2
[12:59:55] [Server thread/INFO]: [EssentialsSpawn] Loading EssentialsSpawn v2.12.2
[12:59:55] [Server thread/INFO]: [EssentialsAntiBuild] Loading EssentialsAntiBuild v2.12.2
[12:59:55] [Server thread/WARN]: **** SERVER IS RUNNING IN OFFLINE/INSECURE MODE!
[12:59:55] [Server thread/WARN]: The server will make no attempt to authenticate usernames. Beware.
[12:59:55] [Server thread/WARN]: While this makes the game possible to play without internet access, it also opens up the ability for hackers to connect with any username they choose.
[12:59:55] [Server thread/WARN]: To change this, set "online-mode" to "true" in the server.properties file.
[12:59:55] [Server thread/INFO]: Preparing level "world"
[12:59:55] [Thread-7/INFO]: ----- Bukkit Auto Updater -----
[12:59:55] [Thread-7/INFO]: It appears that you're running a Beta Build, when you've specified in bukkit.yml that you prefer to run Recommended Builds.
[12:59:55] [Thread-7/INFO]: If you would like to be kept informed about new Beta Build releases, it is recommended that you change 'preferred-channel' in your bukkit.yml to 'beta'.
[12:59:55] [Thread-7/INFO]: With that set, you will be told whenever a new version is available for download, so that you can always keep up to date and secure with the latest fixes.
[12:59:55] [Thread-7/INFO]: If you would like to disable this warning, simply set 'suggest-channels' to false in bukkit.yml.
[12:59:55] [Thread-7/INFO]: ----- ------------------- -----
[12:59:55] [Server thread/INFO]: Preparing start region for level 0 (Seed: -4308037404518459691)
[12:59:56] [Server thread/INFO]: Preparing spawn area: 39%
[12:59:57] [Server thread/INFO]: Preparing spawn area: 89%
[12:59:57] [Server thread/INFO]: Preparing start region for level 1 (Seed: -4308037404518459691)
[12:59:58] [Server thread/INFO]: Preparing spawn area: 41%
[12:59:59] [Server thread/INFO]: Preparing start region for level 2 (Seed: -4308037404518459691)
[13:00:00] [Server thread/INFO]: [CalebCurrency] Enabling CalebCurrency v1.0.0
[13:00:00] [Server thread/INFO]: [CalebCurrency] is now enabled
[13:00:00] [Server thread/INFO]: [Essentials] Enabling Essentials v2.12.2
[13:00:00] [Server thread/INFO]: Essentials: Using config file enhanced permissions.
[13:00:00] [Server thread/INFO]: Permissions listed in as player-commands will be given to all users.
[13:00:00] [Server thread/INFO]: [EssentialsChat] Enabling EssentialsChat v2.12.2
[13:00:00] [Server thread/INFO]: [EssentialsProtect] Enabling EssentialsProtect v2.12.2
[13:00:00] [Server thread/INFO]: [EssentialsSpawn] Enabling EssentialsSpawn v2.12.2
[13:00:00] [Server thread/INFO]: [EssentialsAntiBuild] Enabling EssentialsAntiBuild v2.12.2
[13:00:00] [Server thread/INFO]: Server permissions file permissions.yml is empty, ignoring it
[13:00:01] [Server thread/INFO]: Done (5,598s)! For help, type "help" or "?"
[13:00:48] [Server thread/INFO]: Tomoff1[/127.0.0.1:1272] logged in with entity id 155 at ([world] -267.70608624774906, 64.0, -22.01366479601962)
[13:00:53] [Server thread/INFO]: kristiantomov[/127.0.0.1:1300] logged in with entity id 278 at ([world] -267.5, 64.0, -21.5)
[13:00:53] [pool-4-thread-1/INFO]: Creating empty config: C:\Documents and Settings\KRISTIAN\Desktop\Testing\plugins\Essentials\userdata\kristiantomov.yml
[13:01:02] [Server thread/ERROR]: Could not pass event PlayerDeathEvent to CalebCurrency v1.0.0
org.bukkit.event.EventException
	at org.bukkit.plugin.java.JavaPluginLoader$1.execute(JavaPluginLoader.java:427) ~[craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at org.bukkit.plugin.RegisteredListener.callEvent(RegisteredListener.java:62) ~[craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at org.bukkit.plugin.SimplePluginManager.fireEvent(SimplePluginManager.java:481) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at org.bukkit.plugin.SimplePluginManager.callEvent(SimplePluginManager.java:466) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at org.bukkit.craftbukkit.v1_7_R1.event.CraftEventFactory.callPlayerDeathEvent(CraftEventFactory.java:345) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.EntityPlayer.die(EntityPlayer.java:368) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.EntityLiving.damageEntity(EntityLiving.java:732) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.EntityHuman.damageEntity(EntityHuman.java:746) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.EntityPlayer.damageEntity(EntityPlayer.java:446) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.EntityHuman.attack(EntityHuman.java:918) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.PlayerConnection.a(PlayerConnection.java:1092) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.PacketPlayInUseEntity.a(SourceFile:55) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.PacketPlayInUseEntity.handle(SourceFile:10) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.NetworkManager.a(NetworkManager.java:146) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.ServerConnection.c(SourceFile:134) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.MinecraftServer.u(MinecraftServer.java:655) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.DedicatedServer.u(DedicatedServer.java:250) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.MinecraftServer.t(MinecraftServer.java:545) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.MinecraftServer.run(MinecraftServer.java:457) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.ThreadServerApplication.run(SourceFile:617) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
Caused by: java.lang.NoClassDefFoundError: net/milkbowl/vault/economy/Economy
	at me.calebbfmv.PVPC.onDeath(PVPC.java:48) ~[?:?]
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:1.7.0_25]
	at sun.reflect.NativeMethodAccessorImpl.invoke(Unknown Source) ~[?:1.7.0_25]
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(Unknown Source) ~[?:1.7.0_25]
	at java.lang.reflect.Method.invoke(Unknown Source) ~[?:1.7.0_25]
	at org.bukkit.plugin.java.JavaPluginLoader$1.execute(JavaPluginLoader.java:425) ~[craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	... 19 more
Caused by: java.lang.ClassNotFoundException: net.milkbowl.vault.economy.Economy
	at java.net.URLClassLoader$1.run(Unknown Source) ~[?:1.7.0_25]
	at java.net.URLClassLoader$1.run(Unknown Source) ~[?:1.7.0_25]
	at java.security.AccessController.doPrivileged(Native Method) ~[?:1.7.0_25]
	at java.net.URLClassLoader.findClass(Unknown Source) ~[?:1.7.0_25]
	at org.bukkit.plugin.java.PluginClassLoader.findClass0(PluginClassLoader.java:80) ~[craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at org.bukkit.plugin.java.PluginClassLoader.findClass(PluginClassLoader.java:53) ~[craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at java.lang.ClassLoader.loadClass(Unknown Source) ~[?:1.7.0_25]
	at java.lang.ClassLoader.loadClass(Unknown Source) ~[?:1.7.0_25]
	at me.calebbfmv.PVPC.onDeath(PVPC.java:48) ~[?:?]
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:1.7.0_25]
	at sun.reflect.NativeMethodAccessorImpl.invoke(Unknown Source) ~[?:1.7.0_25]
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(Unknown Source) ~[?:1.7.0_25]
	at java.lang.reflect.Method.invoke(Unknown Source) ~[?:1.7.0_25]
	at org.bukkit.plugin.java.JavaPluginLoader$1.execute(JavaPluginLoader.java:425) ~[craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	... 19 more
[13:01:03] [Server thread/INFO]: Tomoff1 was slain by kristiantomov
[13:01:09] [Server thread/INFO]: kristiantomov issued server command: /bal
[13:01:26] [Server thread/ERROR]: Could not pass event PlayerDeathEvent to CalebCurrency v1.0.0
org.bukkit.event.EventException
	at org.bukkit.plugin.java.JavaPluginLoader$1.execute(JavaPluginLoader.java:427) ~[craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at org.bukkit.plugin.RegisteredListener.callEvent(RegisteredListener.java:62) ~[craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at org.bukkit.plugin.SimplePluginManager.fireEvent(SimplePluginManager.java:481) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at org.bukkit.plugin.SimplePluginManager.callEvent(SimplePluginManager.java:466) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at org.bukkit.craftbukkit.v1_7_R1.event.CraftEventFactory.callPlayerDeathEvent(CraftEventFactory.java:345) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.EntityPlayer.die(EntityPlayer.java:368) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.EntityLiving.damageEntity(EntityLiving.java:732) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.EntityHuman.damageEntity(EntityHuman.java:746) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.EntityPlayer.damageEntity(EntityPlayer.java:446) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.EntityHuman.attack(EntityHuman.java:918) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.PlayerConnection.a(PlayerConnection.java:1092) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.PacketPlayInUseEntity.a(SourceFile:55) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.PacketPlayInUseEntity.handle(SourceFile:10) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.NetworkManager.a(NetworkManager.java:146) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.ServerConnection.c(SourceFile:134) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.MinecraftServer.u(MinecraftServer.java:655) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.DedicatedServer.u(DedicatedServer.java:250) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.MinecraftServer.t(MinecraftServer.java:545) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.MinecraftServer.run(MinecraftServer.java:457) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.ThreadServerApplication.run(SourceFile:617) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
Caused by: java.lang.NoClassDefFoundError: net/milkbowl/vault/economy/Economy
	at me.calebbfmv.PVPC.onDeath(PVPC.java:48) ~[?:?]
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:1.7.0_25]
	at sun.reflect.NativeMethodAccessorImpl.invoke(Unknown Source) ~[?:1.7.0_25]
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(Unknown Source) ~[?:1.7.0_25]
	at java.lang.reflect.Method.invoke(Unknown Source) ~[?:1.7.0_25]
	at org.bukkit.plugin.java.JavaPluginLoader$1.execute(JavaPluginLoader.java:425) ~[craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	... 19 more
[13:01:26] [Server thread/INFO]: kristiantomov was slain by Tomoff1
[13:01:30] [Server thread/INFO]: Tomoff1 issued server command: /bal
[13:01:40] [Server thread/INFO]: kristiantomov issued server command: /bal
[13:01:50] [Server thread/ERROR]: Could not pass event PlayerDeathEvent to CalebCurrency v1.0.0
org.bukkit.event.EventException
	at org.bukkit.plugin.java.JavaPluginLoader$1.execute(JavaPluginLoader.java:427) ~[craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at org.bukkit.plugin.RegisteredListener.callEvent(RegisteredListener.java:62) ~[craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at org.bukkit.plugin.SimplePluginManager.fireEvent(SimplePluginManager.java:481) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at org.bukkit.plugin.SimplePluginManager.callEvent(SimplePluginManager.java:466) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at org.bukkit.craftbukkit.v1_7_R1.event.CraftEventFactory.callPlayerDeathEvent(CraftEventFactory.java:345) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.EntityPlayer.die(EntityPlayer.java:368) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.EntityLiving.damageEntity(EntityLiving.java:732) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.EntityHuman.damageEntity(EntityHuman.java:746) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.EntityPlayer.damageEntity(EntityPlayer.java:446) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.EntityHuman.attack(EntityHuman.java:918) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.PlayerConnection.a(PlayerConnection.java:1092) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.PacketPlayInUseEntity.a(SourceFile:55) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.PacketPlayInUseEntity.handle(SourceFile:10) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.NetworkManager.a(NetworkManager.java:146) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.ServerConnection.c(SourceFile:134) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.MinecraftServer.u(MinecraftServer.java:655) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.DedicatedServer.u(DedicatedServer.java:250) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.MinecraftServer.t(MinecraftServer.java:545) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.MinecraftServer.run(MinecraftServer.java:457) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	at net.minecraft.server.v1_7_R1.ThreadServerApplication.run(SourceFile:617) [craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
Caused by: java.lang.NoClassDefFoundError: net/milkbowl/vault/economy/Economy
	at me.calebbfmv.PVPC.onDeath(PVPC.java:48) ~[?:?]
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:1.7.0_25]
	at sun.reflect.NativeMethodAccessorImpl.invoke(Unknown Source) ~[?:1.7.0_25]
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(Unknown Source) ~[?:1.7.0_25]
	at java.lang.reflect.Method.invoke(Unknown Source) ~[?:1.7.0_25]
	at org.bukkit.plugin.java.JavaPluginLoader$1.execute(JavaPluginLoader.java:425) ~[craftbukkit-1.7.2-R0.2.jar:git-Bukkit-1.7.2-R0.2-b2974jnks]
	... 19 more
[13:01:50] [Server thread/INFO]: Tomoff1 was slain by kristiantomov
[13:01:56] [Server thread/INFO]: kristiantomov issued server command: /bak
[13:01:58] [Server thread/INFO]: kristiantomov issued server command: /bal
[13:02:06] [Server thread/INFO]: Tomoff1 issued server command: /bak
[13:02:06] [Server thread/INFO]: Tomoff1 issued server command: /bal
[13:02:21] [Server thread/INFO]: kristiantomov lost connection: Disconnected
[13:02:21] [Server thread/INFO]: kristiantomov left the game.
[13:02:25] [Server thread/INFO]: Tomoff1 lost connection: Disconnected
[13:02:25] [Server thread/INFO]: Tomoff1 left the game.
[13:02:36] [Server thread/INFO]: CONSOLE: Forcing save..[m
[13:02:36] [Server thread/INFO]: CONSOLE: Save complete.[m
[13:02:36] [Server thread/INFO]: CONSOLE: Stopping the server..[m
[13:02:36] [Server thread/INFO]: Stopping server
[13:02:36] [Server thread/INFO]: [EssentialsAntiBuild] Disabling EssentialsAntiBuild v2.12.2
[13:02:36] [Server thread/INFO]: [EssentialsSpawn] Disabling EssentialsSpawn v2.12.2
[13:02:36] [Server thread/INFO]: [EssentialsProtect] Disabling EssentialsProtect v2.12.2
[13:02:36] [Server thread/INFO]: [EssentialsChat] Disabling EssentialsChat v2.12.2
[13:02:36] [Server thread/INFO]: [Essentials] Disabling Essentials v2.12.2
[13:02:36] [Server thread/INFO]: [CalebCurrency] Disabling CalebCurrency v1.0.0
[13:02:36] [Server thread/INFO]: [CalebCurrency] is now disabled
[13:02:36] [Server thread/INFO]: Saving players
[13:02:36] [Server thread/INFO]: Saving worlds
[13:02:36] [Server thread/INFO]: Saving chunks for level 'world'/Overworld
[13:02:37] [Server thread/INFO]: Saving chunks for level 'world_nether'/Nether
[13:02:37] [Server thread/INFO]: Saving chunks for level 'world_the_end'/The End
[13:02:37] [Thread-4/INFO]: Stopping server
[13:02:37] [Thread-4/INFO]: Saving players
[13:02:37] [Thread-4/INFO]: Saving worlds
[13:02:37] [Thread-4/INFO]: Saving chunks for level 'world'/Overworld
