# MagnitudePostman
Go to the folder location and in cmd </br>

newman run Magnitude.postman_collection.json -e Magnitude.postman_environment.json</br>


To generate html report </br>
---------------------------------- </br>
npm install --g newman-reporter-htmlextra </br>

newman run Magnitude.postman_collection.json -e Magnitude.postman_environment.json -r htmlextra </br>
