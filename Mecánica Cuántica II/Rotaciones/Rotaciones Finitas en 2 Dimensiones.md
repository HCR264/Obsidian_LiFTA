## Operador de Rotación
Vamos a tomar él [[Rotaciones Infinitesimales en 2 Dimensiones#Operador de Rotación en Cuántica| operador de rotación para el caso infinitesimal]] y lo vamos a aplicar $N$ veces, con $N \to \infty$ y utilizando $\epsilon_z = \frac{\phi}{N}$
$$U[R(\phi,\hat{k})] = \lim_{N\to\infty} \bigg(I-\frac{i}{\hbar}\frac{\phi}{N}L_z\bigg)^N = e^{-\frac{i}{\hbar}\phi L_z}$$
## Rotaciones Sobre el Mismo Eje
Al aplicar el operador $U[R]$ de forma sucesiva en el mismo eje $\hat{k}$ obtenemos
$$U[R(\phi_1,\hat{k})]U[R(\phi_2,\hat{k})] = e^{-\frac{i}{\hbar}(\phi_1+\phi_2)L_z} = U[R(\phi_1+\phi_2,\hat{k})]$$
## Rotaciones en Coordenadas Polares
En la ==base de posiciones== (cartesianas), el operador $L_z$ se escribe como
$$L_z = x\bigg(-i\hbar \frac{\partial}{\partial y}\bigg)-y\bigg(-i\hbar\frac{\partial}{\partial x}\bigg)$$
Sin embargo, podemos llevarlo a coordenadas polares. Obteniendo así
$$L_z = -i\hbar \frac{\partial}{\partial \phi}$$ así, el operador queda definido como $$U[R] = e^{\phi \frac{\partial}{\partial \phi}}$$
## Rotación Sobre un Estado
La acción que tiene $U$ sobre un estado $\psi(\rho,\phi)$ se puede obtener haciendo una serie de Taylor alrededor de $\phi_0$, obteniendo
$$e^{-\phi_0\frac{\partial}{\partial \phi}}\psi(\rho,\phi) = \psi(\rho,\phi-\phi_0)$$