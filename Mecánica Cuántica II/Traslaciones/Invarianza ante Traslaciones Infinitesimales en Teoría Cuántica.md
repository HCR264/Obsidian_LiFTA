Para poder analizar la invarianza ante traslaciones nos centraremos en analizar el valor esperado de la posición y del momento. La razón es debido a que el valor esperado juega el mismo rol que la variables clásicas.

Pedimos que la transformación sea tal que $$\langle X \rangle \to \langle X \rangle + \epsilon$$$$\langle P \rangle \to \langle P \rangle$$
## Operador de Traslación
Para poder hacer transformaciones usamos el operador $T(\epsilon)$ definido como el ==*operador de traslación*==, tal que $$\langle \psi_\epsilon |X|\psi_\epsilon \rangle = \langle \psi | T^\dagger(\epsilon) X T(\epsilon)|\psi \rangle = \langle \psi |X|\psi \rangle + \epsilon$$$$\langle \psi_\epsilon |P|\psi_\epsilon \rangle = \langle \psi | T^\dagger(\epsilon) P T(\epsilon)|\psi \rangle = \langle \psi |P|\psi \rangle$$
El operador de traslación puede escribirse explicitamente al considerar una variación alrededor de $\epsilon = 0$ $$T(\epsilon) = I - \frac{i\epsilon}{\hbar}G$$
Donde $G$ es el ==generador de las traslaciones==. En este caso el generador es el operador momento, por lo tanteo$$T(\epsilon) = I - \frac{i\epsilon}{\hbar}P$$

## Estado Transformado
Para traslaciones infinitesimales, un estado $|\psi\rangle$ es modificado a un ==*estado trasladado*== $|\psi_\epsilon\rangle = T(\epsilon)|\psi\rangle$ tal que $$\langle \psi_\epsilon |X|\psi_\epsilon \rangle = \langle \psi |X|\psi \rangle + \epsilon$$$$\langle \psi_\epsilon |P|\psi_\epsilon \rangle = \langle \psi |P|\psi \rangle$$
A esto lo conocemos como una [[Transformación Activa|transformación activa]].
## Operador Transformado
Analizando el caso donde nada le pasa a los vectores de estado, sino que son los operadores los que se trasforman.

Para $\hat{X}$ y $\hat{P}$ tenemos $$X \to T^\dagger(\epsilon)XT(\epsilon) = X + \epsilon I$$$$P \to T^\dagger(\epsilon)PT = P$$
Lo anterior es una [[Transformación Pasiva|transformación pasiva]].
## Invarianza del Hamiltoniano
Para decir que una traslación es [[Invarianza ante Transformaciones|invariante]] se debe cumplir que $$T^\dagger(\epsilon)HT(\epsilon) = H $$
Esto, sumado a como deben transformar los valores esperados nos da la forma explicita de $T(\epsilon)$.
## Invarianza en el Valor Esperado del Hamiltoniano
La invarianza rotacional debe satisfacer que $$\langle \psi | H | \psi \rangle = \langle \psi_\epsilon | H | \psi_\epsilon\rangle$$