# Guion Sincrónico: Defensa del Caso InverUp

**Instrucciones para el Equipo (Tríada):**
1. **Audiencia Real**: Están exponiendo frente a la profesora y la cátedra, **no** frente al directorio del banco. El objetivo es demostrar dominio de los *frameworks* ágiles y estratégicos para resolver una crisis real.
2. **Ritmo y Fluidez**: El reloj de 10 minutos arranca automáticamente al pasar la portada. Mantengan un ritmo ágil y seguro.
3. **Notas de Respaldo (🛡️)**: Usen estas respuestas para defender su razonamiento metodológico si la profesora les hace preguntas difíciles sobre por qué tomaron ciertas decisiones de producto.

---

### Bloque 1: Crisis y Evidencia
**Speaker**: VALE
**Tiempo**: 2:00 min
**Slides**: 1, 2 y 3

*(Slide 1 en pantalla)*
**VALE:** Buenos días, profesora y compañeros. Somos la célula encargada de diseñar el plan de rescate para el caso InverUp y su portafolio Futuro Joven.

*(Avanza a Slide 2)*
**VALE:** Al analizar la data del caso, identificamos que no enfrentamos un simple bug de usabilidad, sino una crisis de retención profunda. La evidencia cuantitativa nos muestra un 30% de fuga de usuarios activos en apenas 45 días. Al auditar el *funnel*, descubrimos que el 62% de quienes abandonaron intentó realizar un retiro justo antes. El quiebre está ahí.

*(Avanza a Slide 3)*
**VALE:** Metodológicamente, mapeamos el flujo y descubrimos que el sistema funciona para la regulación, pero castiga al usuario. Tras una burocrática validación del 50% de abandono, el usuario ve su saldo en $0 y se enfrenta a un silencio de 48 horas. El benchmark es claro: Fintual y Racional entregan en un día sin pedir fotos de carnet. Nuestro desafío de producto fue: ¿Cómo rediseñamos esta experiencia para frenar la fuga, sin tocar el core legacy bancario ni violar la normativa de la CMF?

> 🛡️ **Respuestas de Respaldo (Q&A) para Vale:**
> - *Profesora: "¿Por qué se enfocan solo en el retiro y no en mejorar la captación de usuarios nuevos?"*
>   **Respuesta**: "Porque el análisis de *churn* demostró que estamos perdiendo capital ya adquirido. Llenar la cubeta de adquisición no sirve si el 41% de los usuarios que intenta retirar se frustra y no vuelve. Hay que cerrar el agujero primero."

---

### Bloque 2: Usuario y Métrica Norte
**Speaker**: TAMI
**Tiempo**: 2:00 min
**Slides**: 4 y 5

*(Avanza a Slide 4)*
**TAMI:** Para fundamentar la solución, aplicamos Lean AI Research y construimos el Mapa de Empatía del usuario Sub-30. Simulamos los arquetipos y comprobamos que el dolor no es la espera por la regulación, sino la ansiedad y el miedo al robo. El usuario ve $0, escucha rumores de que es difícil sacar el dinero, y su reacción natural es colapsar el call center o amenazar a la CMF. 

*(Avanza a Slide 5)*
**TAMI:** A partir de este diagnóstico, definimos que el éxito de nuestro rescate no se medirá por cuántos retiros se completan, sino por la **Tasa de Continuidad de Inversión a 30 días (TCI-30)**. Nuestra *North Star Metric* asegura que el usuario no aplique el 'abandono silencioso' tras recibir su plata. Además, fijamos dos *Guardrails* innegociables para el negocio: cero aumento de fraude y 100% de cumplimiento del ciclo T+2.

> 🛡️ **Respuestas de Respaldo (Q&A) para Tami:**
> - *Profesora: "¿De qué sirvió exactamente usar IA en su discovery?"*
>   **Respuesta**: "El framework COSTAR nos permitió modelar rápidamente perfiles sintéticos con alta fricción emocional, acelerando la creación del mapa de empatía antes de validarlo con la data dura de los 1.850 tickets de soporte."

---

### Bloque 3: Gobernanza y Política
**Speaker**: CRISTIAN
**Tiempo**: 2:00 min
**Slides**: 6 y 7

*(Avanza a Slide 6)*
**CRISTIAN:** Ahora, metodológicamente, la mejor solución UX fracasa si no alinea a los *stakeholders* corporativos. Mapeamos la matriz de Poder/Interés triangulando dolores reales que descubrimos en nuestra etapa de *Discovery*. 

Por ejemplo, al realizar **entrevistas sintéticas** (simuladas con IA) con los *stakeholders* clave, descubrimos que el CFO está desesperado por frenar el sangrado de activos bajo administración sin pedir presupuesto. Además, el Gerente de Riesgo nos confirmó que su mayor temor es un alza en los fraudes, y vetará cualquier intento de quitar el SMS. Asimismo, identificamos a un equipo de Ingeniería sin horas para tocar el *core legacy*, y a una Gerente de CX colapsada por tickets en Zendesk.

