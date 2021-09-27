--How to make a server on your PC:--
Click the forge-1.16.5-36.2.4-installer and install server into a new folder 
> Drag Mods Folder, Configs Folder, run.bat, scripts, server-icon and server.properties into the new folder you made 
> run the forge-1.16.5-36.2.4
> accept EULA agreement 
> launch the run.bat file

-> ATTENTION <-
Video to help you set it up: https://www.youtube.com/watch?v=YQQJgLmQ8d8

Extra:
Q: I'm trying to run a server but it's not working, how do I fix this?
A: You need to use Java 8, 64-bit to run a modded Minecraft server. You can download it from here: https://adoptopenjdk.net/ - select OpenJDK 8, Hotspot.
Uninsntall Java 16 if still persists

Q: Are there any JVM parameters that can help pack performance?
A: These parameters improve the way Java handles memory and are selected with Minecraft specifically in mind. Please note that these are intended for use with Forge modpacks using Java 8. 
These will likely not work as well for Minecraft 1.17 which uses Java 16.

-XX:+UseG1GC -Dsun.rmi.dgc.server.gcInterval=2147483646 -XX:+UnlockExperimentalVMOptions -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M

From Reddit Post: https://www.reddit.com/r/feedthebeast/comments/5jhuk9/modded_mc_and_memory_usage_a_history_with_a/

