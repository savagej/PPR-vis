# Visualising the Irish Property Price Register
This repo contains some notebooks to:
- get coordinates for the addresses in the PPR from Open Street Maps
- plot a simple static map
- plot an interactive map
- scrape information from daft for these properties


## Using plotly
To use the interactive_maps notebook, you'll need a plotly username and api_key 
as well as a mapbox access token
Create a `plotly.yml` file in this folder and add the following lines:  
```
"username": "your_username"
"api_key": 'your_api_key'
"mapbox_access_token": 'your_mapbox_access_token'
```
