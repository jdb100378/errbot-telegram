# errbot-heroku-deploy
Easily deploy errbot to telegram using telegram backend. Need to configure the following config vars for the ENV in heroku under upon build:

`bot_token` and set it equal to the value from creating your bot [Here](https://core.telegram.org/bots#botfather)

Don't forget to change BOT_ADMINS value in config.py before deploying.  See http://errbot.io/en/latest/user_guide/configuration/telegram.html?highlight=telegram for more info.


[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)
