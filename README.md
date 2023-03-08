# API-for-Marvel
Retrieves information from Marvel's API, which includes details about comic books, characters, series, and other related content. The goal is to extract relevant character data from a given series using Python and store it in a structured format for further usage.

## Marvel Comics API
The [Marvel Comics API](https://developer.marvel.com/) allows developers everywhere to access information about Marvel's vast library of comics—from what's coming up, to 70 years ago. Through this API you'll be able to access six different ypes of resources, including comics, series, stories, events, creators and characters. More information about the different endpoints available at the [documentation](https://developer.marvel.com/docs).

<img src='https://www.dropbox.com/s/fizr5sip3f55nhu/marvel.png?raw=1' width=1000>

To use the Marvel API, authentication is required. This involves generating an API key, which can be obtained by creating an account on the Marvel Developer Portal. The API key is used in combination with a timestamp and a hash to authenticate each request.

## Implementation
The project will be implemented in Python, using the requests library to make HTTP requests to the Marvel API. The extracted data will be stored in a structured format, such as a Pandas DataFrame or a CSV file.

## Data Extraction
The primary goal of this project is to extract relevant character data from a given series. This will be achieved by first identifying the characters present in the series and then making a request to the API for each character. The response will include information about the character, such as their name, link to the wiki webpage, and a list of their apperance characteristics.

To extract the information, functions will be written that make use of the requests library to send HTTP requests to the Marvel API, parse the JSON response, and extract the relevant information. These functions will be modular and reusable, allowing them to be used for other similar data extraction tasks.

#### Example for series "Avengers"
![image](https://user-images.githubusercontent.com/123428884/223593606-9cafa71b-27cd-4d1a-9fbc-12354931b2d7.png)

## Data Analysis
Once the data has been extracted and stored in a structured format, it can be analyzed to gain insights into the characters and their roles in the series. For example, the most frequently appearing characters could be identified, or the characters with the most comic book appearances. This analysis can be used to inform future storytelling decisions, marketing efforts, and more.
