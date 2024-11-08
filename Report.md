## P05-C2 Assignment: KHALID KHAN

## TASK 1: Theoretical Questions

#### Difference between DHC and L*M
This paper focuses on two main algorithms, DHC (Direct Hypothesis Construction) and L*M.

DHC Algorithm: This algorithm learns Mealy machines directly by building hypotheses from the ground up during each iteration. A queue-based state space exploration method relies on partition refinement to keep hypotheses in canonical form during the learning process.

LM Algorithm: This algorithm is based on the traditional L learning algorithm for deterministic finite automata but is tailored for Mealy machines instead. The L*M algorithm prioritizes efficiency by focusing on minimizing the number of membership queries, especially when handling counterexamples using observation tables. It is used to simplify a model that already exist.

#### Definition of the Mealy machine
A Mealy machine is a finite state machine (FSM) which generates outputs depending on its current state and the current input symbol it gets. It functions reactively as it produces results based on its present condition and the inputs it receives. It names after American Engineer George H Mealy, it is a state machine where each transition between states is associated with an output.

Components of the Mealy Machine S, s0, Σ, Ω

S.	 The set of states in the Mealy machine.
s0.	 The initial state of the Mealy machine.
Σ.	 (Sigma) The input alphabet, representing all possible inputs.
Ω.	 (Omega) The output alphabet, representing all possible outputs.


#### Observation table
Below is a simple layout for an observation table that can be utilized for a Mealy machine, tailored to the amount of states and inputs.


Rows of vertical structures.

The initial column shows the beginnings (series of inputs guiding to every condition).

The suffixes in the other columns are used to differentiate outputs of various states.
a
Every row represents a potential state that a prefix in Sp can achieve.


Prefix (Sp)	Output on ε		Output on a		Output on b
ε				X				Y				X
a				Y				X				Y
b				X				Y				X

Prefix (Sp): Refers to sequences that result in various states. Beginning from the initial state (ε), one state is reached by inputting a, while another state is reached by inputting b.

Suffixes (D): Included are ε (empty input), a, and b to analyse results for every possible state.


## TASK 2: Practical Questions
1.	I install Python 3.13
2.	Install AALpy 
3.	Install Graphviz
4.	Install PyCharm Development Environment
I tried different Python Development Environments i.e. Anaconda, Visual Studio and JupyterLab. But i found PyCharm is best and Intelligent IDE for Python Development.

I execute the program for task 2 but the it didn’t give me final results. I try my best but because of limited time i can’t achieve the goal.

IMAGE 1 is attached with directory for reference of PyCharm IDE.
IMAGE 2 is attached with directory for reference of JupyterLab
#### Correct Vending Machine: XY
Briefly describe its behaviour.

#### For each faulty vending machine, describe the fault
when i compile task2.py file it gives different errors i.e 
1. in PyCharm IDE it didnt access Vending Machine Files 
2. In JupyterLab it didnt compile because of resources. The Kernel Crashes

