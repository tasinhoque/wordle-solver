# How to Run

1. Go to solver directory
2. Run the `wordle_solver.py` file
3. Run `testSolver(word)` to check how many attempts the bot will take.
4. Run `runSolver()` to simulate a game.

| `debug_mode` | meaning        |
| ------------ | -------------- |
| 0            | minimal output |
| 1            | verbose output |

Change `debug_mode` from config.py to 0 (no info print), or 1 (additional info print)\
Change `dictionary_mode` to `True` in the solver to see the dictionary meaning of the word (if the word exists in the [Dictionary API](https://dictionaryapi.dev/)).
