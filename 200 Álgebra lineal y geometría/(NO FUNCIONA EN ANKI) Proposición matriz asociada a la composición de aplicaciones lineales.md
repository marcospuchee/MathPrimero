### Proposición

Sean $f: V \rightarrow V'$ y $g: V' \rightarrow V''$ aplicaciones lineales. Sean $B, B', B''$ [[Base]] de $V, V', V''$ respectivamente. Entonces:
$$M_{B,B''}(g \circ f) = M_{B', B''}(g)M_{B,B'}(f)$$
Es decir, la matriz asociada ([[Matriz asociada a una aplicación lineal]]) a una composición es el producto de matrices asociadas del final al principio. 

---
### Demostración

Sea $v \in V$. Tenemos $(g \circ f)(v)_{B''} = M_{B, B''}(g \circ f)v_B$ ([[Cálculo de las coordenadas una imagen mediante una aplicación lineal dada la matriz asociada]]] aplicado a $g \circ f$). Sabemos que $(g\circ f)(v)_{B''} = g(f(v))_{B''} = M_{B',B''} (g) f(v)_{B'}$, ([[Cálculo de las coordenadas una imagen mediante una aplicación lineal dada la matriz asociada]] aplicado a g) $= M_{B', B''} (g) M_{B,B'} (f) v_B$ ([[Cálculo de las coordenadas una imagen mediante una aplicación lineal dada la matriz asociada]] aplicado a $f$). Por tanto, acabamos de llegar a que $$M_{B, B''} (g \circ f)v_B = M_{B',B''}(g)M_{B,B'}(f)v_B$$Sin embargo, por [[Lema producto matriz asociada y coordenadas]]
$$M_{B,B''}(g \circ f)v_B = M_{B',B''}(g)M_{B,B'}(f)$$


---
### Referencias

[[Aplicación lineal]]