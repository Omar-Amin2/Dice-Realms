# Project Skeleton

## Folder Structure

```
Dice-Realms/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── game/
│   │   │       ├── collectibles/
│   │   │       │   ├── ArcaneBoost.java
│   │   │       │   ├── Bonus.java
│   │   │       │   ├── ElementalCrest.java
│   │   │       │   ├── EssenceBonus.java
│   │   │       │   ├── Power.java
│   │   │       │   ├── Reward.java
│   │   │       │   ├── RewardType.java
│   │   │       │   └── TimeWarp.java
│   │   │       │
│   │   │       ├── creatures/
│   │   │       │   ├── Creature.java
|   |   |       |   |
|   |   |       |   ├── Dragon.java
|   |   |       |   |
|   |   |       |   ├── DragonNumber.java
|   |   |       |   |
|   |   |       |   ├── Gaia.java
|   |   |       |   |
|   |   |       |   ├── Hydra.java
│   │   │       │   ├── Lion.java
│   │   │       │   └── Phoenix.java
|   |   |       |
│   │   │       ├── dice/
│   │   │       │   ├── ArcanePrism.java
│   │   │       │   ├── BlueDice.java
│   │   │       │   ├── Dice.java
│   │   │       │   ├── DiceStatus.java
│   │   │       │   ├── GreenDice.java
│   │   │       │   ├── MagentaDice.java
│   │   │       │   ├── RedDice.java
│   │   │       │   └── YellowDice.java
│   │   │       │
│   │   │       ├── engine/
│   │   │       │   ├── CLIGameController.java
│   │   │       │   ├── GameBoard.java
│   │   │       │   ├── GameController.java
│   │   │       │   ├── GameScore.java
│   │   │       │   ├── GameStatus.java
│   │   │       │   ├── GUIGameController.java
│   │   │       │   ├── Move.java
│   │   │       │   ├── Player.java
│   │   │       │   ├── PlayerStatus.java
│   │   │       │   └── ScoreSheet.java
│   │   │       │
│   │   │       ├── exceptions/
│   │   │       │   ├── CommandFormatException.java
│   │   │       │   ├── DiceRollException.java
│   │   │       │   ├── ExhaustedResourceException.java
│   │   │       │   ├── InvalidDiceSelectionException.java
│   │   │       │   ├── InvalidMoveException.java
│   │   │       │   ├── PlayerActionException.java
│   │   │       │   └── RewardException.java
│   │   │       │
│   │   │       │
│   │   │       ├── gui/
│   │   │       │   ├── BlueRealm.fxml
│   │   │       │   ├── BlueRealmController.java
│   │   │       │   ├── BScoreController.java
│   │   │       │   ├── BScoreSheet.fxml
│   │   │       │   ├── ColorPicker.fxml
│   │   │       │   ├── ColorPickerController.java
│   │   │       │   ├── DiceRealms.java
│   │   │       │   ├── DiceScreen.fxml
│   │   │       │   ├── DiceScreenController.java
│   │   │       │   ├── GameEnd.fxml
│   │   │       │   ├── GameEndController.java
│   │   │       │   ├── GreenRealm.fxml
│   │   │       │   ├── GreenRealmController.java
│   │   │       │   ├── GScoreController.java
│   │   │       │   ├── GScoreSheet.fxml
│   │   │       │   ├── GUIScenes.java
│   │   │       │   ├── Instruction1Controller.java
│   │   │       │   ├── instruction2.fxml
│   │   │       │   ├── Instruction2Controller.java
│   │   │       │   ├── instructions.fxml
│   │   │       │   ├── MagentaRealm.fxml
│   │   │       │   ├── MagentaRealmController.java
│   │   │       │   ├── MainMenu.fxml
│   │   │       │   ├── MainMenuController.java
│   │   │       │   ├── MScoreController.java
│   │   │       │   ├── MScoreSheet.fxml
│   │   │       │   ├── MusicPlayer.java
│   │   │       │   ├── PlayerScoreSheetController
│   │   │       │   ├── PlayerSelector.fxml
│   │   │       │   ├── PlayerSelectorController.java
│   │   │       │   ├── RedRealm.fxml
│   │   │       │   ├── RedRealmController.java
│   │   │       │   ├── RScoreController.java
│   │   │       │   ├── RScoreSheet.fxml
│   │   │       │   ├── SceneController.java
│   │   │       │   ├── ScoreSheet.fxml
│   │   │       │   ├── ScoreSheetsController.java
│   │   │       │   ├── UserName.fxml
│   │   │       │   ├── UserNameController.java
│   │   │       │   ├── YellowRealm.fxml
│   │   │       │   ├── YellowRealmController.java
│   │   │       │   ├── YScoreController.java
│   │   │       │   └── YScoreSheet.fxml
│   │   │       │
│   │   │       ├── realms/
│   │   │       │   ├── BlueRealm.java
│   │   │       │   ├── GreenRealm.java
│   │   │       │   ├── MagentaRealm.java
│   │   │       │   ├── RealmColor.java
│   │   │       │   ├── Realms.java
│   │   │       │   ├── RedRealm.java
│   │   │       │   └── YellowRealm.java
│   │   │       │
│   │   │       └── Main.java 
│   │   │
│   │   └── resources/  
│   │       ├── images/
|   |       |       ├── DiceImages/
|   |       |       |       ├── BLUE1.png
|   |       |       |       ├── BLUE2.png
|   |       |       |       ├── BLUE3.png
|   |       |       |       ├── BLUE4.png
|   |       |       |       ├── BLUE5.png
|   |       |       |       ├── BLUE6.png
|   |       |       |       ├── GREEN1.png
|   |       |       |       ├── GREEN2.png
|   |       |       |       ├── GREEN3.png
|   |       |       |       ├── GREEN4.png
|   |       |       |       ├── GREEN5.png
|   |       |       |       ├── GREEN6.png
|   |       |       |       ├── MAGENTA1.png
|   |       |       |       ├── MAGENTA2.png
|   |       |       |       ├── MAGENTA3.png
|   |       |       |       ├── MAGENTA4.png
|   |       |       |       ├── MAGENTA5.png
|   |       |       |       ├── MAGENTA6.png
|   |       |       |       ├── RED1.png
|   |       |       |       ├── RED2.png
|   |       |       |       ├── RED3.png
|   |       |       |       ├── RED4.png
|   |       |       |       ├── RED5.png
|   |       |       |       ├── RED6.png
|   |       |       |       ├── WHITE1.png
|   |       |       |       ├── WHITE2.png
|   |       |       |       ├── WHITE3.png
|   |       |       |       ├── WHITE4.png
|   |       |       |       ├── WHITE5.png
|   |       |       |       ├── WHITE6.png
|   |       |       |       ├── YELLOW1.png
|   |       |       |       ├── YELLOW2.png
|   |       |       |       ├── YELLOW3.png
|   |       |       |       ├── YELLOW4.png
|   |       |       |       ├── YELLOW5.png
|   |       |       |       └── YELLOW6.png
|   |       |       |
|   |       |       ├── ActivePlayerFlag.png
|   |       |       ├── ArcaneBoost.png
|   |       |       ├── BlueButton.png
|   |       |       ├── BlueColorPicker.jpg
|   |       |       ├── blueScoreSheet.png
|   |       |       ├── BlueWizardCast.png
|   |       |       ├── BlueWizardStill.png
|   |       |       ├── choosePlayer.png
|   |       |       ├── DiceScreen.jpg
|   |       |       ├── ElementalCrest.png
|   |       |       ├── EssenceBonus.png
|   |       |       ├── FirstHelp.jpeg
|   |       |       ├── EndBlueWizard.jpg
|   |       |       ├── EndRedWizard.jpg
|   |       |       ├── Gaia.png
|   |       |       ├── GaiaHealth.png
|   |       |       ├── GreenColorPicker.jpg
|   |       |       ├── greenRealm.jpeg
|   |       |       ├── greenScoreSheet.png
|   |       |       ├── Hydra5.jpg
|   |       |       ├── Hydra6.png
|   |       |       ├── LionCreature.png
|   |       |       ├── MagentaColorPicker.jpg
|   |       |       ├── magentaScoreSheet.png
|   |       |       ├── MainMenu.jpeg
|   |       |       ├── MultiplayerButton.png
|   |       |       ├── NO.png
|   |       |       ├── PassivePlayerFlag.png
|   |       |       ├── PhoenixImg.jpg
|   |       |       ├── Project-UML-Diagram.png
|   |       |       ├── Question.png
|   |       |       ├── RedColorPicker.jpg
|   |       |       ├── RedDragon.png
|   |       |       ├── RedRealm.jpeg
|   |       |       ├── redScoreSheet.png
|   |       |       ├── RedWizardCast.png
|   |       |       ├── RedWizardStill.png
|   |       |       ├── rollButton.png
|   |       |       ├── scoreback.png
|   |       |       ├── SecondHelp.jpeg
|   |       |       ├── SinglePlayerButton.png
|   |       |       ├── TimeWarp.png
|   |       |       ├── UserNameBackground.jpg
|   |       |       ├── WIPButton.png
|   |       |       ├── x.png
|   |       |       ├── yellowBackground.png
|   |       |       ├── YellowColorPicker.jpg
|   |       |       ├── yellowScoreSheet.png
|   |       |       └── YES.png
|   |       |
│   │       ├── config/
|   |       |       ├── EmberfallDominionRewards.properties
|   |       |       ├── MysticalSkyRewards.properties
|   |       |       ├── RadiantSvannaRewards.properties
|   |       |       ├── RoundsRewards.properties
|   |       |       ├── TerrasHeartlandRewards.properties
|   |       |       └── TideAbyssRewards.properties
|   |       |
│   │       ├── songs
|   |       |       └── GameSong.mp3
|   |       | 
│   │       └── EmptyScoreSheet.txt
|   |       
│   └── test/
│       └── java/
│           └── game/
│               ├── collectibles/
│               ├── creatures/
│               ├── dice/
│               ├── engine/
│               ├── exceptions/
│               └── gui/
│
└── README.md
```

## Packages

### game.collectibles

The `game.collectibles` package contains classes for the various collectible items within the game; such as power-ups, elemental crest, color bonus, or the essence bonus.

### game.creatures

In the `game.creatures` package, you'll find classes representing creatures in their corresponding realms; including all necessary features about how to attack them or their current status to update the score sheet accordingly.

### game.dice

The `game.dice` package encompasses classes related to dice functionality within the game. It includes implementations for rolling dice, managing dice states, and handling dice-related actions and interactions.

### game.engine

This package contains the core engine components of the game, including the abstract classes and interfaces that define the game's structure and functionality. It serves as the foundation for implementing various game controllers and managing game logic. Additional classes related to game mechanics and control can be added to this package as needed.

### game.exceptions

The `game.exceptions` package provides classes for defining custom exceptions specific to the game. These exceptions help handle error conditions and unexpected situations, providing meaningful feedback to the player or developer.

### game.gui

The `game.gui` package houses classes related to the graphical user interface (GUI) of the game. This includes components for rendering game graphics, handling user input, and managing the visual presentation of game elements.

### game.realms

In the `game.realms` package, you'll find classes representing realms; including all necessary features about how to attack them or their current status to update the score sheet accordingly.

### game.AI
In the `game.AI` package, it contains a class that implements the ai needed for a player to play against instead of another player.

## Classes

For each package, add the skeleton details for the class and duplicate as much as needed. As an example, the `GameController.java` skeleton is provided as guideline.

### `GameController.java`

- **Package**: `game.engine`
- **Type**: Abstract Class
- **Description**: This abstract class represents the controller for the game. It defines the common blueprint for different controllers used in the game.

#### Methods:

1. `void startGame()`

   - **Description**: Initializes necessary components and starts the game loop.

2. `boolean switchPlayer()`

   - **Description**: Switches the role of the current active player to passive and vice versa, ensuring that the turn-taking mechanism functions correctly.
   - **Return Type**: `boolean`
     - `true` if the switch was successful,
     - `false` otherwise.

3. `Dice[] rollDice()`

   - **Description**: Rolls all available dice for the current turn, assigning each a random number from 1 to 6.
   - **Return Type**: Array of `Dice`
     - An array of the currently rolled dice.

