# Workshop!

## Part I

1. Read the PDF in this repo. This gives you some background on the Q Learning algorithm.

2. Make sure you have Java 8 installed. You will also need the [ant build tool](http://ant.apache.org/manual/install.html)

3. Go to [QMaze](https://github.com/katharinebeaumont/QMaze), and follow instructions there.

## Part II

Now we are interested in the agent in a remote environment. It has to build up it's own idea of where things are. 

1. Go to [QMaze-Env](https://github.com/katharinebeaumont/QMaze_Env). This is the environment, as a server. You don't have to change any code here (but feel free to).
Any issues downloading this or running it please give myself, Linda or Regina a shout.

2. This works in conjunction with [Agent](https://github.com/katharinebeaumont/Agent). This is a remote agent that takes from the environment a set of possible directions, and maybe a reward, and decides which action to take next. You can add more than one agent to the environment. When training, they cannot occupy the same space (this is controlled by the environment), so they are in competition.

You need to complete the missing code in Agent. Bonus points for adding artwork!

## Bonus points

1. Add tests to Agent.

2. Set up 2 Agents on a remote server and compete against other attendee's agents.

3. Look up the minmax Q learning algorithm, and see if you can modify the environment and the agents to have knowledge of each other's actions.
