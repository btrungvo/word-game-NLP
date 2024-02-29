# Word guesser
>[!NOTE]
>Run word_game_NLP.ipynb to play, you can play manually or let it play with the test.txt dataset

## Project Description
Build AI/ML model to guess a hidden word, inspired by this [game](https://en.wikipedia.org/wiki/Hangman_(game))

## Game rules
* Hidden word is given with underscore and whitespace. Eg: "_ _ _ _ _ "
* If the guess letter is correct, the system will return an update state on the hidden word. Eg: "_ p p _ _ "
* There is a limit of 6 attempts, each wrong guess will decrease the attempt by 1.
* Game ends when the word is fully revealed or the attempts remains reaches 0.
* Player choose input hidden word and let the AI guess.

## Current Playable Models
### $${\color{red}Model-1}$$
>n-grams model from scratch without NLTK package. I find that a combination of 1 to 6-grams models is effective, although the number of n-gram models can increase with the extent of computational cost.
