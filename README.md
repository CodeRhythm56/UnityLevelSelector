# UnityLevelSelector
Select series of levels to choose from. Uses array of buttons that disables levels that are not unlocked. 
This script uses PlayerPrefs in order to store unlocked levels data of the player. The name of the variable is "LevelReached" but feel free to manipulate. LoadLevel() can be called on an event user clicks level button. The start function goes through all the level buttons and enables them if unlocked.
