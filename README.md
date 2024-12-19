# scopaCardGame

# Code smells we found in the code:

## main.py

## scopa.py
-- Methods "play_hand" and "calculate_score" are too large and have multiple responsabilities
-- "generate_deck" and "calculate_score" have redundancies. cs has repeated calls to tactics
-- Names like csum and "no_take" aren't very clear
-- Could be a bit better documneted
-- play_hand method make both game logic and state updates wich can be confusing and hard to debug/test
--change hardcoded numbers to constants


## tactics.py

## uipyqt.py
