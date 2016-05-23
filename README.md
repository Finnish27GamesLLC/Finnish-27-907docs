# Finnish-27-907docs

This repository contains text files saved by the BIGS907 software application.

SET OF COMBINATION-DEPENDENT-PLAYING-STRATEGY TABLES

A playing strategy is a strategy for the play of the player's hand. The BIGS collection of software applications supports eighty-four playing strategies. The eighty-four-supported-playing strategies consist of the eighty-one-supported strategies for the player's use of the hit option, and a set of three additional playing strategies consisting of double down, split, and surrender.

A combination-dependent-playing strategy is the best playing strategy for the play of the player's hand given the user-defined set of game rules, and given the combination of card ranks assigned to the cards removed from the stack and dealt face up to form the set of hands consisting of the player's initial hand and the dealer's initial hand. A combination-dependent-playing-strategy table provides a combination-dependent-playing strategy for each of the combinations of card ranks that could be the combination of card ranks assign to the cards removed from the stack and dealt face up to form the set of hands consisting of the player's initial hand and the dealer's initial hand. 

If the user-defined set of game rules does not give the option to split to the player, then a set of combination-dependent-playing-strategy tables consists of one combination-dependent-playing-strategy table found for the set of hands consisting of the player's primary-initial hand and the dealer's initial hand. If the user-defined set of game rules does give the option to split to the player, then the set of combination-dependent-playing-strategy tables consists of one combination-dependent-playing-strategy table found for the set of hands consisting of the player's primary-initial hand and the dealer's initial hand, and two combination-dependent-playing-strategy tables found for the set of hands consisting of the player's post-split-initial hand and the dealer's initial hand. 

Under most circumstances, the player refers to the set of combination-dependent-playing-strategy tables one time per each player's initial hand. 

The BIGS907 software application 920 enables the user to do the following. Load into program memory a set of databases of player-finish probabilities saved to a set of data files by the BIGS903 software application 914. Load into program memory a set of databases of dealer-finish probabilities saved to a set of data files by the BIGS906 software application 916. Load into program memory data about a user-defined subset of game rules saved to a data file by the BIGS903 software application. Input a user-defined set of game rules consisting of the user-defined subset of game rules and the remaining game rules required to play a double-exposure game. Find the set of combination-dependent-playing-strategy tables for a double-exposure game that is subject to the user-defined set of game rules. Calculate an estimate of the expected value of the game wager for the double-exposure game that is subject to the user-defined set of game rules. 

