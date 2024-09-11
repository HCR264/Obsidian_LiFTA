## Operador de Traslación
Partimos de como se define el [[Invarianza ante Traslaciones Infinitesimales en Teoría Cuántica#Operador de Traslación|operador para traslaciones infinitesimales]]. Para transformar este en una trasformación finita lo aplicamos $N$ veces, con $N\to\infty$ y definiendo $\epsilon = \frac{a}{N}$ $$T(a) = \lim_{N\to\infty} \bigg[I - \frac{i}{\hbar}\frac{a}{N}P\bigg]^N = e^{-\frac{i}{\hbar}aP}$$
En la base de posiciones $T(a)$ es $$T(a) = e^{-a\frac{d}{dx}}$$
El valor esperado $\langle\psi | T(a) | \psi\rangle$, haciendo una expansión en serie de Taylor, obtenemos $$\langle\psi | T(a) | \psi\rangle = e^{-a\frac{d}{dx}} \psi = \psi(x+a)$$
## Traslaciones Sucesivas
El resultado de aplicar dos rotaciones sucesivas $T(a)$ y $T(b)$ da como resultado $$T(a)T(b) = e^{-a\frac{d}{dx}}e^{-b\frac{d}{dx}} = T(a+b)$$