# Word guesser
>[!NOTE]
>Work in progress, do not copy or redistribute

## Project Description
Build AI/ML model to guess a hidden word, inspired by this [game](https://en.wikipedia.org/wiki/Hangman_(game))

## Game rules
* Hidden word is given with underscore and whitespace. Eg: "_ _ _ _ _ "
* If the guess letter is correct, the system will return an update state on the hidden word. Eg: "_ p p _ _ "
* There is a limit of 6 attempts, each wrong guess will decrease the attempt by 1.
* Game ends when the word is fully revealed or the attempts remains reaches 0.
* Player choose input hidden word and let the AI guess.

## Current Model - Model1
Using ngrams model from NLP

## Future Plan
Build Deeplearning model with transformer