4. `Dice[] getAvailableDice()`

   - **Description**: Gets the dice available for rolling or rerolling.
   - **Return Type**: Array of `Dice`
     - An array of dice available for the current turn.

5. `Dice[] getAllDice()`

   - **Description**: Gets all six dice, providing their current state and value within the game regardless of their location or status.
   - **Return Type**: Array of `Dice`
     - An array of all six dice, with each die's state and value.

6. `Dice[] getForgottenRealmDice()`

   - **Description**: Gets the dice currently available in the Forgotten Realm.
   - **Return Type**: Array of `Dice`
     - An array of dice that are currently in the Forgotten Realm.

7. `Move[] getAllPossibleMoves(Player player)`

   - **Description**: Gets all possible moves for a given player.
   - **Parameters**:
     - `player`: The player for whom to determine possible moves.
   - **Return Type**: Array of `Move`
     - An array of all possible moves for all rolled dice.

8. `Move[] getPossibleMovesForAvailableDice(Player player)`

   - **Description**: Gets possible moves for all currently rolled dice for a given player.
   - **Parameters**:
     - `player`: The player for whom to determine possible moves.
   - **Return Type**: Array of `Move`
     - An array of all possible moves for all rolled dice.

9. `Move[] getPossibleMovesForADie(Player player, Dice dice)`

   - **Description**: Gets all possible moves for a given die for a given player.
   - **Parameters**:
     - `player`: The player for whom to determine possible moves.
     - `dice`: The dice to determine possible moves for.
   - **Return Type**: Array of `Move`
     - An array of possible moves for the given dice.

10. `GameBoard getGameBoard()`

    - **Description**: Gets the current game board, including all players and all score sheets.
    - **Return Type**: `GameBoard`
      - The current game board object.

11. `Player getActivePlayer()`

    - **Description**: Gets the current active player's information.
    - **Return Type**: `Player`
      - The active player object.

12. `Player getPassivePlayer()`

    - **Description**: Gets the current passive player's information.
    - **Return Type**: `Player`
      - The passive player object.

13. `ScoreSheet getScoreSheet(Player player)`

    - **Description**: Gets the score sheet for a given player.
    - **Parameters**:
      - `player`: The player to get the current score sheet for.
    - **Return Type**: `ScoreSheet`
      - The score sheet object for the given player.

14. `GameStatus getGameStatus()`

    - **Description**: Gets the current game status, including round and turn information for the current active player.
    - **Return Type**: `GameStatus`
      - The current game status object.

15. `GameScore getGameScore(Player player)`

    - **Description**: Gets the current score of the game for a given player.
    - **Parameters**:
      - `player`: The player to determine current score for.
    - **Return Type**: `GameScore`
      - The current game score object for the given player.

16. `TimeWarp[] getTimeWarpPowers(Player player)`

    - **Description**: Gets the array of TimeWarp powers and their status for a given player.
    - **Parameters**:
      - `player`: The player to get the current TimeWarp powers for.
    - **Return Type**: Array of `TimeWarp`
      - An array of `TimeWarp` objects representing the TimeWarp powers for the given player.

17. `ArcaneBoost[] getArcaneBoostPowers(Player player)`

    - **Description**: Gets the array of ArcaneBoost powers and their status for a given player.
    - **Parameters**:
      - `player`: The player to get the current ArcaneBoost powers for.
    - **Return Type**: Array of `ArcaneBoost`
      - An array of `ArcaneBoost` objects representing the ArcaneBoost powers for the given player.

18. `boolean selectDice(Dice dice, Player player)`

    - **Description**: Selects a die and adds it to the player's class, then moves all other dice with less value to the Forgotten Realm.
    - **Parameters**:
      - `player`: The player who selected the die.
      - `dice`: The dice to be selected.
    - **Return Type**: `boolean`
      - `true` if the selection was successful,
      - `false` otherwise.

19. `boolean makeMove(Player player, Move move)`

    - **Description**: Executes a move using the selected dice on a specified creature.
    - **Parameters**:
      - `player`: The player who wants to make the move.
      - `move`: The move to be executed, including the selected dice and target creature.
    - **Return Type**: `boolean`
      - `true` if the move is successfully completed,
      - `false` otherwise.

### `Template` class

- **Package**: `game.?`
- **Type**: ? Class
- **Description**: This class represents ?

#### Methods:

1. `void startGame()`
   - **Description**: ?
   - **Parameters**:
     - `?`: ?
   - **Return Type**: `?`
     - `?` ?

//Note: Methods present In superclass will not be rewritten in subclasses to avoid excessive text     
//==============================================CollectiblesPackage==============================================

### `Reward.java`

- **Package**: `game.collectibles`
- **Type**: Abstract Class
- **Description**: This class represents a superclass that contains all bonuses, powers, and crests. It implements comparable so we can sort the rewards as follows: Bonuses, Powers, Crests.

#### Methods:

1. `int compareTo(Reward o)`
   - **Description**: The comparable method that compares different rewards.
   - **Parameters**:
     - `Reward` : the reward that will will compared to this.
   - **Return Type**: `int`
     - return an integer value. It returns -1 if the reward in the parameter is greater and 1 if the reward in the parameter is lower.

2. `RewardType getRewardType()`
   - **Description**: The getter of the reward type of a certain reward.
   - **Parameters**:
     - `none`
   - **Return Type**: `RewardType`
     - returns the `RewardType` of a certain reward(either bonus or power or crest).

=====================

### `RewardType.java`

- **Package**: `game.collectibles`
- **Type**: Public Enum
- **Description**: This Enum allows us to identify the type of reward of a reward object. It includes BONUS, POWER, and CREST.

=====================   

### `Bonus.java`

- **Package**: `game.collectibles`
- **Type**: Public Class
- **Description**: This class represents the bonuses in the game which include color bonuses and essence bonuses. This class extends the Rewards class.
#### Methods:

1. `RealmColor getBonusColor()`
   - **Description**: The getter of the color of the bonus.
   - **Parameters**:
     - `none`
   - **Return Type**: `RealmColor`
     - return an enum value from `RealmColor` that indicates the color of the bonus.

2. `void setEssenceBonusColor(RealmColor realmColor)`
   - **Description**: The setter of the color of the essence bonus.
   - **Parameters**:
     - `RealmColor` : The color that is chosen for the essence bonus.
   - **Return Type**: `void`

=====================

### `EssenceBonus.java`

- **Package**: `game.collectibles`
- **Type**: Public Class
- **Description**: This class represents the essence bonus which is a color bonus of players choosing that is only awarded at the start of 4th round. This class extends the Bonus class.

#### Methods:

1. `void setEssenceBonusColor(RealmColor realmColor)`
   - **Description**: It calls the method setEssenceBonusColor() from its superclass.
   - **Parameters**:
     - `RealmColor` : The color that is chosen for the essence bonus.
   - **Return Type**: `void`

=====================

### `Power.java`

- **Package**: `game.collectibles`
- **Type**: Public Class
- **Description**: This class (superclass) represents the powers available throughout the game which contains both Arcane Boosts and Time Warps.

=====================

### `ArcaneBoost.java`

- **Package**: `game.collectibles`
- **Type**: Public Class
- **Description**: This class represents the Arcane Boost Power that allows the player to select a dice that was not power selected by him/her before. This class extends the Power class.

=====================

### `TimeWarp.java`

- **Package**: `game.collectibles`
- **Type**: Public Class
- **Description**: This class represents the Time Warp Power that allows the player to reroll all available dices. This class extends the Power class.

=====================

### `ElementalCrest.java`

- **Package**: `game.collectibles`
- **Type**: Public Class
- **Description**: This class represents the elemental crest which is used when calculating the game score and increases it. This class extends the Rewards class.

//Note: Methods present In superclass will not be rewritten in subclasses to avoid excessive text     
//==============================================CreaturesPackage==============================================

### `Creature.java`

- **Package**: `game.creatures`
- **Type**: Abstract Class
- **Description**: This class represents a superclass for all creatures. It contains alll common methods between different creatures.

#### Methods:

1. `boolean checkPossibleAttack(int diceValue)`
   - **Description**: checks if it is possible to attack using the dice value.
   - **Parameters**:
     - `none`
   - **Return Type**: `boolean`
     - return true if it is possible and false if not.

2. `int getMinimumAttackValue()`
   - **Description**: gets the minimum attack value.
   - **Parameters**:
     - `none`
   - **Return Type**: `int`
     - returns the minimum attack value.

3. `RealmColor getCreatureColor()`
   - **Description**: gets the realm color of a certain creature
   - **Parameters**:
     - `none`
   - **Return Type**: `RealmColor`
     - returns the `RealmColor` of a creature

4. `String toString()`
   - **Description**: This is a toString method for the Creature where it prints the creature.
   - **Parameters**:
     - `none`
   - **Return Type**: `String`
     - returns a String of the creature.

=====================

### `Dragon.java`

- **Package**: `game.creartures`
- **Type**: Public class
- **Description**: This class represents a class for the Dragon where it will have all the characteristics of a dragon (Heart, Head, Tail, Wings).

#### Methods:

1. ` final void setHealth(String part)`
    - **Description**: sets the health of the dragon part to zero when hit.
    - **Parameters**:
        - `String`: part to be hit in a dragon.
    - **Return Type**: `void`

2. `int getFace()`
    - **Description**: gets the face health of the dragon.
    - **Parameters**:
        - `none`
    - **Return Type**: `int`

3. ` void setFace(int face)`
    - **Description**: sets the face health of the dragon to zero.
    - **Parameters**:
        - `int`: integer that sets face.
    - **Return Type**: `void`

4. `int getWings()`
    - **Description**: gets the wings health of the dragon.
    - **Parameters**:
        - `none`
    - **Return Type**: `int`

5. ` void setWings(int wings)`
    - **Description**: sets the wings health of the dragon to zero.
    - **Parameters**:
        - `int`: integer that sets wings.
  - **Return Type**: `void`

6. ` int getTail()`
    - **Description**: gets the tail health of the dragon.
    - **Parameters**:
        - `none`
    - **Return Type**: `int`

7. ` void setTail(int tail)`
    - **Description**: sets the tail health of the dragon to zero.
    - **Parameters**:
        -  `int`: integer that sets the tail.
    - **Return Type**: `void`

8. `int getHeart()`
    - **Description**: gets the heart health of the dragon.
    - **Parameters**:
        -  `none`
    - **Return Type**: `int`

9. ` void setHeart(int heart)`
    - **Description**: sets the heart health of the dragon to zero.
    - **Parameters**:
        -  `int`: integer that sets heart.
    - **Return Type**: `void`

10. `int getPoints()`
    - **Description**: gets the points of the dragon.
    - **Parameters**:
        -  `none`
    - **Return Type**: `int`
11. ` void getHealth()`
    - **Description**: gets and prints the health of the body parts of dragon.
    - **Parameters**:
        - `none`
    - **Return Type**: `void`

12. ` DragonNumber getDragonNumber()`
    - **Description**: gets the dragon number of the dragon.
    - **Parameters**:
        - `none`
    - **Return Type**: `DragonNumber`

13. ` boolean isDeadDragon ()`
    - **Description**: Checks if the dragon is dead (all body parts are destroyed).
    - **Parameters**:
        - `none`
    - **Return Type**: `boolean`
        - `true` if the if the dragon is dead,
        - `false` otherwise.

14. ` boolean isFaceKilled ()`
    - **Description**: Checks if the dragon's face is dead.
    - **Parameters**:
        - `none`
    - **Return Type**: `boolean`
        - `true` if face is killed,
        - `false` otherwise.

15. ` boolean isWingsKilled ()`
    - **Description**: Checks if the dragon's wings are dead.
    - **Parameters**:
        - `none`
    - **Return Type**: `boolean`
        - `true` if wings are killed,
        - `false` otherwise.

16. ` boolean isTailKilled ()`
    - **Description**: Checks if the dragon's tail is dead.
    - **Parameters**:
        - `none`
    - **Return Type**: `boolean`
        - `true` if tail is killed,
        - `false` otherwise.

