# CodingChallenge
URL Shortening Web App

How to run the Web App:













Context for Web App:

The language I used to build this web app in is Python. The framework is Django. I used Django for its ability to generate databases, and built in web app functions that integrate with html and css.

The algorithm I used to create the short link is straightforward. I validate the long URL provided by the user and then I generate a random sequence of 10 ascii characters. This gets turned into the short url. The short url is capable of redirecting a user to the original long URL.  The instructions to do the redirect are in the web app but I will paste them here as well:




The web app functionality:

- Have users enter a long URL, the system saves the URL and generates a short link
- Have users copy and paste the short link into their URL box to be redirected to the original long URL
- Users can click on either long url or short url links in the 'Saved Links' table
- All links are saved in a virtual environment database
- Have users enter a long URL and a custom short URL to create a custom short link.
