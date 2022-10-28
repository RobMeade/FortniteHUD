# Recreating the Fortnite HUD

This project was an experiment to see how challenging it might be to recreate elements from the player HUD in Fortnite.

The project focused mainly on the user-interface, but includes a separate interface to allow the selection of elements and change their values.  Some interactions merely output text to the screen.

It was an interesting learning exercise, despite being familiar with the game, having played it, I was surprised at how much there was to the user-interface.  Whilst it appears simplistic and basic, it involves a lot of functionality.

## UI Features

- Mini map
- Cardinal and intercardinal compass points
- Compass degrees based on player direction
- Storm shrink / wait timer
- Remaining players
- Player eliminations
- Team eliminations
- Player elimination messages
- Health / shield
- Experience / level
- Opening / closing of inventory
- Materials (wood, brick, metal)
- Build mode toggle
- Build item (wall, floor, stairs, pyramid)
- Crosshair
- Current / total ammunition
- Load out item selection

## Development

The project was created using Unreal Engine (4.25).  Code was written using Blueprint.  The project makes use of Blueprint Components, DataTables, Structs and Enums to support the HUD and interactive user-interface.  As the focus was purely on recreating the player HUD, the default first-person shooter template was used for convenience.

## Screenshots

HUD<br/>
![HUD](/Images/HUD_01.PNG)

![HUD](/Images/HUD_02.PNG)

Interactive Interface<br/>
![Interactive Interface](/Images/InteractiveInterface.PNG)



