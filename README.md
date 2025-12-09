# ufw_firewall
Task 2 - Basic Firewall Configuration using UFW

┌──(root㉿kali)-[/]
└─# apt install ufw 
ufw is already the newest version (0.36.2-9).
Summary:
  Upgrading: 0, Installing: 0, Removing: 0, Not Upgrading: 1824
                                                                                                                         
┌──(root㉿kali)-[/]
└─# ufw enable
Firewall is active and enabled on system startup
                                                                                                                         
┌──(root㉿kali)-[/]
└─# ufw allow ssh
Rule added
Rule added (v6)
                                                                                                                         
┌──(root㉿kali)-[/]
└─# ufw deny http
Rule added
Rule added (v6)
                                                                                                                         
┌──(root㉿kali)-[/]
└─# ufw status verbose
Status: active
Logging: on (low)
Default: deny (incoming), allow (outgoing), disabled (routed)
New profiles: skip

To                         Action      From
--                         ------      ----
22/tcp                     ALLOW IN    Anywhere                  
80/tcp                     DENY IN     Anywhere                  
22/tcp (v6)                ALLOW IN    Anywhere (v6)             
80/tcp (v6)                DENY IN     Anywhere (v6)             

                                                                                                                         
┌──(root㉿kali)-[/]
└─#  
