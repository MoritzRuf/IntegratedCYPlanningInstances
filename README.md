# IntegratedCYPlanningInstances
These are the test instances used in the computation results of the paper "Ruf, M., &amp; Cordeau, J.-F. (2020). Adaptive Large Neighborhood Search for Integrated Planning in Railroad Classification Yards. Submitted to Transportation Research Part B."

As described in the paper, there are two sets of instances:
- I1, and
- I2

To understand each instance, the following data is required:
- Information on trains: for each train, we provide information on its Id, its destination, its capacity, its arrival or departure time and its type.
- Information on blocks: for each block, we provide information on its destination, its inbound train and its number of railcars
- Information on requests: based on the trains, we provide information for each request: its Id, is abbreviation of type, its duration, its train Id, the earliest possible begin, latest possible begin, and the required skill / qualification
- Information on resources: its Id, its resource type (0: infrastructure, 1: locomotive, 2: staff), and the skills it is trained in (see below).
- Information on transition times of the resources: identical for all instances.

We use the following Ids for skills
0   "receiving_track"
1   "classification_track"
2   "departing_track"
3   "hump"
4   "coupling" 
5   "uncoupling"
6   "brake_check"
7   "inspection" 
8   "humping_locomotive"
9   "locomotive"
