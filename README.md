# T-NSA-501-NAN_2
[![](https://mermaid.ink/img/pako:eNqdVOtu2jAUfhXL_ZtkcZKCbU2dEO3WSm0Vlf4aoMgkLkQkDjJmLQMeaM-xF5tzKZAUCpqlJD4Xfz5fzmUFwyzikMKxZLMJuH8aCKDXXC0TDn4wxV_ZMuhx-YtL8BInCb1AI892Lo25ktmU04sRZiQklWi-xpGaUGf2VsEsRiVuHak05uv6tuv38xcoLcM902Ovr5-Phu9xorjs-yycclVJlZmLaD_--85jgIJOlMYi1gEyFWeiYhERhFvOlkXOYYRPsTiEt4ur0Ad-t-93Qd1n2HTKGQdPTIx5Sb7YUoCIY6EWtjzH8myzZR9n5dRz4nko3CahZHM6J_s4uwBLuV9-vo7k1UOnCyj49r5y1Z1fi7VtD5vnz2DYRiZCn1B0g5t0lmRLziuSIcEIhVuSecLYWSR3SLswtaZKVWn7-2dYN54mgHSOEP7AoNE0pml-UjdHnOtpOeLUpHWw2k3zat1JEuBnUs3XB8Abvzr3v31-9r_kr96xAwevuRO6EQVXBvBjMTaK3jbyNl4fbP9aGf_n-UbgZyNAA6ZcpiyO9ORb5XgDqCY85QNI9TZicjqAA7HRfmyhst5ShJAqueAGXMwiDXUdM11fKaQvLJlvtTdRrDL57jlj4meWpXsipCv4BinBFmrryrFtTPQodVwDLiFF5NIiyEWO3mDiEtfbGPB3AYAs18bYw46j3dstRNoG5MVdD-XwLmb45h_YxdF4?type=png)](https://mermaid-js.github.io/mermaid-live-editor/edit#pako:eNqdVOtu2jAUfhXL_ZtkcZKCbU2dEO3WSm0Vlf4aoMgkLkQkDjJmLQMeaM-xF5tzKZAUCpqlJD4Xfz5fzmUFwyzikMKxZLMJuH8aCKDXXC0TDn4wxV_ZMuhx-YtL8BInCb1AI892Lo25ktmU04sRZiQklWi-xpGaUGf2VsEsRiVuHak05uv6tuv38xcoLcM902Ovr5-Phu9xorjs-yycclVJlZmLaD_--85jgIJOlMYi1gEyFWeiYhERhFvOlkXOYYRPsTiEt4ur0Ad-t-93Qd1n2HTKGQdPTIx5Sb7YUoCIY6EWtjzH8myzZR9n5dRz4nko3CahZHM6J_s4uwBLuV9-vo7k1UOnCyj49r5y1Z1fi7VtD5vnz2DYRiZCn1B0g5t0lmRLziuSIcEIhVuSecLYWSR3SLswtaZKVWn7-2dYN54mgHSOEP7AoNE0pml-UjdHnOtpOeLUpHWw2k3zat1JEuBnUs3XB8Abvzr3v31-9r_kr96xAwevuRO6EQVXBvBjMTaK3jbyNl4fbP9aGf_n-UbgZyNAA6ZcpiyO9ORb5XgDqCY85QNI9TZicjqAA7HRfmyhst5ShJAqueAGXMwiDXUdM11fKaQvLJlvtTdRrDL57jlj4meWpXsipCv4BinBFmrryrFtTPQodVwDLiFF5NIiyEWO3mDiEtfbGPB3AYAs18bYw46j3dstRNoG5MVdD-XwLmb45h_YxdF4)

# Passwords 
### Webserver
root:ad0rx>4Amt
admin:(0P>T4Q%9F

### Gateway
root:
admin:

# Modif
### Webserver
 **Port SSH :** 22 -> 1298
 /etc/pam.d/passwd    #politique de mdp
### Gateway
 **Port SSH :** 22 -> 1337
 /bin/ssh/sshd.config   #désactiver accés au root et cgmt de port
 /etc/pf.conf   #parefeu
 /etc/hostname.em0-1-2-3       #configuration des hostname
 /etc/dhcpd.conf          #regles dhcp

# Politique de mot de passe 

  The above enforces the following:
– forces old passwords to be entered AND
– 12 characters if they are from 3 character classes OR
– 10 characters if they are from 4 character classes AND
– denies new password if it is similar to old one AND
– enforce the above restrictions for non-root users.

