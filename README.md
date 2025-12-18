BMI Calculator – Dockerized Deployment
A simple and responsive BMI (Body Mass Index) Calculator built using HTML and CSS, containerized and deployed using Docker.
This project demonstrates how to package and serve a static web application using Docker and NGINX.

-----------------------------Features-----------------------------

Responsive BMI Calculator UI

Lightweight static web application

Dockerized using NGINX

Easy to build and run anywhere

Ideal beginner DevOps + Docker project

------------------------------Tech Stack--------------------------

HTML5 – Structure

CSS3 – Styling

Docker – Containerization

NGINX – Web server

--------------------------Project Structure-----------------------

BMI_Calculator_with_Docker/
├── index.html
├── Dockerfile
└── README.md

-----------------------How to Run Using Docker---------------------
-> Clone the Repository
      git clone https://github.com/Aniket-kumar07/BMI_Calculator_with_Docker.git
      cd BMI_Calculator_with_Docker/
      
-> Build Docker Image
      docker build -t bmi-calculator .
      
-> Run Docker Container
      docker run -d -p 8080:80 --name bmi-app bmi-calculator
-> Access the Application
      http://localhost:8080
