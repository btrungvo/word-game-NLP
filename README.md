# Word guesser
>[!NOTE]
>Run word_game_NLP.ipynb to play, you can play manually or let it play with the test.txt dataset

## Project Description
Build AI/ML model to guess a hidden word, inspired by this [game](https://en.wikipedia.org/wiki/Hangman_(game))

## Game rules
* Hidden word is given by user or randomly picked from test.txt dataset. Eg: "apple"
* The word is masked with underscores ("_ _ _ _ _")
* AI bot will try to pridict that hidden word by guess a letter per attempt.
* If the guess letter is correct, the system will return an update state on the hidden word. Eg: Guessed "p" -> "_ p p _ _"
* There is a limit of 6 attempts, each wrong guess will decrease the attempt by 1.
* Game ends when the word is fully revealed or the attempts remains reaches 0.

## Current Playable Bots
## $${\color{orange}Model_1}$$
> Model_1 is n-grams model from scratch without NLTK package, it is train on lowcase English words from nltk.corpus.words.words() dictionary.
> I find that a combination of 1 to 6-grams models is effective, although the number of n-gram models can be increased with the expense of computational cost.\
<p align="center">
  <img width="460" height="300" src="https://github.com/btrungvo/word-game-NLP/blob/main/Model_1">
</p>
## $${\color{orange}Model_2}$$
> Work in progresss, thinking LSTM, NLP, Transformer.... I will finish it when I have some free time!
