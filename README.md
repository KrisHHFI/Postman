# Postman

<img src="Postman Logo.png"/>

## About

In this repository I will document different personal use cases for Postman

## Local development environment

I made a browser based application named [React-Full-Stack-Project](https://github.com/KrisHHFI/React-Full-Stack-Project).
 The project's back end uses Express.js and Node.js. 
 The front end uses React. 
 The project enables the user to create, edit and delete notes.
 These notes are saved to a SQLite table.

Use case:

### GET Method

<img src="React-Full-Stack-Project1.png" alt="React-Full-Stack-Project1">
Tested the root URL.

---

<img src="React-Full-Stack-Project2.png" alt="React-Full-Stack-Project2">
Used the GET method to the "/notes" endpoint, which returned all the notes.

---

### POST Method
<img src="React-Full-Stack-Project3.png" alt="React-Full-Stack-Project3">
Used the POST method to the "/notes" endpoint. In the body I defined a new note. This added a new note to the table.

---

### PUT Method

<img src="React-Full-Stack-Project4.png" alt="React-Full-Stack-Project4">
Used the PUT method to the "/notes" endpoint. I defined the note ID in the URL, in this case it was 153. In the body I defined the updated note. This updated the note in the table.

---

### DELETE Method

<img src="React-Full-Stack-Project5.png" alt="React-Full-Stack-Project5">
Used the DELETE method to the "/notes" endpoint. I defined the note ID in the URL, again I used 153. This deleted the note from the table.

