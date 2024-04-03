# ESP32aceTeam
SpaceTeam for ESP32s

Designed by Eliana Shapere
https://docs.google.com/document/d/1vphklPqY_keQlNk1hVz_C3Pq45uIHXlx6fpNlm-N9_k/edit

## Added Features

### Levels

- Added 3 levels to the game
- Adjusted game speed globally between progress message sender and receivers when progress reaches 1/3 and 2/3 of the goal
- In `updateGameSpeed()`, the ask time and expire length decrease by 2/3 on each level increase
- Added error checking to ensure that `askTime` and `expireLength` don't go below 1 second.
