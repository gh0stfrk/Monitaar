# Montiaar
Web Application monitoring with flask.


## Setting up locally 
* Create a copy of `.env.sample` file and add all the details in the file.
* Install all dependencies with `requirements.txt` file.
* Run the server with `python3 app.py`


### Abstract
The web appliction uses a seprate thread to run a function that checks web application status every 5 minutes, If any website is down it sends messages to the slack bots mentioned in the configuration.
