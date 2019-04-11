# Dynmap App

You require to run a Bukkit plugin server like [Spigot](https://www.spigotmc.org) and set up a minecraft server with [Dynmap](https://www.spigotmc.org/resources/dynmap.274/). Configure dynmap to disable its own webserver and be able to serve via nginx. then use this app to super simply allow yunohost to serve it up for you. **Note: this is required to run on the base root location or " / " when selecting a location for this web app. you should probably make a subdomain specifically for this app such as map.yourdomain.tld because no other apps will be able to be on that same domain.**

## Credits

Based off and forked from [Yunohost Redirect](https://github.com/YunoHost-Apps/redirect_ynh).
