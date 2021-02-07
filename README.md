Running the web-app locally

1)In your terminal change directory to the project folder

2)Run the following commands in the terminal

    $ npm install
    $ npm start
    
3)Go to 'http://localhost:5000/'  to view the web-app


Deploying the web-app on Heroku

(Note : you can find the deployed app at https://apna-daftar.herokuapp.com )


1)Also note that Procfile has already been included

2)In your terminal change directory to the project folder

3)Initialise an empty git repository

    $ git init

4)Add changes to the git repository and commit

    $ git addd .
    $ git commit -m 'message'

5)If you don't have a heroku account, create one for free at 'https://www.heroku.com/'

9)In your terminal login to heroku

    $ heroku login

7)Create an app by running

    $ heroku create

8)Set the config variables by running
    
    $ heroku config:set DBPASS=3108fetcha%23
    $ heroku config:set PASSWORD=3108Codor#
    $ heroku config:set SECRET=Thisaintgonacrackthateasybuddy
    
9)Push the app to heroku

    $ git push heroku master

10)All Done! Go to the url in the prompt message in your terminal to run the app
 









