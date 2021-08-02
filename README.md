## Online chess game
Chess playable online with another player. First player initializes a room with a name and password, and the other player can join said room with the same name and password.

#### How it works
1. When a player creates a room, a new **room** is created and added to an array of rooms in the server file. The room item contains a matrix of the chessboard, the name, password and an array of the users in the room (max 2). 
2. When a player makes a move, the server validates that the move is possible by using the board stored in the server array.
