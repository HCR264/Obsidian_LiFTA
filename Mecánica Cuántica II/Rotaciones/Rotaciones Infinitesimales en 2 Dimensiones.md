## Caso Clásico
Clásicamente, una rotación sobre el eje $z$ con un ángulo $\phi$ es 
$$\begin{bmatrix}
x \\ y \end{bmatrix} \to \begin{bmatrix}
x' \\ y' \end{bmatrix} = \begin{bmatrix} \cos(\phi) &-\sin(\phi) \\ \sin(\phi) & \cos(\phi) \end{bmatrix} \begin{bmatrix}
x \\ y \end{bmatrix}$$
$$\begin{bmatrix}
p_x \\ p_y \end{bmatrix} \to \begin{bmatrix}
p_x' \\ p_y' \end{bmatrix} = \begin{bmatrix} \cos(\phi) &-\sin(\phi) \\ \sin(\phi) & \cos(\phi) \end{bmatrix} \begin{bmatrix}
p_x \\ p_y \end{bmatrix}$$
## Operador de Rotación en Cuántica
Vamos a definir $R(\phi_0 \vec{k})$ como la ==matriz que rota los vectores== y, el ==operador asociado== a esta rotación se denota como $U[R(\phi_0\vec{k})]$.

Explícitamente, el ==operador de rotación== queda escrito como $$U[R(\epsilon_z\vec{k})] = I - \frac{i\epsilon_zL_z}{\hbar}$$
Aquí, el generador de la rotación es el momento angular $L_z$ $$L_z = XP_y-YP_x$$
### Transformación Activa
En una [[Transformación Activa|transformación activa]] la rotación se ve como $$|\psi\rangle \to |\psi_R\rangle = U[R(\phi_0\vec{k})]|\psi\rangle$$
Este estado rotado debe cumplir que $$\langle X \rangle_R = \langle X \rangle \cos(\phi_0) - \langle Y \rangle \sin(\phi_0)$$$$\langle Y \rangle_R = \langle X \rangle \sin(\phi_0) + \langle Y \rangle \cos(\phi_0)$$$$\langle P_x \rangle_R = \langle P_x \rangle \cos(\phi_0) - \langle P_y \rangle \sin(\phi_0)$$$$\langle P_y \rangle_R = \langle P_x \rangle \sin(\phi_0) + \langle P_y \rangle \cos(\phi_0)$$
### Transformación Pasiva
Si revisamos el caso para una [[Transformación Pasiva|transformación pasiva]], al aplicar el operador $U$ sobre los operadores obtenemos
$$U^\dagger X U = X-Y\epsilon_z$$
$$U^\dagger Y U = X\epsilon_z+Y$$
$$U^\dagger P_x U = P_x-P_y\epsilon_z$$
$$U^\dagger P_y U = P_x\epsilon_z+P_y$$
## Relaciones de Conmutación
Al utilizar la definición de $U[R]$ obtenemos las siguientes relaciones de conmutación
$$[X,L_z] = -i\hbar Y$$
$$[Y,L_z] = i\hbar X$$
$$[P_x,L_z] = -i\hbar P_y$$
$$[P_y,L_z] = i\hbar P_x$$