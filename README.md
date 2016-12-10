Data is located in Azure files - mounted like described [here](https://docs.microsoft.com/en-gb/azure/storage/storage-how-to-use-files-linux)

 docker run -e EULA=TRUE -p 25565:25565 -v /Minecraft/HeroLords:/data einari/bukkit