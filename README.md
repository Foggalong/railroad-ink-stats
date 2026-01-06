# Railroad Ink Stats

[Railroad Ink](https://horribleguild.com/eu/product-tag/railroad-ink/) is a puzzle game about drawing a transport network. Dice rolls give route segments that players use to connect railways, highways, and stations to score points. The base game also has [28 different dice expansions](https://horribleguild.com/railroad-ink-challenge-expansions-mix/) which add new complications into the mix!

## CSV Format

Game scores are stored in a CSV file with the following four columns:

- **ID** (_unsigned_): number to identify that game.
- **Expansion** (_string_): name of the expansion used.
- **Player** (_string_): name of the player.
- **Score** (_integer_): final score in that game.

Unless playing with the giant or epic board expansions, only one dice expansion can be used per game. That means `Expansion` will be exactly one of: Airline, Alien Farmer, Canyon, City Builder, Construction, Desert, Forest, Galactic Invaders, Investigation, Lake, Lava, Meteor, Pluck-man, Portal, Power grid, Rainbow, Renovation, Ritual, River, Separation, Special, Street lamps, Superconnection, Tentacle, Tetromino, Trail, Underground, and Weather.
