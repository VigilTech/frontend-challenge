# Frontend Challenge

## Abstract
When the game begins, the user is prompted to provide a username. The game then generates its secret number and asks the user to provide a guess.
When the user tries to guess, the game must reveal if the guess was correct or not. It may also notify the user if the guess was lower or higher than the secret number
When the game ends, the game must show the statistics and prompt the user to play again

## Game requirements:
 - The loading page must include an option to see the statistics
 - The game only reveals the secret number when the game ends
 - When the game ends, it must show statistics on the previous games:
  - Current player:
   - Total games played
   - Percentage of wins
   - Percentage of losses
  - Overall:
   - Total games played
   - Top 3 players (between the ones that guessed the secret number)
   - Percentage of wins
   - Percentage of losses
   - Secret number that occurred the most often
   - Number that was used more often by the players

## Tech requirements:
 - Unit tests
 - State management (can use localStorage for persistence)
 - Routing
 - Modern frontend framework (Angular, React or Vue)

## What we will evaluate:
 - Clean code
 - Test coverage
 - Performance
 - Challenge understanding
 - Framework knowledge and best practices

## Bonus
- If you want you can publish the challenge in a free cloud (AWS, Heroku, Digital Ocean, etc) that is a plus.
- e2e Test

## Delivery
- The code should be placed in a public repo and the link should be shared with Vigil
