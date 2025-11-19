# My Current Docker Compose Stack
What I currently have deployed with docker on my home "server" (in quotation marks because it's just a repurposed old PC)

# The Machine itself
![neofetch and not fastfetch because who cares](https://github.com/pingusurmars/my-docker-stack/blob/master/neofetch.png?raw=true)<br>
Nothing fancy, just an old pc doing the stuff I need it to do, might upgrade soon if I really need to (which is likely soon)

# Summary
Here's a list of what's running and why (<ins>underlined</ins> = not running inside docker but could've)
<br><br>
**Pihole** - The one and only DNS Sinkhole, surprisingly works on Netflix and helps a ton with annoying ads<br>
**Portainer** - Makes Docker easier to manage in my opinion that in the CLI, especially on mobile where SSH isn't super convenient<br>
**[Speedtest Tracker](https://docs.speedtest-tracker.dev/)** - Useful tool to see if my internet speed isn't too slow compared to what I normally get, not used often but cool tool<br>
**Nginx Proxy Manager** - Way simpler than struggling with nginx config files, even tho [NGINXConfig](https://www.digitalocean.com/community/tools/nginx?global.app.lang=en) exists<br>
**Watchtower** - Auto-updates for containers, do I really need to explain how life changing this is?<br>
**Jellyfin** - Basically self-hosted Netflix<br><br>

<ins>I'm also including these here as they're not inside the docker compose file:<br><br></ins>
**Mute All Discord Bot (custom made)** - Like the name implies, a Discord bot to server mute/demute everyone inside a voice channel in one go instead of manually doing it. (saves a lot of time, it's also based on the node container image)<br>
**Immich** - Extremely cool for backing up my phone's gallery from anywhere & has a cool UI (not included as it needed a separate docker compose file, it's also running [here](https://immich.pingusurmars.xyz))
