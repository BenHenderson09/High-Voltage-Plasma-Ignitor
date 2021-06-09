# High-Voltage-Plasma-Ignitor
Driving a step-up transformer at a high frequency to produce high temperature continuous plasma arcs.
A broken cordless impact driver was repurposed to act as an enclosure.

<img src="image1.jpg" width="400"><img src="image3.png" width="400">
<img src="circuit.png">

## How does it work?
The battery of the tool provides 18v (nominal) to the circuit.
This is reduced using a step down converter to ~14v to prevent
excessive power damaging the step-up transformer.

The driver of the transformer and a piezo buzzer receive ~14v when the switch
is pressed. High temperature plasma arcs ~11mm long are then observed on the 
secondary of the transformer.

The driver uses a 555 timer configured to produce high frequency waves to an
N channel MOSFET on the primary of the transformer.
