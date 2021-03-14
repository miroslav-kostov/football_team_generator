Football Team Generator
Submit in judge a zip file named project, containing a separate file for each of the classes.

Class Player
Attributes
Private attribute name: string
Private attribute endurance: number
Private attribute sprint: number
Private attribute dribble: number
Private attribute passing: number
Private attribute shooting: number

Methods
__init__(name, endurance, sprint, dribble, passing, shooting) - set all the attributes to the given ones.
Getters and Setters to all of the private attributes
__str__() - should return: 
"Player: {name}
Endurance: {endurance}
Sprint: {sprint}
Dribble: {dribble}
Passing: {passing}
Shooting: {shooting}
"
Note: There is a new line at the end of the __str__()!!!
Class Team
Attributes
Private attribute name: string
Private attribute rating: number
Private attribute players: list
Methods
__init__( name, rating) - set all the attributes to the given ones. Also, initialize a new collection, containing all of the players.
Getters and Setters to all of the private attributes
add_player(player: Player) - adds a new player to the team.
�	If the player is already in the team, return "Player {name} has already joined"
�	Add the player to the team and return "Player {name} joined team {team_name}"
remove_player(player_name: str) - removes a player by its given name
�	Remove the player and return him
�	If the player is not in the team, return "Player {player_name} not found"
