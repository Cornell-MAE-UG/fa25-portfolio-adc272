---
layout: project
title: Thermodynamics
description: Heat Exchanger Lab
technologies: [Heat Exchanger, 2 Water Pumps, 4 Water Buckets, Ice, Water, Styrofoam, Immersion Heater, Thermocouple, 4 Thermometer, Food Dye]
image: /assets/images/CounterFlowSetupPicture.jpg
---

For Cornell's Engineering Thermodynamics Class (ENGRD 2210), we were asked to create our own operating conditions to learn about their different effects on a heat exchanger system. 

In our lab, we tested the effects of 2 different factors: the absolute flow rates and the operation in parallel flow vs counter flow in the heat exchanger system.

The flow rates are determined by m dot, which is shown below. 

--- 
![Photo of mDot]({{ "/assets/images/mDot.jpeg" | relative_url }}){: .center width="60%" }

---

In our experiements, we chose to measure 4 things, the temperature of the hot and cold reservoirs, and the temperatures of both sides of the thermocoupler. We initially started with a low flow rate so we can solely compare the effects of switching between parallel and counter flow. 

The counter flow system looks like: 

--- 
![Photo of CounterFlowSysDiagram]({{ "/assets/images/CounterFlowSysDiagram.jpeg" | relative_url }}){: .center width="60%" }

---

The parallel flow system looks like: 

--- 
![Photo of ParallelFlowSysDiagram]({{ "/assets/images/ParallelFlowSysDiagram.jpeg" | relative_url }}){: .center width="60%" }

---
Here is a picture of our lab set up for the counter flow:

--- 
![Photo of CounterFlow Set Up]({{ "/assets/images/CounterFlowSetupPicture.jpg" | relative_url }}){: .center width="60%" }

---

On the top half of the image, we have the hot water dyed in red in the plastic bin acting as the hot reservoir and the ice water dyed in blue in the cooler acting as the cold reservoir. In the center of the image, there is a heat exchanger where the reservoirs connect to with tubing. 

{: .nice-table }
| Device          | Temperature Before | Temperature After |
|:---------------:|:------------------:|:-----------------:|
| Hot Reservoir   | 41.2               | 21.6              |
| Cold Reservoir  | 6.8                | 27.7              |
| Hot Thermocoupler  | 28                | 37.5              |
| Cold Thermocoupler  | 19.2                | 33.2              |

<br>
- The difference in temperature of the hot reservoir is -19.6K
- The difference in temperature of the cold reservoir is 20.9K
- The difference in temperature of the hot thermocoupler is 9.5K
- The difference in temperature of the cold thermocoupler is 14K

We then switched to a parallel flow system by swapping the tubing's connection to the reservoir so both started on the same exact side. Our set up for the parallel system looked like:

--- 
![Photo of ParallelFlow]({{ "/assets/images/ParallelFlow.jpg" | relative_url }}){: .center width="60%" .rotate-90}

---

{: .nice-table }
| Device          | Temperature Before | Temperature After |
|:---------------:|:------------------:|:-----------------:|
| Hot Reservoir   | 41.3               | 29.5              |
| Cold Reservoir  | 7.2                | 25.7              |
| Hot Thermocoupler  | 31            | 31.5              |
| Cold Thermocoupler  | 22.7                | 22              |


<br>
- The difference in temperature of the hot reservoir is -11.8K
- The difference in temperature of the cold reservoir is 18.5K
- The difference in temperature of the hot thermocoupler is .5K
- The difference in temperature of the cold thermocoupler is -.7K

We then switched to a faster absolute flow rate. We decided to start with the parallel flow orientation since it was already set up that way.

{: .nice-table }
| Device          | Temperature Before | Temperature After |
|:---------------:|:------------------:|:-----------------:|
| Hot Reservoir   | 41.5               | 26.2              |
| Cold Reservoir  | 10.4            | 23.6          |
| Hot Thermocoupler  | 27.2            | 24.8          |
| Cold Thermocoupler  | 21.5            | 31.2          |

<br>

- The difference in temperature of the hot reservoir is -15.3K
- The difference in temperature of the cold reservoir is 13.2K
- The difference in temperature of the hot thermocoupler is -2.4K
- The difference in temperature of the cold thermocoupler 9.7K

We then switched back to the counter flow orientation but now with a faster flow rate.

{: .nice-table }
| Device          | Temperature Before | Temperature After |
|:---------------:|:------------------:|:-----------------:|
| Hot Reservoir   | 41.5           | 22.8          |
| Cold Reservoir  | 10.5            | 22.4          |
| Hot Thermocoupler  | 30.3            | 32.7          |
| Cold Thermocoupler  | 28              | 31.3          |

- The difference in temperature of the hot reservoir is -18.7K
- The difference in temperature of the cold reservoir is 11.9K
- The difference in temperature of the hot thermocoupler is 2.4K
- The difference in temperature of the cold thermocoupler is 3.3K

The differences in temperature tell us a lot about the heat transfer in this system. We are able to draw out the fact that counter flow is significantly more effective than parallel flow. Heat Transfer: The hot water experienced a temperature drop of 19.6K in counter flow, but only 11.8K in parallel flow. This implies that more heat, Q, was transferred in the counter flow arrangement for the same flow rate.

The differences in flow rate also tell us a lot about heat transfer and temperature change. We can see that increasing the flow rate increases the total heat transferred Q, but decreases the temperature change experienced by each fluid.

My overall conclusions are that: 
- Counter Flow Dominates: For a given (low) flow rate, the Counter Flow arrangement transfers significantly more heat than the Parallel Flow arrangement
- Flow Rate Trade-off: Increasing the mass flow rate increases the total heat transfer rate Q, but decreases the thermal effectiveness of the heat exchanger (resulting in a smaller temperature change for a given fluid) because the fluid spends less time interacting with the heat transfer surface