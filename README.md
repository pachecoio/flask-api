## Dockerized Flask api with VSCode debugger setup

This is a simple dockerized flask app with a VSCode debugger setup
###
You can find the complete tutorial on how this works [here](https://dev.to/pacheco/dockerize-a-flask-app-and-debug-with-vscode-34i1)

## Setup the application


#### Create a python virtual env

```
python -m venv venv
```

### Initiate the virtual env and install the necessary dependencies

For Windows users
```
./venv/Scripts/activate
```

For Mac or Linux users:
```
source venv/bin/activate
```

Install dependencies
```
pip install -r requirements.txt
```

## Run the application


#### Start the container

```
docker-compose up -d
```

Press F5 in VSCode and start debugging.
