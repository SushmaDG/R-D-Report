# Extending the Vereshchagin Hybrid Dynamic Solver to Mobile Robots
## Reasearch and Development project report

### Abstract

Most of the current approaches for implementing robot navigation tasks, control the robot motions at velocity-level. Although these methods are relevant for simple navigation tasks, they cannot support complex tasks imposing multiple constraints
on robot motion. An example of such tasks includes object handling actions in manipulators, where there is force/acceleration constraint on end-effector. Similarly, for a mobile robot, the task requirements might impose a constraint on the force/acceleration level. Researchers have continuously focused on providing programming support to handle complex tasks. The existing sensor-based mobile robots cannot resolve such constraints since their motions are velocity-controlled. Therefore, there is a need for a standardized method to specify and control mobile robots while resolving task constraints. One such algorithm that satisfies the above stipulation is Popov-Vereshchagin hybrid dynamic solver. This algorithm is currently applied
in the field of manipulators.

The primary objective of the project is to extend and apply Popov-Vereshchagin Solver to mobile bases. The solver applies to kinematic chain/tree structures, and mobile robots can be modeled as a tree structure. Theoretically, the solver extension
to kinematic tree structure is already available. Utilizing this, an extended algorithm is derived. Further, by modeling an existing omnidirectional robot platform (MPO-700) as a kinematic tree, the derived algorithm is implemented. Finally, experiments are conducted in a simulation environment and obtained results are analyzed.
