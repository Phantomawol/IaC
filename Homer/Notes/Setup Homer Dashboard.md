##### Disclaimer: I do not own any of the images or repos outside of my own mentioned in this article nor do I claim to own them. This is strictly notes for myself for rebuilding if needed.

Setting up Homer Dashboard Instructions
=============

**Note: I had issues with the docker container not containing everything (New to docker, so might of been my issues) and I wanted to set up some instructions for future setups. Will be an Ansible book in the future.**

### Using the bastienwirtz's Homer repo to build docker image:
Using the release tarball (prebuilt, ready to use) repo here: https://github.com/bastienwirtz/homer/tree/main?tab=readme-ov-file#getting-started

> 1.  wget the url listed
> 2.  unzip the file in the assets folder you created with Docker and/or Portainer. **DO NOT UNZIP OUTSIDE THAT FOLDER OR YOU WILL HAVE TO CLEAN IT UP!**
> 3.  cp the config.yml.dist like shown and this will give you the default template.
> 
> (Needs testing): You can skip step 3 if you'd like (Untested as of 4th of April, 2024) and just sudo touch config.yml and load the config.yml listed under files/config.yml

### Pulling down icons for Homer dashboard:
**Note: Testing on 4th of April, 2024 - The pihole icon didn't load on the page and I ended up pulling the icon from here: https://pi-hole.github.io/graphics/Vortex/Vortex_Vertical_wordmark_lightmode.png**
  1. NX211 has a repo of all the PNG images you will need. Repo can be found here: https://github.com/NX211/homer-icons
    a. Pull down whatever is needed. Ex: Pi-hole, Plex, Jellyfin, etc.
