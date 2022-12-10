# Level Design Demo

<p align="center">
<img width="720" alt="Screen Shot 2022-12-09 at 11 12 19 PM" src="https://user-images.githubusercontent.com/67125579/206830441-ab876434-8a2b-4ff3-9d76-33da543afcd2.png">
</p>

## Getting Started

Simply clone or download this game using `git clone`. You can double click the `cs415_mp2.uproject` file to open it in Unreal Engine or you can just open the folder in Unreal Engine. 

### Installing

Open this folder in [unreal engine](https://www.unrealengine.com/). Then hit the `play` button. The game will build and allow you to play it in a demo video. 

### Design Document
When I saw the map in the demo project, I was inspired to make a level on the same land using some of the static meshes provided to us. I imagined breaking up the island into different chunks and allowing the player to interact with different kinds of featured enemies at each stage. 

The first stage, the player gets to get off the platform and interact with the mortar enemy which shoots exploding bombs in an arc. If the player manages to avoid that, they can progress through three round gates into an area with my custom enemy, the landmine. If the player intersects with the landmine, they die instantly. 

There are two more gates into the center part. Here I envisioned that the player could get a bunch of health pickups in case they got hit by the mortar and needed some more health points. But they would have to avoid the pursuer enemy who follows you if you get too close to him within the boundary. If you don’t get close to him, he kinda just loops around. 

Then there’s a gate that indicates you must go through it and up into the house to go further in the level. There are some stairs you must climb. If you venture far away from the path, you could die from falling off the island or colliding into the landmines. Once you enter the courtyard, there are some more landmines. 

Finally, inside the house, there are some health pickups and some landmines to trick you into picking them up and getting killed. But if you keep your eyes on the prize and cross the portal, you will win the game. 

## Authors

@drshika   
[Epic Team - Unreal Learning Kit](https://www.unrealengine.com/marketplace/en-US/product/unreal-learning-kit)

## License

See [LICENSE](https://github.com/drshika/level-design/blob/main/LICENSE).
