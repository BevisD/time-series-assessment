## Exercise 2(a)

$$
W = -2K \sum_{a=1}^{A} \log{\left\{ \left ( 1 - \hat{\gamma}^2_{jk \bullet (\backslash jk)} (f^{'}_a) \right) \mid_{\gamma^2_{jk \bullet (\backslash jk)}(\cdot) = 0} \right\}}
$$

$$
\left ( 1 - \hat{\gamma}^2_{jk \bullet (\backslash jk)} (f^{'}_a) \right) \mid_{\gamma^2_{jk \bullet (\backslash jk)}(\cdot)} \sim \text{Beta}(K - q, 1)
$$

$$
W \sim \text{Gamma}(A, \frac{K - q}{2K})
$$

$$
g(w) = \frac{\left(\frac{K-q}{2k}\right)^A}{\Gamma(A)} w^{A-1} e^{-\frac{K-q}{2K}w}
$$

## Exercise 2(b)

$$
W \overset{K \rightarrow \infty}{\sim} \sim \text{Gamma}(A, \frac{1}{2})
$$

$$
\lim_{K \rightarrow \infty} g(w) = \frac{\left(\frac{1}{2}\right)^A}{\Gamma(A)} w^{A-1} e^{-\frac{1}{2}w}
$$

## Exercise 2(c)
$$
\lim_{A \rightarrow \infty} \frac{W - \frac{2KA}{K-q}}{\frac{2K\sqrt{A}}{K - q}} \sim \mathcal{N}(0, 1)
$$