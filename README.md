# TeekoAI
Users can play Teeko against an AI opponent!

![image](https://github.com/arul-aravinthan/TeekoAI/assets/20894323/2d4f0427-8bb2-45e7-9b04-6f2f01edbd4a)

## Teeko Description:
The Teeko board consists of twenty-five spaces arranged in a five-by-five grid. There are eight markers in a Teeko game, four black and four red. One player, "Black" plays the black markers, and the other, "Red", plays the red. Black moves first and places one marker on any space on the board. Red then places a marker on any unoccupied space; black does the same; and so on until all eight markers are on the board. The object of the game is for either player to win by having all four of their markers in a straight line (vertical, horizontal, or diagonal) or on a square of four adjacent spaces. (Adjacency is horizontal, vertical, or diagonal, but does not wrap around the edges of the board.) If neither player has won after the "drop" (when all eight pieces are on the board), then they move their pieces one at a time, with Black playing first. A piece may be moved only to an adjacent space.

AI is implemented using the [minimax algorithm](https://en.wikipedia.org/wiki/Minimax)
## How to Play!

The user is 'b', and the AI is 'r'. Follow the directions stated by the program to move. 
## Example Game

0:           
1:           
2:           
3:           
4:           
   A B C D E
b's turn
Move (e.g. B3): A0
0: b         
1:           
2:           
3:           
4:           
   A B C D E
r moved at B1
0: b         
1:   r       
2:           
3:           
4:           
   A B C D E
b's turn
Move (e.g. B3): B0
0: b b       
1:   r       
2:           
3:           
4:           
   A B C D E
r moved at C0
0: b b r     
1:   r       
2:           
3:           
4:           
   A B C D E
b's turn
Move (e.g. B3): D1
0: b b r     
1:   r   b   
2:           
3:           
4:           
   A B C D E
r moved at D0
0: b b r r   
1:   r   b   
2:           
3:           
4:           
   A B C D E
b's turn
Move (e.g. B3): C3
0: b b r r   
1:   r   b   
2:           
3:     b     
4:           
   A B C D E
r moved at C1
0: b b r r   
1:   r r b   
2:           
3:     b     
4:           
   A B C D E
b's turn
Move from (e.g. B3): B2
Move to (e.g. B3): B2
0: b b r r   
1:   r r b   
2:           
3:     b     
4:           
   A B C D E
[(2, 1), (2, 1)]
You don't have a piece there!
Move from (e.g. B3): D1
Move to (e.g. B3): D2
0: b b r r   
1:   r r     
2:       b   
3:     b     
4:           
   A B C D E
r moved from C0
  to D1
0: b b   r   
1:   r r r   
2:       b   
3:     b     
4:           
   A B C D E
b's turn
Move from (e.g. B3): C3
Move to (e.g. B3): C2
0: b b   r   
1:   r r r   
2:     b b   
3:           
4:           
   A B C D E
r moved from D0
  to E1
0: b b       
1:   r r r r 
2:     b b   
3:           
4:           
   A B C D E
AI wins! Game over.
