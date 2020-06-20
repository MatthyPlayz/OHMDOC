# KCT (KCL and KVL)<br />
## What is KCT?<br />
<!-- https://latex.codecogs.com/ -->
KCT comprises of three major factors:<br />
<ol>
  <li>That the model is lumped (nothing radiates or creates waste, e.g. resistors don't generate heat)<br /></li>
  <li>Kirchoff's Current Law<br /></li>
  <li>Kirchoff's Voltage Law</li>
</ol>
<Having the model be lumped is *very* important as otherwise the equation will be wrong.<br />
<br />
Having a lumped model in general changes a lot of fine details (e.g if four points connected on one main power rail with a 220-ohm resistor connected on each point two one center point connecting all of the points together, the middle point would not explode due to the laws of the lumped model.)<br />

So, as stated earlier, try not to mix lumped model and standard model (with waste) or else things will go wrong.
## What is KCT in mathematical equations?
**Note:** This applies to KCL and KVL<br />
[V1+V2+V3+V4...=0](https://latex.codecogs.com/svg.latex?V_1+V_2+V_3+V_4...=0)<br />
where:<br />
[Vx=node](https://latex.codecogs.com/svg.latex?V_x%20=%20node)<br />
(If you don't know already, a "node" is a point on the schematic, e.g. the point where two wires connect, or where a resistor connects to a wire.)<br />
