# cinephile-stack
This stack is a compilation of several earlier projects for quickly deploying a home media server using:

**[transmission](https://github.com/linuxserver/docker-transmission)**

**[plexmediaserver](https://github.com/plexinc/pms-docker)**

**[samba](https://github.com/dperson/samba)**

Everything is configured so that all configuration is stored in the user's home directory ~$USER/cinephile-stack

To get started, you need to do a few things:
1. copy the repository to the **home** folder of the selected user
2. fill all variables of the **.env** file with their values
3. fill in the configuration file *~$USER/cinephile-stack/volumes/transmission/config/***settings.json**
4. optionally, if you are migrating a media server, move the plexmediaserver configuration (directory **Library**) to the directory *~$USER/cinephile-stack/volumes/plex/config*
