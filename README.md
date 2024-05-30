Follow the steps for starting the json server locally
Create a folder with any name 
Open it in visual studio
Open terminal and type the command npm init 
press yes to continue with installation process
Then install json server using the command npm install json-server
// this will add json-server as a package into your project

open package.json file and the following to the scripts key
// sampleData.json is the file that you need create and add your json data inside the file
add "start" : "json-server --watch sampleData.json" with value mentioned inside scripts in packaje.json file
then use the command npm run start to start the json server or alternately we can use the coomand as json-server --watch sampleData.json
