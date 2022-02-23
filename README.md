# ridesharingsimulation
Experience reading, understanding, designing and implementing several interacting classes to model 
prospective riders with varying amounts of patience, available drivers starting from various locations, 
and dispatchers trying to match up the riders and drivers.

Working on implementations of classes to run the simulation and monitor the results, and provide utilities such as
sequences to hold objects and a class to represent locations on a grid.

The simulation consists of four key entities: Riders, drivers, the dispatcher, and the monitor. 
Riders request rides from their current location to a destination. 
Drivers drive to pick up and drop off riders. 
The dispatcher receives and satisfies requests from drivers for a rider, and from riders for a driver. 
The monitor keeps track of activities in the simulation, and when asked, generates a report of what happened during the simulation.

