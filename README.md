# OneBitBot - Manage FAQ in chatbot

Second application developed in Bootcamp of [OneBitCode](https://onebitcode.com/)

Access [OneBitPalteBot](https://t.me/OneBitPalteBot)

## Usage

Clone the repository with `git clone https://github.com/tiagompalte/onebitbot.git`. In the repository folder:

* Run `sudo docker-compose build`
* Run `sudo docker-compose run --rm website rake db:create`
* Run `sudo docker-compose run --rm website rake db:migrate`
* Run `sudo docker-compose up`

## What was developed

* [Sinatra](https://github.com/sinatra/sinatra)
* [Rspec](https://relishapp.com/rspec)
* [Dialogflow](https://dialogflow.com)
