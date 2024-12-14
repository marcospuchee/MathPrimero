### Contenido principal

```ad-Formal
Supongamos que estamos explorando el nodo $(P_k)$, y que en la solución óptima de la relajación lineal hay varias variables con valor fraccionario. Existen diferentes criterios para elegir la variable a ramificar:
- **Ramificación simple:** se ramifica la variable más fraccionaria, es decir, aquella variable fraccionaria $x_j$ tal que $x_j^k - \lfloor x_j^k \rfloor$ toma el valor más cercano a $0.5$. En caso de empate tomaremos la variable con menor índice.
- **Ramificación fuerte:** para cada una de las variables fraccionarias se calculan las cotas que tendrían sus dos hijos, y se coge aquella cuya cota mínima (entre los dos hijos) sea máxima. En el caso de maximizar se invierte el criterio pues las cotas son superiores.
```

```ad-note
**Ramificación simple vs fuerte.**
La ramificación simple tiene la ventaja de ser muy fácil de implementar. En cambio, aunque la ramificación fuerte es más laboriosa, suele proporcionar mejores resultados.
```

**Tema:** [[Métodos de PLE#2. Algoritmo de Branch & Bound.]]

**Definiciones referenciadas:** [[Algoritmo de Branch & Bound]]

---
### Anki
