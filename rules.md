# Timeline

Game starts in January, 1900.
Normal turns are 3 months.
Revolution turns are 1 month.
Game ends at the end of 1920.

# Turns

1. Each player chooses 3 actions and assigns people to those actions.
2. Players take turns revealing actions 1 at a time in any order they choose.
3. Counter actions are revealed in response to an action they counter. If no such action occurs, counter actions are not revealed.

# Influence

Each faction has an influence rating, measured 1-100 that represents the sway they have over the general population.

# Unrest

Unrest is represented by a single number 0-100. Milestones as follows:

- Starts at 20
- < 0, Tsarist faction wins.
- >= 80, revolution starts automatically
- <= 50, revolution ends if currently active

At the end of each turn during revolution, Unrest decreases by 5.

# Revolution

Revolutions can be started by actions 

# Actions

Types of actions:

- General: Can be played without assigning a person. Sometimes, can be augmented by assigning one or more people.
- Personal: Must be assigned a person as the primary actor.

Action attributes:

- Cost: Number of type of points required to execute the action.
- Outcome: Effect of the action.
- Requirements: Prerequisites to perform the action. Person's attributes, faction influence level, unrest level, etc.
- Personal/General
- How people participating in the action affect its outcome

Playing actions:

Prerequisites are checked and costs are paid when an action is revealed. If at the time it is revealed, either the prerequisites or not met or the player can't afford the cost, the action does not happen (is skipped).
