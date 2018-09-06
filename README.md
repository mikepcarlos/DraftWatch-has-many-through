# DraftWatch-has-many-through

NFL Draft Watch!

It’s that time of year again. Draft season! You’ve been hired by the NFL to develop a website for this years draft projections. A player can have many teams, a team can have many players. Within the next couple of months players and teams will both have many meetings. Here are the deliverables:

##instructions

1. First, fork and clone this lab.

2. You'll need to create all of the migrations, models, routes, controllers, and views for this lab.

3. Construct a bi-directional has many through.

3. Query for associations via the belongs_to, has_many, and has_many through associations.

4. Iterate over associations in a view and display associated data for a primary instance.

5. Identify the join model in a has many through.

##attributes

table "players"
  string "name"
  string "position"
  string "college_name"

table "teams"
  string "name"

table "meetings"
  string "date"
  integer "player_id"
  integer "team_id"

##objectives

With this website, a user should be:

1. Able to see a list of all the players

2. Able to see a single player and all the teams they’ve had meetings with

3. Able to see a list of all the teams

4. Able to see a single team and all the players they’ve had meetings with

5. Able to log a new player (and make sure that their name, position, and college_name are not blank)

6. Able to edit a players name (and make sure that their name, position, and college_name are not blank)

7. Able to create a new meeting with an association to a player and team (and make sure that their player name,position, and college_name are not blank, as well as team_name)
