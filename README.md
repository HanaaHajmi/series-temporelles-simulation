# series-temporelles-simulation

Simulation de séries temporelles financières en Python.

## Contenu

### `brownien_gbm.ipynb`

Notebook sur le **Mouvement Brownien Géométrique (GBM)** :

- Mouvement brownien standard
- GBM par la méthode d'**Euler-Maruyama**
- GBM par la solution exacte (**lemme d'Itô**)
- Pricing **Monte-Carlo** d'une option Call européenne
- Convergence en **O(1/√n)**

---

## Formules clés

**EDS du GBM :**

$$dS_t = \mu S_t \, dt + \sigma S_t \, dW_t$$

**Solution exacte (lemme d'Itô) :**

$$S_t = S_0 \exp\left(\left(\mu - \frac{\sigma^2}{2}\right)t + \sigma W_t\right)$$

**Prix Call Monte-Carlo :**

$$C = e^{-rT} \mathbb{E}[\max(S_T - K, 0)]$$

---

## Installation

```bash
pip install numpy matplotlib jupyter
```

## Lancement

```bash
jupyter notebook brownien_gbm.ipynb
```

---

## Auteur

Hanaa Hajmi — 2024
