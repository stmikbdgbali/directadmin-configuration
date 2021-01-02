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
5. Cloudlinux versi php berbeda berdasarkan subdomain
https://cloudlinux.zendesk.com/hc/en-us/articles/115004537805-Different-PHP-versions-per-directories-using-mod-lsapi
## backup
1. manual backup menggunakan rclone dengna google drive
`rclone copy src suramadu:/suramadu --fast-list --drive-stop-on-upload-limit --drive-chunk-size 128M --progress`
2. Hapus folder yang usianya melampau 4 hari atau 6 hari
`find /path/to/backups/folder/ -ctime +6 -exec rm -rfv {} +find /path/to/backups/folder/ -ctime +6 -exec rm -rfv {} +`
## Administrasi Server
1. Menampilkan daftar port dan aplikasi-nya
`lsof -i -n`
## security
1. https://help.directadmin.com/item.php?id=247

## directslave


