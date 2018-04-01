# create-react-app with a Node server on Heroku
This is simple template for react application with node js server
-- im trying to add every thing is needed for develping react website in this repo 

<img src="/readme_assets/api.PNG" alt="deployment segment in heroku"/>
# build 
we used build pack to config this file but we change defult config to access to css file as modules 
examples are available in code 


## Demo
You can add this project to Heroku server just by setting deployment method in heroku 
if there is any problem let me know 

<img src="/readme_assets/deployment_method.PNG" alt="deployment segment in heroku"/>
Heroku.com 



## For Local Development

### Run the API Server [NodeJs]

In a terminal:

```bash
# Initial setup
npm install

# Start the server
npm start
```


### Run the React UI

The React app is configured to proxy backend requests to the local Node server. (See [`"proxy"` config](react-ui/package.json))

In a separate terminal from the API server, start the UI:

```bash
# Always change directory, first
cd react-ui/

# Initial setup
npm install

# Start the server
npm start
```
