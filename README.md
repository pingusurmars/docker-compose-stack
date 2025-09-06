# My Current Docker Compose Stack
What I currently have deployed with docker on my home "server" (in quotation marks because it's just a repurposed old PC)

# The Machine itself
![neofetch image](https://github.com/pingusurmars/my-docker-stack/blob/master/neofetch.png?raw=true)

# Summary
Here's a text list of what's running and why (<ins>underlined</ins> = not running inside docker but could've)
<br><br>
**Pihole** - Layer 3 (correct me if I'm wrong) Ad Blocker, surprisingly works on Netflix and helps a ton with annoying ads<br>
**Portainer** - Makes Docker easier to manage in my opinion that in the CLI, especially on mobile where SSH isn't super convenient<br>
**[Speedtest Tracker](https://docs.speedtest-tracker.dev/)** - Useful tool to see if my internet speed isn't too slow compared to what I normally get, not used often but cool tool<br>
**Nginx Proxy Manager** - Way simpler than struggling with nginx config files, even tho [NGINXConfig](https://www.digitalocean.com/community/tools/nginx?global.app.lang=en) exists<br>

I'm also including these here as they're not inside the docker compose file:
**Mute All Discord Bot (custom made)** - Like the name implies, a Discord bot to server mute/demute everyone inside a voice channel in one go instead of manually doing it. (saves a lot of time, it's also based on the node container image)<br>
**<ins>xmrig Proxy</ins>** - To be honest I don't have hundreds of workers mining monero, I just prefer having it to make one big worker on my pool instead of multiple with varying power.
