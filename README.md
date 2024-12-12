# Quiz App

A quiz web application where users can participate in a quiz session, answer questions, and view their scores. Developed using Spring Boot, H2 Database, HTML, CSS, JavaScript, and Bootstrap.

*API, CRUD, Spring Boot, H2 Database, Quiz App.*



---

### Start Page

![Start Page](https://raw.githubusercontent.com/DevRezaur/spring-boot-quiz-app/main/screenshots/Start%20Page.PNG)

### Quiz Page

![Quiz Page 1](https://raw.githubusercontent.com/DevRezaur/spring-boot-quiz-app/main/screenshots/Quiz%20Page%201.PNG)

![Quiz Page 2](https://raw.githubusercontent.com/DevRezaur/spring-boot-quiz-app/main/screenshots/Quiz%20Page%202.PNG)

### Result Page

![Result Page](https://raw.githubusercontent.com/DevRezaur/spring-boot-quiz-app/main/screenshots/Result%20Page.PNG)

### Score Board

![Score Board](https://raw.githubusercontent.com/DevRezaur/spring-boot-quiz-app/main/screenshots/Score%20Board.PNG)


---

### Table of contents 📃

- [Quiz App](#quiz-app)
  - [Table of contents 📃](#table-of-contents-)
  - [Starting 🚀](#starting-)
    - [Pre-requirements 📋](#pre-requirements-)
    - [Installation 🔧](#installation-)
  - [API Endpoints](#api-endpoints-)
  - [Built with 🛠️](#built-with-️)

---

## Starting 🚀

### Pre-requirements 📋

* [Java JDK 17+](https://www.oracle.com/java/technologies/javase-jdk17-downloads.html)
* [Maven](https://maven.apache.org/)
* [Git](https://git-scm.com/)

---

### Installation 🔧

1. Clone the repository:

    ```bash
    $ git clone https://github.com/Ashish23jun/quiz-app.git
    $ cd quiz-app
    ```

2. Build and run the application:

    ```bash
    # Build the application
    $ mvn clean install

    # Run the application
    $ mvn spring-boot:run
    ```

3. Access the application in your browser at [http://localhost:8080](http://localhost:8080).

---

## Built with 🛠️

* [Spring Boot](https://spring.io/projects/spring-boot) - Backend framework  
* [H2 Database](https://www.h2database.com/) - In-memory database  
* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) - Frontend structure  
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) - Styling  
* [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) - Frontend logic  
* [Bootstrap](https://getbootstrap.com/) - Frontend framework  

---

## API Endpoints
1. **Start Quiz Session**

   **Endpoint:** `POST /quiz`  
   
2. **Submit Answer**

   **Endpoint:** `POST /answer`

    
3. **Get Quiz Result**

   **Endpoint:** `POST /results`
---


   
