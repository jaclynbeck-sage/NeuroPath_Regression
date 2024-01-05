# DRAFT
This is a work in progress. 

# Using the Docker container
```
cd NeuroPath_Regression/docker
docker build . -t neuropath_regression

export SYNAPSE_AUTH_TOKEN="<your_synapse_auth_token_in_quotes>"

# TODO eventually this will be set up to run as a single script in the container instead of in RStudio
docker run -d -p 8787:8787 -e PASSWORD=<some_password> -e SYNAPSE_AUTH_TOKEN=$SYNAPSE_AUTH_TOKEN -w /home/rstudio --name rstudio neuropath_regression
```
