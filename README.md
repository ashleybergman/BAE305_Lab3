# BAE305_Lab3
# By: Ashley Bergman

# Summary
The goal of this lab was to use a simulation software to find Kirchhoff's voltage law and Kirchhoff's current law. The online software, Partism, is very useful for evaluating and analyzing circuits or systems without actually constructing them. Another goal of this lab was to apply the superposition and Thevenin's theorems to the analysis of electrical circuits and to confirm the validity of these theorems. 

# Materials
Breadboard, computer with Partism and TinkerCAD circuit software, DC power supply, Resistors with the following values: 1kOhms, 2.2kOhms, 5.1kOhms, 4.7kOhms, 220kOhms, 6.8kOhms, 10kOhms, 3.3kOhms, and 470kOhms.

# Assembly Procedure
Part 1:
1. Build a series circuit, following the schematic in the lab manual.
![series circuit](https://user-images.githubusercontent.com/46691767/52983502-6e0fb400-33b9-11e9-853d-2952176c62e4.jpg)

2. Build the circuit using simulation software.
![series circuit simulation](https://user-images.githubusercontent.com/46691767/52983508-7831b280-33b9-11e9-954c-fd09265aadcc.jpg)

Part 2:
1. Build a parallel circuit, following the schematic in the lab manual. 
![parallel circuit](https://user-images.githubusercontent.com/46691767/52983466-43bdf680-33b9-11e9-99df-bf2930bf24a1.jpg)

2. Build the circuit using the simulation software. 
![parallel circuit simulation](https://user-images.githubusercontent.com/46691767/52983519-854ea180-33b9-11e9-89f7-02c1c2fa9004.jpg)

Part 3: 
1. Determine the correct resistance to place in series with the sensor to yield a voltage output between 0-5V across the sensor using the given sensor that ranges from 0-19.5650K Ohms and a 14.1V input voltage. 

Part 4: 
1. Login to TinkerCAD Circuits.
2. Start a simulation, in the components drop down switch to Starters->Arduino and select Blink.
3. Find and run the starter Analog input.

# Test Equipment
Fluke and the multimeter. The multimeter was used to measure the voltage drop across each resistor but was not used to measure current to prevent more fuses from being blown. The current was measured on the simulation software.

# Test Procedure 
Part 1: 

1. Use the voltage probes to measure the voltage drop across each resistor in the circuit. 
2. Measure the voltage for each resistor on the simulation software.
3. Use the simulaton software to determine the current. 

Part 2:
1. Measure the branch currents I1-7 and make sure to take the direction into account. 
2.Verify that the current leaving a node is equal to the current entering the node.

# Results
Part 1:
![current voltage results](https://user-images.githubusercontent.com/46691767/52983530-8e3f7300-33b9-11e9-9b05-077cf2503220.jpg)

Part 2:
![current results](https://user-images.githubusercontent.com/46691767/52983540-95ff1780-33b9-11e9-8f83-f7c638542cea.jpg)

![voltage results](https://user-images.githubusercontent.com/46691767/52983562-aca56e80-33b9-11e9-8605-287486a02b82.jpg)

The DMMs failed to read the currents so the measured values were left out of the results. Also, the second portion of part 2 would not work correctly since the DC Voltage would only produce 18V.

Part 3: 
![results](https://user-images.githubusercontent.com/46691767/52983568-b333e600-33b9-11e9-8477-cd236d761fc5.jpg)

A resistance with 35.76 Ohms needs to be put in series with the sensor to yield a voltage between 0-5V across the sensor. 
If the maximum current for the sensor is 0.4 mA, the sensor will still work. The maximum current for this circuit is 0.39 mA.

# Discussion
Branches 2 and 3 were the only branches that had the same voltage. There is a difference in the voltage in some branches because some resistors are in series and some are in parallel. There is also a difference because of the difference in resistor values. Overall, the simulated values and measured values were similar. 
