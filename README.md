# Nim
This is a project part of the CS50AI course. I have only written the main functions: get_q_value, update_q_value, best_future_reward, choose_action. Honestly most of this project was written by the course. <br>
In the gamne Nim, we begin with some number of piles, each with some number of objects. Players take turns: on a player’s turn, the player removes any non-negative number of objects from any one non-empty pile. Whoever removes the last object loses.<br> 
The program is an AI that plays with it self and learns how to play the game using Reinforcement learning. Specifically, it uses the Q-learning model.
## Usage:
python play.py <br>
running play.py file you can play againts the model when it finished playing the provided number of times.<br>
You can change the default number of piles and number of objects in each pile in the file nim.py, specifically in the constrcutor of the Nim class with the variable 'initial'. <br> Also, you can change how many times the AI trains with it self in the play.py specifically in the train function paramater.
