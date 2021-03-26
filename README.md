# cisco-config-backup
a simple expect script for backing up iOS and CatOS running configurations via tftp

`config-backup --tftpserver <server> --tftppath <path> --tsv <host,access,enable tsv file>`

##

additionally a small bash script (with some dubious filesystem assumptions) to commit configurations into a git repo in a useful way

`config-git-push --tftproot <tftproot> --tftppath <tftppath> --tsv <host[,access,enable]> --commit-message "<message>"`
