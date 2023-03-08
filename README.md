# API-for-Marvel
Retrieves information from Marvel's API, which includes details about comic books, characters, series, and other related content. The goal is to extract relevant character data from a given series using Python and store it in a structured format for further usage.

## Marvel Comics API
The [Marvel Comics API](https://developer.marvel.com/) allows developers everywhere to access information about Marvel's vast library of comics—from what's coming up, to 70 years ago. Through this API you'll be able to access six different ypes of resources, including comics, series, stories, events, creators and characters. You can read all about the different endpoints available by taking a look at the [documentation](https://developer.marvel.com/docs).

<img src='https://www.dropbox.com/s/fizr5sip3f55nhu/marvel.png?raw=1' width=1000>

## Steps
1. Create an account and log in to retrieve the keys
2. Generate 3 parameters: apikey, ts, hash
3. Generate functions that retrieve information of a single character by providing parameters (name): Make a request to the API for a given character to extract the link to the wiki webpage for that character, to request the HTML code underlying that webpage, to identify the link to the website that stores the IN COMIC FULL REPORT, and finally to extract different character attributes from this tab. 
4. Use the functions to extract information for all the characters in a given series
