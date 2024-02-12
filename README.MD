# Prey-Predator Ecosystem

Learning Activity using NetLogo for CMPLXSY (Complex Systems) class at De La Salle University.

## Description

A basic hawks and rabbits prey predator system with adjustable parameters to create a rough simulation of such actions. The turtles move randomly on the map. Every tick, a hawk eats one rabbit nearby if there are any, and a rabbit eats grass in the patch it is on if there are any. Every tick there is also a chance for both hawks and rabbits to reproduce. This continues until either side is completely depleted.

## Adjustable Parameters

-   Initial Hawk & Rabbit Population
-   Grass Regrowth Time
-   Hawks & Rabbits Energy Gain on Eating
-   Hawks & Rabbits Chance to Reproduce
-   Hawks & Rabbits Movement Configurations

## Changes

-   Added initial-energy and energy-drain variables for both species
-   Replaced reproduction rate with cooldown
-   If cooldown is down, each species will try and find another species to reproduce with
-   Changed hatching to set the variables properly and hatch more than one at a time

## Further Enhancements

-   Initial energy is now randomized to twice the food gain
-   Initial energy of hatching is half of their parent's energy
-   Hatching moves them forward by one tile
-   Reproduction based on probability only (no longer if same tile and cooldown)

## Project Setup

Go to `Tools` > `Turtle Shapes Editor` > `Import from Library` from there you should be able to find the Hawk and Rabbit model.

## Running the Project

Simply press the `setup` and then the `go` button.
