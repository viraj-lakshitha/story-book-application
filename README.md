Install Required Packages
`npm i express mongoose connect-mongo express-session express-handlebars dotenv method-override moment morgan passport passport-google-oauth20`

Install Dev Dependencies
`npm i -D nodemon cross-env`

Configure Script
"scripts": {
    "start": "cross-env NODE_ENV=production node app",
    "dev": "cross-env NODE_ENV=development nodemon app"
}


