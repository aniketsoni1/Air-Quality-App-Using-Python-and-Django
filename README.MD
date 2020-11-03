Air Quality Weather App
---
This application tells users the air quality for any zip code they type into the search box. This project is built using Python Django Web framework on the backend and HTML, CSS, Bootstrap and JavaScript on the frontend. And AirNow's API (https://www.airnow.gov/) for to get the air quality data.

Use this app: https://airquality-app.herokuapp.com/

### Setup
- This project runs on Python 3 and Django 3.0
- Install all the dependencies from `requirements.txt`
- Once you are done with installation go to your terminal and type `python manage.py runserver` and you should see python server start.
```
Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).
June 16, 2020 - 01:28:32
Django version 3.0.7, using settings 'weather.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.

```
For deployment on heroku, follow the code by checking out `heroku` branch.

### Using the app
Go to the search bar and enter any zip code and it tells you about the air quality of that region.

- For example: If iniital webpage is below and you enter `11209`and press `Lookup`:
![](https://github.com/aniketsoni1/Air-Quality-App-Using-Python-and-Django/blob/master/images/lookup.JPG)

- AirNow API gets called and webpage is updated as below:
![](https://github.com/aniketsoni1/Air-Quality-App-Using-Python-and-Django/blob/master/images/lookup2.JPG)

- Error handling for invalid zip codes and unavailable data:
![](https://github.com/aniketsoni1/Air-Quality-App-Using-Python-and-Django/blob/master/images/lookup4.JPG)

- Mobile optimized view:
![](https://github.com/aniketsoni1/Air-Quality-App-Using-Python-and-Django/blob/master/images/lookup3.JPG)