17. ` boolean isHeartKilled ()`
    - **Description**: Checks if the dragon's heart is dead.
    - **Parameters**:
        - `none`
    - **Return Type**: `boolean`
        - `true` if heart is killed,
        - `false` otherwise.

18. ` boolean valueInDragon (int value)`
    - **Description**: Checks if the dragon's heart is dead.
    - **Parameters**:
        - `int` The value to check against the health of the dragon's body parts
    - **Return Type**: `boolean`
        - `true` if value is in the dragon parts,
        - `false` otherwise.

=====================

### `DragonNumber.java`

- **Package**: `game.creatures`
- **Type**: Public Enum
- **Description**: This Enum allows us to choose a certain dragon(either 1, 2, 3, or 4).

=====================

### `Gaia.java`

- **Package**: `game.creatures`
- **Type**: Public Class
- **Description**: This class represents a class for the Gaia creatures with all its characteristics.

#### Methods:

1. `void killGaiaGuardian(int diceValue)`
   - **Description**: changes guardians health according to dice value.
   - **Parameters**:
     - `int`: the dice value representing which guardian will be killed.
   - **Return Type**: `void`

2. `boolean[] getGurdiansHealth()`
   - **Description**: gets all guardians heaths' in an array.
   - **Parameters**:
     - `none`
   - **Return Type**: Array of `boolean`
     - returns an array of boolean: false if killed, true if not.

=====================

### `Hydra.java`

- **Package**: `game.creatures`
- **Type**: Public Class
- **Description**: This class represents a class for the Hydra serpents with all its characteristics.

#### Methods:

1. `boolean killHead()`
   - **Description**: kills head then checks if all heads are killed.
   - **Parameters**:
     - `none`
   - **Return Type**: `boolean`
     - returns a boolean value: true is all heads are killed and false if not.

2. `void spawnHydra()`
   - **Description**: hydra spawns.
   - **Parameters**:
     - `none`
   - **Return Type**: `void`

3. `void respawnHydra()`
   - **Description**: hydra is respawned.
   - **Parameters**:
     - `none`
   - **Return Type**: `void`

4. `boolean isRespawned()`
   - **Description**: checks if hydra is respawned.
   - **Parameters**:
     - `none`
   - **Return Type**: `boolean`
     - returns true if respawned and false if not.

5. `int getRemainingNumberOfHeads()`
   - **Description**: gets the remaining number of heads.
   - **Parameters**:
     - `none`
   - **Return Type**: `int`
     - returns an integer that gets the number of heads.

=====================

### `Phoenix.java`

- **Package**: `game.creatures`
- **Type**: Public Class
- **Description**: This class represents a class for the Magenta Phoenix with all its characteristics.

#### Methods:

1. `int getHealth()`
   - **Description**: gets health of Phoenix.
   - **Parameters**:
     - `none`
   - **Return Type**: `int`
     - returns an integer with the phoenix's health.

2. `void setHealth(int value)`
   - **Description**: sets health of Phoenix.
   - **Parameters**:
     - `int`: uses the value to set the Phoenix's health.
   - **Return Type**: `void`

3. `void resetHealth()`
   - **Description**: resets health of Phoenix to zero.
   - **Parameters**:
     - `none`
   - **Return Type**: `void`

=====================

### `Lion.java`

- **Package**: `game.creatures`
- **Type**: Public Class
- **Description**: This class represents a class for the Slar Lion with all its characteristics.

//Note: Methods present In superclass will not be rewritten in subclasses to avoid excessive text     
//==============================================DicePackage==============================================

### `Dice.java`

- **Package**: `game.dice`
- **Type**: Abstract Class
- **Description**: This class represents the superclass of all the 6 dices of the game. This class implements comparable.

#### Methods:

1. `RealmColor getRealm()`
   - **Description**: It is the getter of the dice color which corresponds to the realm.
   - **Parameters**:
     - `none`
   - **Return Type**: `RealmColor`
     - returns the `RealmColor` of the realm the dice belongs to.

2. `RealmColor getDiceColor()`
   - **Description**: It is the getter of the dice color which corresponds to the realm.
   - **Parameters**:
     - `none`
   - **Return Type**: `RealmColor`
     - returns the `RealmColor` of the realm the dice belongs to.

3. `DiceStatus getDiceStatus()`
   - **Description**: It is the getter of the dice status of a dice whther it is forgotten, available, etc.
   - **Parameters**:
     - `none`
   - **Return Type**: `DiceStatus`
     - returns the `DiceStatus` of a certain dice.

4. `void setDiceStatus(DiceStatus diceStatus)`
   - **Description**: It is the setter of the dice status of a dice whther it is forgotten, available, etc.
   - **Parameters**:
     - `DiceStatus`: setting the dice with this dice status.
   - **Return Type**: `void`

5. `int getValue()`
   - **Description**: It is the getter of the dice value.
   - **Parameters**:
     - `none`
   - **Return Type**: `int`
     - returns an integer that represents the current dice value.

6. `void setValue(int Value)`
   - **Description**: It is the setter of the dice value.
   - **Parameters**:
     - `int`: setting the dice with this dice value.
   - **Return Type**: `void`

=====================

### `DiceStatus.java`

- **Package**: `game.dice`
- **Type**: Public Enum
- **Description**: This Enum allows us to identify the status of the dice which indicates the dice is available, turn selected, power selected, or forgotten.

=====================

### `ArcanePrism.java`

- **Package**: `game.dice`
- **Type**: Public Class
- **Description**: This class represents the white dice.

#### Methods:

1. `RealmColor getChosenColor()`
   - **Description**: It is the getter of the chosen color of play for the white dice.
   - **Parameters**:
     - `none`
   - **Return Type**: `RealmColor`
     - returns the `RealmColor` of the chosen color of the white dice.

2. `int getSelectsDragon()`
   - **Description**: It is the getter of the selected dragon in case of chosen color of red.
   - **Parameters**:
     - `none`
   - **Return Type**: `int`
     - returns an integer indicating the number of the dragon.

3. `void setChosenColor(RealmColor color)`
   - **Description**: It is the setter of the chosen color by player when selecting the white dice.
   - **Parameters**:
     - `RealmColor` : color chosen for white dice
   - **Return Type**: `void`

4. `void selectsDragon(int x)`
   - **Description**: It selects the specific dragon that will be attacked by the dice in case of red.
   - **Parameters**:
     - `int`: the integer represents the number of the dragon.
   - **Return Type**: `void`

=====================

### `RedDice.java`

- **Package**: `game.dice`
- **Type**: Public Class
- **Description**: This class represents the red dice.

#### Methods:

1. `int getSelectsDragon()`
   - **Description**: It is the getter of the selected dragon.
   - **Parameters**:
     - `none`
   - **Return Type**: `int`
     - returns an integer indicating the number of the dragon.

2. `void selectsDragon(int x)`
   - **Description**: It selects the specific dragon that will be attacked by the dice.
   - **Parameters**:
     - `int`: the integer represents the number of the dragon.
   - **Return Type**: `void`

=====================

### `GreenDice.java`

- **Package**: `game.dice`
- **Type**: Public Class
- **Description**: This class represents the green dice.

=====================

### `BlueDice.java`

- **Package**: `game.dice`
- **Type**: Public Class
- **Description**: This class represents the blue dice.

=====================

### `MagentaDice.java`

- **Package**: `game.dice`
- **Type**: Public Class
- **Description**: This class represents the magenta dice.

=====================

### `YellowDice.java`

- **Package**: `game.dice`
- **Type**: Public Class
- **Description**: This class represents the yellow dice.

//Note: Methods present In superclass will not be rewritten in subclasses to avoid excessive text     
//==============================================EnginePackage==============================================

### `CLIGameController.java`

- **Package**: `game.engine`
- **Type**: Public Class
- **Description**: This class extends the controller for the game. It defines the common blueprint for different controllers used in the game. It implements all abstract methods in the Game Controller and contains the Game Loop/Flow.

#### Methods:

1. `String printFinalScore(Player player1,Player player2)`
   - **Description**: prints both players scoresheets and returns final score of both player 1 and player 2.
   - **Parameters**:
     - `Player`: player 1
     - `Player`: player 2
   - **Return Type**: `String`
     - returns a table written as a String where the total score for both players are calculated.

2. `String[] getPlayerData(Player player)`
   - **Description**: puts all gamescores of each realm of a certain player in an array/ getting a players data.
   - **Parameters**:
     - `Player`: the player we are getting the data of.
   - **Return Type**: Array of `String`
     - returns an array of of String where it has each realms score, crests score, and the total score.

3. `String spaceGenerator(String x)`
   - **Description**: Generates spaces so that total length of string equals to 15.
   - **Parameters**:
     - `String`: the string we are adding spaces to
   - **Return Type**: `String`
     - returns the String result after generating spaces.

4. `void printWithColor(RealmColor color,String text,boolean cross)`
   - **Description**: prints text with a certain color depending on realm/creature. Also, it prints crossed out text.
   - **Parameters**:
     - `RealmColor`: color that text will be printed with (corresponds to realm).
     - `String`: text to be printed.
     - `boolean`: if true text is crossed. if false text is not crossed.
   - **Return Type**: `void`

5. `void createDelay()`
   - **Description**: creates delay.
   - **Parameters**:
     - `none`
   - **Return Type**: `void`

6. `void checkRoundReward(Player player)`
   - **Description**: checks round reward (checks if player has gained a reward).
   - **Parameters**:
     - `Player`: the player that has gained the reward
   - **Return Type**: `void`

7. `void selectPlayerName(Player player,int playerNumber)`
   - **Description**: allows player to select his/her name.
   - **Parameters**:
     - `Player`: player that will enter name.
     - `int`: the player number: 1 or 2.
   - **Return Type**: `void`

8. `void displayPlayerGrimore(Player player)`
   - **Description**: prints players grimore/Score sheet.
   - **Parameters**:
     - `Player`: the player that we will print his/her grimore.
   - **Return Type**: `void`

9. `void displayAvailableDice()`
   - **Description**: prints all available dices.
   - **Parameters**:
     - `none`
   - **Return Type**: `void`

10. `void displayTimeWarpPrompt(Player player)`
    - **Description**: asks player if he/she would like to use a time warp.
    - **Parameters**:
      - `Player`: player that will be asked to use time warp.
    - **Return Type**: `void`

11. `void useTimeWarp(Player player)`
    - **Description**: uses/activates time warp power for a specific player.
    - **Parameters**:
      - `Player`: player that will activate time warp power.
    - **Return Type**: `void`

12. `Dice selectDiceSequence(Player player)`
    - **Description**: the sequence in which a player selects a dice(can be passive or active).
    - **Parameters**:
      - `Player`: the player that selects the dice.
    - **Return Type**: `Dice`
      - returns the `Dice` selected.

13. `void attackSequence(Player player,Dice selectedDice)`
    - **Description**: the sequence in which a player attacks a realm with a certain dice.
    - **Parameters**:
      - `Player`: player that will attack.
      - `Dice`: selected dice by player that will attack.
    - **Return Type**: `void`

14. `int displaySelectDicePromt(Player player)`
    - **Description**: asks player to select dice.
    - **Parameters**:
      - `Player`: player that will select dice.
    - **Return Type**: `int`
      - returns an integer that corresponds to the order of selected dice(index +1). 

15. `void displayForgottenRealmDice()`
    - **Description**: prints all forgotten realm dice.
    - **Parameters**:
      - `none`
    - **Return Type**: `void`

16. `void displayChooseArcaneDiceColorPrompt(Dice dice,Player player)`
    - **Description**: asks player to choose color for arcane prism.
    - **Parameters**:
      - `Dice`: dice selected by player.
      - `Player`: player that will choose color for arcane prism.
    - **Return Type**: `void`

17. `Creature selectCreatureToAttack(Player player,RealmColor color,int diceValue)`
    - **Description**: allows player to select creature to attack.
    - **Parameters**:
      - `Player`: player that will select creature to attack.
      - `RealmColor`: corresponds to the realm that the player will attack in.
      - `int`: dice value that creature will be attacked with.
    - **Return Type**: `Creature`
      - returns `Creature` that will be attacked.

