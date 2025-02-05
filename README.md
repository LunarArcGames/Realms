# Realms

Realms

Realms are context files that allow the Lunar Arc system to understand the game and the player's goals. This is the official registry of realms.
Overview

In Realms, players manage and expand their territories by constructing buildings, gathering resources, and strategically competing to achieve victory. Realms serve as the primary source of context for the Lunar Arc system, providing it with the information needed to track game progress, player objectives, and territory statuses.

    Game Type: Strategy, Simulation
    Primary Goal: Collect 12M points by building structures, defending territories, and upgrading realms.
    Key Features:
        Territory construction and upgrades
        Resource management and building placement
        Multiple building types with unique functions
        In-depth game mechanics for strategic play
        Integration with Lunar Arc for intelligent game context interpretation

Game Mechanics
Territories:

Players control territories, which they can upgrade as resources are gathered and specific conditions are met. Each territory has a unique territory_id and is defined by its north_col and north_row.
Resources:

The game includes several types of resources:

    Stone, Coal, Fish, Grain (Basic)
    Obsidian, Mithril, DragonScales (Rare)

Building Types:

Buildings play a crucial role in resource production, unit training, and defense. Examples of building types include:

    GrainField: Produces Grain
    Fisherman's Haven: Produces Fish
    Barracks: Trains Units
    ArcheryStation: Trains Archers
    Warehouse: Stores Resources

Territory Levels:

Territories evolve through different stages:

    Level 0 (Outpost): Initial stage with 6 buildable hexes
    Level 1 (Town): 20 buildable hexes with resource requirements
    Level 2 (Kingdom): Unlocks advanced buildings and requires higher resources
    Level 3 (Empire): The final level requiring rare resources

Lunar Arc System Integration

The Realms files act as the context that informs Lunar Arc about the game state, the player’s current goals, and the actions they can take. Lunar Arc uses this information to provide dynamic interactions, such as suggesting next steps, tracking resources, and supporting the player’s strategy.
Querying & Usage

    Querying Territory Info: Lunar Arc can fetch specific details about a territory using its territory_id and entity_id.
    Construction and Resource Management: Lunar Arc can manage territory construction and resource gathering, helping players make informed decisions.

Official Registry

This repository serves as the official registry of realms, with JSON files like sylphia.json containing critical game data such as:

    Territory information and resources
    Smart contract addresses for in-game transactions
    GraphQL queries for interacting with the game’s data
