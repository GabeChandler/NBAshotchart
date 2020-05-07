# NBAshotchart
Scraping Shot Chart Data from Yahoo!

It's a little hackish, the game stream isn't always perfect.  There's some robustness built into the code that may return wrong information, this is especially true with the on-court lineups, which are not given other than the starting line-ups, and have to be guessed at for each new quarter.  We have verified from contemporaneously monitoring the game stream while watching the game that mistakes are present in the game stream in this regard, and thus the guesses cannot be assured to be perfect. 
