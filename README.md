
# Assignment

This folder contains two files task_1 and task_2.




## Task 1
In this task I have a quantum simulator which implements quantum circuit with Hadmard gate and CNOT gate. This file is python notebook file and in order to run code you just need to run execute_gate_instructions('input.txt'). The file path or file passed in this execute_gate_instructions() function contains all instruction and number qubits our quantum circuit would have. Run last cell of notebook and in order to execute new circuit edit 'input.txt' accordingly.

The state produced using this circuit is called GHZ state.

∣GHZ⟩= 1/sqrt(2)*(∣000⟩+∣111⟩)
## Task 2
In this task I have added a new function called depolarize_channel(). In order to run this file you need to run same execute_gate_instructions('input.txt', nu) function, but it has additional argument of nu which is depolarizing parameter.