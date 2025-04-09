# Analyze_ss_movingload

This repository contains tools for analyzing a simply supported beam under moving loads and designing a bolted lap joint as per IS 800:2007.

## Beam Analysis Under Moving Loads

This module simulates a simply supported beam subjected to moving loads and calculates key parameters such as:
- Maximum reaction forces at the supports.
- Bending moment and shear force distributions.
- Positions where the maximum bending moment and shear force occur.

## Bolted Lap Joint Design

This module designs a bolted lap joint connecting two steel plates under a given tensile force. The design process includes:
- Selecting an optimal bolt diameter and grade from a predefined list.
- Choosing an appropriate plate grade.
- Calculating shear capacity, bearing strength, and detailing distances (pitch, gauge, end, and edge).
- Ensuring the joint design meets IS 800:2007 requirements and uses more than two bolts for safety.

## Usage

1. **Clone the Repository:**
   ```bash
   git clone 
   cd Analyze_ss_movingload
   ```

2. **Run the Python Script:**
   Execute the analysis by running:
   ```bash
   python analyze_ss_movingload.py
   ```
   The script will output the bolted lap joint design details as well as the beam analysis results to the console.
