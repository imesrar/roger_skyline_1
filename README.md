# roger_skyline_1
#configure static ip & disable DHCP
    - https://websiteforstudents.com/configure-static-ip-addresses-on-ubuntu-18-04-beta/
#ssh access only with publickeys, SSH root access should not be allowed directly
    - http://go2linux.garron.me/linux/2010/10/ssh-public-key-only-login-authentication-788/
#firewall
    - UFW is set to deny all incoming connections and allow all outgoing connections.
    This means anyone trying to reach your server would not be able to connect,
    while any application within the server would be able to reach the outside world
