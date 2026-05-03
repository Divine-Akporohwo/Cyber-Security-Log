# Lesson 6: How Websites Work 🌐  
Platform: TryHackMe 🧠  
  
---  
  
## Rooms Completed 📚  
How Websites Work    
The Computer    
Cloud Computing Fundamentals (included within The Computer section)  
  
---  
  
## Core Concept 💡  
Websites are made up of:  
- Front-end (Client-side): What the user sees in the browser 🖥️    
- Back-end (Server-side): Processes and logic running on the server ⚙️    
  
---  
  
## Technologies Used to Build Websites 🛠️  
  
HTML (HyperText Markup Language) – Defines structure 🧱    
CSS (Cascading Style Sheets) – Styles and designs the page 🎨    
JavaScript – Adds interactivity and dynamic behavior ⚡    
  
---  
  
## HTML Basics 📄  
  
HTML defines the structure of a webpage.  
  
### Basic Structure Elements  
  
- `<DOCTYPE HTML>`    
  Tells the browser what type of document it is and how to interpret it 🔍    
  
- `<HTML>`    
  Root element that starts and ends the webpage 🌐    
  
- `<HEAD>`    
  Contains metadata (e.g., title, links, settings) 🏷️    
  
- `<BODY>`    
  Contains all visible content on the webpage 👀    
  
---  
  
## Common HTML Elements 🧩  
  
- `<H1> </H1>` → Main heading 🪧    
- `<P> </P>` → Paragraph ✍️    
- `<IMG>` → Image 🖼️    
- `<BUTTON>` → Clickable button 🔘    
  
---  
  
## Security Concepts 🔐  
  
### Sensitive Data Exposure  
- Occurs when sensitive information is visible in source code or responses    
- Can be exploited if credentials or tokens are exposed ⚠️    
  
### HTML Injection  
- Occurs when user input is not properly sanitized    
- Attackers can inject HTML into a webpage 💉    
- Can modify page content or behavior    
  
---  
  
## Website Components 🧱  
  
### Load Balancer ⚖️  
- Distributes traffic across multiple servers    
- Prevents overload    
- Uses health checks    
  
### CDN (Content Delivery Network) 🌍  
- Stores website content in multiple global locations    
- Improves loading speed    
  
### Database 🗄️  
- Stores and manages application data    
  
### WAF (Web Application Firewall) 🛡️  
- Filters malicious traffic    
- Protects web applications    
  
### Web Server 🌐  
- Handles HTTP requests and responses    
  
### Virtual Hosting 🏠  
- One server hosts multiple websites    
  
### Static vs Dynamic Content 🔄  
- Static: fixed content 📌    
- Dynamic: changes based on user input or logic 🔁    
  
### Backend / Scripting ⚙️  
- Handles logic, processing, and database communication    
  
---  
  
## THE COMPUTER 💻  
  
### Boot Sequence 🚀  
  
- Power button pressed → signal sent to PSU 🔌    
- Firmware (UEFI/BIOS) initializes hardware ⚙️    
- POST (Power-On Self Test) checks hardware 🧪    
- Boot device selected 💽    
- Bootloader starts operating system 🖥️    
  
---  
  
### Computer Types 🖥️📱  
  
- Laptop 💻    
- Desktop 🖥️    
- Workstation ⚙️    
- Server 🗄️    
- Smartphone 📱    
- Tablet 📲    
- IoT devices 🌐 (internet-connected devices that send/receive data)    
- Embedded systems 🔧    
  
---  
  
### Client-Server Basics 🔗  
- Client sends requests 📤    
- Server responds with data 📥    
  
---  
  
### Virtualization 🧠  
  
- One physical machine runs multiple virtual machines    
- Managed by a hypervisor    
  
#### Hypervisor Types  
  
- Type 1 (Bare-metal): Runs directly on hardware ⚙️    
- Type 2 (Hosted): Runs on top of an operating system 💻    
  
---  
  
### Containers 📦  
- Lightweight isolated environments    
- Used to run single applications    
  
---  
  
## CLOUD COMPUTING (UNDER COMPUTER) ☁️  
  
### Cloud Types ☁️  
  
Public Cloud – Open to general users 🌍    
Private Cloud – Restricted to one organization 🔒    
Hybrid Cloud – Combination of public and private cloud 🔁    
  
---  
  
### Cloud Service Models 🧩  
  
IaaS – Renting infrastructure (servers, storage, networking) 🏗️    
PaaS – Platform for building applications 🛠️    
SaaS – Fully managed software services 💡    
  
---  
  
### Major Cloud Providers 🌐  
  
Microsoft Azure – AI, analytics, enterprise tools 🤖    
Google Cloud Platform – AI and machine learning 🧠    
Alibaba Cloud – infrastructure services 🏢    
IBM Cloud – hybrid cloud and AI solutions ⚙️    
Oracle Cloud – enterprise databases and applications 🗄️    
  
---  
  
### Cloud Characteristic 📈  
  
Scalability: ability to handle sudden increases in demand 📊    
  
---  
  
## NOTES (KEY TAKEAWAYS) 📝  
  
- Sensitive data exposure happens when secrets appear in source code ⚠️    
- HTML injection occurs when input is not sanitized 💉    
- Load balancers distribute traffic across servers ⚖️    
- CDN improves performance by serving nearby content 🌍    
- WAF protects applications from attacks 🛡️    
- Web servers handle HTTP communication 🌐    
- Virtual hosting allows multiple websites per server 🏠    
- Static content does not change; dynamic content does 🔄    
- Hypervisors enable virtualization 🧠    
- Containers run lightweight isolated applications 📦    
- Cloud computing provides scalable resources on demand ☁️    
