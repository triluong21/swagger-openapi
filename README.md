# Swagger/OpenApi
This is to publish a Swagger documentation on APIs (example).

### Instructions:
##### Step 1:
Go to https://github.com/swagger-api/swagger-ui 
Click on "Clone or download" then click on "Download ZIP"

##### Step 2:
Extract swagger-ui-master.zip an copy entire 'dist' folder to designated project.

##### Step 3:
In project's dist folder: Create swagger .yml file (example here).
In dist/index.html file, replace "https://petstore.swagger.io/v2/swagger.json" with your custom swagger .yml file name.

##### Step 4:
For Mac: Run python3 -m http.server in Terminal. You will see: "Serving HTTP on 0.0.0.0 port 8000 (http://0.0.0.0:8000/) ..."
In browser: enter http://0.0.0.0:8000/dist (if page not load, change to http://0.0.0.0:8000/dist/index.html)
