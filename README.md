# Stremio Hisense (Vidaa) Sideload Helper

This project allows sideloading Stremio on Hisense TV devices that run Vidaa OS.

It implements simple HTTP and DNS server needed to assist with the sideloading process.

In order to use this project, you need to follow these steps:

1. Download the code from this repository
2. Install required python modules (dnslib)
3. Update the config file - replace "192.168.1.100" with your local IP addresses
4. Run server.py
5. Change the DNS settings on your TV to use your local IP (the one you set in the config.json file)
6. Open https://vidaahub.com/ on your TV (ignore SSL certificate warning)
7. Install the application by pressing "Install Stremio"
8. Switch the DNS settings on your TV back to what they were before
9. Restart TV

