title: Web Developement 101
---

# Introductory Guide to learn Web Development

# 101 to 2.0 Full Guide (Beta Version)
Last Updated on : Sep 09, 2020 (Under Development and writing Phase)

**Disclaimer:** This document has highly practical information and resources for you to learn about web using modern Project Based Learning(PBL) approch.
This document is not for exam clearing or passing point of view it is crafted for those who want to learn about the web using Agile Learning and hands-on projects. 


You will be taken to the web from developer point of view.
**Theory is supported by relevent memes and illustations for ease of understanding.**

## What is Web?
Web is an Internet based system that serves the purpose of sharing resources from one computing device with other.
**Web** in English means a network of interconnected elements. As we know many small computing devices are available on those devices and each node has specific value in the system to contribute to Internet. That is where Internet and Web seem similar.
Web works with many file formats but originally it was meant to avail readable files on internet which could be useful for others.
Today we use HTML (Hyper Text Markup Language) with other modern technologies to bring a beautiful User Experience.

## Why was Web needed?
When Internet started people wanted to share information and resources with other people using other computing devices but there was a problem that the computer or the device which servers the files has to be turned on all day and night for everyone to access specific resources which was not quiet possible with personal computers.
**Solution?** Some tech businesses started to help people and other small business to bring themselfs by making going to your resources and info easily available to any body 24*7. They created services where people can buy some space to put their content on a system which is connected to internet all time.



