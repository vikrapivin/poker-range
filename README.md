# PokerTH fork to practice preflop ranges + GTO strategy

This is a fork of the pokerth project where I have patched the files to do the following
1. keep the preflop cash at a constant $2000 (100 bb at $20 bb)
2. keep all players in (even if eliminated in the prior hand

In order to use this program, you must compile it and then start a local game at constant blinds (click custom blinds and select keep last blind).

This program will then save all of the hands for each round, which you can later analyze with your favorite sqlite viewer/pandas/etc.
