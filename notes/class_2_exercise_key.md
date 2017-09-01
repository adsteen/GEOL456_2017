---
title: "Solution to Class 2 in-class problem"
date: 29 August 2017
author: Dr. Steen
---

Question: The Hoover Dam contains $7 \times 10^9$ kg concrete, and produces $2 \times 10^9$ W of energy. 1 take 1 MJ of energy to produce 1 kg concrete. How long did the dam's power plant have to run to "pay back" the energy cost of manufacturing its concrete?

Solution:

$$
\frac{7 \times 10^9 \textrm{ kg concrete}}{} \cdot
\frac{10^6 \textrm{ J}}{1 \textrm{ kg concrete}} \cdot
\frac{1 \textrm{ W s}}{1 J} \cdot
\frac{}{2 \times 10^9 \textrm{ W}} =
3.5 \times 10^6 \textrm{ s}
$$

That looks funny - we don't usually see a quantity in the denominator of a fraction when there's nothing in the numerator - but it is totally legal. We could just as well start the equation off with the fraction 

$$
\frac{7 \times 10^9 \textrm{ kg concrete}}{2 \times 10^9 \textrm{ W}}
$$

The only reason I didn't, is that it is tough to know from the start that $2 \times 10^9 \textrm{ W}$ will end up in the denominator, rather than the numerator.

We now have the correct answer, but it is perhaps polite to convert to a more intuitive unit of time:

$$
\frac{3.5 \times 10^6 \textrm{s}}{} \cdot
\frac{1 \textrm{ hr}}{3600 \textrm{ s}} \cdot
\frac{1 \textrm{day}}{24 \textrm{ hr}} = 
40.5 \textrm{ days}
$$

An important thing to understand is that there are two ways to solve the part of this problem that I think is the hardest, which is realizing that 1 W $\cdot$ s = 1 J:

* You can just look at the units: 1 J is 1 kg m / s$^2$, and 1 W is 1 kg m / s$^3$, so 1 W $\cdot$ s = 1 J.
* (Better): You can think about what these mean. A Watt is a rate of energy delivery. If you deliver 1 W for 1 s, you have delivered 1 J of energy. This is a little like saying that if you travel at 1 mile per hour for 1 hour, you have traveled 1 mile - so 1 mph $\cdot$ h = 1 mile.