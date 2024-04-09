##### Disclaimer: I do not own any of the images or repos outside of my own mentioned in this article nor do I claim to own them. This is strictly notes for myself for rebuilding if needed.

Setting up Homer Dashboard Instructions
=============

**Note: I had issues with the docker container not containing everything (New to docker, so might of been my issues) and I wanted to set up some instructions for future setups. Will be an Ansible book in the future.**

### Using Walkxcode's repo as it's much cleaner than default layout.
  1. Visit's Walkxcode's github listed here: https://github.com/walkxcode/homer-theme/tree/main?tab=readme-ov-file#getting-started
  2. Git clone the repo and drop it in the main home directory. **Note: You will need to respin up the docker instance (Unless you don't need to, I'm new to docker) and change the Host Volume to the Homer-Theme directory.**
  3. Once that is done, you will be able to delete their config.yml file and load the custom one under assets/config.yml

### Pulling down icons for Homer dashboard:
**Note: Testing on 4th of April, 2024 - The pihole icon didn't load on the page and I ended up pulling the icon from here: https://pi-hole.github.io/graphics/Vortex/Vortex_Vertical_wordmark_lightmode.png**
  1. NX211 has a repo of all the PNG images you will need. Repo can be found here: https://github.com/NX211/homer-icons
    a. Pull down whatever is needed. Ex: Pi-hole, Plex, Jellyfin, etc.
