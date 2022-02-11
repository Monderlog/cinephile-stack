# cinephile-stack
This stack is designed to quickly deploy a home media server based on these projects:
**[transmission](https://github.com/linuxserver/docker-transmission), [samba](https://github.com/dperson/samba), [plexmediaserver](https://github.com/plexinc/pms-docker)**

Everything is configured so that all configuration is stored in the user's home directory ~$USER/cinephile-stack

## To get started, you need to do a few things:

1. copy the repository to the **home** folder of the selected user
2. fill all variables of the **.env** file with their values
3. optionally, you can tune transmission configuration file:
  ~$USER/cinephile-stack/volumes/transmission/config/**settings.json**
4. optionally, if you are migrating a media server, move the plexmediaserver configuration (directory **Library**) to the directory:
  ~$USER/cinephile-stack/volumes/plex/**config**
