# YelpCamp

The Campground Version of Yelp


```
git clone https://github.com/gpldirk/ShareCamp.git
```


### modify the example.env to .env file, adding all the required fields

Cloudary api key and secret for image storage \
CLOUDINARY_API_KEY= \
CLOUDINARY_API_SECRET= 

Google geocoder api key to find the location on google map \
GEOCODER_API_KEY=

OpenWeather map api to get the weather information of the location \
weatherApiKey=

MongoDB data storage \
MONGO_URI=


### modify the "views/campgrounds/show.ejs"
```
<script async defer src="https://maps.googleapis.com/maps/api/js?key=" + process.env.GEOCODER_API_KEY + "&callback=initMap"></script>
```
addd GEOCODER_API_KEY

```
npm install
```

```
nodemon app.js 
```

open http://localhost:3000 to see website.
