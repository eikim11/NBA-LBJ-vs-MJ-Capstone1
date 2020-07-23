# NBA-LBJ-vs-MJ-Capstone1
LeBron James vs. Michael Jordan - Who Is the GOAT?

Gather datasets by web scraping basketball-reference.com for the following:
  - Per game stats for LeBron James' career so far ('03-'19)
  - Per game stats for Michael Jordan's career ('84-'03)
  - Per season stats for all players during 1) "LeBron era" ('03-'19) and 2) "Jordan era" ('84-'03)
  - Advanced season stats for all players during both eras

The metric I will be focusing on to measure "greatness" is Game Score (GmSc):
> GmSc - Game Score; the formula is 
> `PTS + 0.4 * FG - 0.7 * FGA - 0.4*(FTA - FT) + 0.7 * ORB + 0.3 * DRB + STL + 0.7 * AST + 0.7 * BLK - 0.4 * PF - TOV.` 
> This stat is the brainchild of ESPN's John Hollinger, intended to calculate just how well a player performed during a single game while   looking only at box score measures. 

As you can tell from the calculation section, all stats are weighted differently and according to the frequency with which they occur. Positive contributions receive positive coefficients and negative ones receive corresponding negative coefficients. 

Just because of the fact that the box score stats are weighted, game score is light years ahead of efficiency in terms of usefulness. 

It is also set up so that the scale is relatively similar to how we would interpret points per game. 40 is absolutely incredible, 20 is good and so on. 

Null Hypothesis #1:
  > There is no real difference between 
