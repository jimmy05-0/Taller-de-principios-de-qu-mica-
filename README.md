# Taller 1
## Universidad Nacional de Colombia
## Principios de Química
## Estudiantes: 
## Jimmy Fernando Correales Ruiz 
## Sebastian Escobar Castellanos

---

## 1.  Mecanismos de Acción Catalítica

Las **enzimas** son macromoléculas (principalmente proteínas) que actúan como **catalizadores biológicos**. Su función esencial es acelerar drásticamente la velocidad de las reacciones químicas celulares (hasta $10^{17}$ veces), lográndolo al disminuir la **energía de activación ($E_a$)** de la reacción, sin ser consumidas en el proceso.

### 1.1 Modelo Llave–Candado (Key–Lock) 🔑

* **Definición:** Propuesto por **Emil Fischer** en 1894, postula que el **sitio activo** de la enzima posee una estructura tridimensional **rígida** y estática, cuya forma geométrica es **perfectamente complementaria** a la del sustrato, como una **llave (sustrato)** que solo puede encajar en una **cerradura (sitio activo)** específica.

* **Características:**
    * **Alta Especificidad Absoluta:** La enzima está diseñada para interactuar con un único tipo de sustrato.
    * **Rigidez Conformacional:** Se asume que no hay cambios estructurales significativos en el sitio activo tras la unión del sustrato.
    * **Unión por Complementariedad Preexistente:** La forma geométrica óptima ya existe en la enzima antes del acoplamiento.

* **Ejemplo de Aplicación:** La **ureasa** exhibe esta alta especificidad, catalizando únicamente la hidrólisis de la **urea**, ya que su sitio activo es *estereoespecífico* y *geoespecífico* exclusivamente para esta molécula.

<div style="clear: both;"></div>
---

### 1.2 Modelo de Ajuste Inducido (Induced Fit) 

* **Definición:** Propuesto por **Daniel Koshland Jr.** en 1958, sostiene que el sitio activo no es estático, sino **flexible y dinámico**. La llegada y unión inicial del sustrato **induce un cambio conformacional** en la estructura de la enzima, reestructurando y **optimizando el sitio activo** para **"envolver"** y ajustarse mejor al sustrato.

* **Características:**
    * **Flexibilidad Conformacional:** La enzima experimenta un reordenamiento de los dominios proteicos o de los grupos laterales de aminoácidos tras la unión.
    * **Especificidad Relativa:** Permite que la enzima acepte **moléculas similares** (análogos) que puedan inducir el cambio conformacional.
    * **Mecanismo de Catálisis Activa:** La energía liberada por el cambio conformacional contribuye a la **estabilización del estado de transición**.

* **Ejemplo de Aplicación:** La **hexoquinasa** se pliega alrededor de la **glucosa** tras la unión, excluyendo el agua del sitio activo, lo cual es crucial para asegurar la **fosforilación** específica y prevenir la hidrólisis.

<div style="clear: both;"></div>
---

### 1.3 Sitio Inducido (Complemento)

* **Definición:** El **cambio conformacional** provocado por la unión del sustrato es lo que **crea la estructura catalíticamente activa** (el **sitio inducido**), optimizando la catálisis. El sustrato es necesario para **"activar"** completamente la maquinaria catalítica.

---

## 2.  Mecanismos de Degradación y Regulación Catalítica

Estos mecanismos se centran en los factores que limitan o detienen la acción enzimática.

### 2.1 Saturación Catalítica

* **Definición:** Ocurre cuando la **concentración de sustrato ([S])** es tan alta que **todos los sitios activos** están **ocupados continuamente** (E-S). El paso limitante es la conversión del E-S a producto.

* **Consecuencia:** La **velocidad de reacción (V)** alcanza su máximo teórico, denominado **Velocidad Máxima ($V_{max}$)**, independientemente de la adición de más sustrato.

* **Ejemplo:** La **glucoquinasa** en las células hepáticas se satura con glucosa en condiciones de alta glucemia, limitando la velocidad de almacenamiento.

---

### 2.2 Envenenamiento Catalítico (Inhibición Irreversible)

* **Definición:** **Inactivación permanente** de una enzima por una **sustancia tóxica** (el veneno) que se une **irreversiblemente** (a menudo mediante un enlace **covalente**) a un grupo esencial.

