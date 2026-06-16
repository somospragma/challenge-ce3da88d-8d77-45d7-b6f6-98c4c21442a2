# Mejorar la mantenibilidad de un paquete npm

El equipo de desarrollo de Pragma está trabajando en un paquete npm que se utiliza internamente para diversas funcionalidades en proyectos de fintech y banca. El paquete requiere mejoras en su mantenibilidad para asegurar que sea fácil de actualizar y mantener en el futuro. Las áreas de mejora identificadas son la documentación, las pruebas y los tipos.

## Informacion General

| Campo | Valor |
|-------|-------|
| **Tema** | Mantenibilidad de paquetes npm |
| **Nivel** | junior-l2 |
| **Tipo** | practical |
| **Tiempo estimado** | 3-4 horas |

## Fases del Reto

### Fase 0: Configuración del Proyecto

**Objetivo:** Obtener el proyecto base funcional enviando el Código Base a un asistente de IA, que lo analizará, corregirá errores y generará un ZIP listo para usar.

**Tiempo estimado:** 15-30 minutos

**Instrucciones:**

- Asegúrate de tener instalado para ejecutar el proyecto: Node.js 18+, npm, VS Code o similar.
- Copia todo el contenido del campo **Código Base** de este reto — incluyendo el texto de instrucciones que aparece al inicio.
- Abre un asistente de IA (Claude en claude.ai, ChatGPT o Gemini — se recomienda Claude), pega el contenido copiado en el chat y envíalo.
- El asistente analizará los archivos, corregirá errores y generará un archivo ZIP descargable. Descárgalo y extráelo en la carpeta donde quieras trabajar.
- Ejecuta `npm install && npm run build` (o `npm start`). Si no hay errores, estás listo.

**Entregable:** El proyecto compila/arranca sin errores.

<details>
<summary>Pistas de conocimiento</summary>

- Copia el Código Base completo incluyendo el texto de instrucciones al inicio — esas instrucciones le indican al asistente exactamente qué hacer con los archivos.
- Si el asistente no genera el ZIP automáticamente al terminar el análisis, escríbele: "genera el ZIP ahora".
- Si el proyecto tiene errores al arrancar, comparte el mensaje de error con el mismo asistente para que lo corrija.

</details>

### Fase 1: Revisar y mejorar la documentación

**Objetivo:** Comprender la funcionalidad actual del paquete y mejorar su documentación para que sea clara y completa.

**Tiempo estimado:** 1 hora

**Instrucciones:**

- Lee la documentación existente del paquete.
- Identifica las áreas donde la documentación es incompleta o confusa.
- Mejora la documentación para que sea más clara y completa.

**Entregable:** Documentación mejorada del paquete.

<details>
<summary>Pistas de conocimiento</summary>

- La documentación debe incluir una descripción general del paquete, instrucciones de instalación, ejemplos de uso y explicaciones de las funcionalidades principales.

</details>

### Fase 2: Agregar y mejorar las pruebas

**Objetivo:** Asegurar que el paquete tenga pruebas unitarias y de integración para validar su funcionalidad y detectar errores.

**Tiempo estimado:** 1 hora

**Instrucciones:**

- Identifica las funcionalidades clave del paquete que necesitan ser probadas.
- Escribe pruebas unitarias y de integración para esas funcionalidades.
- Ejecuta las pruebas y asegura que pasen.

**Entregable:** Pruebas unitarias y de integración para el paquete.

<details>
<summary>Pistas de conocimiento</summary>

- Las pruebas deben cubrir las funcionalidades principales del paquete y manejar los casos de error.

</details>

### Fase 3: Agregar y mejorar los tipos

**Objetivo:** Asegurar que el paquete tenga tipos definidos para mejorar la experiencia del desarrollador y prevenir errores de tipo.

**Tiempo estimado:** 1 hora

**Instrucciones:**

- Identifica las funcionalidades del paquete que necesitan tipos definidos.
- Agrega tipos a las funcionalidades identificadas.
- Verifica que los tipos sean correctos y que el paquete compile sin errores.

**Entregable:** Tipos definidos para el paquete.

<details>
<summary>Pistas de conocimiento</summary>

- Los tipos deben ser claros y precisos para mejorar la experiencia del desarrollador.

</details>

## Dimensiones Evaluadas

- **queEs**: ¿Qué es la documentación y por qué es importante para la mantenibilidad del paquete?
- **paraQueSirve**: ¿Para qué sirven las pruebas en un paquete npm y cómo contribuyen a su mantenibilidad?
- **comoSeUsa**: ¿Cómo se usan los tipos en un paquete npm y cómo mejoran la experiencia del desarrollador?
- **erroresComunes**: ¿Qué errores comunes pueden ocurrir al escribir pruebas y cómo se pueden prevenir?

## Criterios de Evaluacion

- Documentación mejorada del paquete.
- Pruebas unitarias y de integración para el paquete.
- Tipos definidos para el paquete.

---

*Reto generado automaticamente por Challenge Generator - Pragma*
