# Simple-Flask-Project
This project encompasses a web application that processes and visualizes data obtained from the publications section of a personal website. The primary goal of the project is to extract data from the web page using the Selenium module, create a backend utilizing the Flask framework, and develop a frontend using the Jinja2 template engine.

Step 0: Identification of Data Source
Access was made to the Publications tab on my instructor's personal website, boracanbula.com.tr, and the work was carried out using this data.

Step 1: Data Retrieval
A Python file named publications.py was created. A class named Publications was established. A method was written using the Selenium module to extract data regarding my publications. Another method was created to save this data into a JSON file named data.json.

Step 2: Backend Preparation
A Python file named app.py was generated and designed as a Flask application. The Publications class from the publications.py file was imported. A function was crafted to read data from the JSON file and return a list of dictionaries containing information about my publications.

Step 3: Frontend Preparation
A template file named index.html was created, utilizing the Jinja2 template engine. Plotly.js library was imported into the index.html file. Data obtained from the backend was passed to the frontend to create a histogram showcasing the number of publications released each year.

Step 4: Year Histogram
A histogram illustrating the number of publications released each year was developed using the Plotly.js library.

Step 5: Authors Pie Chart
Using the Plotly.js library, a pie chart displaying the percentage of authors other than myself was generated.

Step 6: Final Step
A word cloud was generated from the titles of the publications and added to the visual dashboard. This process can be implemented both in the backend and frontend.
 

