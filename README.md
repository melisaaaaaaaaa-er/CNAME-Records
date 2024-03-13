# CNAME Records

![13](https://github.com/melisa-er/CNAME-Records/assets/157723219/f55cf13a-bedc-4d34-b207-99f43e7ea057)

A CNAME (canonical name) is a record that allows names to be mapped to other names. It is often used to redirect alternative domain names – called aliases – to the official domain of a website.
To create a CNAME record on DC-1, go to Tools → DNS → DC-1 → Forward Lookup Zone → right-click -your domain- → New Alias (CNAME)...

#
![14](https://github.com/melisa-er/CNAME-Records/assets/157723219/815979c7-b14f-447c-9d3d-acd1dee6b438)

![15](https://github.com/melisa-er/CNAME-Records/assets/157723219/e9426dd1-1511-478d-a3e1-6396a519aed7)

Input the alias name and the official name you want the alias to map to (here it is Fully Qualified Domain Name - FQDN).

For the lab, search will be mapped to www.google.com.

#
![16](https://github.com/melisa-er/CNAME-Records/assets/157723219/109716ff-fc79-41cd-80da-53c2b920d6a4)

When you perform a ping and an nslookup you’ll see the name and public IP address for Google show up.
