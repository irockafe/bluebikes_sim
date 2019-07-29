## Bluebikes Simulator
Trying to simulate the Bluebikes system in Boston. 

First pass is using a markov-model (GIllespie method), where we empirically find the probability of station-station trips and then simulate.

Hopefully the simulation can let me figure out how to re-allocate bikes, or when/where to dispatch fleet management.

One big unknown right now is: I don't know if the existing fleet-management actions are included in the data. I should look for unusualy spikes in docking lots of scooters right before high demand.
