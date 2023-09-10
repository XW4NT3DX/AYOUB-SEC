 
>_**DNS Record Types**_

DNS isn't just for websites though, and multiple types of DNS record exist. We'll go over some of the most common ones that you're likely to come across.

1. A RECORD 
		These records resolve to IPv4 addresses, for example 104.26.10.228

2. AAAA RECORD 
		These records resolve to IPv6 addresses, for example 2606:4700:20::681a:be6
	
3. CNAME RECORD 
		 These records resolve to another domain name, for example, W4NT3Ds online shop has the subdomain name store.W4NT3D.com which returns a CNAME record shops.shopify.com. Another DNS request would then be made to shops.shopify.com to work out the IP address.
		 
4. MX RECORD
		
	These records resolve to the address of the servers that handle the email for the domain you are querying, for example an MX record response for W4NT3D.com would look something like alt1.aspmx.l.google.com. These records also come with a priority flag. This tells the client in which order to try the servers, this is perfect for if the main server goes down and email needs to be sent to a backup server.
	
1. TEXT RECORD 
		TXT records are free text fields where any text-based data can be stored. TXT records have multiple uses, but some common ones can be to list servers that have the authority to send an email on behalf of the domain (this can help in the battle against spam and spoofed email). They can also be used to verify ownership of the domain name when signing up for third party services.
