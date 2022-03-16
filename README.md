# T1A1 - Workbook

## Q1

Markup language is a human readable computer language written in plain text. All markup languages share a common feature which are tags to help specify different contents and create structures on the webpage. Common markup languages include HTML, and XML (Per Christensson 2022).

Markup languages are understood by web browsers due to the standards based on the consistency in processing documents by markup languages (IPL n.d).

BYJU’S (n.d) states as the following:

- **HTML (HyperText Markup language):** 
  
  Displays data and describes the structure of a webpage.

- **XML (Extensible Markup Language):** 
  
  Stores and transfers data.

## Q2

### Packets

Data are split into pieces or information which are then called packets. The are sent through various routes which are then reassembled back together into a message. The packet contains information including sender’s IP address, destination of the packet, email reassembling information, a check sum for error detection and many more. (theteacher.info 2022) Packets are faster and easier to send over the network evenly distributed, preventing from getting stuck in one route whereas to move a large piece of information is a lot more difficult. (Live Action 2021)

### IP addresses (IPv4 and IPv6)

Internet Protocol addresses (IP) are identified through devices or a local network to communicate with each other. (Kaspersky n.d)
ThousandEye (n.d) covers the difference between IPv4 and IPv6:

- **IPv4 (Internet Protocol version 4):** 
  
  The original version of Internet Protocol. IPv4 is a 32-bit address, carrying 2^32 addresses which is approximately 4 billion addresses. It is the primary IP version that is widely used carrying ‘94% of the Internet traffic’. (Lawrence Williams 2022)

- **IPv6 (Internet Protocol version 6):** 
  
  The newest version of Internet Protocol. IPv6 uses a 128-bit address, many times larger than IPv4. IPv6 addresses the shortages of Internet address due to IPv4.

### Routers and routing

Routers is a network device that forwards packets to their destination by connecting to another IP network or subnetworks and passing data packets. When the router receives a packet, the packet header is read to see the intended destination (cloudflare n.d). The routing table which the routing information is checked to find the best routing entry ( Marcin Bialy 2018). 
Abhishek Gupta (2018) mentions that Routing table can be static and dynamic.

- **Static Routing:** 
  
  It can only be set up and updated by the network administrator and is suitable to small networks

- **Dynamic Routing:** 
  
  It updates automatically and is suitable for large networks. Dynamic routers determine the shortest and fastest path through various protocols. 

### Domains and DNS

- **Domains:**
  
  The terms domain and domain name are interchangeable, referring to the location of a website. The length of a domain name can be up to 63 characters (Computer Hope 2017). The first word in a domain name, like 'google,' and the last word, such as '.com,' are referred to as top and second level domains. (Marshal Brain, Nathan Chandler & Stephanie Crawford 2021).

- **DNS:**
  
  The Domain Name System (DNS) connects devices and servers to the internet. To locate and load the webpage, it converts domain names into IP addresses (DNS Made Easy n.d). 'The DNS concept is like a phone book for the internet' according to Marshal Brain, Nathan Chandler, and Stephanie Crawford's (2021).

## Q3

#### TCP

Fortinet (n.d) states that ‘TCP is a communication standard to exchange messages over the network’. It is to ensure that the data and message is delivered successfully over the network (Fortinet n.d). Once the TCP client and server is established which the server can either accept or reject, the connection stays open until the connection is terminated by either client or server (TAL tech n.d). TCP splits the messages in packets from the server, numbers, and sends them to their destination (sdx central 2022).

#### HTTP and HTTPS

- **HTTP (Hypertext Transfer Protocol):** 
  
  HTTP is a client-server protocol used for viewing web pages on the internet (MDN 2021). HTTP uses port 80. Web clients are like web browsers such as google, safari, and Mozilla. The browsers are accessed by sending a request to the web server through HTTP protocol. Client sends a request and server responds by methods (Shreya Ghate 2020). In standard HTTP, information is sent in clear text, meaning all information exchanged through the client and server is transferred over the public internet, making it vulnerable to hacking.

- **HTTPS (Secure Hypertext Transfer Protocol):** 
  
  HTTPS has a security feature using TLS (Transport Layer Security), an improved version of SSL (Secure Sockets Layer) on HTTP. The data transferred are encrypted to ensure the data transferred between the client and server is secure and is no longer sent in clear text (_SSL, TLS, HTTP, HTTPS Explained_ 2018). A padlock would be included in the URL to indicate that website is secure on most browsers for HTTPS otherwise without the security feature they will be flagged as not secure (Cloudflare n.d). HTTPS uses port 443. 

#### Web browsers (requests, rendering and developer tools)

- **Request:** 
  
  A web request is a communication message sent from the client, or web browser, to the server to access resources which the server will then send a response (Source Defense n.d). 

- **Rendering:**

  Rendering is a web development process that converts website code into the interactive pages that users see when they visit a site. The word refers to the use of HTML, CSS, and JavaScript codes mainly. A rendering engine, the software that allows a web browser to render a web page, completes the process (Seobility n.d).

- **Developer tools:**

  Developer tools has software, platforms, and add-ons are common across browsers. They can help developers in producing high-quality code more quickly. The tools that help get rid of friction, distractions, and context switches (Elinor Swery 2021).

## Q4


## Q5

*Compiler and Interpreter: Compiled Language vs Interpreted Programming Languages* (2018) explains that the source codes, a high level language that can be understood by humans are converted into machine language which uses binary by either interpreter and/or compilers. 

- **Interpreter:** 
  
  The source code is copied, and the machine interprets ‘one statement at a time into machine code’ (BI India Bureau 2019). Therefore, the execution time is slower compared to compilers. It will continue to translate until there is an error message making debugging easier. Examples of Interpreted languages are Ruby and Python.

- **Compilers:** 
  
  The program is scanned and translated at once, creating a separate file containing the machine code. Error message appears only after it scans the complete program causing debugging to be harder. Compiled programming languages are C and C++, etc. (BI India Bureau 2019).
  
## Q6

**JavaScript**

- **Advantages:**
  
  JavaScript is a client-side script that runs quickly.  It is easy to learn and understand due to its simple structure.  It is a popular program among developers and is supported by all modern browsers. JavaScript can be embedded into any webpage or another programming language. Drag and drop functionality, and components like sliders, help to improve the site's user-interactivity.

- **Disadvantages:**
  
  People may exploit JavaScript code for malicious purposes, such as using the source code without authentication or disabling JavaScript entirely, due to a lack of client-side security. JavaScript is occasionally interpreted differently by different browsers. As a result, before publishing, the code should be checked in all main browsers (freeCodeCamp 2019).

**Ruby**

- **Advantages:**

  Ruby on rails is an open-source framework that is simple to learn due to its intuitive and user-friendly syntax features. It is also considered a secure technology due to its built-in securities and functionalities (Jakub Jakubowicz 2020). Because of the DRY rule, developers write less code while using RoR, which speeds up application development process. RoR has many open-source libraries which are called gems that enhance or extend the existing functionalities. RoR is supported by an active community of web developers.

- **Disadvantage:**

  There are less creativity, less flexibility due to many default, and set objects. Incorrect decisions made early in the development process can significantly slow down your entire application, cause connectivity issues between different parts of the software, and result in unintended effects (Victor Rak 2021). When compared to competing frameworks like Django and Node.js, RoR has a sluggish runtime speed and performance (Full Scale 2020).

## Q7

 
## Q8


## Q9


## Q10


## Q11


## Q12


## Q13


## Q14


## Q15


<<<<<<< HEAD
## Q16
=======
## `Q16`
>>>>>>> 3377087d444218220b7d8259317f3d1152dbf497
