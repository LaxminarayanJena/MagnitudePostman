# MagnitudePostman
Go to the folder location and in cmd </br>

newman run Magnitude.postman_collection.json -e Magnitude.postman_environment.json</br>


To generate html report </br>
---------------------------------- </br>
npm install --g newman-reporter-htmlextra </br>

newman run Magnitude.postman_collection.json -e Magnitude.postman_environment.json -r htmlextra </br>

![report](https://user-images.githubusercontent.com/24494133/80789183-d440bb00-8ba8-11ea-8470-83e82a6ad45a.PNG)

