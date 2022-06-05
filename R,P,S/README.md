- 👋 Hi, I’m @Thecapstone
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Thecapstone/Thecapstone is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.

no_of_guesses = 1
guess_count=3
print(''''Rock'
'Paper'
'Scissors'
''')

while no_of_guesses <= guess_count:
	Guess=input("Rock, Paper, Scissors?:  ").lower()
	import random
	
	game= ["rock", "paper", "scissors"]
	Computer= random.choice(game)
	print("you guessed: " + Guess , "...Computer guessed: "+ Computer)
			
	no_of_guesses+=1
	if Guess == Computer:
		print("its a tie! ")
		break
	
	if Guess == "rock":
		if Computer== 'scissors':
			print("you win!")
			break
		
		elif Computer == 'paper':
		   	print("you lose! ")
		   	break
	    	
	if Guess == "paper":
		if Computer == "rock":
			print("you win! ")
			break
		
		elif Computer == "scissors":
			print("you lose! ")
			break
	
	if Guess == 'scissors':
		if Computer == 'rock':
			print("you lose! ")
			break
		
		elif Computer == 'paper':
			print("you win!")
			break
			
	else:
		print("wrong command! ")
		break
