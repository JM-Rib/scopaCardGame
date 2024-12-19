# scopaCardGame

# Code smells we found in the code:

## main.py
-- "run_game_with_form" mixes game logic, UI initialization and the application's event loop, making the function less reusable and harder to maintain.
-- There's no mechanism to catch or report errors from the game logic.
-- The name "run_game_with_form" could be better as it is hard to understand wich for it it reffering to.

## scopa.py
-- Methods "play_hand" and "calculate_score" are too large and have multiple responsabilities.
-- "generate_deck" and "calculate_score" have redundancies. cs has repeated calls to tactics.
-- Names like csum and "no_take" aren't very clear.
-- Could be a bit better documneted.
-- play_hand method make both game logic and state updates wich can be confusing and hard to debug/test.
--change hardcoded numbers to constants.


## tactics.py

## uipyqt.py
