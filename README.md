# 🧪 Reactor Monitoring System (RMS) - Chemical Process Monitoring Simulation

## Project Description

This project is a straightforward implementation of a **Chemical Reactor Monitoring System (RMS)** built using Python. Its primary goal is to simulate the monitoring of key operational parameters of a reactor, such as **temperature, pressure, and pH**, and to provide **automatic alerts** if any sensor readings fall outside predefined safe limits.

The system is designed to demonstrate how sensor data can be programmatically processed to ensure optimal and safe operating conditions, a fundamental aspect of modern process industries and chemical engineering.

## Key Features

  * **Safe Limit Definition**: Utilizes a Python `Dictionary` to store reactor specifications and tolerance limits (maximum temperature, maximum pressure, safe pH range).
  * **Simulated Sensor Readings**: Processes simulated sensor reading data stored in `List`s. This data includes both normal and anomalous (out-of-bounds) scenarios.
  * **Conditional Monitoring Logic**: Applies `if-elif-else` statements and logical operators (`and`, `or`) to evaluate each sensor reading against the established safe limits.
  * **Automated Alert System**: Prints specific warning messages if parameters are detected outside limits, along with confirmation messages for normal conditions.
  * **Critical Condition Detection**: Identifies and reports if a combination of parameters indicates a critical operating condition requiring immediate intervention.
  * **Summary Report**: Calculates and displays the total number of alerts detected throughout the entire simulated monitoring period.

## How to Run the Program

1.  **Clone the Repository**:
    If you've uploaded it to GitHub, others can clone it:

    ```bash
    git clone https://github.com/Kyuraez/Kyuraez.git
    cd Kyuraez
    ```

    Or, if you only have the file locally:
    Download the `reactor_monitor.py` file to your computer.

2.  **Execute with Python**:
    Open your Terminal or Command Prompt in the directory where `reactor_monitor.py` is located, then run the command:

    ```bash
    python reactor_monitor.py
    ```

## Example Output

*(This section is where **you'll paste your actual output** from running `reactor_monitor.py` in your terminal. Copy a few initial and final lines, or sections that highlight warnings.)*

```
# Paste your terminal output here.
# Example:
# === Starting Reactor Monitoring ===

# --- Reading Data Point 1 ---
# ✅ Temperature 145.2°C: NORMAL.
# ✅ Pressure 7.5 MPa: NORMAL.
# ✅ pH 7.1: NORMAL.
# 🟢 All parameters at this time point are within normal limits.

# --- Reading Data Point 3 ---
# ✅ Temperature 130.5°C: NORMAL.
# ✅ Pressure 6.9 MPa: NORMAL.
# ⚠️ pH Alert: 5.8 is outside limits (6.0 - 8.0)!
#
# 🔴 CRITICAL CONDITION! Some parameters are exceeding normal limits, immediate action needed!
#    Specific alerts at this time: 1
#    Suggested action: Check cooling system, ventilation, or adjust pH as needed.
# ... (continue with a few more lines until the end)

# === Monitoring Complete ===
# Total 6 alerts detected throughout the simulation.
# Check the log above for details on each alert.
```

## Key Learnings

Through this project, I have gained practical understanding and strengthened my skills in:

  * **Python Fundamentals**: Variables, data types (`int`, `float`, `str`, `bool`).
  * **Essential Data Structures**: Using `List` for ordered collections and `Dictionary` for key-value structured data.
  * **Control Flow**: Implementing conditional logic (`if`, `elif`, `else`) and loops (`for` loop) to automate data processing.
  * **Comparison & Logical Operators**: Building complex conditions using `==`, `>`, `<`, `>=`, `<=`, `!=`, `and`, `or`, `not`.
  * **Problem-Solving**: Analyzing a technical problem (reactor monitoring) and translating it into a code-based solution.
  * **Industry Relevance**: Connecting programming concepts with practical applications in Chemical Engineering, specifically in process control and alert systems.
