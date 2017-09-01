---
Title: "GEOL 456 class 2"
Date: 29 Aug 2017
Author: Dr. Steen
---

# Dimensional analysis

Dimensional analysis means multiplying a number by fractions which are equivalent to one. However, these fractions are not numerically equal to one, because they are in different units.

For instance: we know that 1 mile is physically equivalent to 1.6 km. Thus, $\frac{1 \textrm{ mile}}{1.6 \textrm{ km}}$ is physically equivalent to 1, even though it is numerically equal to about 0.63.

So, say we know that Nashville is 286 km from Strong Hall. If we want to know how far that is in miles, we would do the following calculation:

$$
286 \textrm{ km} \times \frac{1 \textrm{ mi}}{1.6 \textrm{ km}} = 179 \textrm{ mi}
$$

This is physically correct, because it is equivalent to writing

$$
86 \textrm{ km} \times 1 = 179 \textrm{ mi}
$$



(Of course, part 3 is the *'draw the rest of the owl'* step)

```
Exercise: (Think, pair, share): Write three fractions that are 
physically equal to one, but numerically not equal to one, because 
the quantities in the numerator and the denominator are equivalent.
```

We can string out the dimensional analysis further, by continuously multiplying a quantity by 1. For instance: if people could use electricity to get energy instead of food, would a laptop charger be enough to power a human?

OK, we need a couple of pieces of information:

* How much power does a laptop charger supply? (Usually about 60 - 100 Watts, or W)
* What's a Watt? 1 J s$^{-1}$
$$
\frac{2000 \textrm{ food cal}}{24 \textrm{ hr}} \cdot
\frac{1 \textrm{kcal}}{1 \textrm{ food cal}} \cdot
\frac{1000 \textrm{ cal}}{1 \textrm{ kcal}} \cdot
\frac{4.2 \textrm{ J}}{1 \textrm{ cal}} \cdot
\frac{\textrm{s} \cdot 1\textrm{ W}}{1 \textrm{ J}} \cdot
\frac{1 \textrm{ W}}{3600 \textrm{ s}}
= 97 \textrm{W}
$$

We can use a general system to calculate answers in units we want, from information we have:

1. List the information we know
2. Write the units of the quantity we want to calculate
3. Figure out how to convert the information we have in the units in which it is given, to the units we want.

# Group questions:

How much energy did it take to build the Hoover Dam?

* The Hoover Dam contains $9 \times 10^9$ kg concrete. 1 kg concrete requires about 1 MJ (MegaJoule) to produce
* How long does it take the Hoover Dam to 'repay' that energy?
* Lake Mead has an area of 247 $\textrm{mi}^2$. If 250 W/$\textrm{mi}^2$ of sunlight strikes Lake Mean, and solar cells are 12% efficient (that is to say, for every W of sunlight that falls on a solar cell, you get 0.12 W energy), how much power could you get by covering Lake Mead with solar cells?

\section*{Reference information}

\subsection*{SI prefixes}

\begin{tabular}{l c r} 
prefix & text & factor \\
\hline
T &  tera & $10^{12}$ \\
G &  giga & $10^{9}$ \\
M &  mega & $10^{6}$ \\
k &  kilo & $10^{3}$ \\
hecto &  h & $10^{2}$ \\
(none) &  (none) & 1 \\
centi &  c & $10^{-1}$ \\
milli &  m & $10^{-3}$ \\
micro &  $\mu$ & $10^{-6}$ \\
nano &  n & $10^{-9}$ \\
pico &  p & $10^{-12}$ \\

\end{tabular}

\subsection*{Useful units}

\begin{tabular} {l c c c r} 
quantity & SI unit & unit symbol & fundamental units & notes\\
\hline
length & meter & m & m & \\
area & square meter & m$^2$ & m$^2$ & \\
volume & cubic meter & m$^3$ & m$^3$ & \\
time & second & s & s & \\
temperature & kelvin & K & K & \\
number of things & mole & mol &  &$6.022 \times 10^{23} \textrm{ things}$ \\
%electrical charge & coulomb & C & =1 ampere $\times$ 1 s \\ % Don't think we'll talk about this much in class
force & newton & N & $\textrm{kg} \cdot \textrm{m} \cdot \textrm{s}^{-2}$ \\
pressure & pascal & Pa & $\textrm{kg} \cdot \textrm{m}^{-1} \cdot \textrm{s}^{-2}$ \\
energy & joule & J & $\textrm{kg} \cdot \textrm{m}^2 \cdot \textrm{s}^{-2}$ \\
power & watt & W & $\textrm{kg} \cdot \textrm{m}^{2} \cdot \textrm{s}^{-3} $\\
\end{tabular} 




