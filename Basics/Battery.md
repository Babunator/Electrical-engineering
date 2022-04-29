# Voltaic Cells
- Atoms bound together by electrons are called molecules.
- Ionic bonds are molecular unions formed when an electron-deficient atom (a positive ion) joins with an electron-excessive atom (a negative ion).
- Electrochemical reactions involve the transfer of electrons between atoms. This transfer can be harnessed to form an electric current.
- A voltaic cell, or cell for short, usually consisting of two metal electrodes immersed in a chemical mixture (called an electrolyte) designed to facilitate such an electrochemical (oxidation/reduction) reaction:<br/>
![](https://www.allaboutcircuits.com/uploads/articles/voltaic_cell.jpg)
- A cell is a device constructed to harness such chemical reactions to generate electric current.
- The voltage produced by any particular kind of cell is determined strictly by the chemistry of that cell type.
- If the electrodes of the cell are connected to an external circuit, thelectrons have a place to flow from one to the other.
- In the common “lead-acid” cell (the kind commonly used in automobiles), the negative electrode is made of lead (Pb) and the positive is made of lead (IV) dioxide (PbO2), both metallic substances. he electrolyte solution is a dilute sulfuric acid (H2SO4 + H2O.
- lead(IV) atoms in the positive electrode (PbO2) will gain two electrons each to produce Pb(II)O. The oxygen atoms which are “leftover” combine with positively charged hydrogen ions (H)+to form water (H2O). This flow of electrons into the lead dioxide (PbO2) electrode gives it a positive electrical charge. 
- Led atoms in the negative electrode give up two electrons each to produce lead Pb(II), which combines with sulfate ions (SO4-2) produced from the dissociation of the hydrogen ions (H+) from the sulfuric acid (H2SO4) to form lead sulfate (PbSO4). The flow of electrons out of the lead electrode gives it a negative electrical charge.<br/>
![](https://www.allaboutcircuits.com/uploads/articles/lead-acid-cell-discharging-diagram-1.jpg)

- A cell is said to be discharged when its internal chemical reserves have been depleted through use.
- In a Lead-acid battery this will be, when all of the sulfuric acid has been exhausted, the result will be two electrodes of lead sulfate (PbSO4) and an electrolyte solution of pure water (H2O), leaving no more capacity for additional ionic bonding.
- Lead-acid cell charge can be assessed with an instrument called a hydrometer, which measures the density of the electrolyte liquid. The denser the electrolyte, the stronger the acid concentration, and the greater charge state of the cell. (Sulfuric acid is denser than water)
- The chemical reactions of some types of cells can be reversed by forcing electric current backward through the cell (in the negative electrode and out the positive electrode). This process is called charging
- A secondary cell’s chemistry can be reversed (recharged) by forcing current backward through it.
- A primary cell cannot be practically recharged.

# Battery Construction
- A battery is a cluster of cells connected together for greater voltage and/or current capacity.
- The symbol for a cell is very simple, consisting of one long line and one short line. symbol for a battery is couple of cell symbols stacked in series.<br/>
![](https://www.allaboutcircuits.com/uploads/articles/cell.jpg)![](https://www.allaboutcircuits.com/uploads/articles/battery.jpg)<br/>
- Symbol for a battery with unusually high voltage is intentionally drawn with extra lines:<br/>
![](https://www.allaboutcircuits.com/uploads/articles/unusually-high-voltage-symbol-for-battery.jpg)<br/>
- Cells connected together in series (polarities aiding) results in greater total voltage. (For example a typical automotive lead-acid battery (12V) has six cells (2V).
- Physical cell size impacts cell resistance, which in turn impacts the ability for the cell to supply current to a circuit. The larger a cell is constructed, the greater the electrode contact area with the electrolyte, and thus the less internal resistance it will have.
- Cells connected together in parallel results in less total resistance, and potentially greater total current

# Battery Ratings
- The amp-hour is a unit of battery energy capacity, equal to the amount of continuous current multiplied by the discharge time, that a battery can supply before exhausting its internal store of chemical energy.<br/>
![](https://www.allaboutcircuits.com/uploads/articles/amp-hour.jpg)<br/>
- An amp-hour battery rating is only an approximation of the battery’s charge capacity and should be trusted only at the current level or time specified by the manufacturer. In an ideal battery, this relationship between continuous current and discharge time is stable and absolute, but real batteries don’t behave exactly as this simple linear formula would indicate. 
- Such a rating cannot be extrapolated for very high currents or very long times with any accuracy. With higher currents, the battery will dissipate more heat across its internal resistance, which has the effect of altering the chemical reactions taking place within. If a very light load is applied (e.g years) the chemical energy in a real battery would have been drained due to other factors (evaporation of electrolyte, deterioration of electrodes, leakage current within battery).
- Discharged batteries lose voltage and increase in resistance (as the electrolyte becomes less and less conductive). 
The best check for a battery’s condition is a voltage measurement under load, while the battery is supplying a substantial current through a circuit. Otherwise, a simple voltmeter check across the terminals may falsely indicate a healthy battery (adequate voltage) even though the internal resistance has increased considerably.<br/>
![](https://www.allaboutcircuits.com/uploads/articles/scenario-for-slightly-discharged-battery_2.jpg)

# Practical Considerations - Batteries
### Batteries in Series
- Connecting batteries in series increases voltage, but does not increase overall amp-hour capacity.
- All batteries in a series bank must have the same amp-hour rating. Or else some of the batteries will become depleted sooner than others, compromising the capacity of the whole bank. 
- 
### Batteries in Parallel
- Connecting batteries in parallel increases total current capacity by decreasing total resistance, and it also increases overall amp-hour capacity.
- All batteries in a parallel bank must have the same voltage rating.
- 
### Overcurrent Protection
- For our series battery bank, one fuse will suffice to protect the wiring from excessive current, since any break in a series circuit stops current through all parts of the circuit:<br/>
![](https://www.allaboutcircuits.com/uploads/articles/overcurrent-protection.jpg)<br/>
- In Parallel Batteries have been known to internally short-circuit, due to electrode separator failure, causing a problem, not unlike that where batteries of unequal voltage are connected in parallel: the good batteries will overpower the failed (lower voltage) battery, causing relatively large currents within the batteries’ connecting wires. 
- To guard against this eventuality, we should protect each and every battery against overcurrent with individual battery fuses, in addition to the load fuse:<br/>
![](https://www.allaboutcircuits.com/uploads/articles/parallel-battery-bank.jpg)<br/>
- Batteries can be damaged by excessive cycling and overcharging.
- Water-based electrolyte batteries are capable of generating explosive hydrogen gas, which must not be allowed to accumulate in an area.

# Special-purpose Batteries
## Mercury Standard Cell
- Mercury standard cells are special types of batteries which were once used as voltage calibration standards before the advent of precision semiconductor reference devices.
- Mercury standard cells were also susceptible to slight changes in voltage if physically or thermally disturbed. Two different types of mercury standard cells were developed for different calibration purposes: saturated and unsaturated. 
- Saturated standard cells provided the greatest voltage stability over time, at the expense of thermal instability. 
- Unsaturated cells provided thermal stability at the expense of stability over time, the voltage remaining virtually constant with changes in temperature but decreasing steadily by about 100 µV every year. <br/>
![](https://www.allaboutcircuits.com/uploads/articles/mercury-standard-cell.jpg)

## Fuel cell 
- A fuel cell is a kind of battery that uses a combustible fuel and oxidizer as reactants to generate electricity. They are promising sources of electrical power in the future, “burning” fuels with very low emissions.
- The process of chemical oxidation (oxygen ionically bonding with other elements) is capable of producing current flow between two electrodes just as well as any combination of metals and electrolytes. <br/>
![](https://www.allaboutcircuits.com/uploads/articles/hydrogen-oxygen-fuel-cell.jpg) <br/>
- To date, the most successful fuel cells constructed are those which run on hydrogen and oxygen, although much research has been done on cells using hydrocarbon fuels. While “burning” hydrogen, a fuel cell’s only waste byproducts are water and a small amount of heat. 
- When operating on carbon-containing fuels, carbon dioxide is also released as a byproduct. Because the operating temperature of modern fuel cells is far below that of normal combustion, no oxides of nitrogen (NOx) are formed, making it far less polluting, all other factors being equal

## Solar cell
- A solar cell uses ambient light energy to motivate charge carriers from one electrode to the other, producing voltage (and current, if there is an external circuit).
- The photoelectric effect describes whereby electrons are dislodged from atoms under the influence of light.<br/>
![](https://www.allaboutcircuits.com/uploads/articles/solar-cell.jpg)<br/>
- Conversion efficiencies for silicon solar cells are still quite low, but their benefits as power sources are legion: no moving parts, no noise, no waste products or pollution, and indefinite life.
- 
## Chemical detection cell 
- A chemical detection cell is a special type of voltaic cell which produces voltage proportional to the concentration of an applied substance (usually a specific gas in ambient air).
- hese cells chemically react with specific substances in the air to create a voltage directly proportional to the concentration of that substance. 
- A common application for a chemical detection cell is in the detection and measurement of oxygen concentration.
- Cell chemistry must be designed to match the specific substance(s) to be detected, and the cells do tend to “wear out,” as their electrode materials deplete or become contaminated with use.
