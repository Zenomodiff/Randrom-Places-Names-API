# Place Names API 🗼🏞️🗽🌉

+ An API that will return random Place Names 🚞🗻🏛️🏗️
+ Dedicated To All Place Lovers ❤️

## Usage:

+ ### [https://randomplacenamefactsapi.herokuapp.com/](https://randomplacenameapi.herokuapp.com/) to get the documentation.
+ ### [https://randomplacenamefactsapi.herokuapp.com/api/Place-Names/all](https://randomplacenameapi.herokuapp.com/api/Place-Names/all) to get all the Place Names at once.
+ Change `all` to parameter `?number=` to specify the number of Place Names you want to receive.
+ Change `all` to parameter `?index=` to specify the index of the Place Name you are targeting.

This project is hosted by [Heroku](https://www.heroku.com/)

## Rebuild the project:
+ Clone the repo.
+ Run `python -m venv .env` to create a virtual environment.
+ Run `source .env/bin/activate` to activate the virtual environment.
+ Run `pip install requirements.txt`.
+ Run `python app.py`.
+ App starts at `http://localhost:5000` by default, but can be configured with a `.env` file. 

## Example:

+ ### [https://randomplacenamefactsapi.herokuapp.com/api/Place-Names?number=1](https://randomplacenameapi.herokuapp.com/api/Place-Names?number=1) returns: ↓
```JSON
[
  {
    "Place_Name": "Pittsburgh"
  }
]
```

+ ### [https://randomplacenamefactsapi.herokuapp.com/api/Place-Names?number=2](https://randomplacenameapi.herokuapp.com/api/Place-Names?number=2) returns: ↓
```JSON
[
  {
    "Place_Name": "Dallas"
  }, 
  {
    "Place_Name": "New York"
  }
]
```
