# Number Guessing Game

This repository contains a Number Guessing Game script written in Bash.

## Instructions

To complete this project, follow the steps below:

| Task                                   | Description                                                                                         |
|----------------------------------------|-----------------------------------------------------------------------------------------------------|
| Create a `number_guessing_game` folder | Create a folder named `number_guessing_game` within the project directory.                         |
| Create `number_guess.sh`              | Create a Bash script named `number_guess.sh` within the `number_guessing_game` folder.              |
| Ensure shebang in script              | Ensure the script has a shebang at the top of the file using `#!/bin/bash`.                          |
| Turn folder into git repository       | Initialize the `number_guessing_game` folder as a git repository.                                    |
| Minimum five commits                  | Make at least five commits to the git repository.                                                   |

## User Stories

| User Story                                                               | Description                                                                                                                                                                 |
|--------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Generate random number                                                   | The script should generate a random number between 1 and 1000 for users to guess.                                                                                           |
| Prompt for username                                                      | When the script is run, it should prompt the user to enter their username with the message `Enter your username:`.                                                          |
| Handle existing username                                                 | If the username has been used before, print `Welcome back, <username>! You have played <games_played> games, and your best game took <best_game> guesses.`.              |
| Handle new username                                                      | If the username is new, print `Welcome, <username>! It looks like this is your first time here.`.                                                                          |
| Prompt for guess                                                         | After the username is entered, the script should print `Guess the secret number between 1 and 1000:` and wait for the user to input their guess.                          |
| Provide feedback on guess                                                | Provide appropriate feedback on the guess. If the guess is higher than the secret number, print `It's lower than that, guess again:`. If lower, print `It's higher than that, guess again:`. |
| Handle non-integer guess                                                 | If the user inputs anything other than an integer as a guess, print `That is not an integer, guess again:`.                                                                |
| Print success message upon correct guess                                  | When the secret number is guessed correctly, print `You guessed it in <number_of_guesses> tries. The secret number was <secret_number>. Nice job!`.                         |

## Notes

- If you leave your virtual machine, your database may not be saved. You can make a dump of it by entering `pg_dump -cC --inserts -U freecodecamp number_guess > number_guess.sql` in a bash terminal (not the psql one).
- If you are saving your progress on freeCodeCamp.org, after getting all the tests to pass, follow the instructions above to save a dump of your database.
- Save the `number_guess.sql` file, as well as the final version of your `number_guess.sh` file, in a public repository and submit the URL to it on freeCodeCamp.org.

## Tasks

- Complete the tasks as outlined in the user stories.

### Commits

| Commit Message     | Description      |
|--------------------|------------------|
| Initial commit     | Initial setup    |
| Task: Generate random number | Implement code to generate a random number |
| Task: Prompt for username | Implement code to prompt for username |
| Task: Handle existing/new username | Implement logic to handle existing and new usernames |
| Task: Prompt for guess | Implement code to prompt for user guess |
| Task: Provide feedback on guess | Implement feedback mechanism for user guesses |
| Task: Handle non-integer guess | Implement logic to handle non-integer guesses |
| Task: Print success message | Implement code to print success message upon correct guess |



Certainly! You can use the following markdown code to display the commands table in your GitHub README:




1. Initial commit
2. [Prefix: Task] Commit message...
3. [Prefix: Task] Commit message...
4. [Prefix: Task] Commit message...
5. [Prefix: Task] Commit message...

Certainly! You can use the following markdown code to display the commands table in your GitHub README:

markdown
Copy code
| commands                                     | 
|----------------------------------------------|
| `vim number_guess.sh`                        | 
| `mkdir number_guessing_game`                 | 
| `cd number_guessing_game`                    | 
| `git init`                                   | 
| `chmod +x number_guess.sh`                   | 
| `git add number_guess.sh`                    | 
| `git commit -m "Initial commit"`             | 
| `./number_guess.sh`                          | 
| `psql --username=freecodecamp --dbname=postgres` |
| `cd ..`                                      | 
| `vim file1`                                  | 
| `git add file1`                              | 
| `git commit -m "feat: add unique reference"` | 
| `vim file2`                                  |
