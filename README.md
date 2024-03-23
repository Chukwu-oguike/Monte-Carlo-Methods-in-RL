# Monte-Carlo-Methods-in-RL

The project consists of three classes: the track; the Umpire and the Agent.

The track class has three variables: three different tracks defined as 2D character arrays. The first track mirrors the second proposed track in the problem statement, the second track is similar to the first track but has one obstacle within the race track; and the third track has two obstacles in it.

The Umpire class defines the rules that govern the agents race and takes two arguments: and instance of the track class and an integer number in [0,3] that specifies the which of the three tracks is used in an episode

Agent class defines the structure of the agent using On-policy first-visit MC control for ε-greedy policy. This class takes three arguments: an instance of the Umpire class, a value for epsilon and an initial value for the state-action pairs.

The notebook’s cells should be run in sequential order and the parameters such as epsilon; number of episodes, track number can be adjusted accordingly. The output of the entire program is a cmap of the paths taken by the agent and plot of the returns vs episodes
