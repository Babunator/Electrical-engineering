# Series Circuits
- The defining characteristic of a series circuit is that there is only one path for current to flow. 
In this circuit, the current flows in a clockwise direction, from point 1 to point 2 to point 3 to point 4 and back around to 1.</br>
![](https://www.allaboutcircuits.com/uploads/articles/series-connection.jpg)
![](https://www.allaboutcircuits.com/uploads/articles/series-circuit.jpg)

1. **Current**: The amount of current is the same through any component in a series circuit. </br>
```ITotal = I1 = I2 = . . . In```
2. **Resistance**: The total resistance of any series circuit is equal to the sum of the individual resistances. </br>
```RTotal = R1 + R2 + . . . Rn```
3. **Voltage**: The supply voltage in a series circuit is equal to the sum of the individual voltage drops.  </br>
```ETotal = E1 + E2 + . . . En```

![](https://www.allaboutcircuits.com/uploads/articles/for-series-circuits-2.png)
# Parallel Circuits
- The defining characteristic of a parallel circuit is that all components are connected between the same set of electrically common points. 
- In a purely parallel circuit, there are never more than two sets of electrically common points, no matter how many components are connected. There are many paths for current flow, but only one voltage across all components:</br>
![](https://www.allaboutcircuits.com/uploads/articles/parallel-connection.jpg)
- Looking at the schematic diagram, we see that points 1, 2, 3, and 4 are all electrically common. So are points 8, 7, 6, and 5. Note that all resistors, as well as the battery, are connected between these two sets of points.</br>
![](https://www.allaboutcircuits.com/uploads/articles/parallel-circuit.jpg)

![](https://www.allaboutcircuits.com/uploads/articles/for-parallel-circuits-3.png)

1. **Voltage**: Voltage is equal across all components in a parallel circuit.  </br>
```ETotal = E1 = E2 = . . . En```
2. **Current**: The total circuit current is equal to the sum of the individual branch currents. </br>
```RTotal = 1 / (1/R1 + 1/R2+ . . . 1/Rn)```
3. **Resistance**: Individual resistances diminish to equal a smaller total resistance rather than add to make the total. </br>
```RTotal = 1 / (1/R1 + 1/R2+ . . . 1/Rn)```

# Power Calculation -  Series And Parallel Circuits
- When calculating the power dissipation of resistive components, use any one of the three power equations to derive the answer from values of voltage, current, and/or resistance pertaining to each component: </br>
![](https://www.allaboutcircuits.com/uploads/articles/power-equations.png)
- Power is additive in any configuration of resistive circuit: </br> ```PTotal = P1 + P2 + . . . Pn```
- Power is a measure of the rate of work, and since power dissipated must equal the total power applied by the source(s) (as per the Law of Conservation of Energy in physics), circuit configuration has no effect on the mathematics.

# Analysis for Series Parallel Resistor Circuits
To analyze a series-parallel combination circuit, follow these steps:
- Reduce the original circuit to a single equivalent resistor, re-drawing the circuit in each step of reduction as simple series and simple parallel parts are reduced to single, equivalent resistors.
- Solve for total resistance.
- Solve for total current (I=E/R).
- Determine equivalent resistor voltage drops and branch currents one stage at a time, working backwards to the original circuit configuration again.<br/>
[Example  Analysis of Series-Parallel Combination Circuit](https://www.allaboutcircuits.com/textbook/direct-current/chpt-7/analysis-technique/)

# Component Failure Analysis
- For any single component failure (open or shorted), the total resistance will always change in the same direction (either increase or decrease) as the resistance change of the failed component.
- When a component fails shorted, its resistance always decreases. Also, the current through it will increase, and the voltage across it may drop. I say “may” because in some cases it will remain the same (case in point: a simple parallel circuit with an ideal power source).
- When a component fails open, its resistance always increases. The current through that component will decrease to zero, because it is an incomplete electrical path (no continuity). This may result in an increase of voltage across it. The same exception stated above applies here as well: in a simple parallel circuit with an ideal voltage source, the voltage across an open-failed component will remain unchanged.