* **Ejemplos:**
    * El **cianuro** ($CN^-$) se une al **hierro hémico ($Fe^{2+}$)** en el sitio activo de la enzima **citocromo c oxidasa**, bloqueando la respiración celular.
    * Los **organofosforados** (pesticidas) inhiben irreversiblemente la enzima **acetilcolinesterasa**.

---

### 2.3 Bloqueo Catalítico (Inhibición Competitiva)

* **Definición:** **Inhibición reversible** en la que un **compuesto inhibidor ($I$)** estructuralmente similar al sustrato ($S$) **compite** directamente por el **sitio activo**, bloqueándolo temporalmente.

* **Efecto Cinético:** La $V_{max}$ **no cambia**, pero la **$K_m$ aparente aumenta**.

* **Ejemplo:** El **etanol** se administra para tratar la intoxicación por **metanol**, ya que actúa como un **inhibidor competitivo** de la enzima **alcohol deshidrogenasa (ADH)**, ralentizando el metabolismo del metanol tóxico.

---

## 3.  Modelos Cinéticos (Cuantificando la Acción Enzimática)

### 3.1 Modelo Michaelis–Menten

* **Definición:** Describe la **relación hiperbólica** entre la **velocidad inicial ($V_0$)** y la **concentración de sustrato ([S])**, bajo la asunción clave del **estado estacionario**.

* **Ecuación:** La ecuación clave derivada de este modelo es:
    $$V = \frac{V_{max} [S]}{K_m + [S]}$$

* **Parámetros:**
    * **$V_{max}$ (Velocidad Máxima):** Velocidad teórica máxima que se alcanza cuando la enzima está completamente saturada.
    * **$K_m$ (Constante de Michaelis):** Concentración de sustrato a la cual la velocidad es la **mitad de la $V_{max}$**. Se usa como medida inversa de la **afinidad**.

* **Ejemplo:** El modelo se aplica para determinar los parámetros cinéticos de cualquier enzima purificada, como la **lactato deshidrogenasa**.

---

### 3.2 Modelo Lineweaver–Burke

* **Definición:** Conocida como la **gráfica de doble recíproco**, es una **linealización** de la Ecuación de Michaelis–Menten (graficando $\frac{1}{V}$ versus $\frac{1}{[S]}$) para facilitar la determinación precisa de $V_{max}$ y $K_m$.

* **Ecuación:** La ecuación resultante es la de una línea recta:
    $$\frac{1}{V} = \left(\frac{K_m}{V_{max}}\right) \left(\frac{1}{[S]}\right) + \frac{1}{V_{max}}$$

* **Utilidad:** Es la herramienta visual estándar para **identificar y distinguir** los diferentes tipos de **inhibición enzimática** (competitiva, no competitiva, acompetitiva).

---

### 3.3 Pseudo–cinética de Reacción

* **Definición:** Simplificación experimental donde la concentración de **uno de los reactivos** está en un **exceso considerable**, por lo que se considera **constante**, permitiendo tratar la reacción como de **primer orden** respecto al componente limitante.

* **Ejemplo:** La **hidrólisis** catalizada por enzimas en **solución acuosa** se trata como reacción de **pseudo-primer orden** respecto al sustrato debido al exceso constante de **agua** ($\sim 55.5M$).

---

## 📚 Referencias Bibliográficas

Para la profundización de los conceptos de cinética y acción enzimática, se consultaron las siguientes fuentes académicas primarias y secundarias:

1.  **Berg, J. M., Tymoczko, J. L., & Stryer, L.** (2015). **Bioquímica** (8.ª ed.). Editorial Reverté. (Capítulos 8 y 13: Enzimas y Cinética).
2.  **Nelson, D. L., & Cox, M. M.** (2021). **Lehninger Principles of Biochemistry** (8.ª ed.). W. H. Freeman and Company. (Capítulo 6: Enzimas).
3.  **Koshland, D. E.** (1958). Application of a Theory of Enzyme Specificity to Protein Synthesis. **Proceedings of the National Academy of Sciences (PNAS)**, 44(2), 98–104. (Referencia original del modelo de Ajuste Inducido).
