## The beginning

Historically, abstract thinking came into play very late in human kind development. Everything apart from counting was literally non-existent, so the only numbers were 1, 2, 3..., the natural numbers, except 0. Even the concept of zero wasn't invented up until the Persians. Ancient Greeks and Romans were very suspicious about negative numbers and zero. You will be surprised that this was the case in Europe even after the Renaissance, while Chines, 2000 years ago, knew how to use negatives. People just didn't have problems to which such numbers are the answer, so they were not interested in solving theoretical problems.

But eventually, when life became more complex people gradually developed new numbers. For instance, expressing debt is probably where negative numbers originated from. Dividing land was also a common thing and good candidate for use of rational numbers. Think a minute about the word "rational". "ratio-" means proportion. So, rational numbers won't represent sizes of sets, insted they'll represent ratios of sizes.

The more life developed, the more numbers also did so. Howerver, every step forward was faced with denail and scepticism. Complex numbers made no exception. Let's see why.

Around (790-850), Al-Khwarizm knew how to solve various types of quadratic equations, but restricted to only positive solutions. On the other hand, the famous

(2.1) <a href="https://www.codecogs.com/eqnedit.php?latex=x^2&space;=&space;-&space;1" target="_blank"><img src="https://latex.codecogs.com/gif.latex?x^2&space;=&space;-&space;1" title="x^2 = - 1" /></a>

was considered to not have a solution, because people couldn't find any number that satisfies it.

Of cource, we know that for sure because in

(2.2) <a href="https://www.codecogs.com/eqnedit.php?latex=x^2&space;=&space;mx&space;&plus;&space;c" target="_blank"><img src="https://latex.codecogs.com/gif.latex?x^2&space;=&space;mx&space;&plus;&space;c" title="x^2 = mx + c" /></a>

the left hand side is parabola, while the right hand side is straight line, so the solution is the intersection of both. In the case of (2.2) there is no intesection point.

Al-Khwarizm methods were introduced in Italy by Gerard of Cremona (1114-1187), and by the work of Leonardo da Pisa (Fibonacci)(1170-1250). About 1225, when Frederick II held court in Sicily, Leonardo da Pisa was presented to
the emperor. A local mathematician posed several problems, all of which were solved by
Leonardo. One of the problems was the solution of the equation

(2.3) <a href="https://www.codecogs.com/eqnedit.php?latex=x^3&space;&plus;&space;2x^2&space;&plus;&space;10x&space;=&space;20" target="_blank"><img src="https://latex.codecogs.com/gif.latex?x^3&space;&plus;&space;2x^2&space;&plus;&space;10x&space;=&space;20" title="x^3 + 2x^2 + 10x = 20" /></a>

It took several generations of mathematicians, from del Fero, Fiore and Tartaglia to Cardano who was the first to publish the general formula for cubic equation solution

(2.4) <a href="https://www.codecogs.com/eqnedit.php?latex=x&space;=&space;\sqrt[3]{\sqrt{\frac{q^2}{4}&space;-&space;\frac{p^3}{27}}&space;&plus;&space;\frac{q}{2}}&space;-&space;\sqrt[3]{\sqrt{\frac{q^2}{4}&space;-&space;\frac{p^3}{27}}&space;-&space;\frac{q}{2}}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?x&space;=&space;\sqrt[3]{\sqrt{\frac{q^2}{4}&space;-&space;\frac{p^3}{27}}&space;&plus;&space;\frac{q}{2}}&space;-&space;\sqrt[3]{\sqrt{\frac{q^2}{4}&space;-&space;\frac{p^3}{27}}&space;-&space;\frac{q}{2}}" title="x = \sqrt[3]{\sqrt{\frac{q^2}{4} - \frac{p^3}{27}} + \frac{q}{2}} - \sqrt[3]{\sqrt{\frac{q^2}{4} - \frac{p^3}{27}} - \frac{q}{2}}" /></a>

Take for instance

(2.5) <a href="https://www.codecogs.com/eqnedit.php?latex=x^3&space;=&space;-&space;6x&space;&plus;&space;20" target="_blank"><img src="https://latex.codecogs.com/gif.latex?x^3&space;=&space;-&space;6x&space;&plus;&space;20" title="x^3 = - 6x + 20" /></a>

Plugging the coefficients into Cardano's formula we get `x = 2`, so the formula appears to be correct. But there was a problem. Cardano intentionally avoided equations like

(2.6) <a href="https://www.codecogs.com/eqnedit.php?latex=x^3&space;=&space;15x&space;&plus;&space;4" target="_blank"><img src="https://latex.codecogs.com/gif.latex?x^3&space;=&space;15x&space;&plus;&space;4" title="x^3 = 15x + 4" /></a>

because you end up having square root of negative numbers. In this case

(2.7) <a href="https://www.codecogs.com/eqnedit.php?latex=\sqrt[3]{2&space;&plus;&space;\sqrt{-121}}&space;&plus;&space;\sqrt[3]{2&space;-&space;\sqrt{-121}}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\sqrt[3]{2&space;&plus;&space;\sqrt{-121}}&space;&plus;&space;\sqrt[3]{2&space;-&space;\sqrt{-121}}" title="\sqrt[3]{2 + \sqrt{-121}} + \sqrt[3]{2 - \sqrt{-121}}" /></a>

Cardano knew that `x = 4` satisfied the equation but he couldn't prove it because of the square root of a negative number. This case was know as _casus irreducibilis_.

Bombelli (1526-1572) was the first to find a solution to equation (2.6) through some clever substitutions. He looked at the expression and thought that maybe if he can work out both cube roots, the square roots of negative numbers might cancel out. He deduced that

<a href="https://www.codecogs.com/eqnedit.php?latex=\sqrt[3]{2&space;&plus;&space;\sqrt{-121}}&space;=&space;2&space;&plus;&space;\sqrt{-1},&space;\sqrt[3]{2&space;-&space;\sqrt{-121}}&space;=&space;2&space;-&space;\sqrt{-1}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\sqrt[3]{2&space;&plus;&space;\sqrt{-121}}&space;=&space;2&space;&plus;&space;\sqrt{-1},&space;\sqrt[3]{2&space;-&space;\sqrt{-121}}&space;=&space;2&space;-&space;\sqrt{-1}" title="\sqrt[3]{2 + \sqrt{-121}} = 2 + \sqrt{-1}, \sqrt[3]{2 - \sqrt{-121}} = 2 - \sqrt{-1}" /></a>

So when you add them together you get 4. This somewhat workarounded the problem. Bombelli gave up explaining the nature of these square roots of negatives though.
