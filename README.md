# Simple FastAPI Example

This is a really basic example of a FastAPI application.

To run your app on server, use uvicorn
    uvicorn main:app --reload # Reload to make the server automatically refreshed if the file changes

Then click on the link with /docs like http://127.0.0.1:8000/docs. We get an iterative UI page
    Test with POST, click on try it out - execute
        Get the Curl command that we could run in terminalas well 

Other UI can also go for http://127.0.0.1:8000/redoc - which ever docs or redoc is preferred

Click on openapi.json - all information about your fastapi server as in json file