# Vending-Machine
# Vending Machine Using VHDL

This repository contains a digital design project that implements a vending machine using VHDL. The system is modeled using a Finite State Machine (FSM) to simulate the behavior of a real vending machine that accepts coin inputs and dispenses a product once the required amount of money has been inserted.

The vending machine accepts two types of coin inputs and keeps track of the total amount inserted by the user. Based on the inserted value, the machine transitions between different states that represent the current balance in the system. When the total amount reaches the required product cost, the machine dispenses the product. If the user inserts more than the required amount, the machine returns the appropriate change. If a transaction is incomplete and no additional coins are inserted, the machine returns the inserted money.

The project demonstrates the use of VHDL for modeling digital systems and designing control logic using state machines. It highlights important concepts such as sequential logic, state transitions, synchronous design with clock signals, and hardware simulation using a testbench.

The repository includes the main VHDL design file that implements the vending machine logic, along with a testbench used to verify the functionality of the system. The simulation allows different input scenarios to be tested to ensure correct operation of product dispensing and change handling.

This project was developed as part of a digital design or hardware description language coursework to demonstrate practical implementation of FSM-based control systems using VHDL.
