## Running Simulation and Analyzing Output in Ubuntu

Follow these steps to run a simulation and analyze the output using Tcl and AWK scripts in Ubuntu:

1. **Create Tcl Program**: Open the vi editor and create a Tcl program. Save the program with the extension ".tcl".
   ```bash
   $ vi lab1.tcl
   ```

2. **Save Tcl Program**: Press the "ESC" key, then type ":wq", and press Enter to save the program.

3. **Create AWK Program**: Open the vi editor and create an AWK program. Save the program with the extension ".awk".
   ```bash
   $ vi lab1.awk
   ```

4. **Save AWK Program**: Press the "ESC" key, then type ":wq", and press Enter to save the program.

5. **Run Simulation**: Execute the simulation program using the network simulator (ns).
   ```bash
   $ ns lab1.tcl
   ```
   - "ns" indicates the network simulator. The simulation window will display the topology.
   - Press the play button in the simulation window to start the simulation.

6. **Analyze Output**: After the simulation completes, run the AWK script to analyze the output.
   ```bash
   $ awk -f lab1.awk lab1.tr
   ```

7. **View Trace File**: To view the contents of the trace file, open the file using the vi editor.
   ```bash
   $ vi lab1.tr
   ```

Follow these instructions to run the simulation and analyze its output effectively in Ubuntu.
