# UGCAnalitica

## ¿Qué es esto?

**UGCAnalitica** es mi primer proyecto real de análisis de datos, realizado con **datos reales y para un cliente real**: un freelancer de Upwork especializado en contenido UGC.

El objetivo del proyecto es utilizar datos de la plataforma para entender qué factores influyen en la **visibilidad, generación de oportunidades y conversión de contratos**, y transformar esos datos en decisiones accionables.

Este proyecto representa mi primer acercamiento práctico al análisis de datos. Por eso, antes de enfocarme en dominar herramientas técnicas, decidí concentrarme en una pregunta más fundamental:

> **¿Cómo piensa un analista de datos y cómo genera valor a partir de los datos?**

El proyecto sigue un proceso iterativo:

**Problema → Pregunta → Hipótesis → Datos → Análisis → Insight → Decisión**

---

# Análisis realizados

## 1. Impacto de la Availability Badge de Upwork

### Problema

El cliente experimentó una caída en las visitas y contratos de su perfil y necesitaba entender si la **Availability Badge** podía estar relacionada con su rendimiento.

### Método

- Comparación entre períodos con la Badge activada y desactivada.
- Análisis de **Profile Views** y contratos obtenidos.
- Cálculo de tasa de conversión:

**Tasa de conversión = Contratos / Visitas al perfil**

- Contraste con documentación oficial de Upwork.

### Resultado inicial

- Con Badge activa: hasta **5 contratos mensuales** en el período inicial analizado.
- Sin Badge: **1 contrato**.
- La documentación de Upwork indica que los clientes pueden utilizar la disponibilidad como criterio para encontrar freelancers.

### Conclusión

Los datos iniciales mostraron una **asociación entre la activación de la Availability Badge y un mayor volumen de contratos**.

Esto llevó a plantear la Badge como un elemento importante dentro de la estrategia de visibilidad y disponibilidad del perfil.

### Recomendación

Mantener la Availability Badge activa y combinarla con una estrategia de optimización del perfil.

