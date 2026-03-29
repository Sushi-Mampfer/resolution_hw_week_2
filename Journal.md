## 23. 04. 2026

Today I finished the falstad circuit and tried to make it only light up one led at a time instead of 2.

After trying many small things(an and gate on the output and using pnp transistors) I asked claude, which produced a useless diagram where the components weren't connected properly and the explanation it produced also didn't make much sense.

### Time Spent: 2 Hours

## 24. 04. 2026

Today I tried to make a cooler cuircuit, but I couldn't get the transistors to trigger in a consistent way so that I could chain more than 2 for more complex operations(the goal was an adder).



After 3.5 hours of creating a lot of messy circuits in falstad that more or less didn't work I decided to give up and go back to my old circuit and tried to make it stoppable, which was way harder than I anticipated, because it needs to interupt the signal shortly to start up. I tried to add a monostable multivibrator, but it was unable to power the transistor to cut power temporarily.

<img width="1310" height="865" alt="image" src="https://github.com/user-attachments/assets/fe9b871c-6726-4226-8cb2-779c1a9b4bea" />

In the end I just added a button to turn it on(which interrupts one line when turned off and therefore fixes my start problems).

After that I put it in kicad which went pretty smooth, except for a missing connection in the outline which broke the 3d render, but the drc catched it and pointed me to the broken end.

### Time Spent: 6 Hours
