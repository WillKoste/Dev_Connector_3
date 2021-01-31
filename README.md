# Dev_Connector_3

Full-stack MERN web application for developers to meet and connect with other developers. This project was developed to dain and display several web development fundamentals. To start it off, submit the following commands in the terminal:
```
cd ./config
touch config.env
```

in `config.env` supply the following variables:
```
{
  "mongoURI": "<MONGO_URI>",
  "jwtSecret": "<JWT_SECRET>",
  "githubClientId": "<GITHUB_CLIENT_ID>",
  "githubClientSecret": "<GITHUB_CLIENT_SECRET>"
}
```

## Start the application
```
/* IN THE PROJECT ROOT */

npm i && cd ./client && npm i && cd ../

npm run dev
```
