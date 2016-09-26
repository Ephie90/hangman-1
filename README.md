# Hangman

Name: Ephraim Wickline
SID: (28176178)
Assignment_2b

This module will choose a random word, and let you, the human player, guess letters. 
You start out with 10 lives. If your letter is not in the word, you lose a life. 
If you lose all your lives, you lose the game. 

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add `hangman` to your list of dependencies in `mix.exs`:

    ```elixir
    def deps do
      [{:hangman, "~> 0.1.0"}]
    end
    ```

  2. Ensure `hangman` is started before your application:

    ```elixir
    def application do
      [applications: [:hangman]]
    end
    ```

