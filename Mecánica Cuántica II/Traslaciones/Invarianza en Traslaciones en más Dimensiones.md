Vamos a tomar una dirección arbitraría con vector normal $\hat{n}$. Para esto casos vamos a tomar la forma de los operadores de traslación [[Invarianza ante Traslaciones Infinitesimales en Teoría Cuántica#Operador de Traslación|infinitesimal]] y [[Invarianza ante Traslaciones Finítas en Teoría Cuántica#Operador de Traslación|finita]], con la diferencía de que proyectaremos el generador de la traslación en la dirección $\hat{n}$.

## Caso Infinitesimal
El operador de traslación queda definido como $$T(\delta \vec{n}) = I - \frac{i}{\hbar} \delta\hat{n} \cdot \vec{P}$$
## Caso Finito
El operador de traslación se obtiene aplicando $T(\delta\vec{n})$ $N$ veces con $N \to \infty$. Así, obtenemos $$T(\vec{n}) = \lim_{N\to\infty} T(\delta\vec{n})^N = e^{\frac{i}{\hbar}\vec{n}\cdot\vec{P}}$$
## Traslación Sucesiva
Se verifica que $$T(\vec{a})T(\vec{b}) = T(\vec{a}+\vec{b})$$