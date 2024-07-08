# Simple FastAPI Example

This is a basic example of a FastAPI application.

## Run 
To run your app on server, use uvicorn
    uvicorn main:app --reload # Reload to make the server automatically refreshed if the file changes

Then click on the link with /docs like http://127.0.0.1:8000/docs. We get an iterative UI page
    Test with POST, click on try it out - execute
        Get the Curl command that we could run in terminalas well 

Other UI can also go for http://127.0.0.1:8000/redoc - which ever docs or redoc is preferred

Click on openapi.json - all information about your fastapi server as in json file

## Build Docker Image

Build the Docker Image
    docker build -t myimage .

Start the Docker Container¶
    docker run -d --name mycontainer -p 80:80 myimage

Now you can go to http://192.168.99.100/docs or http://127.0.0.1/docs (or equivalent, using your Docker host).
