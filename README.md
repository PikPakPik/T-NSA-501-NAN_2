# T-NSA-501-NAN_2
[![](https://mermaid.ink/img/pako:eNqdlP9umzAQx18Fuf8C8xEDxpoqRWm3Vmor1PSvJRFywE1Q-RERZ22W5oH2HHuxmcCSQJMmmiXA5zt_fR_O9gqFeSQQQ5OCz6ba3eMw01Sby2UitO9cile-DPqi-CkK7TlOEnYBY4ItW5_LIn8R7GJMuRd6tWm8xpGcMmv2VsssxpVuU6lylu3qpucPypdWeUZ7rof-QD0fHd_iRIpi4PPwRcjaqt0ii_bzv-s-BBB0ozTOYpUgl3Ge1RSRB9SxthQlw5ieojikt8trMx74vYHf05oxo3ZQSRw88mwiKvhNl2ngWSY41CSWSbDh4ONUVrMmhEC4LUJFc7om-zq7BCt7UH2-jovL-25PYxqmDGNmuQwTJggjUem69Rs5u3jU1jmD1AUD4BPUTnCdzpJ8KUQNG3oUINzCloXjZ8HulHZpqpG6ZJXvz-9R03kaAFStgH4gaB0ewzA-2T9HgpvlORLUxjq46w3j8r2bJJqfF3L-fkC89avL-JunJ_9L-errmh9nE708k8fmHlzxNlNnMxNyO1_9wVrl0I3Q2Nn_Ob_FcLYC0lEqipTHkboMV6XeEMmpSMUQMdWNePEyRMNsreL4Qub9ZRYiJouF0NFiFimpq5irrZYi9syT-Xb0OoplXvyLnPHsR56neyZiK_SGmAG4Y1LbdmxKMVgELB0tEYMOMZVpu7RDKNiA3bWOfm0UwATPxZbjgAfEtj1i60hsFruvLvTNvb7-C78V1kk?type=png)](https://mermaid-js.github.io/mermaid-live-editor/edit#pako:eNqdlP9umzAQx18Fuf8C8xEDxpoqRWm3Vmor1PSvJRFywE1Q-RERZ22W5oH2HHuxmcCSQJMmmiXA5zt_fR_O9gqFeSQQQ5OCz6ba3eMw01Sby2UitO9cile-DPqi-CkK7TlOEnYBY4ItW5_LIn8R7GJMuRd6tWm8xpGcMmv2VsssxpVuU6lylu3qpucPypdWeUZ7rof-QD0fHd_iRIpi4PPwRcjaqt0ii_bzv-s-BBB0ozTOYpUgl3Ge1RSRB9SxthQlw5ieojikt8trMx74vYHf05oxo3ZQSRw88mwiKvhNl2ngWSY41CSWSbDh4ONUVrMmhEC4LUJFc7om-zq7BCt7UH2-jovL-25PYxqmDGNmuQwTJggjUem69Rs5u3jU1jmD1AUD4BPUTnCdzpJ8KUQNG3oUINzCloXjZ8HulHZpqpG6ZJXvz-9R03kaAFStgH4gaB0ewzA-2T9HgpvlORLUxjq46w3j8r2bJJqfF3L-fkC89avL-JunJ_9L-errmh9nE708k8fmHlzxNlNnMxNyO1_9wVrl0I3Q2Nn_Ob_FcLYC0lEqipTHkboMV6XeEMmpSMUQMdWNePEyRMNsreL4Qub9ZRYiJouF0NFiFimpq5irrZYi9syT-Xb0OoplXvyLnPHsR56neyZiK_SGmAG4Y1LbdmxKMVgELB0tEYMOMZVpu7RDKNiA3bWOfm0UwATPxZbjgAfEtj1i60hsFruvLvTNvb7-C78V1kk)  
# Passwords 
### Webserver  
root:ad0rx>4Amt  
admin:(0P>T4Q%9F

### Gateway
root:q;#XD3]ge+FD

### Admin-Client
admin-client:admin

### Employee-Client
employee-client:employee

# Modif
### Webserver
 - **Port SSH :** 22 -> 1298
 - **/etc/pam.d/passwd**    #politique de mdp
### Gateway
 - **Port SSH :** 22 -> 1337  
 - **/bin/ssh/sshd.config**   #désactiver accés au root et changement de port  
 - **/etc/pf.conf**   #pare-feu  
 - **/etc/hostname.em0-1-2-3**       #configuration des hostnames 
 - **/etc/dhcpd.conf**          #regles dhcp  

# Politique de mot de passe 
- 12 caractères si il y a 3 caractères spéciaux
- 10 caractères si il y a 4 caractères spéciaux
- Impossible de remetre un mot de passe utilisé

