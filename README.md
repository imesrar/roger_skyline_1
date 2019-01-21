# roger_skyline_1
#configure static ip & disable DHCP
    - https://websiteforstudents.com/configure-static-ip-addresses-on-ubuntu-18-04-beta/


#ssh access only with publickeys, SSH root access should not be allowed directly
    - http://go2linux.garron.me/linux/2010/10/ssh-public-key-only-login-authentication-788/


#firewall
    - UFW is set to deny all incoming connections and allow all outgoing connections.
      This means anyone trying to reach your server would not be able to connect,
      while any application within the server would be able to reach the outside world


#fail2ban & DOS
   -How To: Stop Apache DOS attacks with Fail2Ban
       https://r3dux.org/2013/06/how-to-stop-apache-dos-attacks-with-fail2ban/
   -Use Fail2ban to Secure Your Server
       https://www.linode.com/docs/security/using-fail2ban-for-security/   
   -How To Protect SSH and Apache Using Fail2Ban on Ubuntu Linux
       https://blog.rapid7.com/2017/02/13/how-to-protect-ssh-and-apache-using-fail2ban-on-ubuntu-linux/


#partie WEB
   -set a self-signed SSL
       https://www.digitalocean.com/community/tutorials/how-to-create-a-self-signed-ssl-certificate-for-apache-in-ubuntu-18-04
