#  D3 Fun  

----------  
Some small tests using D3 javascript

## Key points

 1. Gravity, and charge set to 0, friction set to 1
 2. Schedule the transition on the radius in the timer callback
 3. Create a dynamic radius on the data (d.rt) and, in the tick callback, update it with the current DOM element radius to synchronise with the transition
 4. Use the dynamic radius for calculating collisions
 5. Use the dynamic radius to adjust the line x0 and x1 in the tick callback
 6. Use a transform on the nodes (g element) to decouple text and line positioning from node position, adjust the transform x and y, only in the tick callback
 7. Remove the CSS transitions and add d3 transitions so that you can synchronise everything
 1. Closed loop speed control with getters and setters for speed and velocity on the nodes
 1. Parallel transitions to coordinate geometry animations

[Attempt at CSS version](http://bl.ocks.org/cool-Blue/f810911f5f84b94f2e3e)  
[velocity.js version](http://bl.ocks.org/cool-Blue/5b3161f6be8bd2baac52)  

----------  