18. `Creature displaySelectDragonPrompt(Player player,int diceValue)`
    - **Description**: asks player to select dragon to attack.
    - **Parameters**:
      - `Player`: player that will select dragon.
      - `int`: dice value that will attack the dragon.
    - **Return Type**: `Creature`
      - returns a `Creature`, more specifically a dragon that will be attacked.

19. `void checkForPossibleRewards(Player player,RealmColor diceColor)`
    - **Description**: checks for possible rewards in each realm then adds it to the player.
    - **Parameters**:
      - `Player`: the player that might have rewards added.
      - `RealmColor`: check rewards according to the dice color.
    - **Return Type**: `void`

20. `void displaySelectEssenceBonusColorPromt(Player player,EssenceBonus bonus)`
    - **Description**: asks player which realm to attack when recieving essence bonus.
    - **Parameters**:
      - `Player`: player that will be asked to choose realm to attack by essence bonus.
      - `EssenceBonus`: the essence bonus recieved.
    - **Return Type**: `void`

21. `void useColorBonusPrompt(Player player,Bonus bonus)`
    - **Description**: tells player that he/she recieved a color bonus and attacks the realm based on the color of the color bonus.
    - **Parameters**:
      - `Player`: player that recieved color bonus.
      - `Bonus`: color bonus recieved.
    - **Return Type**: `void`

22. `Dice selectRedColorBonusDragon(Player player)`
    - **Description**: player selects a dragon to attack in red bonus.
    - **Parameters**:
      - `Player`: player that will select dragon to attack.
    - **Return Type**: `Dice`
      - returns `Dice` (red dice), which will be power selected and used to attack dragon.

23. `Dice selectGreenColorBonusGaia(Player player)`
    - **Description**: player selects a gaia to attack in green bonus.
    - **Parameters**:
      - `Player`: player that will select gaia to attack.
    - **Return Type**: `Dice`
      - returns `Dice` (green dice), which will be power selected and used to attack gaia guardian.

24. `void displayArcaneBoostPrompt(Player player)`
    - **Description**: asks player if he/she wants to use arcane boost. If yes, arcane boost will be used.
    - **Parameters**:
      - `Player`: player that will be asked whether to not to use arcane boost.
    - **Return Type**: `void`

25. `void useArcaneBoost(Player player)`
    - **Description**: allows player to use arcane boost and attacks depending on the dice.
    - **Parameters**:
      - `Player`: player that will use arcane boost.
    - **Return Type**: `void`

26. `Dice selectDiceSequenceArcane(Player player)`
    - **Description**: the sequence where the player selects a dice.
    - **Parameters**:
      - `Player`: player that selects the dice to attack.
    - **Return Type**: `Dice`
      - returns `Dice` that is turn selected.

27. `int displaySelectArcaneDicePromt(Player player)`
    - **Description**: asks player to select a dice based on index.
    - **Parameters**:
      - `Player`: player that will select dice.
    - **Return Type**: `int`
      - returns an integer with the order of the dice chosen (index +1).

28. `void passivePlayerSequence(Player player)`
    - **Description**: the sequence where the passive player chooses a dice from forgotten realm and attacks.
    - **Parameters**:
      - `Player`: passive player that will attack.
    - **Return Type**: `void`

29. `void resetDiceStatus()`
    - **Description**: resets all dices to available.
    - **Parameters**:
      - `none`
    - **Return Type**: `void`

30. `public Move[] mergeMoves(Move[] red,Move[] green,Move[] blue,Move[]magenta,Move[] yellow,Move[]white)`
    - **Description**: merges all moves from all 6 dices into 1 array.
    - **Parameters**:
      - 6 Arrays of `Move`: arrays of moves from each dice.
    - **Return Type**: Array of `Move`
      - returns an array of `Move` with all moves from all dices.

31. `public void setRoundRewards()`
    - **Description**: Reads round rewards from config file.
    - **Parameters**:
    -   `none`
    - **Return Type**: `void`

=====================

### `GameBoard.java`

- **Package**: `game.engine`
- **Type**: Public Class
- **Description**: This class represents the Game Board which includes the dices, players, and game status.

#### Methods:

1. `Player getActivePlayer()`
   - **Description**: It is the getter of the active player.
   - **Parameters**:
     - `none`
   - **Return Type**: `Player`
     - returns the active `Player`.

2. `Player getPassivePlayer()`
   - **Description**: It is the getter of the passive player.
   - **Parameters**:
     - `none`
   - **Return Type**: `Player`
     - returns the passive `Player`.

3. `Player getPlayer1()`
   - **Description**: It is the getter of the first player.
   - **Parameters**:
     - `none`
   - **Return Type**: `Player`
     - returns the first `Player`.

4. `Player getPlayer2()`
   - **Description**: It is the getter of the second player.
   - **Parameters**:
     - `none`
   - **Return Type**: `Player`
     - returns the second `Player`.
5. `RedDice getRedDice()`
   - **Description**: It is the getter of the red dice.
   - **Parameters**:
     - `none`
   - **Return Type**: `RedDice`
     - returns the red dice.

6. `GreenDice getGreenDice()`
   - **Description**: It is the getter of the green dice.
   - **Parameters**:
     - `none`
   - **Return Type**: `GreenDice`
     - returns the green dice.

7. `BlueDice getBlueDice()`
   - **Description**: It is the getter of the blue dice.
   - **Parameters**:
     - `none`
   - **Return Type**: `BlueDice`
     - returns the blue dice.

8. `MagentaDice getMagentaDice()`
   - **Description**: It is the getter of the magenta dice.
   - **Parameters**:
     - `none`
   - **Return Type**: `MagentaDice`
     - returns the magenta dice.

9. `YellowDice getYellowDice()`
   - **Description**: It is the getter of the yellow dice.
   - **Parameters**:
     - `none`
   - **Return Type**: `YellowDice`
     - returns the yellow dice.

10. `ArcanePrism getArcanePrism()`
    - **Description**: It is the getter of the white dice.
    - **Parameters**:
      - `none`
    - **Return Type**: `ArcanePrism`
      - returns the white dice.

11. `GameStatus getGameStatus()`
    - **Description**: It is the getter of the game status.
    - **Parameters**:
      - `none`
    - **Return Type**: `GameStatus`
      - returns the `GameStatus` which includes the turns and rounds.

12. `Dice[] getAllDice()`
    - **Description**: It is the getter of all dice.
    - **Parameters**:
      - `none`
    - **Return Type**: Array of `Dice`
      - returns an array of `Dice` which contains all dice.

13. `Dice[] getDice()`
    - **Description**: It is the getter of all dice.
    - **Parameters**:
      - `none`
    - **Return Type**: Array of `Dice`
      - returns an array of `Dice` which contains all dice.

### `GameStatus.java`

- **Package**: `game.engine`
- **Type**: Public Class
- **Description**: This class represents the Game Status that checks if players are switched and keeps rack of rounds and turns

#### Methods:

1. `void resetTurn()`
   - **Description**: resets turn and makes it start from 1.
   - **Parameters**:
     - `none`
   - **Return Type**: `void`

2. `void incrementTurn()`
   - **Description**: increments turn by 1.
   - **Parameters**:
     - `none`
   - **Return Type**: `void`

3. `void incrementRound()`
   - **Description**: increments round by 1.
   - **Parameters**:
     - `none`
   - **Return Type**: `void`

4. `boolean isGameFinished()`
   - **Description**: checks if game is finished.
   - **Parameters**:
     - `none`
   - **Return Type**: `boolean`
     - returns true if game is finished, and false if not.

5. `int getGameRound()`
   - **Description**: the getter of the game round.
   - **Parameters**:
     - `none`
   - **Return Type**: `int`
     - returns an integer indicating the round.

6. `int getTurn()`
   - **Description**: the getter of the turn.
   - **Parameters**:
     - `none`
   - **Return Type**: `int`
     - returns an integer indicating the turn.

=====================

### `GameScore.java`

- **Package**: `game.engine`
- **Type**: Public Class
- **Description**: This class represents the Game Score that calculates each players points.

#### Methods:

1. `void calculateGameScore(int red, int blue, int green, int yellow, int magenta, int numberCrests)`
   - **Description**: calculates/updates game score based on all realms score and the elemental crests
   - **Parameters**:
     - 6 `int` values: 5 values are the realm scores, and the last value is the elemental crests value
   - **Return Type**: `void`

2. `int getRedRealmScore()`
   - **Description**: the getter of the score of the red realm.
   - **Parameters**:
     - `none`
   - **Return Type**: `int`
     - returns an integer indicating the red realm score.
3. `int getGreenRealmScore()`
   - **Description**: the getter of the score of the green realm.
   - **Parameters**:
     - `none`
   - **Return Type**: `int`
     - returns an integer indicating the green realm score.
4. `int getBlueRealmScore()`
   - **Description**: the getter of the score of the blue realm.
   - **Parameters**:
     - `none`
   - **Return Type**: `int`
     - returns an integer indicating the blue realm score.
5. `int getMagentaRealmScore()`
   - **Description**: the getter of the score of the magenta realm.
   - **Parameters**:
     - `none`
   - **Return Type**: `int`
     - returns an integer indicating the magenta realm score.
6. `int getYellowRealmScore()`
   - **Description**: the getter of the score of the yellow realm.
   - **Parameters**:
     - `none`
   - **Return Type**: `int`
     - returns an integer indicating the yellow realm score.
7. `int getTotalGameScore()`
   - **Description**: the getter of the total game score.
   - **Parameters**:
     - `none`
   - **Return Type**: `int`
     - returns an integer indicating the total game score.

### `PlayerStatus.java`

- **Package**: `game.engine`
- **Type**: Public Enum
- **Description**: This Enum allows us to identify whether the player is active or passive.

=====================

### `Player.java`

- **Package**: `game.engine`
- **Type**: Public Class
- **Description**: This class represents the player that will play the game.

#### Methods:

1. `void updateGameScore()`
   - **Description**: updates game score of a certain player.
   - **Parameters**:
     - `none`
   - **Return Type**: `void`

2. `void addArcaneBoost(ArcaneBoost boost)`
   - **Description**: adds arcane boost.
   - **Parameters**:
     - `ArcaneBoost`: arcane boost that will be added.
   - **Return Type**: `void`

3. `void addTimeWarp(TimeWarp warp)`
   - **Description**: adds time warp.
   - **Parameters**:
     - `TimeWarp`: time warp to be added.
   - **Return Type**: `void`

4. `void addElementalCrest(ElementalCrest crest)`
   - **Description**: adds elemental crest.
   - **Parameters**:
     - `ElementalCrest`: crest to be added.
   - **Return Type**: `void`

5. `void removeTimeWarp()`
   - **Description**: removes time warp.
   - **Parameters**:
     - `none`
   - **Return Type**: `void`

6. `void removeArcaneBoost()`
   - **Description**: removes arcane boost.
   - **Parameters**:
     - `none`
   - **Return Type**: `void`

7. `void setPlayerStatus(PlayerStatus status)`
   - **Description**: the setter of the player status: active or passive.
   - **Parameters**:
     - `PlayerStatus`: status given/will be set to the player.
   - **Return Type**: `void`

8. `void setPlayerName(String name)`
   - **Description**: the setter of the player name.
   - **Parameters**:
     - `String`: name given/will be set to the player.
   - **Return Type**: `void`
   
9. `PlayerStatus getPlayerStatus()`
   - **Description**: the getter of the player status: active or passive.
   - **Parameters**:
     - `none`
   - **Return Type**: `PlayerStatus`
     - returns the `PlayerStatus` of the given player: either active or passive.

10. `String getPlayerName()`
    - **Description**: the getter of the player name.
    - **Parameters**:
      - `none`
    - **Return Type**: `String`
      - returns a string with the player's name.

11. `RedRealm getRedRealm()`
    - **Description**: the getter of the red realm.
    - **Parameters**:
      - `none`
    - **Return Type**: `RedRealm`
      - returns the `RedRealm` of the player.

12. `GreenRealm getGreenRealm()`
    - **Description**: the getter of the green realm.
    - **Parameters**:
      - `none`
    - **Return Type**: `GreenRealm`
      - returns the `GreenRealm` of the player.

