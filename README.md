# 19-7BlackJack
A one-hot Moore Machine dice blackjack style game implemented using digital logic. The goal is for the sum of cumulative rolls to be exactly 19. 
The player has a total of 7 rolls to make the sum exactly 19. The player automatically loses if the sum goes over 19.
On each turn, the program waits for a die roll to be asserted. If the die roll is between 1-5, the player can choose to accept (add the roll to the score) or reject (not add the roll to the score). If the die roll is equal to 6, the roll is automatically added.
The game can be linked onto a Intel® MAX® 10 FPGA 10M50DAF484C7G board.

