Flickzilla is a cinema booking system made by Mohamad Fawaz, Ali Nahle, Wafik Safa and Abdelsalam Mahari
This website provide solutions booking inside cinemas and make it easier for cinema owners to make and adjust there
movie rooms as they like depending on the time that the movie is going to be displayed.

in this website we used OMDB,IMDB apis and the MERN stack.

to run the project you can clone this repository using (git clone https://github.com/AbdelsalamMahari/flickzilla.git)
where each one of us has his own branch 

REQUIREMENTS TO RUN THE PROJECT:
1-npm install inside server and client folder once the repository is cloned

2-inside the server folder create a .env folder and add in:

-MONGODB_URL="your mongodb connection link"
-SECRET_KEY = "zadbfflx3"(random numberand letters for nodemailer and jwt,u can change it)
-PORT = 5000
-API_KEY = api key for imdb that you can get from "https://developer.imdb.com/documentation/api-documentation/getting-access/"
-GOOGLE_APIS = google api key that you can get from google services
-TMDB_API = tmdb api key that you can get from "https://developer.themoviedb.org/reference/intro/getting-started"
-JWTPRIVATEKEY = jwt private key that you acquire from the jwt documentation 
-SALT=10
-BASE_URL = http://localhost:3000
-HOST = smtp.gmail.com
-SERVICE = gmail
-EMAIL_PORT = 465
-SECURE = true
-USER = add in your own email
-PASS = Your email's password
-CLIENT_ID = client id provided by the google api above
-CLIENT_SECRET =client sercret key provided also by the google api
