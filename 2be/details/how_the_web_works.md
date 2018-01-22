## How The Web Works

### Background:

Review the materials below.

* First let's read [MDN HOW WEB WORKS](https://developer.mozilla.org/en-US/Learn/Common_questions/How_does_the_Internet_work)
* Next let's watch a few quick examples of [how the internet works](https://www.youtube.com/watch?v=7_LPdttKXPc).
* And [how IP addresses work](https://www.youtube.com/watch?v=KFooN7Mu0IM   - how IP addresses work).
* Finally let's tie these things together and watch a video about [DNS - what happens when you type an address into a web browser](https://www.youtube.com/watch?v=72snZctFFtA).
* Lastly, let's read a little about [the anatomy of a URL](https://doepud.co.uk/blog/anatomy-of-a-url)

### Questions:

Now we have a better grasp about the internet, and how some of the things are working. Now, let's answer a few questions to check our understanding. Don't be afraid to do additional research (googleing) for an answer. Fork this gist and answer the following questions:

?1. Describe, step by step, what happens when I type `www.example.com` into my browser and try to go to the page?
Computer sends a get request with the IP address associated with example.com to the ISP (first it does a DNS lookup for the numeric IP address), which directs it to example.com's servers over a series of routers and wires (the infrastructure called the internet), which returns a response back through the same route. The response includes a body which is a string of html (or other language) that your browser can read and display properly.

2.  What does HTTP stand for?
Hypertext Transfer Protocol

3. 	What protocol does the World Wide Web use?
HTTP
URLs
HTML

4. 	Each computer on the Internet is assigned an IP address, what does IP stand for?
Internet Protocol

5. 	What does DNS stand for?
  * A. Domain Name System

1. 	How are text (host) domain names matched to their respective numeric IP addresses.
The browser queries the local operating system if it recognizes the host name; if it does not, the operating system (specifically the resolving name server) queries a series of other servers including the root name, TLD (top level domain) and authoritative servers (in that order) to find the IP address. Once it has the numeric IP address, it returns in back to the browser.

2. 	What is the client?
  * C. The software which requests information from a server (browser)

1. 	What does URL stand for?
Uniform Resource Locator

?2. 	What are protocols
 * D.	The standardized method for transferring data or documents over a network

 * A. The standardization of IP addresses
 * B. The DNS standard method for data transfer
 * C.	The standardized network address system
 * E.	The standardized method for prioritizing data or document storage over a network

1. What does DNS stand for?
Domain Name System

?2. what is the `www` portion of a url?
World Wide Web server

3. What is The markup language used for all web documents?
HTML

?4. What is the organization that monitors web technologies?
World Wide Web Consortium (W3C) - why is this important? What specifically do they control? Who are they?

5. What is the Protocol for transferring web documents on the Internet?
HTTP

6. What matches the domain names with numeric IP addresses?
DNS
