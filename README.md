# php-ip-logger

Logs the IP of the visitor who runs the script to a .txt file.
Useful when you don't have a dynamic DNS and need to access your home network / Raspberry Pi.

Example Usage: 

``crontab -e``

Update IP every hour (= 'at minute 0')

``0 * * * * curl http://urlofyourhost.com/ip.php ``

The logged ip will then be written to 'ip.txt' (located in the same folder as ip.php)
