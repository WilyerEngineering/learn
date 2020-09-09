title: Instagram API Project
---

# InstaGram Live Followers Counter
## Building a Live Instagram Followers Counter Website

## Why to build this?
#### There is no exact reason as to why you would want to build such a system even when many sites are available which do the same. 
### But 
 If you are curious about web-technology and want to know how it works this project will teach you all the components that are to be taken in mind while building a Web-based Application which also communicates with an API (Application Programming Interface) - donot get confused with this API just means you can send a request to the server and a valid and relevent data as per the request will be recieved in response as **JSON Format** which can be parsed in Any programming language.
 ## Following Image may be helpful to understand the flow.
![image](https://user-images.githubusercontent.com/33034184/89768962-00f65e00-db1a-11ea-921e-1974397cd7bc.png)


## What Tech will I learn?
### This is the ultimate Goal so you get gist of how web-tech is built and works.

Following are the Technologies and Stacks that you will be working on:
- ### Format JSON Intro and Basics
- ### Github
- ### HTML , CSS (Bootstrap based Design)
- ### JavaScript (Extaracting data from JSON Object, Creating a JSON object to send to the server)
- ### Sending POST/GET Requests using JQUERY (Optimsed JS Lib) and making and Handling AJAX Request and JSON Response parsing.
- ### JavaScript DOM (HTML UI) Changing and Accessing data from Forms
- ### Getting overall familier with JS Event Listners and Funtions
- ### Understanding of How websites work
- ### !****_Git Version Control System for Deployments Very important in Software Development_****!
- ### You will gain confidence to build any web-based project which works with APIs and brings Dynamic Content.



### Useful Resources

 - Open and Free JSON data based API for getting live Details of an account 
   [https://www.instagram.com/rahulshyokand/?__a=1](https://www.instagram.com/rahulshyokand/?__a=1)

- BootStrap for Page Design [https://getbootstrap.com/](https://getbootstrap.com/)
- Github for maintaing Code and Workflow
- JSON Data Visiualizer
[http://chris.photobooks.com/json/default.htm](http://chris.photobooks.com/json/default.htm)

### Similar Current Websites

- https://instastatistics.com/
- [https://counts.live/instagram-follower-count](https://counts.live/instagram-follower-count)
- [https://www.instafollowers.co/instagram-follower-count](https://www.instafollowers.co/instagram-follower-count)
- [https://realtimefollowers.com/](https://realtimefollowers.com/)
- [https://famoid.com/instagram-follower-count-checker/](https://famoid.com/instagram-follower-count-checker/)
- [https://socialblade.com/instagram/user/instagram/realtime](https://socialblade.com/instagram/user/instagram/realtime)

#### Well there are many sites that do this but they do lack in user Experience. Can be build our own and deploy it... Anyways our priority is Learning


### Main Features

- #### Beautiful Card based UI
- #### Show Profile Photo from JSON
- #### Show Name, Username and Blue Tick if yes
- #### Show Number of Posts made by account
- #### Show a Count up or Down based animation after follower change
- #### Show Famous Insta Accounts so user can demo how the system works
- #### Smooth Design 
- #### Show Site Visitor Counter
- #### Make PNG Image Fly when new followers are detected

### Note : There could be many features that it can have but list given above is minimal thing that it should have.

 
# Development Guide - 101

# Practical Steps to Build it

### Learning Material
Each Step has Learning Material for understanding and working on the Given Step. 


## Step 0: Choose IDE you like
- ### Most of people Visual Studio Code
> **Install a IDE like Atom or Visual Studio Code**
> [https://code.visualstudio.com/]
> [https://atom.io/](https://atom.io/)
> [https://www.sublimetext.com/](https://www.sublimetext.com/)

- ### Github, Git Repo Basics
Github/Git is an indirect gift you will get if you follow this document. Following Video will be a good place to set Github Repo for this project.
[https://www.youtube.com/watch?v=iR5WIknxdkY](https://www.youtube.com/watch?v=iR5WIknxdkY)

## Step 1: Design (HTML, CSS using Bootstrap Template)

You will need following material.
### Learning Material for (HTML, CSS) Basics
There are many resources to learn Basics you can find many on the web...
**Note that You should try building on your personal PC so you can learn by doing**

Following HTML Resources may be useful but you can always learn HTML CSS using Google.
[https://www.w3schools.com/html/html_css.asp](https://www.w3schools.com/html/html_css.asp)
[https://www.w3schools.com/html/html_scripts.asp](https://www.w3schools.com/html/html_scripts.asp)

### HTML CSS Task
We need a Bootstrap Template to start out work.
We need to play with Bootstrap Elements to get gist of how it works.
There are many templates available We also have a template which we can play with.
We have Dummy Design and we have to play with this and design as per desired UI we need.

**Use your HTML CSS Skills to place the elements in your fav design.**
Following are the Examples for UI Inspiration

![image](https://user-images.githubusercontent.com/33034184/89869598-33fc2880-dbd2-11ea-8fb3-ff3a4cc794aa.png)

![image](https://user-images.githubusercontent.com/33034184/89780405-04481480-db2f-11ea-809a-202cf94ec86f.png)
![image](https://user-images.githubusercontent.com/33034184/89780475-25106a00-db2f-11ea-8adc-2602f7820a3e.png)



## Step 3 : Now let's make those input buttons intractive.

### !!JavaScript Tutorial
Donot Download NodeJS as shown in the video as you will not need it for now.
[https://www.youtube.com/watch?v=W6NZfCO5SIk](https://www.youtube.com/watch?v=W6NZfCO5SIk)







## Hiding Elements Onclick



## Step  : API Intergration
**What is API?**
API is a web service which is available on a Web address(IP or Domain Name) to do specific action like creating a new user account, getting information of a specific username.
An API provides us access to the data as per request we send.
Example : [https://www.instagram.com/username/?__a=1](https://www.instagram.com/rahulshyokand/?__a=1)
Above URL is a Path where the Instagram Open API (Unofficial Term) serves the request which contains a Username to get details of.

### Can You Write Your Own API?
Yes! You will need to make your Project's API in Action Project #3. For Now You will just be interacting with an Existing API to learn.

### What is a Request

### There are 2 types of Requests
**GET Request:**

**POST Request:**

There are other requests also but for now GET and POST knowledge should serve the purpose.

### We will be communicating with open Instagram API using JQUERY AJAX Request
Then filter needed data from JSON using JavaScript
Following Image is Demo of Insta API.


### What is JSON
JSON is a format in which we can get data from any API and transfer some data using Requests.
[https://www.youtube.com/watch?v=iiADhChRriM](https://www.youtube.com/watch?v=iiADhChRriM)

![image](https://user-images.githubusercontent.com/33034184/89780763-ad8f0a80-db2f-11ea-818c-a182acda83cf.png)


[https://www.instagram.com/username/?__a=1](https://www.instagram.com/username/?__a=1)

Copy the response to [http://chris.photobooks.com/json/default.htm](http://chris.photobooks.com/json/default.htm)
and hit render to understand available data

# Git for Collaborative Development

### Github, Git Repo Basics
[https://www.youtube.com/watch?v=iR5WIknxdkY](https://www.youtube.com/watch?v=iR5WIknxdkY)





