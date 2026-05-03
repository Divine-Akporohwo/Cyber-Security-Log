# Lesson 4: How the Web Works 🌐  
Platform: TryHackMe 🧠  
  
---  
  
## DNS (Domain Name System)  
DNS allows humans to use easy-to-remember domain names (e.g., google.com) instead of IP addresses (e.g., 8.8.8.8) to access devices on the internet.  
  
---  
  
## Domain Hierarchy 🌍  
  
### Top-Level Domain (TLD)  
The extreme right of a URL (e.g., .com, .org, .ng)    
- gTLD (Generic): general use (.com, .net)    
- ccTLD (Country Code): geographical location (.ng, .uk)  
  
### Second-Level Domain (SLD)  
Main part of the domain (e.g., “google” in google.com)    
- Can contain letters, numbers, hyphens (max ~63 characters)  
  
### Subdomain  
Left-hand side of a domain (e.g., mail.google.com)    
- Used for sections or services of a site    
  
---  
  
## DNS Record Types 📡  
  
A Record – Maps domain to IPv4 address    
AAAA Record – Maps domain to IPv6 address    
CNAME Record – Maps one domain to another domain    
MX Record – Directs email delivery (includes priority)    
TXT Record – Stores text data for verification/authentication    
  
---  
  
## DNS Request Process 🔄  
  
1. User enters a domain    
2. Request goes to recursive resolver    
3. Resolver checks cache    
4. If not found → Root server    
5. Root server → TLD server    
6. TLD server → Authoritative server    
7. Authoritative server returns IP    
8. Browser connects to server    
  
---  
  
## HTTP & HTTPS 🔐  
  
HTTP – Used by websites for communication    
HTTPS – Secure version of HTTP (encrypted using TLS)  
  
---  
  
## URL (Uniform Resource Locator) 🔗  
  
Scheme – Protocol used (http/https)    
User – Optional login info    
Host – Domain name or IP    
Port – Optional service port    
Path – Resource location    
Query String – Extra parameters    
Fragment – Specific section of page    
  
---  
  
## HTTP Methods 📤  
  
GET – Retrieve data    
POST – Send data    
PUT – Update data    
DELETE – Remove data    
  
---  
  
## HTTP Status Codes 📊  
  
100–199 → Informational    
200–299 → Success    
300–399 → Redirection    
400–499 → Client error    
500–599 → Server error    
  
Common examples:  
- 200 OK – Success    
- 201 Created – Resource created    
- 301 Moved Permanently – Redirect    
- 302 Found – Temporary redirect    
- 400 Bad Request – Invalid request    
- 401 Unauthorized – Authentication required    
- 403 Forbidden – No access    
- 404 Not Found – Resource missing    
- 405 Method Not Allowed – Wrong method    
- 500 Internal Server Error – Server issue    
- 503 Service Unavailable – Server down    
  
---  
  
## HTTP Headers 📬  
  
Request Headers:  
- Host – Target domain    
- User-Agent – Browser info    
- Content-Length – Size of request    
- Accept-Encoding – Compression support    
- Cookie – Stored client data    
  
Response Headers:  
- Set-Cookie – Store cookie on client    
- Cache-Control – Caching rules    
- Content-Type – Data type    
- Content-Encoding – Compression method    
  
---  