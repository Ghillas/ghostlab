# ghostlab
catch all the ghost

# compile
javac *.java

# execute
`java Serveur` to run the server
`java Client` to run the client


# how to play
enter the action you want to do

	- NEWPL pseudo port
		to create a new game
		pseudo = the name of your choice
		port = the port you want to use
	
	- REGIS pseudo port num
		to rejoin the game with the id num
		pseudo = the name pf your choice
		port = the port you want to use
		num = the id of the game you want to join
		
	- LIST? num
		print all the players in the game with the id num
		num = the id of the game
	
	- GAME?
		print all the existing games
		
	- SIZE? num
		print the size of the labyrinth of the game with the id num
		num = the id of the game
		
	- UNREG
		leave the game you are currently in
		
	-START 
		when you are ready to start (the game will start when everybody is ready)
		
When you are in a game :

	- UPMOV nb_step
		do nb_step step to the top
		nb_step = the number of step you want to do
		
	- LEMOV nb_step
		nb_step step on the left 
		
	- RIMOV nb_step
		nb_step step on the right
		
	- DOMOV nb_step
		nb_step step down
		
	- GLIS?
		print the position of all players
		
	- MALL? message_to_send
		send the message message_to_send to all the players in the game
		
	- SEND? n_player message_to_send
		send the message message to send to the player with the name n_player
		
	- IQUIT
		leave the game
		
		
		
		
		
		
		
		
		
		
		
		
