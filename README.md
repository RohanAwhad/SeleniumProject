This is my Selenium project made for College miniproject submission. It has Django based website in website folder. 

Selenium testing has 3 sub methods
  *#Grid*
  *#Web Driver*
  *#IDE*

The project is also divided into respective folders.
To execute:

  **Starting project:<br />**
      cd Website/pollster
      ./manage.py runserver


  1. Grid:
      cd Grid/
      java -jar selenium-server-standalone-3.141.59.jar
      pytest -n 8

  2. WebDriver:
      cd WebDriver/
      python3 pollingTestSuite.py
      python3 loginTestSuite.py
