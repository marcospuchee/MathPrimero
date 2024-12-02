## 1. Tema 1: Teoría de grupos.
**Referencia:** [[Teoría de grupos]]
### 1. Definición y ejemplos.
- [[Grupo]]
- [[Grupo abeliano]]
### 2. Propiedades básicas.
- [[Propiedades de los grupos]] (elemento neutro único y elemento inverso único).
- [[Ley asociativa generalizada]]
- [[Ley conmutativa generalizada]]
- (iv), (v) de [[Propiedades de los grupos]]
### 3. Estructura de ciclos.
- [[Permutación]]
- [[Soporte de una permutación]]
- [[Permutaciones disjuntas]]
- [[r-ciclo]]
- [[Permutaciones disjuntas conmutan]]
- [[Teorema de la descomposición en ciclos]]
- [[Todo r-ciclo es una composición de r-1 2-ciclos]]
### 4. Exponenciales y orden de un elemento.
- [[Definición exponente]]
- [[Leyes de exponenciación]]
- [[Orden de un elemento de un grupo]]
- [[Grupo finito implica todo elemento del grupo tiene orden finito]]
- [[Exponente de un elemento de un grupo es neutro sii su orden divide al exponente]]
- [[Orden de un exponente de un elemento de un grupo]]
- [[Cálculo de órdenes (r-ciclos)]]
### 5. Subgrupo.
- [[Subgrupo]]
- [[Caracterización de subgrupo]]
- [[Condición necesaria y suficiente para que la unión de subgrupos sea subgrupo]]
- [[Condición necesaria y suficiente para que el producto de subgrupos sea subgrupo]]
### 6. Teorema de Lagrange.
- [[Coclase]]
- [[Propiedades coclases]]
- [[Biyección entre conjuntos de coclases]]
- [[Índice de un subgrupo]]
- [[Teorema de Lagrange (cardinal de un grupo)]]
- [[Corolario índice de un subgrupo a partir de otros dos índices]]
### 7. Subgrupo generado.
- [[Subgrupo generado]]
- [[Subgrupo generado es subgrupo]]
- [[Subgrupo generado es mínimo subgrupo que contiene al conjunto que lo genera]]
- [[Subgrupo generado es intersección de subgrupos que contienen al conjunto que lo genera]]
### 8. Grupos cíclicos.
- [[Grupo cíclico]]
- [[Propiedades orden grupos cíclicos]]
- [[G grupo finito impica que el orden de sus elementos divide al cardinal de G]]
- [[G grupo de orden primo entonces G es cíclico]]
- [[Grupo cíclico finito tiene un único subgrupo del orden de cada uno de sus divisores]]
### 9. Homomorfismos.
- [[Homomorfismo]]
- [[Propiedades homomorfismos]]
- [[Homomorfismo respeta estructura de subgrupo]]
- [[Inyectiva sii núcleo es neutro]]
- [[Teorema de unicidad de grupos cíclicos]]
- [[Conjugación es automorfismo]]
### 10. Conjugación en $S_n$.
- [[Permutación conjugada por otra permutación]]
- [[Tipo de una permutación]]
- [[Forma de todo conjugado de una permutación]]
- [[Permutaciones son conjugadas sii tienen el mismo tipo]]
### 11. Subgrupos normales.
- [[Subgrupo normal]]
- [[Definiciones equivalentes a subgrupo normal]]
- [[(ejercicio) Homomorfismo respeta normalidad]]
- [[Propiedades subgrupo normal]]
- [[Todo subgrupo de índice dos es normal]]
### 12. Grupos cociente.
- [[Grupo cociente]]
- [[Grupo cociente respeta propiedades]]
- [[Teorema de Cauchy para grupos abelianos]]
### 13. El grupo alternado $A_n$.
- [[Matriz permutada]]
- [[Matriz permutada por una composición]]
- [[Teorema de la paridad de una permutación]]
- [[Grupo alternado]]
- [[Teorema del grupo alternado]]
### 14. Simplicidad de $A_n$.
- [[3-ciclos (resp. transposiciones de tipo (2,2)) son conjugados y generan An]]
- [[Grupo simple]]
- [[Teorema de la simplicidad de An]]
### 15. Teoremas de isomorfía.
- [[Primer teorema de isomorfía]]
- [[Segundo teorema de isomorfía]]
- [[Tercer teorema de isomorfía]]
### 16. Teorema de correspondencia.
- [[Teorema de correspondencia]]
### 17. Los grupos $\textrm{Aut}(G)$ e $\textrm{Int}(G)$.
- [$\textrm{Aut}(G)$](Grupo de automorfismos), [$\textrm{Int}(G)$](Grupo de automorfismos internos)
- [$(\textrm{Aut}(G), \circ)$ es grupo](Grupo de automorfismos es grupo), [$\textrm{Aut}(G) \le S_G$](Grupo de automorfismos es grupo)
- [$\textrm{Int}(G) \unlhd \textrm{Aut}(G)$](Grupo de automorfismos internos es normal al grupo de automorfismos)
- [$G/Z(G) \cong \textrm{Int}(G)$](Grupo cociente con el centro es isomorfo a grupo de automorfismos internos)
- [$H \textrm{ car } G$](Subgrupo característico)
- [$Z(G) \textrm{ car } G$](Centro característico)
- [Propiedades $\textrm{car}$](Propiedades subgrupo característico)
- [$\forall n \ge 2, \, \, A_n \textrm{ car } S_n$](Grupo alternado característico en permutaciones)
---
## Tema 2: Acciones de grupos.
**Referencia:** [[Acciones de grupos]]
### 1. Definición.
- [Acción](Acción de grupo), [$G \curvearrowright \Omega$](Acción de grupo)
- [Homomorfismo representación](Teorema del homomorfismo representación)
- [Todo $p: G \to S_\Omega$ es homomorfismo representación de alguna acción](Todo homomorfismo es representación de alguna acción)
- [$\textrm{Ker}(\rho)$](Núcleo de la acción)
### 2. Teorema Órbita-Estabilizador.
- [$\textrm{Stab} \\_ \alpha$](Estabilizador), [$G \\_ \alpha$](Estabilizador)
- [$\textrm{Orb} \\_ \alpha$](Órbita), [$\mathcal O \\_ \alpha$](Órbita), [$\Omega \\_ \alpha$](Órbita)
- [Punto fijo](Estabilizador), [$\Omega \\_ \textrm{fix}$](Órbita)
- [$\textrm{Ker}(\rho) = \bigcap \\_ {\alpha \in \Omega} \textrm{Stab} \\_ \alpha$](Estabilizador)
- [$\forall \alpha \in \Omega$, $\textrm{Stab}_ \alpha \le G$](Propiedades estabilizador y órbita), 
- [$\forall \alpha \in \Omega, g \in G, \, \, \textrm{Stab}_ {g \cdot \alpha} = g \textrm{Stab}_ \alpha g^{-1}$](Propiedades estabilizador y órbita)
- [$\{\textrm{Orb}_ \alpha : \alpha \in G\}$ forma una partición de $\Omega$](Propiedades estabilizador y órbita)
- [$|\textrm{Orb} \\_ \alpha | = |G: \textrm{Stab} \\_ \alpha |$](Teorema órbita-estabilizador)
- [$|\Omega| = \sum^n_ {i = 1} |\textrm{Orb}_ {\alpha_ i}| = \sum^n_ {i = 1} |G: \textrm{Stab} \\_ {\alpha \\_ i}|$](Corolario teorema órbita-estabilizador)
- [$|\Omega| = |\Omega_{\textrm{fix}}| + \sum_{i = t+1}^n |\textrm{Orb} \\_ {\alpha \\_ i}|$](Corolario 2 teorema órbita-estabilizador)
- [$p$-grupo](p-grupo)
- [$p$-grupo $\implies$ $|\Omega| \equiv |\Omega \\_ \textrm{fix}| \pmod p$](Teorema cardinal conjunto con acción sobre p-grupo)
- [[Acción transitiva]], [$g \cdot \alpha = \beta$](Acción transitiva)
### 3. La acción natural.
- [[Acción natural]]
### 4. La acción sobre clases.
- [[Acción sobre clases]]
- [$\textrm{Core} \\_ G (H)$](Acción sobre clases)
- [$G/\textrm{Core} \\_ G(H) \overset{\sim}{\le} S \\_ {\mathcal L_H}$ ](Teorema de Cayley (grupo cociente con core isomorfo a grupo simétrico en las coclases))
- [$\textrm{Core} \\_ G (H)$ es el mayor subgrupo normal contenido en $H$](Core es el mayor subgrupo normal contenido en H)
- [[Subgrupo con el menor primo que divide al grupo como índice es normal]]
### 5. La acción por conjugación.
- [[Acción por conjugación]]
- [$\textrm{Cl} \\_ G(x)$](Acción por conjugación), [Clase de conjugación de $x$](Acción por conjugación)
- [$C_G(x)$](Acción por conjugación), [Centralizador de $x$ en $G$](Acción por conjugación)
- [$|G| = |Z(G)| + \sum \\_ {i = t+1}^n |G:C_G(x_i)|$](Ecuación de las clases)
- [$G$ $p$-grupo no trivial $\implies$ $Z(G) \neq 1$](Corolario ecuación de las clases)
- [$C_G(H)$](Centralizador de un subgrupo)
- [$H \le G$ abeliano $\iff$ $H \le C_G(H)$](Caracterización subgrupo abeliano (centralizador))
### 6. La acción sobre los subgrupos.
- [[Acción sobre los subgrupos]]
- [$N_G(H)$](Acción sobre los subgrupos), [Normalizador de $H$ en $G$](Acción sobre los subgrupos)
- [$|\{{}^gH : g \in G \}| = |G: N_G(H)|$](Acción sobre los subgrupos)
- [$N_G(H)$ es el mayor subgrupo de $G$ en el que $H$ es normal](El normalizador de H en G es el mayor subgrupo de G en el que H es normal)
- [$C_G(H) \unlhd N_G(H)$](Propiedades del normalizador de un subgrupo)
- [$N_G(H) / C_G(H) \overset{\sim}{\le} \textrm{Aut}(G)$](Propiedades del normalizador de un subgrupo)
---
## Tema 3: Teorema de Sylow
**Referencia:** [[Teorema de Sylow (referencia)]]

