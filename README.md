# Pac-Man-Game
For making pacman game the first requirement was to create board on which pacman and monsters could move. For that purpose I had used 2D arrays containing zeroes and ones as data. Zeroes on which pacman and monsters could move while ones were obstacles. I used ASCII 178 to create solid blocks to act as obstacles. I used a separate array to create food on my 28x28 board which appear as dots. For the movement of pacman I had used capture key built in function and used ASCII values of keys a, s, d and w. i added one or -1 according to key pressed in position pointer of pacman. ASCII 4 was used as pacman and was displayed using goto function. ASCII 2 was used as monsters while keeping displaying procedure as same.
 Monsters motion was controlled by rand function in order to make them move randomly. I used space in order to remove tails of monsters as well as pacman. I stored 3 in array of food to differentiate btw food eaten by pacman and monsters so that monster one could be recovered. I used a score counter on base of food eaten. game exits on collusion of pac man and monster.
 A player can win game by eating all food. If player pacman collide with
Monster player will lose game. For that purpose I had used pointers to compare objects of different classes like I had to compare pacman location coordinates with 4 different  monsters location coordinates.  When both pacman or monster
Have  same location coordinates game will end as pacman collide with monster. Score is displayed on right top corner of the console screen. Scoere is added in a int type integer count where pacman goes and changed that location coordinates into 3 from 0. So next time program will check whether food is present or not at that location.  

