---
layout: post
mathjax: true
title: "Interesting integral quotient dentity"
date: 2020-05-26
categories: math
---

So, I recently saw an interesting sort of quotient identity in a Discord server that I'm in, and thought that I should write about it.

$$\int_{1}^{a} \frac{1}{x} dx + \int_{1}^{b} \frac{1}{x} dx = \int_{1}^{ab} \frac{1}{x}dx$$

How would we go about proving this? Let's start by evaluating each side of this equation first. We'll start with the left side.

$$\begin{eqnarray}
\int_{1}^{a} \frac{1}{x} dx + \int_{1}^{b} \frac{1}{x} dx &=& ln |a| - ln |1| + ln |b| - ln|1| \nonumber \\
&=& ln |a| + ln |b| \nonumber
\end{eqnarray}$$

We then evaluate the right side.

$$\begin{eqnarray}
\int_{1}^{ab} \frac{1}{x} dx &=& ln |ab| - ln |1| \nonumber \\
&=& ln |ab| \nonumber
\end{eqnarray}$$

We can rewrite the equation now.

$$ln |a| + ln |b| = ln |ab|$$

This may look familiar; this is the *logarithm sum rule*. You can use that rule to justify this and be done with it, but my math teacher gave me a penchant for proving things, so let's prove that rule.

To begin, let $$M = b^m$$ and $$N = b^n$$.

$$\begin{eqnarray}
log_{b} (M) + log_{b} (N) &=& log_{b} (b^m) + log_{b} (b^n) \nonumber \\
    &=& m + n \nonumber \\
log_{b} (MN) &=& log_{b} (b^m * b^m) \nonumber \\
    &=& log_{b} (b^{m + n}) \nonumber \\
    &=& m + n \nonumber
\end{eqnarray}$$

Therefore,

$$\begin{eqnarray}
log_{b} (M) + log_{b} (N) &=& log_{b} (MN) \nonumber \\
&\downarrow& \nonumber \\
ln |a| + ln |b| &=& ln |ab| \nonumber \\
&\downarrow& \nonumber \\
\int_{1}^{a} \frac{1}{x} dx + \int_{1}^{b} \frac{1}{x} dx &=& \int_{1}^{ab} \frac{1}{x}dx \nonumber
\end{eqnarray}$$

Pretty cool, right?
