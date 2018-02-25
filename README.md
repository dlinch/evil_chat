# Evil Chat
Based on the Evil Martians tutorial. [tutorial](https://evilmartians.com/chronicles/evil-front-part-1)

## Purpose
I wanted to see how Evil Martians suggested integrated a modern component-based JavaScript infrastructure into a Rails application. Also, I haven't played with ActionCable before either so that was pretty neat.

### Setup 
Global dependencies: Yarn, Postgres, Ruby >= 2.4.0, Node >= 9.4.0

To run the application, pull down, cd into the project.

run `bundle install && yarn install && rake db:create db:migrate`

run `yarn global add hivemind`

### Run the Project
From the command line, run `hivemind` in order to spin the project up in development mode.

Visit localhost:5000 to see the application running.