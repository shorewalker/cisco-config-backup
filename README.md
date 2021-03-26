# cisco-config-backup
a simple expect script for backup up iOS and CatOS via tftp

`config-backup --tftpserver <server> --tftppath <path> --tsv <host,access,enable tsv file>`

##

aditionally a small bash script (with some dubious filesystem assumptions) to commit configurations into a git repo in a useful way

`config-git-push --tftproot <tftproot> --tftppath <tftppath> --tsv <host[,access,enable]> --commit-message "<message>"`
