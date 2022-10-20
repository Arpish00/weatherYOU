# weatherYOU

#### Video Demo:  <URL HERE>
#### Description:
It's a simple weather forecasting web application made with React.JS and highly responsive single html page website.
![Logo](https://i.postimg.cc/VNW6VQV6/Pics-Art-10-11-05-38-40.png)

It uses openweathermap API to get data of weather and show it in html file,
The Ui is quite simple:

![ui](https://i.postimg.cc/R0zmnzDt/Web-capture-19-10-2022-23248-localhost.jpg)

The basic structure of this web app is as below:

![structure](https://i.postimg.cc/jSSgg3n1/Screenshot-9.png)

Inside of weatheryou directory it includes public and src folders.
Inside public index.html take place, and src contains all the files needed to included in index.html.

![src](https://i.postimg.cc/PrSs5wmB/Screenshot-12.png)

Components are the each small elements of website devided separately into different jsx files.
The Services is main Javascript folder for calling data from API and assigning them to individual variables and exporting them for later use in Components and app.js. For CSS it uses the tailwind CSS.

#### overview:
If the API key gets the necessary data than the by default the weather, Time-Date, Forecast data will shown for Berlin, you can change that by either clicking any of cities mentioned under Logo or you can search for city in search bar or you can get your local forecast by clicking location button next to serach button.

Time and Date mentioned under serach bar and below this you can see city name and county.

Overall weather status is mention after that, And Temperature in default metric which can be changed by Unit button next to location button. Real fell, Humidity, Wind speed is indicated next to Temperature for selected city. Below that Sunrise, Sunset, Highest Temperature , Lowest Temperature indicated.

**If the temperature gets higher than 20° than page will change it's color to orange itself.**

![Ui](https://i.postimg.cc/GmWHX2XS/Web-capture-19-10-2022-2336-localhost.jpg)

At the bottom hourly and daily forecast has been shown along with the icon depending on weather.
