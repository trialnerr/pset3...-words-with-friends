# pset3...-words-with-friends

TAKEN FROM MIT6.0001
This game is a lot like Scrabble or Words With Friends. Letters are dealt to players, who then construct one or more words using their letters. Each ​valid​ word earns the user points, based on the length of the word and the letters in that word. The rules of the game are as follows:

DEALING

●A player is dealt a hand of ​HAND_SIZE​ letters of the alphabet, chosen at random. This may include multiple instances of a particular letter. 
● The player arranges the hand into as many words as they want out of the letters, but using each letter at most once.
● Some letters may remain unused, though the size of the hand when a word is played does affect its score.

SCORING

● The score for the hand is the sum of the score for each word formed.
● The score for a word is the ​product​ of two components: o First component: the sum of the points for letters in the word. o Second component: ​ either ​ [7 * ​word_leng ​ th - 3 * (n​ -​word_length)] or 1, whichever value is greater, where: ​ ▪ word_length is the number of letters used in the word
▪ n is the number of letters available in the current hand 
