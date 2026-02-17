ATM System - OOP Abstraction Demo
This repository contains a Python script that illustrates how to use Abstract Base Classes to enforce a blueprint for subclasses. The project simulates a simple ATM interface with core banking functionalities.

🚀 Overview
The code utilizes Python's built-in abc (Abstract Base Classes) module. It defines a template for what an ATM should do, without specifying how it does it. The implementation details are then provided in the ATM_SBI class.

Key Features
Abstraction: The ATM class serves as a contract, ensuring any bank implementation includes balance checking, deposits, and withdrawals.

Security Simulation: Methods require a PIN verification before performing transactions.

State Management: Tracks user balance and performs validation for insufficient funds.
