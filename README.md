# HexWorldGen-Unity2020.3.12

A system for creating natural-looking biomes in a hexagon based world.

Automatically creates hexagons using unity's mesh definition functions, and assigns world co-ordinates with the cubic system

These are given an invisible texture, and populated with a further 44 hexagons (this function is recusive, allowing a theoretically infinte level of detail)

From noise maps, the lesser hexagons are assigned a height, and a biome from comparing their temparature and precipitation

Maps curtesy of [open simplex 2](https://github.com/KdotJPG/OpenSimplex2)

Most of this is just putting theory from [RedBlobGames](redblobgames.com/grids/hexagons/) into practice

![Worldgen](https://user-images.githubusercontent.com/65967700/140128255-320ca71e-bb70-4b1e-838d-d5faa86fbf55.png)