Con estos *insights* claros, diseñamos una táctica de **"No Oposición"**: decidimos conscientemente que nuestro Sprint 1 sea 100% UI y no toque la autenticación ni el motor bancario. Así, Riesgo e Ingeniería no tienen motivos para vetarnos, y le damos a Finanzas y CX el alivio inmediato que buscan.

*(Avanza a Slide 7)*
**CRISTIAN:** Además, para mitigar los riesgos de usar Inteligencia Artificial en textos legales, diseñamos flujos de *Definition of Ready* y *Definition of Done* automatizados. Ningún *copy* llega a producción sin la validación anti-alucinaciones y la firma de Compliance. Demostramos que podemos ganar agilidad sin saltarnos la gobernanza del banco.

> 🛡️ **Respuestas de Respaldo (Q&A) para Cristian:**
> - *Profesora: "¿Acaso no es cobarde no enfrentarse a Riesgo para quitar la foto del carnet?"*
>   **Respuesta**: "Es estratégico. Ingeniería nos dijo que solo tienen 90 días-hombre de capacidad y no pueden tocar el *core*. Pelear con Riesgo hoy implicaría demorar la solución meses. Ganamos el alivio hoy, y preparamos el caso de negocio de biometría para el Sprint 2."

---

### Bloque 4: Priorización y Solución (Sprint 1)
**Speaker**: ERICK
**Tiempo**: 3:30 min
**Slides**: 8, 9 y 10

*(Avanza a Slide 8)*
**ERICK:** Con la política alineada, pasamos al tablero. Evaluamos 10 ideas a través de un modelo ponderado basado en datos. Asignamos 35% a UX, 25% a Negocio, 20% a Factibilidad y 15% a Seguridad. Este modelo nos permitió descartar falsos *quick-wins* como la 'Liquidez inmediata' por su alto riesgo, y priorizar dos soluciones front-end factibles: **El estado 'Fondos en tránsito' y el 'Lenguaje Claro'.** Ambas con puntajes sobre 4,40.

*(Avanza a Slide 9)*
**ERICK:** Como ven en el *mockup* de la derecha, diseñamos los incrementos en formato Gherkin. Transformamos la caja negra del "saldo cero" en un *tracker* visual que muestra el dinero protegido, las etapas de liquidación y la fecha de abono. Todo esto desde el *frontend*, sin tocar el motor bancario, atacando directamente la causa raíz de la ansiedad que colapsa el soporte.

*(Avanza a Slide 10)*
**ERICK:** Pero, ¿cómo sabremos si esto funciona? Definimos un tablero de métricas claro. A las 2 semanas del despliegue, mediremos la correcta finalización del flujo, la caída en los tickets por 'saldo cero' y la comprensión de nuestros nuevos copies. Planteamos la hipótesis de reducir entre un 35% y 40% estos tickets, pero lo presentamos como meta a validar, no como resultado garantizado. Además, el verdadero éxito se evaluará a los 30 días con nuestra North Star Metric: la tasa de continuidad de inversión. Si los números acompañan sin romper los *guardrails*, en la segunda etapa iremos por la biometría.

> 🛡️ **Respuestas de Respaldo (Q&A) para Erick:**
> - *Profesora: "¿Están seguros de que un simple cambio visual reducirá la fuga del 30%?"*
>   **Respuesta**: "La evidencia muestra que el 38% de los reclamos del call center son explícitamente por ver el saldo en cero. Al eliminar el agujero negro informativo, proyectamos matemáticamente una reducción de un 35% en tickets. El freno de la ansiedad es el primer paso para frenar el *churn*."

---

### Bloque 5: Solicitud Formal y Cierre
**Speaker**: ERICK
**Tiempo**: 1:00 min
**Slide**: 11

*(Avanza a Slide 11)*
**ERICK:** En conclusión, para materializar este plan de rescate establecimos 3 habilitadores críticos: asignar *Compliance* al Sprint, liberar acceso a los datos de cohorte, y comprometer al CFO con la evaluación de la métrica a 30 días. 

Con este trabajo demostramos que, aplicando *discovery* basado en datos, agilidad estratégica y un manejo político inteligente, es factible salvar un producto legacy en dos semanas. 

Demostramos que la regulación bancaria puede justificar por qué un proceso tarda dos días, pero gracias al diseño de producto, logramos evitar que el usuario sienta que perdió su dinero durante esa espera. 

Muchas gracias. 

> 🛡️ **Respuestas de Respaldo (Q&A) final:**
> - *Profesora: "Excelente presentación. ¿Qué lecciones se llevan de este caso para su futuro como Product Managers?"*
>   **Respuesta**: "Que el rol del PM no es solo velar por la tecnología o la UX, sino dominar la negociación de las restricciones del negocio. El mejor producto es el que logra sobrevivir a la tensión de factibilidad, deseabilidad y gobernanza."