13. `BlueRealm getBlueRealm()`
    - **Description**: the getter of the blue realm.
    - **Parameters**:
      - `none`
    - **Return Type**: `BlueRealm`
      - returns the `BlueRealm` of the player.

14. `MagentaRealm getMagentaRealm()`
    - **Description**: the getter of the magenta realm.
    - **Parameters**:
      - `none`
    - **Return Type**: `MagentaRealm`
      - returns the `MagentaRealm` of the player.

15. `YellowRealm getYellowRealm()`
    - **Description**: the getter of the yellow realm.
    - **Parameters**:
      - `none`
    - **Return Type**: `YellowRealm`
      - returns the `YellowRealm` of the player.

16. `Arcaneboost getArcaneBoosts()`
    - **Description**: the getter of arcane boosts.
    - **Parameters**:
      - `none`
    - **Return Type**: `ArcaneBoost`
      - returns the `ArcaneBoost` of the player.

17. `TimeWarp getTimeWarps()`
    - **Description**: the getter of time warps.
    - **Parameters**:
      - `none`
    - **Return Type**: `TimeWarp`
      - returns the `TimeWarp` of the player.

18. `ElementalCrest getElementalCrests()`
    - **Description**: the getter of elemental crests.
    - **Parameters**:
      - `none`
    - **Return Type**: `ElementalCrest`
      - returns the `ElementalCrest` of the player.

19. `GameScore getGameScore()`
    - **Description**: the getter of the game score for a certain player.
    - **Parameters**:
      - `none`
    - **Return Type**: `GameScore`
      - returns the `GameScore` of the player.

20. `ScoreSheet getScoreSheet()`
    - **Description**: the getter of the score sheet of a certain player.
    - **Parameters**:
      - `none`
    - **Return Type**: `ScoreSheet`
      - returns the `ScoreSheet` of the player.

=====================

### `ScoreSheet.java`

- **Package**: `game.engine`
- **Type**: Public Class
- **Description**: This class represents the Score Sheet for each realm.

#### Methods:

1. `Creature getCreatureByRealm(Dice dice)`
   - **Description**: allows the score sheet to access the creature by accessing the dice.
   - **Parameters**:
     - `Dice`: Using the given Dice we can access the realm and then the creature.
   - **Return Type**: `Creature`
     - returns a `Creature` based on the realm (ex: red realm --> returns Dragon, etc.).

2. `RedRealm getRedRealm()`
   - **Description**: the getter of the red realm.
   - **Parameters**:
     - `none`
   - **Return Type**: `RedRealm`
     - returns the `RedRealm`.

3. `GreenRealm getGreenRealm()`
   - **Description**: the getter of the green realm.
   - **Parameters**:
     - `none`
   - **Return Type**: `GreenRealm`
     - returns the `GreenRealm`.

4. `BlueRealm getBlueRealm()`
   - **Description**: the getter of the blue realm.
   - **Parameters**:
     - `none`
   - **Return Type**: `BlueRealm`
     - returns the `BlueRealm`.

5. `MagentaRealm getMagentaRealm()`
   - **Description**: the getter of the magenta realm.
   - **Parameters**:
     - `none`
   - **Return Type**: `MagentaRealm`
     - returns the `MagentaRealm`.

6. `YellowRealm getYellowRealm()`
   - **Description**: the getter of the yellow realm.
   - **Parameters**:
     - `none`
   - **Return Type**: `YellowRealm`
     - returns the `YellowRealm`.

7. `String toString()`
   - **Description**: the toString of the score sheet which gives all score sheets of all realms.
   - **Parameters**:
     - `none`
   - **Return Type**: `String`
     - returns a String of the scoresheets of all realms.

=====================

### `Move.java`

- **Package**: `game.engine`
- **Type**: Public Class
- **Description**: This class represents the moves that the player can make/makes throughout the game. Tis class implements comparable.

#### Methods:

1. `Dice getDice()`
   - **Description**: It is the getter of the dice which will make the move.
   - **Parameters**:
     - `none`
   - **Return Type**: `Dice`
     - returns the `Dice` that will make the move.

2. `Creature getMoveCreature()`
   - **Description**: It is the getter of the creature required to make move.
   - **Parameters**:
     - `none`
   - **Return Type**: `Creature`
     - returns the `Creature` of the move.

3. `String toString()`
   - **Description**: the toString of the move which gives us the dice that attacks and creature that is attacked.
   - **Parameters**:
     - `none`
   - **Return Type**: `String`
     - returns a String of the dice and creature.

4. `int compareTo(Move o)`
   - **Description**: The comparable method that compares different moves.
   - **Parameters**:
     - `Move` : the move that will be compared to this.
   - **Return Type**: `int`
     - return an integer value. It returns -1 if the reward in the parameter is greater and 1 if the reward in the parameter is lower.

=====================

### `GUIGameController.java`

- **Package**: `game.engine`
- **Type**: Public Class
- **Description**: This class extends GameController, implements Runnable, and represents the controller class for the GUI of the game.

#### Methods:

1. `Stage getStage()`
   - **Description**: the getter of the stage.
   - **Parameters**:
     - none
   - **Return Type**: `Stage`

2. `void initializeScoreSheet()`
   - **Description**: initializes score sheet.
   - **Parameters**:
     - none
   - **Return Type**: `void`

3. `void updateScoreSheets()`
   - **Description**: updates score sheets.
   - **Parameters**:
     - none
   - **Return Type**: `void`

4. `void initializeScoreSheet(String player1Name,String player2Name)`
   - **Description**: Takes both players and initializes their score sheets.
   - **Parameters**:
     - `String`: the first player.
     - `String`: the second player.
   - **Return Type**: `void`

5. `boolean isRoundBonusActivated()`
   - **Description**: checks if round bonus is activated.
   - **Parameters**:
     - none
   - **Return Type**: `boolean`
     - returns true if round bonus is activated and false if not.

6. `void resetRoundBonusActivated()`
   - **Description**: sets round bonus activated to false.
   - **Parameters**:
     - none
   - **Return Type**: `void`

7. `void run()`
   - **Description**: fixes/ updates screen when moving/running.
   - **Parameters**:
     - none
   - **Return Type**: `void`

8. `PlayerScoreSheetController getPlayer1ScoreSheetController()`
   - **Description**: the getter of the player score sheet controller of player 1.
   - **Parameters**:
     - none
   - **Return Type**: `PlayerScoreSheetController`

9. `PlayerScoreSheetController getPlayer2ScoreSheetController()`
   - **Description**: the getter of the player score sheet controller of player 2.
   - **Parameters**:
     - none
   - **Return Type**: `PlayerScoreSheetController`

10. `void updateStagePosition()`
    - **Description**: updates the stage position.
    - **Parameters**:
      - none
    - **Return Type**: `void`

11. `void initializeScenes()`
    - **Description**: initializes scenes.
    - **Parameters**:
      - none
    - **Return Type**: `void`

12. `void setChosenColor(RealmColor color)`
    - **Description**: sets the chosen color.
    - **Parameters**:
      - `RealmColor`: the color that will chosen.
    - **Return Type**: `void`

13. `void resetDiceStatus()`
    - **Description**: resets all dices to status of AVAILABLE.
    - **Parameters**:
      - none
    - **Return Type**: `void`

14. `void switchScene(GUIScenes nextScene)`
    - **Description**:  switches scenes.
    - **Parameters**:
      - `GUIScenes`: the scene that we want to switch to.
    - **Return Type**: `void`

15. `void sendUnusedToForgotten()`
    - **Description**: sets the unused dices to the forgotten realm.
    - **Parameters**:
      - none
    - **Return Type**: `void`

16. `boolean checkRoundReward(Player player)`
    - **Description**: checks round rewards for a certain player.
    - **Parameters**:
      - `Player`: the player that we are checking their round rewards.
    - **Return Type**: `boolean`
      - returns true if there are round rewards.

17. `boolean getNextReward()`
    - **Description**: gets next reward.
    - **Parameters**:
      - none
    - **Return Type**: `boolean`
      - tells us if a bonus is activated or not.

18. `boolean checkForPossibleRewards()`
    - **Description**: checks for possible rewards.
    - **Parameters**:
      - none
    - **Return Type**: `boolean`
      - returns true if there are possible rewards and false if not.

19. `void startArcaneSequence()`
    - **Description**: starts the arcane sequence(the point where a player plays the arcane boost).
    - **Parameters**:
      - none
    - **Return Type**: `void`

20. `void endArcaneSequenceActive()`
    - **Description**: ends the arcane sequence(the point where a player plays the arcane boost) for the active player.
    - **Parameters**:
      - none
    - **Return Type**: `void`

21. `void endArcaneSequencePassive()`
    - **Description**: ends the arcane sequence(the point where a player plays the arcane boost) for the passive player.
    - **Parameters**:
      - none
    - **Return Type**: `void`

22. `boolean isArcaneSequenceActive()`
    - **Description**: checks if the active player will play an arcane boost.
    - **Parameters**:
      - none
    - **Return Type**: `boolean`
      - returns true if the active player will and no if not.

23. `boolean isArcaneSequence()`
    - **Description**: checks if the active or passive player will play an arcane boost.
    - **Parameters**:
      - none
    - **Return Type**: `boolean`
      - returns true if active or passive player will and false if neither.

24. `Player getCurrentPlayer()`
    - **Description**: the getter of the current player (active or passive depending who is playing).
    - **Parameters**:
      - none
    - **Return Type**: `Player`
      - the current player.

25. `PlayerSelectorController getPlayerSelectorController()`
    - **Description**: the getter of the player selector controller.
    - **Parameters**:
      - none
    - **Return Type**: `PlayerSelectorController`

26. `Dice getChosenDice()`
    - **Description**: the getter of the chosen dice.
    - **Parameters**:
      - none
    - **Return Type**: `Dice`
      - the chosen dice.

27. `void setChosenDice(Dice dice)`
    - **Description**: sets a chosen dice.
    - **Parameters**:
      - `Dice`: the dice that will be set to be chosen.
    - **Return Type**: `void`

28. `boolean isBonusActivated()`
    - **Description**: checks if bonus is activated.
    - **Parameters**:
      - none
    - **Return Type**: `boolean`
      - returns true if bonus is activated and false if not.

29. `void resetBonusActivated()`
    - **Description**: sets bonusActivated to false.
    - **Parameters**:
      - none
    - **Return Type**: `void`

30. `public Move[] mergeMoves(Move[] red,Move[] green,Move[] blue,Move[]magenta,Move[] yellow,Move[]white)`
    - **Description**: merges all moves from all 6 dices into 1 array.
    - **Parameters**:
      - 6 Arrays of `Move`: arrays of moves from each dice.
    - **Return Type**: Array of `Move`
      - returns an array of `Move` with all moves from all dices.

31. `public void setRoundRewards()`
    - **Description**: Reads round rewards from config file.
    - **Parameters**:
    -   `none`
    - **Return Type**: `void`

//Note: Methods present In superclass will not be rewritten in subclasses to avoid excessive text     
//==============================================ExceptionsPackage==============================================

### `DiceRollException.java`

- **Package**: `game.exceptions`
- **Type**: Public Class
- **Description**: This class represents an exception due to rolling the dice or getting the dice.

=====================

### `ExhaustedResourceExceptio.java`

- **Package**: `game.exceptions`
- **Type**: Public Class
- **Description**: This class represents an exception where the resources are exhausted(null).

=====================

### `InvalidDiceSelectionException.java`

- **Package**: `game.exceptions`
- **Type**: Public Class
- **Description**: This class represents an exception where the dice selection is not valid.

=====================

### `InvalidMoveException.java`

- **Package**: `game.exceptions`
- **Type**: Public Class
- **Description**: This class represents an exception where the make move or move is not valid.

=====================

### `PlayerActionException.java`

- **Package**: `game.exceptions`
- **Type**: Public Class
- **Description**: This class represents an exception due to the player action.

=====================

### `RewardException.java`

- **Package**: `game.exceptions`
- **Type**: Public Class
- **Description**: This class represents an exception due to the rewards.

//Note: Methods present In superclass will not be rewritten in subclasses to avoid excessive text     
//==============================================RealmsPackage==============================================

