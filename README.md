# TrafficLightController

Implemented in Simulink the State flow diagram of a streetlight model that adheres to following specifications:
•	Starts at the Red Light state
•	Transition from Red light state to Green Light state after 10 seconds.
•	If there are no pedestrians, transition from Green Light state to Yellow light state after 10 seconds.
Otherwise if there is a pedestrian approaching anytime while it is at Green light state, it stays in Green light state for up to 20 seconds before transitioning to Yellow light state. 
•	Stays at Yellow light state for 3 seconds before transitioning to Red light state.

Tech Stack - MATLAB 2017b, Simulink
