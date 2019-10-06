This is my Selenium project made for College miniproject submission. It has Django based website in website folder. 

Selenium testing has 3 sub methods
  ***Grid***
  ***Web Driver***
  ***IDE***

The project is also divided into respective folders.
To execute:<br />

  **0. Starting project:<br />**
      cd Website/pollster<br />
      ./manage.py runserver<br />
  **1. Grid:<br />**
      cd Grid/<br />
      java -jar selenium-server-standalone-3.141.59.jar<br />
      pytest -n 8<br />
  **2. WebDriver:**
      cd WebDriver/<br />
      python3 pollingTestSuite.py<br />
      python3 loginTestSuite.py<br />
