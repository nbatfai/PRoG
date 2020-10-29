# PRoG - PageRank of Games
Which is the best game? The question is similar to what was asked in the ancient days of internet searching, which is the best webpage?
Then the answer was given by the PageRank algorithm.
Now in this project we try to create a PageRank order of games.

## How to contribute
Do you like to play electronic games? Are you an expert in any of the games?
Then, you may contribute your knowledge here. This page helps you to get start building the phylogenetic tree of video games.

### "Gamer Experience" trees
At the moment, we focus on constructing such a graph. 
Here the vertices of the graph are labeled with well-known games,  and the edges are the common game experiences between them.
The basic use cases are as follows.

#### Missing game
If you can't find your favorite game in the graph, add the name of the game and the release date to [game_releases](https://github.com/nbatfai/PRoG/blob/main/initial_hack/game_releases) file. And then enumerate the game experiences of the game in question under the games folder in the file called the same as the name of the game.

#### Missing edge
If there is no connection between two games, but you think it should be, then add to the description files of the games the experiences common in two games.

#### Inappropriate edge between two games
As an expert, if you don’t agree with a drawn relationship between two games then you can fix it. In this case, check the experience descriptions of the two games. And then, for example, delete from the description file of the younger edition game the experiences common in two games. Or delete from both desc files the experiences in question and introduce a more specific experience. Then you can open an issue or submit a pull request with the fix.

### "Robopsychological Experience" trees
Here, only such the game experiences can be used to build the graph, that have been generalized, merged and derived from the games experiences by (robo)psychologists.

### Automatically generated trees
Write a description of the history and gameplay of your favorite game in a plain text file. You can see an example of this here. From these files, we use [the similarity metric](https://arxiv.org/pdf/cs/0111054.pdf) to build a game tree in the way well known there. We are going to build a default tree based on the Wikipedia articles of games.

# References
- K. M. Frahm, A. D. Chepelianskii, D. L. Shepelyansky (2012) *PageRank of integers*, Journal of Physics A Mathematical and Theoretical 45(40). doi: 10.1088/1751-8113/45/40/405101, https://arxiv.org/abs/1205.6343
- Page, Lawrence and Brin, Sergey and Motwani, Rajeev and Winograd, Terry (1999) The PageRank Citation Ranking: Bringing Order to the Web. Technical Report. Stanford InfoLab. http://ilpubs.stanford.edu:8090/422/1/1999-66.pdf

