# Debian 9 VPN Script

Feature

<h3 align="center">Installation</h3>

  ```html
wget https://github.com/johndesu090/johndesu090.github.io/raw/master/deb9.sh && chmod +x deb9.sh && ./deb9.sh
  ```

Here are the full features of this script.

    OpenSSH, port : 22, 444
    Dropbear, port : 80, 143
    STunnel, port : 443
    Squid3, port : 8000, 8080 (limit to IP SSH)
    Badvpn : badvpn-udpgw port 7200
    Webmin : http://IPVPS:10000/
    
    Script menu: displays a list of available commands
    Usernew script: create an SSH account
    Script trial: create a trial account
    Delete script: delete SSH account
    Check script: check user login
    Script member: check the list of SSH members
    Script speedtest : speedtest VPS
    Script info: displays system information
    Script about: information about auto install scripts
    VPS auto reboot every 12 hours

Terms

    Make sure your VPS uses the Debian 9 64 bit operating system.
    Make sure the VPS condition is still fresh, no application has been installed.

Credits
  Evira & SxC