### `Realms.java`

- **Package**: `game.realms`
- **Type**: Abstract Class
- **Description**: This abstract class represents the super class of all realms. It contains all common methods between all realms.

#### Methods:

1. `boolean attack(int diceValue, Creature creature)`
   - **Description**: Attacks creature with the dice value.
   - **Parameters**:
     - `int`: value to attack with
     - `Creature`: creature to attack
   - **Return Type**: `boolean`
     - returns true if attack is successful and false if unsuccessful.

2. `void initializePreviousAttacks(String[] previousAttacks)`
   - **Description**: initializes previous attacks.
   - **Parameters**:
     - Array of `String`: represents previous attacks.
   - **Return Type**: `void`

3. `void updateTotalRealmScore(int value)`
   - **Description**: updates total realm score.
   - **Parameters**:
     - `int`: value to be added to total realm score.
   - **Return Type**: `void`

4. `Move[] getAllPossibleMoves()`
   - **Description**: gets all possible moves of a certain realm.
   - **Parameters**:
     - `none`
   - **Return Type**: Array of `Move`
     - returns all possible moves and returns an array of `Move`.

5. `Move[] getPossibleMovesForADie(int diceValue,RealmColor colorOfDice)`
   - **Description**: gets possible moves for a certain dice.
   - **Parameters**:
     - `int`: dice value needed to check possible moves.
     - `RealmColor`: the realm that we will check for moves in.
   - **Return Type**: Array of `Move`
     - returns all possible moves for a dice and returns an array of `Move`.

6. `void incrementTotalNumberOfAttacks()`
   - **Description**: increments total number of attacks.
   - **Parameters**:
     - `none`
   - **Return Type**: `void`

7. `void rewardClaimed(int index)`
   - **Description**: claims rewards and updates the rewards array.
   - **Parameters**:
     - `int`: index of reward that was claimed.
   - **Return Type**: `void`

8. `void recordAttack(int diceValue)`
   - **Description**: records attack in previous attacks array.
   - **Parameters**:
     - `int`: diceValue used in attack.
   - **Return Type**: `void`

9. `boolean isRealmDefeated()`
   - **Description**: checks if realm is defeated.
   - **Parameters**:
     - `none`
   - **Return Type**: `boolean`
     - returns true if defeated and false if not.

10. `boolean isRewardAvailable()`
    - **Description**: checks if reward is available in given realm.
    - **Parameters**:
      - `none`
    - **Return Type**: `boolean`
      - returns true if reward is available and false if not.

11. `RealmColor getRealmColor()`
    - **Description**: gets realm color based on realm.
    - **Parameters**:
      - `none`
    - **Return Type**: `RealmColor`

12. `void closeRealm()`
    - **Description**: makes realm not accessible.
    - **Parameters**:
      - `none`
    - **Return Type**: `void`

13. `boolean isRealmAccessible()`
    - **Description**: checks if realm is accessible.
    - **Parameters**:
      - `none`
    - **Return Type**: `boolean`
      - return true if realm is accessible and false if not.

14. `int getTotalRealmScore()`
    - **Description**: gets total realm score.
    - **Parameters**:
      - `none`
    - **Return Type**: `int`
      - returns an integer of the total realm score.

15. `void setTotalRealmScore(int value)`
    - **Description**: sets the total realm score.
    '
    - **Parameters**:
      - `int`: value to set the total realm score.
    - **Return Type**: `void`

16. `int getTotalNumberOfAttacks()`
    - **Description**: gets total number of attacks.
    - **Parameters**:
      - `none`
    - **Return Type**: `int`
      - returns an integer of the total number of attacks.

17. `Reward[] getRealmRewards()`
    - **Description**: gets realm rewards in an array.
    - **Parameters**:
      - `none`
    - **Return Type**: Array of `Reward`
      - returns realm rewards in array of `Reward`.

18. `String[] getPreviousAttacks()`
    - **Description**: gets previous attacks.
    - **Parameters**:
      - `none`
    - **Return Type**: Array of `String`
      - returns previous attacks in an Array of `String`.

19. `Reward[] getReward()`
    - **Description**: gets rewards of a certain realm.
    - **Parameters**:
      - `none`
    - **Return Type**: Array of `Reward`
      - returns an array of `Reward` corresponding to a certain realm.

20. `void setRealmRewards(Reward[] realmRewards)`
    - **Description**: sets realm rewards.
    - **Parameters**:
      - Array of `Reward`: sets the realm rewards 
    - **Return Type**: `void`

21. `Creature getCreatureByRealm(Dice dice)`
    - **Description**: gets creature of a certain realm.
    - **Parameters**:
      - `Dice`
    - **Return Type**: `Creature`

22. `String toString()`
    - **Description**: This is a toString method for the Realms which returns the Score sheet of each realm.
    - **Parameters**:
      - `none`
    - **Return Type**: `String`
      - returns a String that coresponds to the score sheet of a given realm.

=====================

### `RealmColor.java`

- **Package**: `game.realms`
- **Type**: Public Enum
- **Description**: This Enum allows us to identify the realm color: red, green, blue, magenta, yellow, or white(for the white dice).

=====================

### `RedRealm.java`

- **Package**: `game.realms`
- **Type**: Public Class
- **Description**: This class represents how the red realms works with having the four dragons and their info.

#### Methods:

1. `Dragon getDragon1()`
   - **Description**: returns the first Dragon.
   - **Parameters**:
     - `none`
   - **Return Type**: `Dragon`

2. `Dragon getDragon2()`
   - **Description**: returns the second Dragon.
   - **Parameters**:
     - `none`
   - **Return Type**: `Dragon`

3. `Dragon getDragon3()`
   - **Description**: returns the third Dragon.
   - **Parameters**:
     - `none`
   - **Return Type**: `Dragon`

4. `Dragon getDragon4()`
   - **Description**: returns the fourth Dragon.
   - **Parameters**:
     - `none`
   - **Return Type**: `Dragon`

5. `boolean isRegionHit()`
   - **Description**: Check whether a region has been hit (if a part across all dragons are hit).
   - **Parameters**:
     - `none`
   - **Return Type**: `boolean`
     - returns a boolean of true if region is hit and false if not.

6. `boolean isDiagonalRegionHit()`
   - **Description**: Check whether the diagonal region has been hit.
   - **Parameters**:
     - `none`
   - **Return Type**: `boolean`
     - returns a boolean of true if diagonal region is hit and false if not.

=====================

### `GreenRealm.java`

- **Package**: `game.realms`
- **Type**: Public Class
- **Description**:  This class represents the green realm.

#### Methods:

1. `Gaia getGaia()`
   - **Description**: gets the Gaia Creature from the green realm.
   - **Parameters**:
     - `none`
   - **Return Type**: `Gaia`
     - return `Gaia` creature.

=====================

### `BlueRealm.java`

- **Package**: `game.realms`
- **Type**: Public Class
- **Description**:  This class represents the blue realm.

#### Methods:

1. `Hydra getHydra()`
   - **Description**: gets the Hydra Creature from the blue realm.
   - **Parameters**:
     - `none`
   - **Return Type**: `Hydra`
     - return `Hydra` creature.

=====================

### `MagentaRealm.java`

- **Package**: `game.realms`
- **Type**: Public Class
- **Description**:  This class represents the magenta realm.

#### Methods:

1. `Phoenix getPhoenix()`
   - **Description**: gets the Phoenix Creature from the magenta realm.
   - **Parameters**:
     - `none`
   - **Return Type**: `Phoenix`
     - return `Phoenix` creature.

=====================

### `YellowRealm.java`

- **Package**: `game.realms`
- **Type**: Public Class
- **Description**: This class represents the yellow realm.

#### Methods:

1. `Lion getLion()`
   - **Description**: gets the Lion Creature from the yellow realm.
   - **Parameters**:
     - `none`
   - **Return Type**: `Lion`
     - return `Lion` creature.

==============================================GUIPackage==============================================

### `SceneController.java`

- **Package**: `game.gui`
- **Type**: Abstract Class
- **Description**: This class represents the scenes super class.

#### Methods:

1. `void finishAttack()`
   - **Description**: updates gui after finishing attack.
   - **Parameters**:
     - none
   - **Return Type**: `void`

2. `void dontCheckRewards()`
   - **Description**: updates the dontCheckRewards boolean to false.
   - **Parameters**:
     - none
   - **Return Type**: `void`

3. `void enteredObject(MouseEvent e)`
   - **Description**: sets the opacity of an entered object to 0.8.
   - **Parameters**:
     - `MouseEvent`: mouse needed.
   - **Return Type**: `void`

4. `void exitedObject(MouseEvent e)`
   - **Description**: sets the opacity of an entered object to 1.
   - **Parameters**:
     - `MouseEvent`: mouse needed.
   - **Return Type**: `void`

5. `void switchToScene(GUIScenes scenes)`
   - **Description**: switches to a certain scene.
   - **Parameters**:
     - `GUIScenes`: takes the enum to get the scene i want to switch to.
   - **Return Type**: `void`

6. `GUIGameController getGuiGameController()`
   - **Description**: the getter of the gui game controller.
   - **Parameters**:
     - none
   - **Return Type**: `GUIGameController`
     - returns `GUIGameController` 

7. `void initialize()`
   - **Description**: Used to initialize images and other components to prevent errors.
   - **Parameters**:
     - none
   - **Return Type**: `void`

=====================

### `ScoreSheetsController.java`

- **Package**: `game.gui`
- **Type**: Abstract Class
- **Description**: This class represents the scoresheets super class.

#### Methods:

1. `Image getImage(String rew)`
   - **Description**: image getter based on a string.
   - **Parameters**:
     - `String`: String that represents the which image to get.
   - **Return Type**: `Image`
     - returns the image.

2. `GUIGameController getGuiGameController()`
   - **Description**: getter of the game controller.
   - **Parameters**:
     - none
   - **Return Type**: `GUIGameController`
     - returns the gui game controller.

3. `void switchScoreScene(MouseEvent e)`
   - **Description**: switches score scene.
   - **Parameters**:
     - `MouseEvent`: event needed to switch scene. 
   - **Return Type**: `void`

4. `void switchScoreScreen(char color,Player player)`
   - **Description**: switches scorescreen based on color for a certain player.
   - **Parameters**:
     - `char`: represents the color.
     - `Player`: a certain players score screen.
   - **Return Type**: `void`

5. `void initialize()`
   - **Description**: Used to initialize images and other components to prevent errors.
   - **Parameters**:
     - none
   - **Return Type**: `void`

=====================

### `BlueRealm.fxml`

- **Package**: `game.gui`
- **Type**: fxml file
- **Description**: This fxml file represents the blue realm.

=====================

### `BlueRealmController.java`

- **Package**: `game.gui`
- **Type**: Public Class
- **Description**: This class extends the SceneController class and represents the controller for the blue realm scene.

#### Methods:

1. `void setBlueRealm()`
   - **Description**: sets the blue realm in the gui.
   - **Parameters**:
     - none
   - **Return Type**: `void`

2. `void attack(MouseEvent e)`
   - **Description**: allows the player to attack and makes a move.
   - **Parameters**:
     - `MouseEvent`: mouse needed to attack.
   - **Return Type**: `void`

3. `void hover(MouseEvent e)`
   - **Description**: changes opacity to hover.
   - **Parameters**:
     - `MouseEvent`: mouse needed to hover.
   - **Return Type**: `void`

4. `void hoverExit(MouseEvent e)`
   - **Description**: sets back opacity to original
   - **Parameters**:
     - `MouseEvent`: mouse needed to exit hover.
   - **Return Type**: `void`

=====================

### `BScoreController.java`

- **Package**: `game.gui`
- **Type**: Public Class
- **Description**: This class extends ScoreSheetController and represents the blue score sheet controller.

#### Methods:

1. `void setScoreSheet(Player player)`
   - **Description**: sets the player score sheet.
   - **Parameters**:
     - `Player`: String that represents the which image to get.
   - **Return Type**: `void`

2. `void switchScoreScene(MouseEvent e)`
   - **Description**: switches score scene.
   - **Parameters**:
     - `MouseEvent`: mouse needed to switch the score scene.
   - **Return Type**: `void`

