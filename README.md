# Welcome to TiktokClone 


Make a web app Like TIKTOK



this is a web appy

## 💻 Install

First you need to install Nodejs and npm, this is different depending on the OS you are running so it is easier to check the node [page](https://nodejs.org/en/download/)

Install [expo](https://expo.io/learn), if it fails run you might need to run this with sudo
```sh
npm install expo-cli --global
```

Install the needed packages while in the root folder of the project
```sh
npm install
```


Install firebase tools
```sh
npm install -g firebase-tools
```

Deploy the project to yout firebase projhect (make sure to have billing enabled for that project). copy the backend/functions/index.js into a different place
```sh
cd backend
firebase login
firebase init (choose functions, javascript, EsLint and install deplendencies)
```

Copy the index.js into the place of the new index.js
```sh
firebase deploy
```

You can check the first [video](https://www.youtube.com/watch?v=5S9HM6pprZo&t=2s) on this series to learn how to do it easily

<br>

## 📱 Usage

To Start expo all you have to do is run this line
```sh
expo start
```