### Funfact: The Domain we search are not how the website is named or identified.
An IP Address is logged behind each running website or domain where the web traffic is sent.
An **Internet Protocol address** (**IP address**) is a numerical label assigned to each device connected to a [computer network](https://en.wikipedia.org/wiki/Computer_network "Computer network") that uses the [Internet Protocol](https://en.wikipedia.org/wiki/Internet_Protocol "Internet Protocol") for communication.
**Bonus**: Currently there are 2 Types of IP addresses.
- IPv4
![image](https://user-images.githubusercontent.com/33034184/89873941-ca334d00-dbd8-11ea-8bdf-682d6cbb6f40.png)

- IPv6
![image](https://user-images.githubusercontent.com/33034184/89874025-e636ee80-dbd8-11ea-937b-65280009de61.png)

**You can study about IP Addresses from other resources but for now just know that IP Address is behind each active domain.**


## How Web Works
![image](https://user-images.githubusercontent.com/33034184/89870514-943f9a00-dbd3-11ea-9c4d-e1f6c2a50f58.png )

### Interesting Note: Web is not limited to Websites.
Web is cosidered to be a place where you can find websites you need but for Developers it is more than that. Websites work with https:// (Port 443) or http://(Port 80) domains but under the hood websites communicate with APIs or Websockets to fetch data and resources from other services also.
**All the smart phone apps that we use communicate with a server which is hosted on the Web using Domain which has server IP.
That is how we can access same data over the Phone Apps or Web-based apps as the Server is not client side dependent any type of device can ping server if the developers want.
**

## What is Client Side
Client Side is anything that pings the website and uses it. User uses Website using Client like Web-browsers from various available devices.

## What is Server Side
Anything that happens related to logic of the service or the backend it is done on the server side.

## Where is Programming
There are different programming languages for various purposes in Web Dev and some do fulfill 
many purposes.
**Client Side Progamming** 
HTML and CSS are just the Structure and Design parts of Website which cannot be considered as programming laguages as we donot write logics in HTML and CSS.


 They are in simple words controlled by JavaScript to function in intractive manner.
**Laughter Warning !**

<img  src="https://user-images.githubusercontent.com/33034184/89984984-eba73e00-dc97-11ea-8c06-aba803e30d61.png"  alt="web dev 101"  title="Web dev Memes"  width="300"  height="auto" />

<img  src="https://user-images.githubusercontent.com/33034184/89984909-c6b2cb00-dc97-11ea-853a-de6bd5e37430.png"  alt="web dev 101"  title="Web dev Memes"  width="300"  height="auto" />




JavaScript is the language which executes in user's browser to provide the functionality to smooth and interative websites.


## Server Side Programming

**Programming logic and business logic of a site resides on Server Side. Server Side Programming languges are**
 - PHP 
 - Java(Spring Boot)
 -  Python (using Django or Flask Web Dev
   Frameworks) Note: Python Frameworks can also manipulate client side pages. 
   - NodeJS
   These languages help the developer write the logic for backend or server side.
   **Note that Backend languages can be used for building API's for your project too.** 
   

## What is Server
Server serves the desired Webpage or API for users. Server is nothing but a port that runs and serves what the Developer has coded.
**If you are a developer, You will be working simulating the server on your local machine to develop the desired functioning of server.**

### Where is server kept
Server itself is a specifically configured Computer/PC usually runs on Linux OS and can also run Windows or Mac but practically Linux is useful and widely used, now server has a port opened for public to access it's resources.

Server is a running service on a port of an IP address which allows web traffic to use it's resources.


**What is Port and opened port**
This is an important element of servers and website.

**Port** :
Computers do **not** have ports. 
 Think of it as a virtual place which is available for specific service. If you want to access files on the web you go to port 443(https) or 80 (http) traffic. If you wish to run a database on the server you will be given a 3306 Port Number in case of MySQL.
There are total of 65535 Ports available on a system/PC's Networking Layers.
**Opened Port:** The networking protocols like TCP and UDP need the source and destination port to send data to specific service. 

Port is always assigned with IP address for Network devices to identify sender and reciever.
General Format to hit a IP at specific Port
**IPADDRESS:PORT (192.168.90.255:5005)**
**Try This**
[https://www.google.com:80/]
This is Google server's port 80 means http means the we are hitting the google IP@ Port 80.
Google has configured their server to not use port 80 as the data is not secured over port 80.
You can read about difference between http and https from the web in case and know how https is secure.

<img  src="https://user-images.githubusercontent.com/33034184/89976334-c8739300-dc85-11ea-90c9-09138ae70e70.png"  alt="web dev 101"  title="Web dev"  width="300"  height="auto" />


**Now Test This**
This is where our google request is served. Port 443 open for HTTPS request/traffic
[https://www.google.com:443]
(https://www.google.com:443)
By Default Modern Browsers take us to PORT number 443 to achieve https but if we donot have https enabled in our site/server browser then tries port 80 and shows we are using unsecured connection.
**More on this will be discussed in coming steps.**

**Loads normal Google**


**Why 65535 Ports to be specific**

The concept of "ports" is strictly related to the [TCP](https://en.wikipedia.org/wiki/Transmission_Control_Protocol) and [UDP](https://en.wikipedia.org/wiki/User_Datagram_Protocol) protocols of the [TCP/IP networking stack](https://en.wikipedia.org/wiki/Internet_protocol_suite). From a strictly technical point of view, both TCP and UDP are structured in such a way as to carry several kinds of information (Source port, Destination Port, Sequence Number, Data, etc.). As both "Source port" and "Destination port" are structured (within the TCP and UDP packet) with a 16 bit "field", here are the limits: source ports and destinations ports can assume all the values that can be represented with 16 bits (aka: from 0 to 65535);

**0 to 65535 'cause they are both represented with a 16 bit value.**

<img  src="https://user-images.githubusercontent.com/33034184/89870937-3cedf980-dbd4-11ea-88df-c72e73fa0e33.png"  alt="web dev 101"  title="Web dev"  width="400"  height="auto" />


#### We are yet to get introduction to Linux and how you will be using Linux to host your site.
Hosting means putting the site live on ports 80, or 443 on internet. 
**Think of Hosting as someone else's computer which can be used as a paid service by you and most importantly it hosting systems are configured to get a static ip and are 24*7 available.**
This is a business of the web. Linux machines are available to use as provided by hosting providers at different costs and machine hardware configurations like RAM and storage.
Linux hosting is not the only option as mentioned earlier but for now keep it to linux. 

**Does that mean you need hosting to start building your website?**
No, not yet!
### **Did you know about localhost or 127.0.0.1**
As developers we need to make our website on our available OS or System so we simulate the server on our local OS and build and test the website on local network before starting to pay for a hosting service.
Like all other Linux hosting machines all of computers have basics networking functionality to run local services. The only difference in your personal computer and Hosting service machines is that it is up all day and night with stable internet connection until you can pay .
Your personal Computer can be your server till the time you can keep it turned on.

## How will I make my PC become server for my development?
You will need what's called a Web-Server Software which will make your pc a server for you and your other network devices connected on the same network.
Keep Reading this document and you will reach on the step for using that software and know that there are many ways to start a local server using different Web-server softwares.


### Wow! You made it to practicals now!

**Congratulate yourself as you now have basic understanding of the web and know what are major components in building your own Web-based solution or Website**

### Let's Begin :-)

## Development 101


### Choose IDE you like
IDE is an Advanced text-editor specifically built for writing code. IDE helps us with simple tools to ease the workflow and manage the code.

***Le Beginners**
<img  src="https://user-images.githubusercontent.com/33034184/89989266-59566880-dc9e-11ea-838a-3a3575e45417.png"  alt="web dev 101"  title="Web dev"  width="250"  height="auto" />


Most of us Visual Studio Code 
> **Install a IDE like Atom or Visual Studio Code**
> [https://code.visualstudio.com/]
> [https://atom.io/](https://atom.io/)


## The Subtle art of Googling

> Everything you are trying to do it already done by someone on the web.

**Just enter your errors or question on google and the many resources will be given to you right a way.**

Example Doubt:
Case: I am developing a webpage where users can run a JavaScript function or script after clicking a button which will do a task. I know that a button element is needed using which should run a funtion so my search could be
"how to listen to html button click using js"
or "how to run js on html button click"
<img  src="https://user-images.githubusercontent.com/33034184/90005586-0e941b00-dcb5-11ea-8b7b-e7d80ca892ae.png"  alt="web dev 101"  title="Web dev"  width="400"  height="auto" />

<img  src="https://user-images.githubusercontent.com/33034184/90005707-35525180-dcb5-11ea-90d6-f24adfaf5445.png"  alt="web dev 101"  title="Web dev"  width="400"  height="auto" />



### Meme Alert!
<img  src="https://user-images.githubusercontent.com/33034184/90006177-0b4d5f00-dcb6-11ea-9185-b0ea303a402b.png"  alt="web dev 101"  title="Web dev"  width="350"  height="auto" />

<img  src="https://user-images.githubusercontent.com/33034184/90006203-11dbd680-dcb6-11ea-9e2d-35b8041b3045.png"  alt="web dev 101"  title="Web dev"  width="300"  height="auto" />

<img  src="https://user-images.githubusercontent.com/33034184/90006229-228c4c80-dcb6-11ea-8904-e5e71289cffa.png"  alt="web dev 101"  title="Web dev"  width="300"  height="auto" />





## Learn HTML CSS
There are many resources to learn Basics you can find many on the web. 
**Note that You should try building it on your personal PC so you can learn by doing**
https://www.w3schools.com/html/](https://www.w3schools.com/html/)
[https://www.w3schools.com/html/html_css.asp](https://www.w3schools.com/html/html_css.asp)
[https://www.w3schools.com/html/html_scripts.asp](https://www.w3schools.com/html/html_scripts.asp)


Understand HTML, CSS and JS Roles
<img  src="https://qph.fs.quoracdn.net/main-qimg-d46874fe1c78ad54e201c24a81ed4a40"  alt="web dev 101"  title="Web dev"  width="400"  height="auto" />


## Project #1 Alert!!!!

### Rollup your sleeves...Now You need to get started
<img  src="https://user-images.githubusercontent.com/33034184/90006560-be1dbd00-dcb6-11ea-848a-1f0fec840d1e.png"  alt="web dev 101"  title="Web dev"  width="250"  height="auto" />


## Action Project #1 

### Make Static Website and Deploy using Github Pages
Using Github Pages and deploying your own static website will help you build your desired HTML CSS Template Based.

You will use, learn and work on:
- HTML
- CSS (divs , classes , import css and fonts)
- JS imports
- Downloading a predesigned web page and customizing it (Bootstrap Templates in short)
- Setting up an IDE for your project development.
- Creating Github Account and Basics of Git
- Deploy your first website on internet using Github Pages(Static Site)

### Step 1: Download Visual Studio Code (VSCode)  


### Step 2: Install an Extension named Live server in VSC

### Step 3: Make your project Dir
It is recommended that you make a Directory/Folder on your system which you will only use for development related work like "DevelopmentProjects", "Coding" or any cool name you wish.
Now understand that each one of your project will have a folder dedicated to it. So when you do this project make a folder named whatever you like.

### Step 4: Open the Folder in VSCode and create a hello world HTML File.

### Step 5:Now Learn how to open an HTML Page in browser.

There are 2 ways to open your html page in browser
Run The live Reload server or paste path in web browser

### Step 6: Now Download the Pre-designed Bootstrap Template
#### What is Bootstrap Template
It is like someone has already done basic UI design so you can build your website elements using that.

Some suggested Templates:

 - [https://bootstrapmade.com/free-html-bootstrap-template-lonely/](https://bootstrapmade.com/free-html-bootstrap-template-lonely/)
 -   [https://bootstrapmade.com/devfolio-bootstrap-portfolio-html-template/](https://bootstrapmade.com/devfolio-bootstrap-portfolio-html-template/)

**You can Explore more from here**

 - [https://bootstrapmade.com/bootstrap-portfolio-templates/](https://bootstrapmade.com/bootstrap-portfolio-templates/)

 - [https://colorlib.com/wp/cat/portfolio/](https://colorlib.com/wp/cat/portfolio/)

### Step 7: Extract Downloaded Template and Copy to the project folder you created
Folder Downloads as .zip file so you will need to Extract to proceed.

### Step 8: Launch it on you local using Step #5 options

### You should see the working page like you did on the web preview when you downloaded

#### Open the code files of downloaded project in VSCode


## Now YA OYO(you are own your own)
Play with the code and make it look like yours.
Add you images, Text make it cool. You can always use the art of googling to clear your doubts.
Add Your Social Media Handles and make it professional.

### Hyyyy Now what? Don't you want your friends to see our personal website live?

### 

    If (yes){
    print("Fasten your seat belts now we are going in the Realm of Git.");
    }
    else{
    print("As you wish");
    }

**Git or Github may seem a intimidating at first but when you know it's uses and Advantages you will never look back.**

Create an account on Github it is developer's Linkedin.
### Learn Git from any of these YT tutorials or watch other videos you like on YT
[https://www.youtube.com/watch?v=iR5WIknxdkY](https://www.youtube.com/watch?v=iR5WIknxdkY) (Hindi)

[https://www.youtube.com/watch?v=0fKg7e37bQE](https://www.youtube.com/watch?v=0fKg7e37bQE) (English)

[https://www.youtube.com/watch?v=SWYqp7iY_Tc](https://www.youtube.com/watch?v=SWYqp7iY_Tc)  (English)
### Following Image can be kept handy to use Git Commands
![image](https://user-images.githubusercontent.com/33034184/84883173-dbb31980-b0ad-11ea-8d59-1b89b2004793.JPG)





## Action Project #2 


## Realtime Instagram Follower Counter.


You will learn about AJAX Request and JavaScript DOM Interaction.
[https://gist.github.com/rahulshyokand/ea12f3817a05f71b55fc3013dd4e2630](https://gist.github.com/rahulshyokand/ea12f3817a05f71b55fc3013dd4e2630)





# AJAX
<img  src="https://user-images.githubusercontent.com/33034184/89857884-e1fbd880-dbba-11ea-9562-abc2e46db8c8.png"  alt="web dev 101"  title="Web dev"  width="500"  height="auto" />




## Action Project #3
Playing with User inputs in forms and storing in Database.


## What are Databases?
Database is a service which helps in management and storage of Database.A database is useful if you woould want to store information of users and help them back when they need.
Almost all websites we use store user data for various purposes. Like most websites need us to login to there system and so we can do specific operation with an identity like Email or Username.
In simple terms an entry in database is made when we create an account on a web-based or a software based platform. When we login the program checks if user with the given username or password exists in database and accordingly we can proceed.

### There are many Databases available in market but there are 2 main types of DBs

Relational DB or NoSQL (Structured or Unstructured DBs)
 
 For Now understand that RDBMS is like an advanced EXCEL Sheet which can be accessed using all Server Side programming languages as the DB is on the Server Side.
 
## MySQL 
(Basic RDBMS) for Starting


[https://www.tutorialspoint.com/mysql/index.htm](https://www.tutorialspoint.com/mysql/index.htm)

## Deploy - Yet to be written


## Linux OS Basics
- Making Directories 
- Accessing Linux using SSH using git commands on Linux to handle production server deployments of Code
- Installing Python / Django on Linux 
- Bash Scripts 
- Start Django App after Linux VM Reboot