3. `void enteredObject(MouseEvent e)`
   - **Description**: sets the opacity of an entered object to 0.8.
   - **Parameters**:
     - `MouseEvent`: mouse needed.
   - **Return Type**: `void`

4. `void exitedObject(MouseEvent e)`
   - **Description**: sets the opacity of an entered object to 1.
   - **Parameters**:
     - `MouseEvent`: mouse needed.
   - **Return Type**: `void`

5. `void updateAT()`
   - **Description**: updates arcane boosts, time warps, and round rewards
   - **Parameters**:
     - none
   - **Return Type**: `void`

6. `void updateBlueScoreSheet()`
   - **Description**: updates blue score sheet.
   - **Parameters**:
     - none
   - **Return Type**: `void`

=====================

### `BScoreSheet.fxml`

- **Package**: `game.gui`
- **Type**: fxml file
- **Description**: This fxml file represents the blue score sheet.

=====================

### `ColorPicker.fxml`

- **Package**: `game.gui`
- **Type**: fxml file
- **Description**: This class represents ?

=====================

### `ColorPickerController.java`

- **Package**: `game.gui`
- **Type**: Public Class
- **Description**: This class extends Scene controller and it controls the color picker during essence bonuses, and anything else that needs it.

#### Methods:

1. `void updateScene()`
   - **Description**: updates scene based on color picked.
   - **Parameters**:
     - none
   - **Return Type**: `void`

2. `void enteredObject(MouseEvent e)`
   - **Description**: sets the opacity of an entered object to 0.8, and changes the color based on the color picked.
   - **Parameters**:
     - `MouseEvent`: mouse needed.
   - **Return Type**: `void`

3. `void exitedObject(MouseEvent e)`
   - **Description**: sets the opacity of an entered object to 1, and changes the color based on the color picked.
   - **Parameters**:
     - `MouseEvent`: mouse needed.
   - **Return Type**: `void`

4. `void red(MouseEvent e)`
   - **Description**: moves to red realm.
   - **Parameters**:
     - `MouseEvent`: mouse needed to go to red realm.
   - **Return Type**: `void`

5. `void green(MouseEvent e)`
   - **Description**: moves to green realm.
   - **Parameters**:
     - `MouseEvent`: mouse needed to go to green realm.
   - **Return Type**: `void`

6. `void blue(MouseEvent e)`
   - **Description**: moves to blue realm.
   - **Parameters**:
     - `MouseEvent`: mouse needed to go to blue realm.
   - **Return Type**: `void`

7. `void magetna(MouseEvent e)`
   - **Description**: moves to magenta realm.
   - **Parameters**:
     - `MouseEvent`: mouse needed to go to magenta realm.
   - **Return Type**: `void`

8. `void yellow(MouseEvent e)`
   - **Description**: moves to yellow realm.
   - **Parameters**:
     - `MouseEvent`: mouse needed to go to yellow realm.
   - **Return Type**: `void`

=====================

### `DiceRealms.java`

- **Package**: `game.gui`
- **Type**: Public Class
- **Description**: This class extends application and represents the main game class where we run the gui.

#### Methods:

1. `public void start(Stage primaryStage)`
   - **Description**: the start methods that displays the primary stage.
   - **Parameters**:
     - `Stage`: the primary stage used.
   - **Return Type**: `void`

2. `GUIGameController getGUIGameController()`
   - **Description**: getter of the gui game controller.
   - **Parameters**:
     - none
   - **Return Type**: `GUIGameController`

3. `void main(String[] args)`
   - **Description**: sets the blue realm in the gui.
   - **Parameters**:
     - an Array of `String` (args)
   - **Return Type**: `void`

=====================

### `DiceScreen.fxml`

- **Package**: `game.gui`
- **Type**: fxml file
- **Description**: This class represents ?

=====================

### `DiceScreenController.java`

- **Package**: `game.gui`
- **Type**: Public Class
- **Description**: This class represents the dice screen controller.

#### Methods:

1. `void updateScene()`
   - **Description**: updates scene.
   - **Parameters**:
     - none
   - **Return Type**: `void`

2. `void attack(MouseEvent e)`
   - **Description**: allows the player to attack and makes a move.
   - **Parameters**:
     - `MouseEvent`: mouse needed to attack.
   - **Return Type**: `void`

3. `void enteredObject(MouseEvent e)`
   - **Description**: sets the opacity of an entered object to 0.8.
   - **Parameters**:
     - `MouseEvent`: mouse needed.
   - **Return Type**: `void`

4. `void exitedObject(MouseEvent e)`
   - **Description**: sets the opacity of an entered object to 1.
   - **Parameters**:
     - `MouseEvent`: mouse needed.
   - **Return Type**: `void`

5. `void rollDice(ActionEvent e)`
   - **Description**: rolls dice.
   - **Parameters**:
     - `ActionEventEvent`: action event needed.
   - **Return Type**: `void`

6. `void usePower(MouseEvent e)`
   - **Description**: uses power.
   - **Parameters**:
     - `MouseEvent`: mouse needed to use power.
   - **Return Type**: `void`

7. `void rejectPower(MouseEvent e)`
   - **Description**: sets the opacity of an entered object to 1.
   - **Parameters**:
     - `MouseEvent`: mouse needed to reject the power.
   - **Return Type**: `void`

8. `boolean shouldSkipTurn()`
   - **Description**: checks if i should skip turn.
   - **Parameters**:
     - none
   - **Return Type**: `boolean`
     - returns true if i should skip turn or not.

9. `void promptToSkipTurn()`
   - **Description**: gives the prompt to skip turn.
   - **Parameters**:
     - none
   - **Return Type**: `void`

10. `void skipTurn(ActionEvent e)`
    - **Description**: skips turn/ finishes attack.
    - **Parameters**:
      - `ActionEvent`: event needed to skip turn.
    - **Return Type**: `void`

11. `void skipsth(ActionEvent e)`
    - **Description**: end round/ skips turn.
    - **Parameters**:
      - `ActionEvent`: event needed .
    - **Return Type**: `void`

12. `void promptToEndRound()`
    - **Description**: prompt to end round.
    - **Parameters**:
      - none
    - **Return Type**: `void`

13. `void endRound(ActionEvent e)`
    - **Description**: ends round.
    - **Parameters**:
      - `ActionEvent`: event needed to end round.
    - **Return Type**: `void`

14. `void ToggleDiceView(ActionEvent e)`
    - **Description**: toggles the dice view.
    - **Parameters**:
      - `ActionEvent`: event needed to toggle the dice view.
    - **Return Type**: `void`

15. `void getRoundReward()`
    - **Description**: getter of round rewards.
    - **Parameters**:
      - none
    - **Return Type**: `void`

16. `void shouldGetRoundReward()`
    - **Description**: checks if could get round rewards.
    - **Parameters**:
      - none
    - **Return Type**: `void`

17. `void updateDiceData()`
    - **Description**: updates dice data.
    - **Parameters**:
      - none
    - **Return Type**: `void`

18. `void updatePlayerData(Player player1,Player player2)`
    - **Description**: updates players data.
    - **Parameters**:
      - `Player`: first player.
      - `Player`: second player.
    - **Return Type**: `void`

19. `void viewArcaneSequence()`
    - **Description**: views arcane sequence.
    - **Parameters**:
      - none
    - **Return Type**: `void`

=====================

### `GameEnd.fxml`

- **Package**: `game.gui`
- **Type**: fxml file
- **Description**: This class represents ?

=====================

### `GameEndController.java`

- **Package**: `game.gui`
- **Type**: Public Class
- **Description**: This class extends scene controller and represents the end of the game.

#### Methods:

1. `void updateScene()`
   - **Description**: updates scene.
   - **Parameters**:
     - none
   - **Return Type**: `void`

=====================

### `GreenRealm.fxml`

- **Package**: `game.gui`
- **Type**: fxml file
- **Description**: This fxml file represents the green realm.

=====================

### `GreenRealmController.java`

- **Package**: `game.gui`
- **Type**: Public Class
- **Description**: This class extends the SceneController class and represents the controller for the green realm scene.

#### Methods:

1. `void setGreenRealm()`
   - **Description**: sets the green realm in the gui.
   - **Parameters**:
     - none
   - **Return Type**: `void`

2. `void attack(MouseEvent e)`
   - **Description**: allows the player to attack and makes a move.
   - **Parameters**:
     - `MouseEvent`: mouse needed to attack.
   - **Return Type**: `void`

3. `void hover(MouseEvent e)`
   - **Description**: changes opacity to hover.
   - **Parameters**:
     - `MouseEvent`: mouse needed to hover.
   - **Return Type**: `void`

4. `void hoverExit(MouseEvent e)`
   - **Description**: sets back opacity to original
   - **Parameters**:
     - `MouseEvent`: mouse needed to exit hover.
   - **Return Type**: `void`

5. `void setOpacity(StackPane pane, double opacity)`
   - **Description**: sets opacity.
   - **Parameters**:
     - `StackPane`: pane that we set the opacity of.
     - `double`: the value of the opacity
   - **Return Type**: `void`

=====================

### `GScoreController.java`

- **Package**: `game.gui`
- **Type**: Public Class
- **Description**: This class extends ScoreSheetController and represents the green score sheet controller.

#### Methods:

1. `void setScoreSheet(Player player)`
   - **Description**: sets the player score sheet.
   - **Parameters**:
     - `Player`: String that represents the which image to get.
   - **Return Type**: `void`

2. `void switchScoreScene(MouseEvent e)`
   - **Description**: switches score scene.
   - **Parameters**:
     - `MouseEvent`: mouse needed to switch the score scene.
   - **Return Type**: `void`

3. `void enteredObject(MouseEvent e)`
   - **Description**: sets the opacity of an entered object to 0.8.
   - **Parameters**:
     - `MouseEvent`: mouse needed.
   - **Return Type**: `void`

4. `void exitedObject(MouseEvent e)`
   - **Description**: sets the opacity of an entered object to 1.
   - **Parameters**:
     - `MouseEvent`: mouse needed.
   - **Return Type**: `void`

5. `void updateAT()`
   - **Description**: updates arcane boosts, time warps, and round rewards
   - **Parameters**:
     - none
   - **Return Type**: `void`

6. `void updateGreenScoreSheet()`
   - **Description**: updates green score sheet.
   - **Parameters**:
     - none
   - **Return Type**: `void`

=====================

### `GScoreSheet.fxml`

- **Package**: `game.gui`
- **Type**: fxml file
- **Description**: This fxml file represents the green score sheet.

=====================

### `GUIScenes.java`

- **Package**: `game.gui`
- **Type**: Public Enum
- **Description**: This enum contains all the gui scenes.

=====================

### `Instruction1Controller.java`

- **Package**: `game.gui`
- **Type**: Public Enum
- **Description**: This enum contains all the gui scenes.

#### Methods:

1. `void next(ActionEvent e)`
   - **Description**: goes to the next page of instructions.
   - **Parameters**:
     - `ActionEvent`: event needed to go to the next page of instructions.
   - **Return Type**: `void`

=====================

### `instruction2.fxml`

- **Package**: `game.gui`
- **Type**: fxml file
- **Description**: This fxml file represents the second scene of instructions.

=====================

### `Instruction2Controller.java`

- **Package**: `game.gui`
- **Type**: Public Class
- **Description**: This enum contains all the gui scenes.

#### Methods:

1. `void end(ActionEvent e)`
   - **Description**: ends the display of the instructions.
   - **Parameters**:
     - `ActionEvent`: event needed to end display.
   - **Return Type**: `void`

2. `void back(ActionEvent e)`
   - **Description**: goes back to the first page of instructions.
   - **Parameters**:
     - `ActionEvent`: event needed to go to the first page of instructions.
   - **Return Type**: `void`

=====================

### `instructions.fxml`

- **Package**: `game.gui`
- **Type**: fxml file
- **Description**: This fxml file represents the first scene of instructions.

=====================

### `MagentaRealm.fxml`

- **Package**: `game.gui`
- **Type**: fxml file
- **Description**: This fxml file represents the magenta realm.

=====================

### `MagentaRealmController.java`

