# GORDLE

A Wordle clone done in go just for the fun of it

## TODO

- [ ] Send a get request to the Wordle server and get the json response
- [ ] Parse the response from the json and get the word for the day
- [ ] Get a user input and compare the user input with the word of the day
  - [ ] If the user input is different than 5, return an error
  - [ ] If the user input includes one of the runes of the word, but at the wrong index, color the letter yellow and save it either in the buffer or in a new slice to then display it
  - [ ] If the user input includes the rune and is at the correct, color the rune green and either add it to the buffer or print
- [ ] If the user tries more than 6 times, an error should be thrown as the game was failed
- [ ] If the user guesses the word under 6 takes, the game is won
