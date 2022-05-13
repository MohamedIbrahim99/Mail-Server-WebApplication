# Mail-Server-WebApplication

- Designed a Gmail-like web application using OOP concepts and Design Patterns. 
- Developed different web pages using Web API Routing. Implemented a REST API for the website. 
- Implemented the basic functionalities of a mail server, including manipulation of mails and contacts like : 
  - Sending mails, receiving mails and also dividing them into folders. 
  - Delete, filter, search for mails and contacts.
  - Add, edit and remove contacts.


- Back-end with Java spring-boot. 

- Front-end with Vue.js.
- Objective : Applying principles of oop and design patterns.
- We are team of 4.
 
 
 ## Design Patterns Used

 1- proto type : when we need to copy an email and send it to user or if we need to add it to another folder of user’s folder.

 2- adapter : used to convert get the user the suitable page of emails where the user enters the page number and the adapter converts it into start and end index and get them from required folder.

 3- iterator : when we need to iterate over a list of users , emails , Folders so we get an iterator over them and iterate as we want.

 4- Proxy : when we need to deal with emails by sending or deleting or editing and contacts by crud and also with users with crud operations.

 5- filter : to filter emails according to subject and sender and importance and emailAddress and other attributes.

 6- facade : after we end our classes we need to collect them to the facade to ease the user’s control to the program where he can call only one function that calls many functions.
 
 
 ## Class Diagram
 
 
 
 ![image](https://user-images.githubusercontent.com/61321123/168186528-7d62e183-cbc8-4813-8b73-8afb6f27e64f.png)



## Videos 

- Screen Video for the application & Design explanation :

https://drive.google.com/drive/folders/10TGRFntbYzBfz1X-1cza9hY7tqgyEJl9?usp=sharing

 ## How to run the program :

1. run the back end program from any spring boot IDE in port 8080.

2. Open the file of  front end from terminal and run: 
npm run serve   
(should be in Port 8081)




*for more information about the program -like the UML, how we have applied design patterns and Snapshots of the program- you can check the pdf file "Project proposal".*https://github.com/MohamedIbrahim99/Mail-Server-WebApplication/blob/main/Project%20proposal.pdf
