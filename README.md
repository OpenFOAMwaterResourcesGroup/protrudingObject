# protrudingObject
Put together by Jason Duguay March 15, 2019

Case description:

- Two phase flow around a protruding bed mounted obstacle using interFoam.
- Uniform velocity presribed at inlet, zeroGradient at outlet.
- Water set downstream using p_rgh

To run:

./Allrun

Limitations:

- Drowned 'in' patch prevents instabilities where 'in' and 'aboveIn' meet
- Drowned 'out' patch prevents instabilities at 'out' and 'aboveOut' patch
- A wave sweeps the domain but abates with time
- Side walls are imposed, ideally I image these should be 
