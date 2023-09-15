# *__What is ==HTTP==? (Hypertext Transfer Protocol)__	
HTTP is what's used whenever you view a website, developed by Tim Berners-Lee and his team between 1989-1991. HTTP is the set of rules used for communicating with web servers for the transmitting of webpage data, whether that is HTML, Images, Videos, etc.
 
# *___What is ==HTTPS==? (Hypertext Transfer Protocol Secure)*
 	
HTTPS is the secure version of HTTP. HTTPS data is encrypted so it not only stops people from seeing the data you are receiving and sending, but it also gives you assurances that you're talking to the correct web server and not something impersonating it.


------------------------------------------------------------------------

When we access a website, your browser will need to make requests to a web server for assets such as HTML, Images, and download the responses. Before that, you need to tell the browser specifically how and where to access these resources, this is where ==URLs== will help.

# **What is a ==URL==? (Uniform Resource Locator)**
If you’ve used the internet, you’ve used a URL before. A URL is predominantly an instruction on how to access a resource on the internet. The below image shows what a URL looks like with all of its features (it does not use all features in every request). 

![34ad66d8b90aaaa35f9536d3b152ea97](https://github.com/AyoubHub212/AYOUB-SEC/assets/136107596/d94a2911-ce12-43ee-8345-a9dcd8ddb5bd)



**Scheme:** = This instructs on what protocol to use for accessing the resource such as HTTP, HTTPS, FTP (File Transfer Protocol).  

**User:** = Some services require authentication to log in, you can put a username and password into the URL to log in.  

**Host:** = The domain name or IP address of the server you wish to access.  

**Port:** = The Port that you are going to connect to, usually 80 for HTTP and 443 for HTTPS, but this can be hosted on any port between 1 - 65535.  

Path:** = The file name or location of the resource you are trying to access.  

**Query String: = Extra bits of information that can be sent to the requested path. For example, /blog?**id=1** would tell the blog path that you wish to receive the blog article with the id of 1.  

**Fragment:** = This is a reference to a location on the actual page requested. This is commonly used for pages with long content and can have a certain part of the page directly linked to it, so it is viewable to the user as soon as they access the page.
________________________________________________________________________

**It's possible to make a request to a web server with just one line "GET / HTTP/1.1"**


 ![232](https://github.com/AyoubHub212/AYOUB-SEC/assets/136107596/d75fe767-c359-4d30-a9d4-a0cde9bb2226)

 
