As we had discussed, I am attaching the solution to problem 3. The only other problem without a solution is Q9, but I already solved for $E[X^2]$ in the class; You can ask Prof. Ashwin about the probability tree part. <br>
Solution - 
```math
\begin{align*}
P(T < 10) &= 0.4 \\
P(W | T < 10) &= 0.75 \\
P(10 < T < 30) &= 0.4 \\
P(W | 10 < T < 30) &= 0.65 \\
P(T > 30) &= 0.2 \\
P(W | T > 30) &= 0.55 \\
\text{We need to find P(T < 10 | W),} \\
P(T < 10 | W) &= \frac{P(W | T < 10)P(T < 10)}{P(W)} \\
P(W) &= P(W | T < 10)P(T < 10) \\
     &+ P(W | 10 < T < 30)P(10 < T < 30) \\
     &+ P(W | T > 30)P(T > 30) \\
\text{Plugging in the values,} \\
P(T < 10 | W) &\approx 0.447
\end{align*}
```
