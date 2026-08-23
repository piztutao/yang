**Pregunta 1 (Análise):** Estudo e representación gráfica da función racional $f\left(x\right)={{x^2}\over{x-1}}$.

**Resolución:**

- **Dominio:** dom(f) = ℝ ∖ {1}.
- **Asíntota vertical:** En $x=1$, xa que:  
lim (x → 1⁻) ${{x^2}\over{x-1}}$ = -∞ e lim (x → 1⁺) ${{x^2}\over{x-1}}$ = +∞.
- **Asíntota oblicua:** $y=m\,x+n$  
m = lim (x → ∞) ${{f\left(x\right)}\over{x}}$ = $1$  
n = lim (x → ∞) $f\left(x\right)-x$ = $1$  
Polo tanto, a asíntota oblicua é a recta $y=x+1$.
- **Extremos relativos:** Calculamos a primeira derivada:  
f'(x) = ${{2\,x}\over{x-1}}-{{x^2}\over{\left(x-1\right)^2}}$ = ${{\left(x-2\right)\,x}\over{\left(x-1\right)^2}}$  
Igualando a cero: $\left(x-2\right)\,x=0$ ⇒ $x=0$ e $x=2$.  
• En $x=0$, $f\left(0\right)=0$ → Máximo relativo en (0, 0).  
• En $x=2$, $f\left(2\right)=4$ → Mínimo relativo en (2, 4).

![gráfico](images/img_1.png)

**Pregunta 2 (Cálculo integral):** Calcula a área do recinto limitado polas curvas $f\left(x\right)=4-x^2$ e $g\left(x\right)=x+2$.

**Resolución:**

- **Puntos de corte:** Igualamos ámbalas dúas funcións:  
$4-x^2=x+2$ ⇒ $x^2+x-2=0$  
Resolvendo a ecuación obtemos $x=-2$ e $x=1$.
- **Cálculo da área:** No intervalo \[-2, 1\], compróbase que $f\left(x\right)\geq g\left(x\right)$.  
Área = ∫₋₂¹ ((4 - x²) - (x + 2)) dx = ∫₋₂¹ (2 - x - x²) dx  
Primitiva: $F\left(x\right)=-{{x^3}\over{3}}-{{x^2}\over{2}}+2\,x$  
Aplicando a regra de Barrow:  
Área = F(1) - F(-2) = ${{9}\over{2}}$ u² = 4.5 u².

![gráfico](images/img_2.png)

**Pregunta 3 (Álxebra lineal):** Discute segundo os valores do parámetro *m* o seguinte sistema de ecuacións lineais e resólveo para $m=0$:

x + y + z = 2  
2x - y + m·z = 1  
3x + m·y - z = 3

**Resolución:**

- **Determinante da matriz de coeficientes:**  
|A| = $-m^2-m+6=\left(-m-3\right)\,\left(m-2\right)$  
Igualando a cero: |A| = 0 ⇒ $m=2$ ou $m=-3$.
- **Discusión:**  
• Se *m* ≠ 2 e *m* ≠ -3: ran(A) = ran(A\*) = 3 = n° incógnitas ⇒ **Sistema Compatible Determinado** (solución única).  
• Se *m* = 2 ou *m* = -3: ran(A) = 2 ≠ ran(A\*) = 3 ⇒ **Sistema Incompatible**.
- **Resolución para m = 0:**  
O sistema é SCD. Aplicando a regra de Cramer ou eliminando variables:  
x = $1$, y = $1$, z = $0$.  
Solución única: (x, y, z) = (1, 1, 0). Representa a intersección de tres planos nun único punto.

![tikz](images/img_3.png)

**Pregunta 4 (Xeometría no espazo):** Dado o punto $P\left(1 , 2 , 3\right)$ e a recta r: (x - 1)/2 = (y + 1)/1 = z/2, calcula a proxección ortogonal de P sobre r e a distancia do punto P á recta r.

**Resolución:**

- **Plano π perpendicular a r que pasa por P:**  
O vector director da recta $v=\left[ 2 , 1 , 2 \right]$ actúa coma vector normal do plano.  
Ecuación: $2\,\left(z-3\right)+y+2\,\left(x-1\right)-2=0$ ⇒ $2\,z+y+2\,x-10=0$.
- **Proxección ortogonal M (corte de r e π):**  
Ecuacións paramétricas de r: $x=2\,t+1$, $y=t-1$, $z=2\,t$.  
Substituíndo no plano: $2\,\left(2\,t+1\right)+5\,t-11=0$ ⇒ $9\,t-9=0$ ⇒ $t=1$.  
Polo tanto, o punto proxección é $M\left(3 , 0 , 2\right)$.
- **Distancia de P á recta r:**  
Vector PM = [3 - 1, 0 - 2, 2 - 3] = [2, -2, -1].  
d(P, r) = |PM| = √(2² + (-2)² + (-1)²) = √(4 + 4 + 1) = √9 = $3$ unidades.

![tikz](images/img_4.png)

**Pregunta 5 (Probabilidade e Estatística):** O tempo de realización dun exame de acceso segue unha distribución normal $X$ ~ $N\left(60 , 10\right)$ en minutos.

**a)** Calcula a probabilidade de que un estudante tarde máis de 75 minutos.  
**b)** Calcula a probabilidade de que remate entre 50 e 70 minutos.

**Resolución:**

- **Tipificación:** $Z={{X-60}\over{10}}$ segue unha distribución $N\left(0 , 1\right)$.
- **Apartado a:**  
P(X > 75) = P(Z > (75 - 60)/10) = P(Z > 1.5) = 1 - P(Z ≤ 1.5) = 1 - 0.9332 = **0.0668** (6.68%).
- **Apartado b:**  
P(50 ≤ X ≤ 70) = P((50 - 60)/10 ≤ Z ≤ (70 - 60)/10) = P(-1 ≤ Z ≤ 1) = P(Z ≤ 1) - P(Z ≤ -1)  
= P(Z ≤ 1) - (1 - P(Z ≤ 1)) = 2·0.8413 - 1 = **0.6826** (68.26%).

![tikz](images/img_5.png)
