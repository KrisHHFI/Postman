# Postman

<img src="Postman Logo.png"/>

## About

- In this repository I will document different personal use cases for Postman
- Postman is software which allows us to test API end points. When targeting an end point we can try different HTTP methods like GET, PUT, POST and more. We can't do anything which isnt defined my the API. For example, if an API hasn't defined a function for adding new items, then we can't insert new there items with Postman.

<br>

## Local development environment

I made a browser based application named [React-Full-Stack-Project](https://github.com/KrisHHFI/React-Full-Stack-Project).
The project's back end uses Express.js and Node.js. 
The front end uses React. 
The project enables the user to create, edit and delete notes.
These notes are saved to a SQLite table.

<details>
<summary>GET Method</summary>

 <img src="React-Full-Stack-Project1.png" alt="React Full Stack Project image 1">
 Tested the root URL.

 ---
 
 <img src="React-Full-Stack-Project2.png" alt="React Full Stack Project image 2">
 Used the GET method to the "/notes" endpoint, which returned all the notes.
 
</details>

<details>
<summary>POST Method</summary>
 
 <img src="React-Full-Stack-Project3.png" alt="React Full Stack Project image 3">
 Used the POST method to the "/notes" endpoint. In the body I defined a new note. This added a new note to the table.
 
</details>

<details>
<summary>PUT Method</summary>
  
 <img src="React-Full-Stack-Project4.png" alt="React Full Stack Project image 4">
 Used the PUT method to the "/notes" endpoint. I defined the note ID in the URL, in this case it was 153. In the body I defined the updated note. This updated the note in the table.
 
</details>

<details>
<summary>DELETE Method</summary>
  
 <img src="React-Full-Stack-Project5.png" alt="React Full Stack Project image 5">
 Used the DELETE method to the "/notes" endpoint. I defined the note ID in the URL, again I used 153. This deleted the note from the table.

</details>

<br>

## Online API service (OpenWeatherMap API)

I previously used the OpenWeatherMap API in my [React Weather App](https://github.com/KrisHHFI/React-Weather-App). This app used a GUI to interact with the API. However, Postman can also be used to return the same data. So, I made the same calls I did in my weather app in Postman.

<details>
<summary>GET Method</summary>

 <img src="WeatherAPI1.png" alt="Weather API Image 1">
 Today's weather in Helsinki.

 ---

 <img src="WeatherAPI2.png" alt="Weather API Image 2">
 The forecasted weather in Helsinki.

</details>


