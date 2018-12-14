# HASS DEVL Sample Notebooks

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/HASSCloud/hassdevl-samples.git/master)

This repository contains sample notebooks from the [Humanities and Social Sciences Data 
Enhanced Virtual Laboratory](https://hasscloud.net.au/) (HASS DEVL) project funded by 
[ARDC](https://nectar.org.au/).  

Some services used in these notebooks require secret API keys or usernames.  The scripts read these
from a file `secret.json` in this directory.   To get the scripts to work, copy the file `secret.json.dist` 
to `secret.json` and edit it to add your keys. 

- [Trove API Key](http://help.nla.gov.au/trove/building-with-trove/api)
- [Alveo API Key](http://alveo.edu.au/documentation/getting-access-to-alveo-and-galaxy/whats-an-api-key/)
- [Geonames username](http://www.geonames.org/login)
- [Google Maps API key](https://developers.google.com/maps/documentation/javascript/get-api-key)
    
Note that I am using [nbstripout](https://github.com/kynan/nbstripout) to remove output from notebooks
before committing changes to git.  This prevents minor changes such as re-running the notebooks showing up
as changes on Github.
