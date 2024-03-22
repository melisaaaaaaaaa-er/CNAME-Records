# CNAME Records

<h3>Purpose</h3>

- Observing CNAME records on Windows Server.

#
<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/dns-images/main/13.png"/>

A CNAME (canonical name) is a record that allows names to be mapped to other names. It is often used to redirect alternative domain names – called aliases – to the official domain of a website.
To create a CNAME record on DC-1, go to Tools → DNS → DC-1 → Forward Lookup Zone → right-click -your domain- → New Alias (CNAME)...

#
<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/dns-images/main/14.png"/>

<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/dns-images/main/15.png"/>

Input the alias name and the official name you want the alias to map to (here it is Fully Qualified Domain Name - FQDN).

For the lab, search will be mapped to www.google.com.

#
<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/dns-images/main/16.png"/>

When you perform a ping and an nslookup you’ll see the name and public IP address for Google show up.
