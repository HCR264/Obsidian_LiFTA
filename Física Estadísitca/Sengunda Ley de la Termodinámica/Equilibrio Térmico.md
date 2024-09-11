- Se toma un sistema aislado dividido en dos subsistemas, tal que $$E=E_1+E_2$$ $$V=V_1+V_2$$$$N=N_1+N_2$$ y con un peso estadístico $$\Omega=\Omega_1\Omega_2$$
- La entropía del sistema (usando la [[Ley de Boltzman||Boltzman]]) es $S=k\ln(\Omega_1)+k\ln(\Omega_2)=S_1+S_2$.

- Si se considera que hay transferencia de energía entre ellos $V_1=V_2=cte$ y $N_1=N_2=cte$.
- Dejamos a la energía en función de $E$ y $E_1$ haciendo $E_2=E-E_1$, por lo tanto $$S(E_1,E_2,V_1,V_2,N_1,N_2)\to(E,E_1,V,V_1,N,N_1)$$
- Maximizamos la entropía $$\bigg(\frac{\partial S}{\partial E_1}\bigg)_{E}=\bigg(\frac{\partial S_1}{\partial E_1}\bigg)+\bigg(\frac{\partial S_2}{\partial E_2}\bigg)\frac{dE_2}{dE_1}=0$$
- Como $E_2=E-E_1$ entonces, lo anterior da como resultado $$\bigg(\frac{\partial S_1}{\partial E_1}\bigg)_{V_1,N_1}=\bigg(\frac{\partial S_2}{\partial E_2}\bigg)_{V_2,N_2}$$
- Esta igualdad es la ==condición para el equilibrio térmico.== 

- Otra interpretación nos dice que no hay transferencia de calor. Bajo esta consideración podemos decir una temperatura absoluta para un subsistema $$\bigg(\frac{\partial S_i}{\partial E_i}\bigg)_{V_1,N_1}=\frac{1}{T_i}$$
- En otras palabras $T_1=T_2$.

- Por otro lado, derivando respecto al tiempo y usando $S=S_1+S_2$, llegamos a $$\frac{dE}{dt}=\bigg(\frac{1}{T_1}-\frac{1}{T_2}\bigg)\frac{dE_1}{dt}>0$$
- La desigualdad expresa el [[Principio de Clausius|principio de Clausius]].