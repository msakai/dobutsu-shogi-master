# Dobutsu-Shogi Master instances

This dataset contains instances related to "Dobutsu-Shogi," a simplified variant of Shogi (Japanese chess) played on a 3x4 board. For details about the game, please refer to the [Wikipedia article on Dōbutsu Shōgi](https://en.wikipedia.org/wiki/D%C5%8Dbutsu_sh%C5%8Dgi).

In Dobutsu Shogi, the second player (White) has a winning strategy from the initial position. The [Dobutsu-Shogi Master](https://github.com/mame/dobutsu-shogi-master/) program materializes this by always choosing the optimal moves as the second player. During the implementation process of the program, a 0-1 integer optimization problem was solved to minimize the number of board positions needed to be stored.

## Dataset Overview

This dataset includes two instances:

- `dobutsu-shogi-master`:
  This is the primary instance used by the Dobutsu-Shogi Master program. Several transformations were applied to reduce the problem size and the file size for efficient processing.
- `dobutsu-shogi-master-noopt`:
  This instance is similar to the primary one, but no transformations were applied.

## Supplemental Files

`dobutsu-shogi-master.opb.map` and `dobutsu-shogi-master-noopt.opb.map` are files for decoding the solution of these problem instances.
