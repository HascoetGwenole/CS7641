This repository contains the code I used for my 4th assignment of CS 7641 that focusses on reinforcement learning. In particalar,
I used value iteration, policy iteration and Epsilon greedy Q-Learning.

This github repository contains a jupyter notebook for both MDP I chose for this assigment (respectively named 
"Forest Management Problem.ipynb" and "Taxi.ipynb"). 

-The Forest Management problem uses the MDP proposed in the library pymdptoolbox. To run "Forest Management Problem.ipynb",
one must first install this library using "pip install mdptoolbox". Then, you cange the file "mdp.py" that you'll find in 
the installation folder by the file "mdp.py" that is in the git repository.

-The Taxi MDP uses OpenAI gym environment, that must be install using "pip install gym". Then 3 files of this environment 
must be changed to make the notebook "Taxi.ipynb" run:
  	1) in "gym/env", replace the files "__init__.py" and "registration.py" by the two files of the same name avialable 
	on my github.
	2)in "gym/env/toy_text", add the file "taxi_extended.py", and replace the file "__init__.py" by "__init__1.py" that 
	is on my github. Then rename "__init__1.py" into "__init__.py"

Once this environment is set up, the two notebooks can be runned.

References:
Value iteration and Policy iteration used for the taxi problem:
https://medium.com/@annishared/searching-for-optimal-policies-in-python-an-intro-to-optimization-7182d6fe4dba
Q-Learning used for the taxi problem:
https://www.learndatasci.com/tutorials/reinforcement-q-learning-scratch-python-openai-gym/
The OpenAI gym library (for the taxi problem):https://gym.openai.com/
The pymdptoolbox library (for the Forest management problem):
https://pymdptoolbox.readthedocs.io/en/latest/api/example.html