- [[Teorema de Cauchy generalizado]]
- [$p$-subgrupo de Sylow](p-subgrupo de Sylow), [$\textrm{Syl} \\_ p(G)$](p-subgrupo de Sylow)
- [$n_p(G)$](p-subgrupo de Sylow)
-  [$|G| = p^k m$ donde $p \in \mathbb P$ y $p \nmid m \implies \textrm{Syl} \\_ p(G) \neq \emptyset$](Corolario teorema de Cauchy generalizado)
- [Los $p$-subgrupos de Sylow son $p$-subgrupos maximales](Los p-subgrupos de Sylow son p-subgrupos maximales)
- [$|G| = p^km$, $p \in \mathbb P : p \nmid m$, $S \in \textrm{Syl} \\_ p(G) : S \unlhd G \implies S$ es el único $p$-subgrupo de Sylow de $G$](Condición suficiente para la unicidad de los p-subgrupos de Sylow de un grupo)
- [[Teorema de Sylow]]
- [$\textrm{Syl} \\_ p(G) = \{S\} \iff S \unlhd G$](Corolario 1 teorema de sylow)
- [$\textrm{Syl} \\_ p (G) = \{S\} \iff S \textrm{ car } G$](Corolario 2 teorema de Sylow)
---
## Tema 4: Anillo de polinomios.
**Referencia:** [[Anillo de polinomios]]
### 1. Definición.
- [[Anillo]]
- [[Anillo conmutativo]]
- [[Anillo con identidad]]
- [$0_Rr = r0_R = 0_R$](Identidad de la primera operación anula segunda operación)
- [Anillo con identidad $\implies (1_R = 0_R \iff R = \{0_R\})$](Condición necesaria y suficiente para la igualdad de identidades)
- [[Cuerpo]]
### 2. Anillo de polinomios.
- [[Polinomio]]
- [$\delta(p)$](Grado de un polinomio)
- [[Polinomio mónico]]
- [[Suma de polinomios]]
- [[Multiplicación de polinomios]]
- [[Propiedades polinomios]]
### 3. Ideales y anillos cociente.
- [[Ideal]]
- [$(a)$](Ideal generado), [$aR$](Ideal generado)
- [$(a)$ es el menor ideal de $R$ que contiene a $a$](Ideal generado es el menor ideal)
- [$R/I$](Teorema del anillo cociente)
### 4. $K[x]$
- [[Teorema división de polinomios]]
- [Existencia y unicidad de $p$ polinomio mónico $: I = (p)$](Existencia y unicidad de polinomio mónico tal que su ideal generado sea un ideal determinado)
### 5. Irreducibilidad
- [[Suma de ideales es ideal]]
- [[Polinomio irreducible]]
- [[Caracterización de polinomio irreducible]]
