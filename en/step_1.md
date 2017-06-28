### RC Timing Circuits

RC stands for **Resistor** and **Capacitor**. RC circuits have a variety of functions, but there is a way of using them to help digital devices read analogue components.
In the timing circuit illustrated below, a 2.2kΩ resistor has been placed in series with a 1µF capacitor. They are connected to a 3.3V power supply and a switch has been used that can be pushed to short the circuit and **Earth** both the capacitor and the resistor.

*[Resistor]: A component that resists the flow of current. Resistance is measured in Ohms (Ω).
*[Capacitor]: A component that can store charge. Capacitance is measured in Farads (F).

![rc-circuit](images/circuit.png)

You can watch this video or read the explanation below for what happens in this circuit.

<iframe width="560" height="315" src="https://www.youtube.com/embed/sNn3vjEU_H0" frameborder="0" allowfullscreen></iframe>

When the switch is open, current can flow though the resistor and the capacitor. The capacitor starts to store charge immediately. This causes the voltage across the capacitor to rise, as charge is stored. It eventually becomes fully charged and the voltage across it will match that of the supply - in this case 3.3V.
When the switch is closed, the capacitor rapidly discharges as charge flows straight to Earth or Ground. This causes the voltage to drop to zero almost instantly. Opening the switch will start the process all over again.

The rate at which the capacitor charges is constant, so long as the resistance is constant. Using a resistor with a larger resistance will case the charging process to slow down. Using a smaller resistance will make charging faster.

If you can measure the time it takes for the capacitor to charge, you can fairly accurately calculate the resistance of the resistor. This means that you could use this type of circuit to measure the resistance of a component such as a Light Dependent Resistor, a Thermistor or a Potentiometer. All these components have variable resistances.
