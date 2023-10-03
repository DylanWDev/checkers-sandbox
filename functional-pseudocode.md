// Functional

document.addEventListener("load", init);
let gameState = {};



init (){
    // update or populate gameState
    // add properties to gameState with values
    // build ui
    buildUI();
}

//below ae functions with the R&R -mvc

// Model -
function newGame(){
    // create game obj
    game = new Game();
    // create player1 add play2 obj
    player1 = new Player();
    player2 = new Player(;)
    // check local storage
    // if we have a game in ls
    // hydrate state
}

// Model functions
/*
    updateState({key:value});
    addMove({who:player1, where:square32});
    

// View -
function buildUI(){

}

// Controller -
function onMove(){

}