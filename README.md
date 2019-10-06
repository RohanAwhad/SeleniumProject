This is my Selenium project made for College miniproject submission. It has Django based website in website folder. 

Selenium testing has 3 sub methods<br />
  ***Grid<br />***
  ***Web Driver<br />***
  ***IDE<br />***

The project is also divided into respective folders.
To execute:<br />

&nbsp;&nbsp;**0. Starting project:<br />**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;cd Website/pollster<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;./manage.py runserver<br />
&nbsp;&nbsp;**1. Grid:<br />**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;cd Grid/<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;java -jar selenium-server-standalone-3.141.59.jar<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;pytest -n 8<br />
&nbsp;&nbsp;**2. WebDriver:<br />**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;cd WebDriver/<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;python3 pollingTestSuite.py<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;python3 loginTestSuite.py<br />

