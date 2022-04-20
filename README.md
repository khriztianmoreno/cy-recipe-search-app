<h2>React Recipe Search App 🔎</h2>
React recipe search is a web application based on  React app that shows recipes 🥓 based on searched food 🍕 keywords. Write the food item and hit the search button, and BOOM!!! 💥 you found its recipe.<br>


<h2>Demo ✨</h2>

![ezgif-3-e22d59716417](https://user-images.githubusercontent.com/56751927/116272470-8d2add00-a79e-11eb-8e89-01bb6609ac63.gif)


<h2>How to set the project locally</h2>

* Open the terminal and then type
 ```
 $ git clone <the url of the Github repo>
 ```
This clones the repo


* ``cd`` into the new folder and type
```sh
$ npm install
```
This installs the required dependencies


* Create a ```.env``` file in the root directory and add the following
```
REACT_APP_API_ID=<YOUR_API_ID>
REACT_APP_API_KEY=<YOUR_API_KEY>
```
*You can get your API ID and API KEY from https://developer.edamam.com/edamam-nutrition-api*


* To run the React project
 ```sh
 $ npm start
 ```


<h2>API 🚀</h2>

API used : https://edamam.com


### Project Structure 🕸
```
react-recipe-search
│
├───public                      # Contains all the icons and index.html file
│
├───src                         # Project Main App Directory
│   │
│   └───components              # components for the Project
│   |   └───Footer.js           # Footer section
│   |   └───Header.js           # Header section
│   |   └───Recipe.js           # Main JS file
|   |
│   ├───App.js
│   ├───index.css
│   ├───index.js
│   ├───reportWebVitals.js
|

```
