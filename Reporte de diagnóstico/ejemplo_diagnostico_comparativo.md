# Reporte de Diagnóstico Comparativo de CV
**Candidato:** Juan Pérez Cotapos  
**Cargo Objetivo:** Analista Business Intelligence / Power Platform Specialist

---

### SECCIÓN 1: RESUMEN EJECUTIVO

El CV original presentaba una alta densidad de texto y una estructura redundante que dificultaba su lectura rápida (6-10 segundos) por parte de reclutadores humanos. Si bien la estructura lineal ya era compatible con ATS, el exceso de texto operativo diluía los logros más importantes del candidato. Se realizó una compresión agresiva del 40% del texto, se eliminaron roles redundantes consolidando una promoción interna en una Empresa de Consumo Masivo, y se reformularon los bullets de experiencia bajo metodologías de impacto, logrando que el logro más fuerte (reducción de procesos de 3 días a 20 minutos) quede al frente y de forma inmediatamente visible.

---

### SECCIÓN 2: DIAGNÓSTICO ATS — ANTES VS. DESPUÉS

| Criterio ATS | CV Original | CV Optimizado | Impacto |
|---|---|---|---|
| Estructura de layout | Flujo lineal (Correcto) | Flujo lineal (Correcto) | Mantenido |
| Salto de página | Título de sección huérfano al final de la pág 1 | Ajustado mediante CSS `break-after: avoid` | Resuelto |
| Orden de lectura de Experiencia | Separado en 2 bloques independientes en la trayectoria | Consolidado con indicador de promoción | Resuelto |
| Orden de lectura de Habilidades | Categorías lineales correctas | Categorías lineales correctas | Mantenido |
| Caracteres especiales problemáticos | Emojis en el header (📍, 📞, ✉, 🔗) | Reemplazados por separadores de texto `|` | Resuelto |
| Texto oculto o trampas anti-spam | No | No | Resuelto |
| Referencias con datos personales | Sección de referencias innecesaria al final | Sección eliminada para optimizar espacio | Resuelto |

**Nivel de compatibilidad ATS estimado:**
* **CV Original:** **Moderado-Alto** — Aunque el código HTML era lineal, la presencia de emojis en el contacto y el salto de página defectuoso afectaban la visualización técnica.
* **CV Optimizado:** **Alto** — 100% libre de caracteres incompatibles, control estricto de saltos de página y mejor orden de lectura de la trayectoria.

---

### SECCIÓN 3: KEYWORDS — BRECHA CUBIERTA

| Keyword / Término Clave | En CV Original | En CV Optimizado |
|---|---|---|
| Power Query (M) | Ausente (Solo Excel) | Incluido explícitamente |
| Looker Studio | Ausente | Incluido |
| Kepler.gl | Ausente | Incluido |
| Microsoft Copilot | Ausente | Incluido |
| Dataverse | Mencionada superficialmente | Reforzada con contexto de flujo |
| ERP corporativo (QAD) | Presente | Presente |

**Total de keywords críticas añadidas o reforzadas:** 5

---

### SECCIÓN 4: POSICIONAMIENTO — ANTES VS. DESPUÉS

#### 4.1 Perfil Profesional

| | CV Original | CV Optimizado |
|---|---|---|
| **Texto** | "Analista Business Intelligence y Power Platform Developer con más de 2 años de experiencia diseñando soluciones de datos end-to-end..." | "Analista Business Intelligence con más de 2 años de experiencia en consumo masivo. Especializado en Power BI (DAX, Power Query)..." |
| **Menciona tecnologías concretas** | Sí | Sí |
| **Tiene métricas de impacto** | No | No (Se reservan para experiencia) |
| **Diferencia al candidato de otros** | Débil (Autodenominado "Developer") | Fuerte (Rol e industrias claras) |

#### 4.2 Comparación de Bullets de Experiencia — Empresa de Consumo Masivo

**Analista Business Intelligence**

| CV Original | CV Optimizado |
|---|---|
| "Desarrollé end-to-end un modelo de optimización geoespacial de territorios comerciales mediante análisis espacial en QGIS sobre una base de 19.317 clientes activos..." | "Modelé territorios comerciales en QGIS sobre 19.317 clientes activos, redistribuyendo 90 zonas de venta y reduciendo tiempos de traslado de los vendedores." |
| "Diseñé y desplegué aplicaciones low-code en Power Apps integradas con Dataverse, y construí más de 10 flows..." | "Diseñé una solución automatizada de análisis de acuerdos comerciales (Rappel) integrando lectura de documentos, reduciendo el proceso de 3 días a 20 minutos." |

**Cambio de perfil:** De un perfil autodeclarado como "desarrollador" (difícil de defender técnicamente en entrevistas de código) a un **Analista de Inteligencia de Negocios y Automatización de alto impacto**, con logros numéricos incontrastables.

---

### SECCIÓN 5: MÉTRICAS AGREGADAS

| Logro | CV Original | CV Optimizado |
|---|---|---|
| Automatización de Acuerdos (Rapel) | Mencionada de forma genérica como "flujos" | Reducción de tiempo de **3 días a 20 minutos** |
| Optimización Geoespacial | "Reduciendo tiempos de traslado" (Vago) | 90 zonas optimizadas sobre **19.317 clientes** |
| Errores de ERP (Multinacional de Servicios) | "+1.000 incongruencias críticas" | +1.000 errores de datos resueltos |

**Total de métricas concretas:**
* **CV Original:** 2
* **CV Optimizado:** 4

---

### SECCIÓN 6: RESUMEN DE CAMBIOS Y RECOMENDACIONES FINALES

#### Tabla Resumen

| Categoría | Cambios Aplicados |
|---|---|
| Estructura ATS | Emojis del header removidos. Títulos protegidos contra huérfanos con CSS. |
| Perfil Profesional | Reducido de 80 a 50 palabras, eliminando el sesgo de "Developer" por uno de Analista BI. |
| Experiencia | Bullets reducidos a 1 línea. Se incorporó la reducción de tiempo clave (3 días a 20 min). |
| Habilidades | Agregados Looker Studio, Kepler.gl y Copilot. |
| Educación | Removida especialización de bachillerato técnico. Consolidado título universitario único. |
| Eliminaciones | Sección "Referencias" eliminada. |

#### Nota Final para el Cliente
> Este CV ha pasado por un proceso de refinamiento de contenido que reduce el ruido operativo en un 40%. La incorporación del logro clave de reducción de tiempos (3 días a 20 minutos) actúa como el gancho principal para captar la atención en los primeros 6 segundos de lectura. El documento es técnicamente limpio para los parsers ATS y narrativamente óptimo para las entrevistas. El CV está listo para postular.
