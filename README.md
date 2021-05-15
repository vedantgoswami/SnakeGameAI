# Snake Game AI 
AI driven snake game using Reinforcement Learning and Deep Q Learning.<br>

The game of Snake actually has a trivial, unbeatable solution. It can be driven by <b> Simple Non-ML Technique </b>by just traversing every block of the board, this gives the unbeateablre solution but it is very time taking and very brute force approach.<br>

But we will be using reinforcement learning techinque.
## Reinforcement Learning
The first question arises in mind that why we are using reinforcement learning instead of supervised machine learning, the answer is, in supervised ML algorithms need to be trained with an input and a “correct answer” called target.In this example, we don’t know what the best action to take at each stage of the game is, so a traditional approach would not be effective.<br>
In Reinforcement Learning, we have two main components: the <b>environment</b> (our game) and the <b>agent</b> (our Snake.. or to be correct, the Deep Neural Network that drives our Snake’s actions). Every time the agent performs an action, the environment gives a reward to the agent, which can be positive or negative depending on <i>how good the action was from that specific state.</i>

