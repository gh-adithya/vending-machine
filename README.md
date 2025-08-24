# Vending Machine FSM (Verilog)

## Overview
This project implements a **Mealy FSM-based vending machine controller** in Verilog.  
The system accepts coin inputs (₹5 and ₹10), dispenses a product when sufficient balance is reached, and returns change if required.  

- **Inputs**:  
  - `01` → ₹5 coin  
  - `10` → ₹10 coin  
- **Outputs**:  
  - `out` → Product dispense signal  
  - `change` → Returned change (`01` = ₹5, `10` = ₹10)  

## Features
- Implements **finite state machine (FSM) logic** for transaction handling.  
- Handles different coin insertion sequences with proper state transitions.  
- Dispenses product and returns appropriate change automatically.  
- Designed as a **Mealy machine** (outputs depend on state + input).  
- Includes a **testbench with waveform simulation** for verification.  
