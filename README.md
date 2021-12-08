# Plugins Permissions
## Collecting different plugins permissions in an easy cut-and-paste list per plugin.

Using a lot of plugins means adding a lot of permissions. This would be quite fine if the permissions for plugins was easy to find and just copy in, but many times (most?) they're listed together with description, sometimes with the command used as well. Basically, you have to copy each permission one by one or copy it all into a notepad file and remove a lot of lines of text that's in the way.

This here is basically just a list of permissions for a bunch of plugins. A list easy to just copy/paste into your permissions plugin. I prefer, like many others, to use LuckPerms as my permissions manager. These lists are easy to copy/paste into LuckPerms web editor and then just go through them clicking true/false depending on what you want to allow. 

Sure. This might seem like a trivial thing, but with sometimes up to 70 different plugins on the server (or is that just me? :P) it takes forever to get it right. This just helps me, and I put it here to always have it within reach and perhaps help someone else.

## Now. There might be some errors...
I have tried to keep it as copy/paste-friendly as possible, but some permissions includes flags that are set by the player. Like names, or numbers. These are added with <name>, <number> or <flagname> etc. 
These are easily copied into ex. LuckPerms and then just edited to change <name> to the actual name/names you want perms for. But... I might have missed a space somewhere and if there's a space like <region name> instead of <regionname> LuckPerms will add that as two permissions. One <region and one name>. This is because LuckPerms can't handle spaces when you add permissions. It can handle spaces if adding them by editing an already added perm, but not when mass copying it in.
  
  If there is any I've missed. Please feel free to tell me and I'll fix it. Or change it yourself and push that change.

  
  Every variable like .< map name> or .< name> etc is written in capital letters like .MAPNAME or .NAME without spaces and <>[] etc. This is because if you just select all permissions and copy/paste into LuckPerms it will cut at the spaces and <>[] which would give you multiple perms in LuckPerms that just say .name> etc. This way it doesn't and you can just add all and then in LuckPerms change NAME and MAPNAME etc to the names and maps you want. 

  ### Moving into folders later
  I'm moving every permission file into their own folder based on plugin. This way I will be able to add a readme.md file for every plugin to add some info that might be needed (or add the full information for each permission while still have the file list them for easy copy/paste. I will probably add a commands list as well per plugin in the future. I hate how many plugins have the commands and permissions spread out. I need to have them listed to easily use them on my servers.  
