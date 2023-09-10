
>**_What is DNS?_** 

DNS (Domain Name System) provides a simple way for us to communicate with devices on the internet without remembering complex numbers. Much like every house has a unique address for sending mail directly to it, every computer on the internet has its own unique address to communicate with it called an IP address. An IP address looks like the following 104.26.10.229, 4 sets of digits ranging from 0 - 255 separated by a period. When you want to visit a website, it's not exactly convenient to remember this complicated set of numbers, and that's where DNS can help. So instead of remembering 104.26.10.229, you can remember W4NT3D.com instead.


>**_Domain Hierarchy_**
![[Screenshot from 2023-07-23 11-53-28.png]]

1 /     **TLD (Top-Level Domain)**

the TLD is the most righthand part of domain name for example of W4NT3D.com is .com
and there is two type of TLD :
		a) the first one is the gTLD  ( Generic top level ) , its used to tell the user the domain name's purpose for example :
					->  .com = commercial .
					->  .org  =  organisation.
					-> ...
b) the second one is ccTLD ( County Code Top Level Doamine )it's used for geographical pruposes for example :
					->  .ca = for sites based in Canada
					->  .co.uk = for sites based in United Kingdom 
					-> ...   

2/      **Second-Level Domain**

Taking W4NT3D.com as an example, the .com part is the TLD, and tryhackme is the Second Level Domain. When registering a domain name, the second-level domain is limited to 63 characters + the TLD and can only use a-z 0-9 and hyphens (cannot start or end with hyphens or have consecutive hyphens).

3/       **Subdomain**  

A subdomain sits on the left-hand side of the Second-Level Domain using a period to separate it; for example, in the name admin.W4NT3D.com the admin part is the subdomain. A subdomain name has the same creation restrictions as a Second-Level Domain, being limited to 63 characters and can only use a-z 0-9 and hyphens (cannot start or end with hyphens or have consecutive hyphens). You can use multiple subdomains split with periods to create longer names, such as jupiter.servers.W4NT3D.com. But the length must be kept to 253 characters or less. There is no limit to the number of subdomains you can create for your domain name.