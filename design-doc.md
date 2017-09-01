# SquidColosseum
---


## Introduction
SquidColosseum is a Splatoon 2 alternative match-making service, providing a sophistiacted ranking system to more accurately evaluate a player's skill. SquidColosseum uses these evaluations of skill to do the following  
  - Provide a pick-up-game matchmaking service
  - Provide a scrimmage service for teams
  - Maintain leaderboards of various types as follows:  
    - global leaderboard
    - rank division leaderboards
    - team leaderboards
  
Additionally, SquidColosseum makes finding scrim partners easy. Players may create teams through their profile page, and then may either queue for a scrim where they will be matched against a team of similar skill, or manually find a scrim partner from a list of teams looking for a scrimmage.



## Profiles

Upon registering with SquidColosseum, a profile page is created for that user.   
This profile page shows metrics calcuated by SquidColosseum such as:
  - division rank
  - Win/Loss record
  - Games Played
  - etc.  

These metrics are separate for each type of game the user plays.  
For example, the user may apply a filter of "PUG" (pick-up-game).   
In this instance, only statisics from pick-up-games they have played are displayed  

Users' profiles will also contain information that they must set to register with the matchmaking backend, as well as optional "vanity" information.  
Some examples of these types of information are as follows:
- Required information example:  

    - Weapons a user has registered as being able to play
    - Nintendo Switch Friend-Code
    
- Optional information example:  

    - Location
    - Gamepad sensitivity
    - Links to the user's twitch/twitter/youtube/etc
    

## Matchmaking
After registering with SquidColesseum, a user may choose to play in a variety of enviroments.  
The principle queue types are as follows:

- PUG (pick-up-game)  

    - When a user queues for a pickup game, the matchmaking service attempts to create the most optimal game for the user by finding 7 other player who are in queue with similar skill rating. The matchmaking service also prefers to match users with other users based on location.  

- Scrimmage (scrim)  

    - Users may only queue for this mode if they are a part of a team with at least 4 players on the roster. Once 4 members of a team enter the scrim queue, the matchmaker attempts to find another team for them to play. The matchmaker in this case will create the most optimal game by finding another team with the similar **_team skill level_**. Team skill level is a separate skill metric calculated soley based on a team's performance. It is _not_ calculated from the individual team member's PUG skill rating.
    
    

## TODO

- Bot Doc  
- League season doc
- More









