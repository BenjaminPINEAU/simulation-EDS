# Résolution numérique d’une EDS : étude d’erreur et simulation
On se place dans l'espace de probabilités $(\Omega, \mathcal{A}, \mathbb{P})$, et on le muni de la filtration $\mathcal{F} = (\mathcal{F}_t)_{t \geq 0}$. On notera $W$ un mouvement brownien standard (m.b.s) adapté à la filtration $\mathcal{F}$. On s'intéresse à l'approximation numérique d'un processus numérique de diffusion $X$ définit sur $I = [0, T]$, $T > 0$ solution de l'équation différentielle stochastique (EDS) monodimensionnelle définie par 
\begin{equation}
    \text{d}X_t = b(t, X_t)\text{d}t + \sigma(t, X_t)\text{d}W_t, \quad \forall t \in ]0, T]
\end{equation}
