# ATS Resume Optimizer Toolkit

Un conjunto de herramientas y frameworks basados en Prompt Engineering y plantillas HTML para auditar, optimizar y adaptar currículums al estándar técnico de los sistemas de seguimiento de candidatos (ATS) y tomadores de decisiones técnicos.

Este repositorio contiene las instrucciones y plantillas necesarias para transformar un CV convencional en un documento optimizado de alta conversión.

---

## Estructura del Proyecto

* **01-CV-Optimizer/**: 
  * `Prompt_Maestro_CVs.md`: Prompt del sistema diseñado para analizar la estructura técnica de un CV, identificar brechas de palabras clave según el área profesional, y reescribir la experiencia laboral bajo la fórmula XYZ de Google (Acción + Herramienta + Impacto).
* **02-Reporte de diagnóstico/**:
  * `Prompt_Diagnostico_Comparativo_CVs.md`: Prompt comercial diseñado para generar informes de diagnóstico comparativo "Antes vs. Después" para clientes de consultoría de empleabilidad.
  * `ejemplo_diagnostico_comparativo.md`: Ejemplo real del diagnóstico resultante para servir de guía del *output* esperado.

---

## Cómo utilizar las herramientas

### 1. Optimización del CV (Prompt Maestro)
1. Copia el contenido de `01-CV-Optimizer/Prompt_Maestro_CVs.md`.
2. Pégalo en tu asistente de IA de preferencia (Claude 3.5 Sonnet recomendado).
3. Adjunta o pega el texto del CV que deseas auditar.
4. Sigue las instrucciones interactivas para reescribir los logros y estructurar el HTML.

### 2. Generación del Reporte (Prompt de Diagnóstico)
1. Copia el contenido de `02-Reporte de diagnóstico/Prompt_Diagnostico_Comparativo_CVs.md`.
2. Proporciona a la IA el CV original y la versión optimizada.
3. La IA generará un reporte estructurado en 6 secciones obligatorioas listo para entregar al usuario final.

---

## Estándares de Diseño HTML implementados

La plantilla resultante sigue estrictas reglas de compatibilidad con parsers automáticos:
* **Diseño lineal estricto**: Evita el uso de tablas complejas, floats, flexbox o grids que generen lecturas en zigzag en extractores de texto básicos.
* **Keywords estructuradas**: Las secciones de habilidades técnicas están agrupadas horizontalmente por categorías para un indexado eficiente.
* **Sin elementos invisibles**: Cero uso de texto oculto o técnicas anti-spam que puedan ser penalizadas por los motores de reclutamiento.

---

## Exportación a PDF

Para obtener el PDF final con la máxima fidelidad de renderizado:
1. Abre el archivo `.html` en Google Chrome o Microsoft Edge.
2. Presiona `Ctrl + P` (Imprimir).
3. Selecciona **Guardar como PDF** como destino.
4. Desactiva la opción **Encabezados y pies de página**.
5. Establece los márgenes como **Ninguno** o **Predeterminados** y haz clic en Guardar.
