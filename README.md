# DSJ2 - unofficial update

This repository contains modified DSJ2 game, so that it displays a yellow line indicating where current jumper has to jump in order to be first.

## Motivation

It was implemented since it is a feature we are used to when watching ski jumping on TV, but it wasn't present in the original version of the game.

## How it was done

It was done by patching the original game. In order to do so, I had to reverse engineer the game and understand how the entire game mechanics work, including how lines are displayed on hills.

## Installation

In order to install the update, you just need to replace the original executable with DSJ.exe file from this repository. Then you can enjoy the update just by starting the game as usual.

## Few notes
- This was tested on DOSBox0.74 only (though it should work on other environments as well).
- The line is being displayed based on the calculations made by the game (i.e. the distance being displayed in the upper left corner before the jumper starts).
- If the jumper has to jump 0m, the line will not be displayed.
- Sometimes the jumper already has the advantage before his jump, for example he has the advantage of 34.6 points. The yellow line will not show the distance required to lose 34.6 points; in such a case, it will show the distance required to get 0 points.
- Please keep in mind that it is an unofficial, fan made update. I get the permission from the game author - Jussi Koskela to share it with you, but it's my own initiative. Jussi didn't participate in the implementation, so he cannot approve it and it will remain unofficial.
