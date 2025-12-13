# Magnitudes Relacionales

> **Las Magnitudes Relacionales son magnitudes vectoriales invariantes que conservan su valor y forma bajo transformaciones de traslación y rotación.**

---

## I. Definiciones I (Magnitudes Relacionales)

La posición relacional ($\mathbf{r}\_i$), la velocidad relacional ($\mathbf{v}\_i$) y la aceleración relacional ($\mathbf{a}\_i$) de una partícula $i$ con respecto a un Sistema de Referencia Auxiliar, están dadas por:

$\mathbf{r}\_i \doteq \vec{r}\_i$

$\mathbf{v}\_i \doteq \dfrac{d(\vec{r}\_i)}{dt} = \vec{v}\_i$

$\mathbf{a}\_i \doteq \dfrac{d^2(\vec{r}\_i)}{dt^2} = \vec{a}\_i$

Donde $\vec{r}\_i$, $\vec{v}\_i$ y $\vec{a}\_i$ son la posición, velocidad y aceleración vectorial ordinaria de la partícula $i$ con respecto al Sistema de Referencia Auxiliar.

**Nota**

Las Magnitudes Relacionales (Vectoriales) son siempre las mismas que las Magnitudes Ordinarias (Vectoriales) en el Sistema de Referencia Auxiliar.

---

## II. Definiciones II (Magnitudes Relacionales)

La posición relacional ($\mathbf{r}\_i$), la velocidad relacional ($\mathbf{v}\_i$) y la aceleración relacional ($\mathbf{a}\_i$) de una partícula $i$ con respecto a cualquier Sistema de Referencia $S$, están dadas por:

$\mathbf{r}\_i \doteq \vec{r}\_i - \vec{R}$

$\mathbf{v}\_i \doteq (\vec{v}\_i - \vec{V}) - \vec{\omega} \times (\vec{r}\_i - \vec{R})$

$\mathbf{a}\_i \doteq (\vec{a}\_i - \vec{A}) - 2\vec{\omega} \times (\vec{v}\_i - \vec{V}) + \vec{\omega} \times [\ \vec{\omega} \times (\vec{r}\_i - \vec{R})\ ] - \vec{\alpha} \times (\vec{r}\_i - \vec{R})$

Donde:
* $\vec{r}\_i, \vec{v}\_i, \vec{a}\_i$ son la posición, velocidad y aceleración vectorial ordinaria de la partícula $i$ con respecto al Sistema $S$.
* $\vec{R}, \vec{V}, \vec{A}$ son la posición, velocidad y aceleración del origen del Sistema Auxiliar con respecto a $S$.
* $\vec{\omega}$ y $\vec{\alpha}$ son la velocidad angular y la aceleración angular del Sistema Auxiliar con respecto a $S$.

---

## III. Transformaciones (Invarianza$\cdot$Relaciones)

Las transformaciones de la posición relacional ($\mathbf{r}\_i$), la velocidad relacional ($\mathbf{v}\_i$) y la aceleración relacional ($\mathbf{a}\_i$) de una partícula $i$ entre un Sistema $S$ y otro Sistema $S'$, están dadas por:

$\mathbf{r}\_i \doteq (\vec{r}\_i - \vec{R}) = \mathbf{r}'\_i$

$\mathbf{r}'\_i \doteq (\vec{r}'\_i - \vec{R}') = \mathbf{r}\_i$

$\mathbf{v}\_i \doteq (\vec{v}\_i - \vec{V}) - \vec{\omega} \times (\vec{r}\_i - \vec{R}) = \mathbf{v}'\_i$

$\mathbf{v}'\_i \doteq (\vec{v}'\_i - \vec{V}') - \vec{\omega}' \times (\vec{r}'\_i - \vec{R}') = \mathbf{v}\_i$

$\mathbf{a}\_i \doteq (\vec{a}\_i - \vec{A}) - 2\vec{\omega} \times (\vec{v}\_i - \vec{V}) + \vec{\omega} \times [\ \vec{\omega} \times (\vec{r}\_i - \vec{R})\ ] - \vec{\alpha} \times (\vec{r}\_i - \vec{R}) = \mathbf{a}'\_i$

$\mathbf{a}'\_i \doteq (\vec{a}'\_i - \vec{A}') - 2\vec{\omega}' \times (\vec{v}'\_i - \vec{V}') + \vec{\omega}' \times [\ \vec{\omega}' \times (\vec{r}'\_i - \vec{R}')\ ] - \vec{\alpha}' \times (\vec{r}'\_i - \vec{R}') = \mathbf{a}\_i$

---

## IV. Bibliografía

1. A. Blatter, *Una Reformulación de la Mecánica Clásica* (2015). [PDF](https://atorassa.github.io/physics-authors/blatter/spanish/pdf/09.pdf)
2. A. Tobla, *Una Reformulación de la Mecánica Clásica* (2024). [PDF](https://atorassa.github.io/physics-authors/tobla/spanish/pdf/02.pdf)
