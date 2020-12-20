# plugin-direct-admin

## tips and trick
1. How to migrate cpanel to directadmin
https://forum.directadmin.com/threads/how-to-cpanel-to-da-migration.58059/
2. Installing an SSL certificate for your hostname using LetsEncrypt
https://help.directadmin.com/item.php?id=629
setelah itu eksekusi perintah `chown -R admin. /home/admin/all_backups/`
3. Setting panjang username
https://www.directadmin.com/features.php?id=189
4. instalasi custom build diaktifkan dulu
`./build set ioncube yes` kemudian 
`./build ioncube`
## backup
1. manual backup menggunakan rclone dengna google drive
`rclone copy src suramadu:/suramadu --fast-list --drive-stop-on-upload-limit --drive-chunk-size 128M --progress`
## security
1. https://help.directadmin.com/item.php?id=247

