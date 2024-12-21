# BattleshipsV
Contains all released versions of Battleships

## Structure
<p>
  In ships you can define more ships, with custom names, which will be searched for as a source by the application. In the gamemodes you can define the grids size, as well as the number of ships, that are given to the player. To differ between the game modes in the ui,
  they also contain a unique name. The player count is listed BUT CANNOT BE CHANGED as of 21.12.2024.
</p>

```
{
  "ships": {
    "submarine": 1,
    "destroyer": 2,
    "cruiser": 3,
    "battleship": 4,
    "aircraftCarrier": 5
  },
  "gameModes": [
    {
      "ships": {
        "aircraftCarrier": 1,
        "battleship": 1,
        "submarine": 2,
        "destroyer": 2,
        "cruiser": 1
      },
      "gridsize": 10,
      "players": 2,
      "name": "Classic"
    },
    {
      "ships": {
        "aircraftCarrier": 1,
        "battleship": 1,
        "submarine": 2,
        "destroyer": 1,
        "cruiser": 1
      },
      "gridsize": 8,
      "players": 2,
      "name": "Quick Match"
    }
  ]
}
```

## Usage
<p>
  These versions are used in another project. The repository is private, but if you have access, you can find it under: https://github.com/DodoDorian/Battleships/
</p>

## License
<p>
  Anything you find on this repository can be used under the MIT license. The file structure and any names of ships or gamemodes are free to use as well.
</p>