- **Package**: `game.gui`
- **Type**: Public Class
- **Description**: This class extends the SceneController class and represents the controller for the Magenta realm scene.

#### Methods:

1. `void setMagentaRealm()`
   - **Description**: sets the magenta realm in the gui.
   - **Parameters**:
     - none
   - **Return Type**: `void`

2. `void attackPhoenix(MouseEvent e)`
   - **Description**: allows the player to attack and makes a move.
   - **Parameters**:
     - `MouseEvent`: mouse needed to attack.
   - **Return Type**: `void`

3. `void enterPhoenix(MouseEvent e)`
   - **Description**: changes opacity of the Phoenix.
   - **Parameters**:
     - `MouseEvent`: mouse needed to hover.
   - **Return Type**: `void`

4. `void exitPhoenix(MouseEvent e)`
   - **Description**: sets back opacity in Phoenix.
   - **Parameters**:
     - `MouseEvent`: mouse needed to exit hover.
   - **Return Type**: `void`

=====================

### `MainMenu.fxml`

- **Package**: `game.gui`
- **Type**: fxml file
- **Description**: This class represents the main menu.

=====================

### `MainMenuController.java`

- **Package**: `game.gui`
- **Type**: Public Class
- **Description**: This class extends scene controller and represents the main menu controller.

#### Methods:

1. `void startGame(MouseEvent e)`
   - **Description**: starts game.
   - **Parameters**:
     - `MouseEvent`: mouse needed to start game.
   - **Return Type**: `void`

2. `void enteredObject(MouseEvent e)`
   - **Description**: sets the opacity of an entered object to 0.8, and changes the color based on the color picked.
   - **Parameters**:
     - `MouseEvent`: mouse needed.
   - **Return Type**: `void`

3. `void exitedObject(MouseEvent e)`
   - **Description**: sets the opacity of an entered object to 1, and changes the color based on the color picked.
   - **Parameters**:
     - `MouseEvent`: mouse needed.
   - **Return Type**: `void`

4. `void startGameAI(MouseEvent e)`
   - **Description**: starts game with ai.
   - **Parameters**:
     - `MouseEvent`: mouse needed to start the game with ai.
   - **Return Type**: `void`

=====================

### `MScoreController.java`

- **Package**: `game.gui`
- **Type**: Public Class
- **Description**: This class extends ScoreSheetController and represents the magenta score sheet controller.

#### Methods:

1. `void setScoreSheet(Player player)`
   - **Description**: sets the player score sheet.
   - **Parameters**:
     - `Player`: String that represents the which image to get.
   - **Return Type**: `void`

2. `void switchScoreScene(MouseEvent e)`
   - **Description**: switches score scene.
   - **Parameters**:
     - `MouseEvent`: mouse needed to switch the score scene.
   - **Return Type**: `void`

3. `void enteredObject(MouseEvent e)`
   - **Description**: sets the opacity of an entered object to 0.8.
   - **Parameters**:
     - `MouseEvent`: mouse needed.
   - **Return Type**: `void`

4. `void exitedObject(MouseEvent e)`
   - **Description**: sets the opacity of an entered object to 1.
   - **Parameters**:
     - `MouseEvent`: mouse needed.
   - **Return Type**: `void`

5. `void updateAT()`
   - **Description**: updates arcane boosts, time warps, and round rewards
   - **Parameters**:
     - none
   - **Return Type**: `void`

6. `void updateMagentaScoreSheet()`
   - **Description**: updates magenta score sheet.
   - **Parameters**:
     - none
   - **Return Type**: `void`

=====================

### `MScoreSheet.fxml`

- **Package**: `game.gui`
- **Type**: fxml file
- **Description**: This fxml file represents the magenta score sheet.

=====================

### `MusicPlayer.java`

- **Package**: `game.gui`
- **Type**: Public Class
- **Description**: This class represents the class that will set the music throughout the game.

=====================

### `PlayerScoreSheetController.java`

- **Package**: `game.gui`
- **Type**: Public Class
- **Description**: This class represents the player score sheet.

#### Methods:

1. `void switchScoreSheets(char color)`
   - **Description**: switches score sheets based on color.
   - **Parameters**:
     - `char`: char representing the color. 
   - **Return Type**: `void`

2. `Player getScoreSheetPlayer()`
   - **Description**: returns player of a certain scoresheet.
   - **Parameters**:
     - none 
   - **Return Type**: `Player`

3. `void updateScoreSheets()`
   - **Description**: updates score sheets of player.
   - **Parameters**:
     - none
   - **Return Type**: `void`

=====================

### `PlayerSelector.fxml`

- **Package**: `game.gui`
- **Type**: fxml file
- **Description**: This fxml file represents the player selector (active or passive).

=====================

### `PlayerSelectorController.java`

- **Package**: `game.gui`
- **Type**: Public Class
- **Description**: This class extends scene controller and represents the player selector controller where the player is selected based on a dice roll.

#### Methods:

1. `void setNames(String player1, String player2)`
   - **Description**: switches score sheets based on color.
   - **Parameters**:
     - `String`: String representing name of player1. 
     - `String`: String representing name of player2. 
   - **Return Type**: `void`

2. `void rollDice(MouseEvent e)`
   - **Description**: rolls dice.
   - **Parameters**:
     - `MouseEvent`: mouse needed to roll dice.
   - **Return Type**: `void`

3. `void switchToDiceScreen(ActionEvent e)`
   - **Description**: switches to dice screen.
   - **Parameters**:
     - `ActionEvent`: event needed to switch.
   - **Return Type**: `void`

=====================

### `RedRealm.fxml`

- **Package**: `game.gui`
- **Type**: fxml file
- **Description**: This fxml file represents the red realm.

=====================

### `RedRealmController.java`

- **Package**: `game.gui`
- **Type**: Public Class
- **Description**: This class extends the SceneController class and represents the controller for the red realm scene.

#### Methods:

1. `void setRedRealm(int dice)`
   - **Description**: sets the red realm in the gui.
   - **Parameters**:
     - `int` : integer of dice needed to chack available dragons to attack.
   - **Return Type**: `void`

2. `void attack(MouseEvent e)`
   - **Description**: allows the player to attack and makes a move.
   - **Parameters**:
     - `MouseEvent`: mouse needed to attack.
   - **Return Type**: `void`

3. `void hover(MouseEvent e)`
   - **Description**: changes opacity to hover.
   - **Parameters**:
     - `MouseEvent`: mouse needed to hover.
   - **Return Type**: `void`

4. `void hoverExit(MouseEvent e)`
   - **Description**: sets back opacity to original
   - **Parameters**:
     - `MouseEvent`: mouse needed to exit hover.
   - **Return Type**: `void`

5. `void setDragonCircles(Dragon dragon,int dice)`
   - **Description**: sets circles on dragon parts to attack.
   - **Parameters**:
     - `int`: integer of dice needed to chack available dragons to attack.
     - `Dragon`: Dragon to be attacked and will have circles in place of attack.
   - **Return Type**: `void`

6. `void switchDragon(ActionEvent e)`
   - **Description**: switches the dragon displayed.
   - **Parameters**:
     - `ActionEvent`: event needed to switch dragon.
   - **Return Type**: `void`

=====================

### `RScoreController.java`

- **Package**: `game.gui`
- **Type**: Public Class
- **Description**: This class extends ScoreSheetController and represents the red score sheet controller.

#### Methods:

1. `void setScoreSheet(Player player)`
   - **Description**: sets the player score sheet.
   - **Parameters**:
     - `Player`: String that represents the which image to get.
   - **Return Type**: `void`

2. `void switchScoreScene(MouseEvent e)`
   - **Description**: switches score scene.
   - **Parameters**:
     - `MouseEvent`: mouse needed to switch the score scene.
   - **Return Type**: `void`

3. `void enteredObject(MouseEvent e)`
   - **Description**: sets the opacity of an entered object to 0.8.
   - **Parameters**:
     - `MouseEvent`: mouse needed.
   - **Return Type**: `void`

4. `void exitedObject(MouseEvent e)`
   - **Description**: sets the opacity of an entered object to 1.
   - **Parameters**:
     - `MouseEvent`: mouse needed.
   - **Return Type**: `void`

5. `void updateAT()`
   - **Description**: updates arcane boosts, time warps, and round rewards
   - **Parameters**:
     - none
   - **Return Type**: `void`

6. `void updateRedScoreSheet()`
   - **Description**: updates red score sheet.
   - **Parameters**:
     - none
   - **Return Type**: `void`


=====================

### `RScoreSheet.fxml`

- **Package**: `game.gui`
- **Type**: fxml file
- **Description**: This fxml file represents the red score sheet.

=====================

### `UserName.fxml`

- **Package**: `game.gui`
- **Type**: fxml file
- **Description**: This fxml file represents the scene where the user name is taken as input.

=====================

### `UserNameController.java`

- **Package**: `game.gui`
- **Type**: Public Class
- **Description**: This class extends SceneController and represents the controller that takes the user name as input.

#### Methods:

1. `void submit(ActionEvent e)`
   - **Description**: submits names of wizards.
   - **Parameters**:
     - `ActionEvent`: event needed to submit the names.
   - **Return Type**: `void`

2. `void selectWizard(MouseEvent e)`
   - **Description**: selects wizard.
   - **Parameters**:
     - `MouseEvent`: mouse needed to select wizard
   - **Return Type**: `void`

3. `void updateWizardName(KeyEvent e)`
   - **Description**: updates wizard name.
   - **Parameters**:
     - `KeyEvent`: event needed to update wizard name under each wizard.
   - **Return Type**: `void`

=====================

### `YellowRealm.fxml`

- **Package**: `game.gui`
- **Type**: fxml file
- **Description**: This fxml file represents the yellow realm.

=====================

### `YellowRealmController.java`

- **Package**: `game.gui`
- **Type**: Public Class
- **Description**: This class extends the SceneController class and represents the controller for the yellow realm scene.

#### Methods:

1. `void setYellowRealm()`
   - **Description**: sets the yellow realm in the gui.
   - **Parameters**:
     - none
   - **Return Type**: `void`

2. `void attackLion(MouseEvent e)`
   - **Description**: allows the player to attack and makes a move.
   - **Parameters**:
     - `MouseEvent`: mouse needed to attack.
   - **Return Type**: `void`

3. `void EnterLion(MouseEvent e)`
   - **Description**: changes opacity of lion image to 0.8.
   - **Parameters**:
     - `MouseEvent`: mouse needed to hover.
   - **Return Type**: `void`

4. `void exitLion(MouseEvent e)`
   - **Description**: changes opacity of lion image to 1.
   - **Parameters**:
     - `MouseEvent`: mouse needed to exit hover.
   - **Return Type**: `void`


=====================

### `YScoreController.java`

- **Package**: `game.gui`
- **Type**: Public Class
- **Description**:  This class extends ScoreSheetController and represents the yellow score sheet controller.

#### Methods:

1. `void setScoreSheet(Player player)`
   - **Description**: sets the player score sheet.
   - **Parameters**:
     - `Player`: String that represents the which image to get.
   - **Return Type**: `void`

2. `void switchScoreScene(MouseEvent e)`
   - **Description**: switches score scene.
   - **Parameters**:
     - `MouseEvent`: mouse needed to switch the score scene.
   - **Return Type**: `void`

3. `void enteredObject(MouseEvent e)`
   - **Description**: sets the opacity of an entered object to 0.8.
   - **Parameters**:
     - `MouseEvent`: mouse needed.
   - **Return Type**: `void`

4. `void exitedObject(MouseEvent e)`
   - **Description**: sets the opacity of an entered object to 1.
   - **Parameters**:
     - `MouseEvent`: mouse needed.
   - **Return Type**: `void`

5. `void updateAT()`
   - **Description**: updates arcane boosts, time warps, and round rewards
   - **Parameters**:
     - none
   - **Return Type**: `void`

6. `void updateYellowScoreSheet()`
   - **Description**: updates yellow score sheet.
   - **Parameters**:
     - none
   - **Return Type**: `void`

=====================

### `YScoreSheet.fxml`

- **Package**: `game.gui`
- **Type**: fxml file
- **Description**: This fxml file represents the yellow score sheet.