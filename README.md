# Grinder
> Author: Ratnodeep Bandyopadhyay ([@QuarterShotofEspresso](https://github.com/QuarterShotofEspresso))

Automated a task which has been done a couple times in the past week. Grind is intended to ease a mundane but neccesary task of teeny project management. It's as easy to use as it was to build. A secure, remote repository for any project.

##API

`grind push <file-path>` Compress, encrypt, and secure copy project to remote location

`grind pull <file-path>` Secure copy project from remote location then decrypt and inflate

`grind pull` List all projects saved on remote site

`grind lock <file-path>` Compress and encrypt project

`grind unlock <file-path>` Decrypt and inflate project

The `.grinds` document is what saves information on the remote site.
New features are added as the needs arise. The API will be updated as new functions are added.
