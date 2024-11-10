# City Generator

<img alt="Sprawling City" title="Sprawling City" width="250px" src="img/anim.gif"/>

A geometry-nodes-based city generator for Blender 4.2.1 LTS! It'll probably also work in later versions, but I haven't tested so I can't be sure

## How to use

- Ensure you have Blender 4.2.1 LTS or later installed - if you don't, you can install it the lates version of Blender [here](https://www.blender.org/download/)
- Download the latest City Generator Blender file from the [releases page](https://github.com/AxiDragon/city-generator/releases) and open it
- In the bottom-left, you can modify the values to change the appearance of the city
<img alt="Modifiers" title="Modifiers" width="250px" src="img/modifier.jpg"/>

- If you want to change the appearance of the materials, you can modify them in the materials tab
<img alt="Materials" title="Materials" width="250px" src="img/material.jpg"/>

- If you want to use the city generator in another Blender file, in the other Blender file, press File > Append in the top left.
<img alt="Append" title="Append" width="250px" src="img/append.jpg"/>

- Navigate to the City Generator Blender file, open it, and select the City object in the Object folder, and click Append.

## Examples
<img alt="Small City 1" title="Small City 1" src="img/small1.png"/>
<img alt="Small City 2" title="Small City 2" src="img/small2.png"/>
<img alt="City 1" title="City 1" src="img/medium1.png"/>
<img alt="City 2" title="City 2" src="img/medium2.png"/>
<img alt="Big City 1" title="Big City 1" src="img/big1.png"/>
<img alt="Big City 2" title="Big City 2" src="img/big2.png"/>

## Known Issues

- Setting BuildingHeight to a low value (less than 1) makes the city sprawl to the edges of the grid, resulting in an unnatural look
