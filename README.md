# data-visualization

A setup for getting plotly dash running in a docker container with a configured volume to read data from.
This should allow anyone interested be able to quickly visualize data in a mounted volume to a browser.

original work started from: https://github.com/ericcgu/Flask-Dash-Plotly

I'll be building on it by having a mounted a volume in the config, possibly trying to make it more lightweight
and anything else that comes to mind.

 ## Starting and stopping
 
 In the root directory execute the following. Assumes you have docker and docker compose installed.
 
    docker-compose up --build -d

### Preview

    http://localhost:8000/

when you are done just execute:

    docker-compose down
    
Make sure to persist anything you want to keep into the mounted volume!

### Volume mounting

### Hot Reloading
