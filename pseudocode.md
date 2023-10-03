# procedural

START

INIT
create the game
create the players
create the state
build the ui
init the handlers, event listeners
load game state from LocalStorage

LOOP
render the UI
display score board
determine moves (type: regular diagonal forward, Jump, unrestricted diagonal move)
change the turn
evaluate the win condition
display error message
display turn log
assign a name to player
display removed checkers pieces
prompt to restart and begin the game
save the game state (localStorage)

DISPOSE
Quit
Restart


END