# LazyBackup
A simple script to help me migrate to a new pc.

**NOTE:** It is not intended for regular backups.

## Use
1. Clone the project (`git clone git@github.com:andresemartinez/lazy-backup.git`)
2. Review the list of stuff to backup (the `backup.list` file)
3. Give execution permissions to the script (`chmod +x lazy-backup`)
4. Execute the lazy-backup script (`./lazy-backup`)

This will create a backup (.tar.gz file) with all the dirs and files listed in the `backup.list` file inside.
By default, if the backup is bigger than 4Gb it will split it in 4Gb chunks to be able to store it in a FAT32 filesystem (like a pendrive).


