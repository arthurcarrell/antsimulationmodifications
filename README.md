 # Ant Simulation
Ant Simulation is a program that allows a user to see how ant populations change over time. Like all simulations, it is a simplified version of what happens in the real world.

In the simulation there are one or more ant nests, some ants and some food sources. The “world” is represented as a two-dimensional grid.

The simulation contains two of the many different types of ant that exist in the real world – queen ants and worker ants.

Queen ants stay in their nest and reproduce (create new ants). They are only able to reproduce when there is enough food at the nest to allow the population to increase.

Worker ants move randomly around the grid searching for a source of food. When they find one, they bring some food from the source back to their nest, laying a pheromone (scent) trail as they return to their nest. This pheromone trail is used so ants can follow it to the source of food.

If a worker ant detects a pheromone trail, they stop moving randomly and follow the pheromone trail instead. If there are several pheromones detected, the ant will follow the trail containing the strongest pheromone. As time passes, the strength of a pheromone trail fades.

If the level of food at the nest is low then the population of the nest will decrease. The ants to be removed from the simulation are selected randomly.

The simulation is advanced one stage at a time. At each stage an ant takes one action: move to a new cell, pick up food or add food to the nest. The amount of food in the nest decreases at each stage by an amount determined by the number of ants that belong to the nest.

In the Skeleton Program, there are four different simulations to select from:

- **Simulation 1** is a 5×5 grid with one nest. Five ants belong to that nest (one queen and four workers). At the start of the simulation the nest has 500 food units in it. There are three sources of food in the grid. It is possible that some of the food sources could be in the same cell as each other. The strength of a new pheromone is 1000 and the pheromone decay rate is 50 per stage.
- **Simulation 2** is the same as simulation 1 except the pheromone decay rate is 100 per stage.
- **Simulation 3** is a 10×10 grid with one nest. Nine ants belong to that nest (one queen and eight workers). At the start of the simulation the nest has 500 food units in it. There are three sources of food in the grid. It is possible that some of the food sources could be in the same cell as each other. The strength of a new pheromone is 1000 and the pheromone decay rate is 25 per stage.
- **Simulation 4** is a 10×10 grid with two nests. Six ants belong to each nest (one queen and five workers). At the start of the simulation each nest has 500 food units in it. There are three sources of food in the grid. It is possible that some of the food sources could be in the same cell as each other. The strength of a new pheromone is 1000 and the pheromone decay rate is 25 per stage.
After choosing which simulation to use the user repeatedly selects one of the options from the menu until they choose the quit option. The other options available are to display overall details about the simulation, to display details about a selected area in the grid, to inspect one cell in the grid in detail, to advance the simulation by one stage or to advance the simulation by X stages (where X is a value specified by the user).

There could be errors in the implementation of the simulation in the Skeleton Program, which mean that it does not work correctly under all circumstances.

