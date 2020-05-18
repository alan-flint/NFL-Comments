# NFL-Comments

In this project, I scrapped comments from the NFL subreddit during the 2020 NFL draft and analyzed the sentiment of comments by fans. I also trained word embeddings from these comments to practice my NLP and PyTorch skills.

The repo has
1. the data scraping notebook [here](nfl_Scrape.ipynb)
2. the sentiment analysis notebook [here](nfl_eda.ipynb)
3. the word embedding notebook [here](nfl_embeddings.ipynb)


### Sentiment Analysis Interesting Findings
I manipulated the data so I only analyzed comments from fans of the team with the most recent draft pick. For example, for the I only analyzed comments from Seahawks fans right after the Seahawks drafted a player, then from Packer fans right after the Packers drafted a player, etc. This was to get the raw, immediate reaction of fans to the players their team drafted.

Steelers, Chiefs, and Chargers fans were the most positive about their draft picks overall. While Eagles, Packers and Seahawks were in the bottom 5. 

Chargers Round 4 (local RB from UCLA), 49ers Round 7 , and Cardinals Round 7 (local RB from Arizona State) were the most positive fans by round. 

The Eagles selecting Jalen Hurts in Round 2 was the least positive draft pick. The Packers had both their Round 2 and Round 3 picks in the bottom 10 as well (RB and TE, while the team needs defensive players the most).

Kansas City Cheifs fans had the most positive first round, where they drafted a pass catching running back to fit with an already potent offense.

###### Notes
This is an ongoing project. If I have more time, I'd like to visualize the sentiment findings in a clear and concise manner.