📄 **Archivo:** [PDF - Análisis de Badge y vistas al perfil](https://github.com/user-attachments/files/27981813/BADGE_Y_VISTAS_AL_PERFIL_GITHUB.pdf)

🎥 **Video resumen:** [LinkedIn](https://www.linkedin.com/posts/dalmiro-rivadera-847854384_consegu%C3%AD-mi-primer-cliente-un-freelancer-ugcPost-7462303425741955072-jU28)

---

# 2. Propuestas y tasa de conversión — Identificación del cuello de botella

### Problema

El cliente tenía la Badge activa, recibía visitas al perfil y sus propuestas eran vistas, pero no todas se convertían en contratos.

La pregunta fue:

> **¿El problema está en conseguir visibilidad o en convertir esa visibilidad en una respuesta del cliente?**

### Método

Se analizaron manualmente **103 propuestas** desde la interfaz de Upwork:

- **94** propuestas archivadas.
- **9** propuestas activas.
- Cálculo de tasa de éxito.
- Cálculo del porcentaje de propuestas vistas sin respuesta.
- Comparación con benchmarks publicados por fuentes de la industria.

### Resultados

- Tasa de éxito: **6,4%**.
- Propuestas activas vistas sin respuesta: **33%**.
- Benchmark de visualización reportado: **12–17%**.
- El **33%** observado se encontraba por encima de ese rango de referencia.

### Interpretación

El análisis sugirió que el principal problema no era únicamente la visibilidad.

Las propuestas estaban llegando a clientes y siendo vistas, por lo que el siguiente punto a investigar era la **conversión posterior a la visualización**.

Esto llevó a plantear una nueva hipótesis:

> **¿Un video personalizado podría mejorar la respuesta de los clientes?**

### Recomendación inicial

Experimentar con videos personalizados de **30–60 segundos**, adaptados al contexto de cada cliente, como alternativa a propuestas exclusivamente textuales.

📄 **Archivo:** [PDF - Análisis de propuestas y conversión](https://github.com/user-attachments/files/28291470/INSIGHT_PROPUESTAS_CONVERSION.pdf)

🎥 **Video resumen:** [LinkedIn](https://www.linkedin.com/posts/dalmiro-rivadera-847854384_dataanalytics-upwork-freelancer-ugcPost-7465391928034029568-PGQ7/)

---

# 3. Availability Badge + Profile Boost — Del tráfico a la conversión

### Problema

Después de analizar la visibilidad del perfil y el rendimiento de las propuestas, surgió una nueva pregunta:

> **¿Cómo interactúan las herramientas de adquisición de Upwork con la generación de contratos?**

El objetivo fue analizar conjuntamente la **Availability Badge** y el **Profile Boost**, diferenciando entre exposición, visitas y conversiones.

### Métricas analizadas

**Profile Views**

Cantidad de personas que ingresaron y revisaron el perfil. Incluye tráfico orgánico y visitas generadas cuando el perfil está destacado.

**Invitations**

Invitaciones formales enviadas por clientes para participar en una oportunidad antes de que el freelancer envíe una propuesta.

**Impressions**

Cantidad de veces que el perfil apareció frente a clientes mediante Profile Boost. Representa exposición asociada a la promoción del perfil.

**Clicks**

Interacciones realizadas sobre el perfil promocionado. Upwork también registra acciones como guardar el perfil, invitar o contratar desde el anuncio.

**Conversion Rate**

Relación entre contratos obtenidos y visitas al perfil.

**Conversion Rate = Contratos / Profile Views**

### Resultados

Entre mayo y agosto se registraron:

- **25 contratos**.
- Promedio de **6,25 contratos/mes**.
- Agosto alcanzó **9 contratos en 25 días**.

### Comparación de escenarios

#### Abril — Boost sin Badge

- ~**350 impresiones**
- ~**90 visitas**
- **1 contrato**

#### Junio y julio — Badge sin Boost

- ~**100–145 visitas mensuales**
- **5 contratos por mes**
- **0 impresiones pagadas**

#### Agosto — Badge + Boost

- ~**180 impresiones**
- **145 visitas**
- **9 contratos en 25 días**

### Hallazgo clave

Los resultados sugieren que ambas herramientas cumplen funciones diferentes dentro del funnel:

**Profile Boost → Atracción**

Aumenta la exposición del perfil y genera oportunidades de interacción.

**Availability Badge → Señal de disponibilidad**

Refuerza frente al cliente que el freelancer se encuentra disponible para trabajar.

La combinación de ambas herramientas produjo el **mayor volumen de contratos observado**, con **9 contratos en 25 días**.

### Conclusión

Los datos sugieren que la estrategia más efectiva observada fue combinar **exposición + disponibilidad**, especialmente cuando existe capacidad para absorber una mayor demanda.

📄 **Archivo:** [PDF - Análisis de Badge, Boost y Conversión](PEGAR-AQUÍ-EL-LINK-DEL-PDF)

---

# 4. Video personalizado — Validación de la hipótesis de conversión

### Problema

El análisis anterior planteó que el video personalizado podía ser una herramienta para mejorar la conversión de propuestas.

El siguiente paso fue comprobar si los contratos obtenidos después de esa recomendación realmente estaban asociados al uso de videos personalizados.

### Método

Se realizó una auditoría manual de los chats correspondientes a **6 clientes** con contratos iniciados o completados.

Cada caso fue clasificado según:

- Origen del contacto: **Inbound / Outbound / Invite**.
- Existencia de video personalizado en el primer contacto.
- Forma en que se inició la conversación.
- Evolución del contacto hasta el contrato.

### Resultado del muestreo

De los **6 clientes auditados**:

- **0** tuvieron un video personalizado en el primer contacto.
- **4** llegaron mediante contacto **Inbound**.
- **1** correspondió a **Outbound**.
- **1** correspondió a una **Invite**.

En varios casos, los propios clientes indicaron que el perfil o contenido había llamado su atención antes de iniciar la conversación.

### Hallazgo analítico

La muestra **no proporciona evidencia suficiente para afirmar que el video personalizado fue el factor que convirtió las propuestas en contratos**.

En cambio, los casos analizados mostraron un patrón diferente:

**Perfil optimizado → Cliente descubre el perfil → Contacto inbound → Respuesta rápida → Negociación → Contrato**

### Conclusión

El análisis permitió revisar la hipótesis inicial.

En los casos auditados, la conversión estuvo más directamente asociada al **posicionamiento del perfil, la generación de leads inbound y la velocidad de respuesta y negociación** que al uso de un video personalizado.

El video continúa siendo una táctica válida para experimentar en propuestas outbound, pero **su impacto no puede considerarse demostrado a partir de esta muestra**.

📄 **Archivo:** [PDF - Resultados de Badge, Boost y Conversión](PEGAR-AQUÍ-EL-LINK-DEL-PDF)

---

# Conclusiones generales

Los análisis realizados permiten construir una visión progresiva del funnel de adquisición y conversión en Upwork:

EXPOSICIÓN
    ↓
Profile Boost
    ↓
VISITA AL PERFIL
    ↓
Availability Badge + Portfolio
    ↓
CONTACTO / INVITACIÓN
    ↓
RESPUESTA Y NEGOCIACIÓN
    ↓
CONTRATO
Principales aprendizajes

1. La visibilidad por sí sola no garantiza conversiones.

El Profile Boost puede aumentar la exposición, pero una mayor cantidad de impresiones no implica necesariamente un mayor número de contratos.

2. La Availability Badge mostró una fuerte asociación con la recuperación del volumen de contratos.

Después del período con 1 contrato en abril, se registraron 25 contratos entre mayo y agosto, con un promedio de 6,25 contratos/mes.

3. La combinación de herramientas produjo el mejor resultado observado.

Badge + Boost alcanzó 9 contratos en 25 días durante agosto.

4. El análisis de propuestas permitió identificar un problema posterior a la visibilidad.

El 33% de las propuestas activas analizadas fueron vistas pero no respondidas, lo que llevó a investigar mecanismos adicionales de conversión.

5. Las hipótesis deben validarse con datos reales.

El análisis del video personalizado mostró que una hipótesis razonable no necesariamente queda demostrada por los resultados observados.

De los 6 casos auditados, 0 utilizaron video personalizado en el primer contacto.

Herramientas utilizadas

Este proyecto fue desarrollado principalmente con asistencia de herramientas de Inteligencia Artificial, entre ellas:

ChatGPT
Google Gemini
DeepSeek

Las herramientas de IA fueron utilizadas para ayudar a procesar, explorar e interpretar los datos, contrastar hipótesis y estructurar el análisis.

No se utilizaron Python, SQL, PostgreSQL, Power BI ni otras herramientas tradicionales de análisis para procesar estos datos en esta etapa del proyecto.

¿Por qué?

UGCAnalitica fue mi primer proyecto real con datos reales y un cliente real.

Antes de enfocarme en dominar herramientas técnicas, quise entender algo más fundamental:

¿Cómo piensa y genera valor un analista de datos?

Por eso, el foco inicial estuvo puesto en aprender a:

Identificar problemas de negocio.
Formular preguntas relevantes.
Construir hipótesis.
Buscar y organizar evidencia.
Interpretar métricas.
Detectar patrones.
Cuestionar las hipótesis iniciales.
Transformar los resultados en decisiones.

Las herramientas técnicas serán incorporadas progresivamente para reproducir, automatizar y escalar este proceso de análisis.

Enfoque del proyecto

UGCAnalitica no busca únicamente mostrar gráficos o métricas.

El objetivo principal es demostrar un proceso de análisis de datos aplicado a una problemática comercial real.

El proyecto se construye alrededor de una idea:

El valor del análisis no está en la herramienta utilizada, sino en la capacidad de convertir datos en mejores decisiones.

Por eso, cada insight parte de un problema concreto y busca responder una pregunta:

PROBLEMA
   ↓
PREGUNTA
   ↓
HIPÓTESIS
   ↓
DATOS
   ↓
ANÁLISIS
   ↓
INSIGHT
   ↓
DECISIÓN

Este proyecto representa mi primera etapa de aprendizaje:

Primero aprender a pensar como analista.
Después aprender a automatizar ese pensamiento con herramientas técnicas.

Estado del proyecto

En desarrollo.

UGCAnalitica continúa evolucionando a medida que se incorporan nuevos datos, se validan hipótesis anteriores y se profundiza en el análisis del comportamiento del perfil y las oportunidades dentro de Upwork.
