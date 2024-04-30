# Deep neural engineering - assignment 2
## Playing with words: Comparing LLM model to DQN/AC in playing simple games

Structure of code:
* src
  * **cartpole**: all notebooks for training and playing cart pole.
    * play_cartpole_random.ipynb: Play cart pole with Random agent.
    * play_cartpole_Zephyr3B.ipynb: Play cart pole with LLM agent.
    * training_cartpole_dqn.ipynb: Train DQN policy agent and play cart pole.
    * training_cartpole_ppo.ipynb: Train PPO policy agent and play cart pole.
  * **blackjack**: all notebooks for training and playing blackjack.
    * play_blackjack_random.ipynb: Play blackjack with Random agent.
    * play_blackjack_Zephyr3B.ipynb: Play blackjack with LLM agent.
    * training_blackjack_dqn.ipynb: Train DQN policy agent and play blackjack.
    * training_blackjack_ppo.ipynb: Train PPO policy agent and play blackjack.
  * **tic_tac_toe**:
    * training_tictactoe_dqn_play_llm.ipynb: Train DQN policy agent in multiplayer environment and play Tic Tac Toe in combinations with a random agent, DQN policy trained agent and a LLM agent.
  * data: Collection of .csv files with data that is collected while playing the games with different prompts for the LLM agent.
  * LLM blackjack data analysis.ipynb: Notebook for analysing the data for the different prompts for the LLM agent player blackjack.
  * LLM Cartpole data analysis.ipynb: Notebook for analysing the data for the different prompts for the LLM agent player cart pole.