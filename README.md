![banner](/src/banner.png)

# AestheticStandards

Bienvenido a AestheticStandards, un repositorio dedicado a promover prácticas efectivas y estéticas en la nomenclatura de proyectos y commits. Este espacio está diseñado para ayudar a desarrolladores, tanto novatos como experimentados, a crear nombres más descriptivos, coherentes y útiles que mejoren la navegabilidad y la mantenibilidad de sus proyectos de software.

---
## ¿Por qué es importante una buena nomenclatura?

Una buena nomenclatura no solo facilita la comprensión del propósito y alcance de un proyecto o un commit, sino que también:

1. Mejora la *legibilidad* del código y la estructura del proyecto.
2. *Facilita* la colaboración entre múltiples desarrolladores.
3. Ayuda en el *mantenimiento* y la escalabilidad a largo plazo del código.
4. Permite que nuevos colaboradores se integren más fácilmente a un proyecto.

## AestheticStandard para Proyectos

En esta sección, proporcionamos recomendaciones sobre cómo nombrar tus proyectos de manera efectiva. Algunos puntos clave incluyen:

- *Consistencia*: Utiliza un formato consistente que pueda ser fácilmente reconocido y seguido por todos los miembros del equipo.
- *Descriptividad*: Elige nombres que expliquen claramente el contenido o la función del proyecto.
- *Simplicidad*: Evita el uso de jergas complicadas o siglas que podrían no ser entendidas por todos.

### Estructura de Nomenclatura de Proyecto
`[Plataforma]_[Tipo]_[Grupo?]_[Nombre]-[Detalle?]`

#### Reglas Generales

1. **Claridad:** Los nombres deben ser claros y precisos para evitar cualquier confusión sobre el contenido o propósito del proyecto.

2. **Consistencia:** Utiliza un formato consistente en todos los nombres para facilitar la búsqueda y el reconocimiento de los proyectos relacionados.

3. **Unicidad:** Cada nombre de proyecto debe ser único para evitar duplicidades dentro del mismo espacio de trabajo o entre espacios de trabajo similares.

4. **No Incluir Caracteres Especiales:** Evita el uso de caracteres especiales como `!`, `@`, `#`, `$`, `%`, `^`, `&`, `*`, `(`, `)`, excepto el guion bajo `_` y `-`.

#### Reglas de Componentes

1. **Plataforma:** Define el ambiente principal para el cual el proyecto está destinado. Debe ser lo suficientemente específico para diferenciar entre posibles plataformas objetivo pero no tan detallado que se convierta en jerga.
   - Ejemplo: `Windows`, `Web`, `Mac`, `Cross_Platform`
   - Utiliza abreviaturas reconocidas si es necesario para mantener la brevedad.

2. **Tipo de Proyecto:** Describe la categoría general del proyecto. Esta etiqueta ayuda a identificar rápidamente el tipo de trabajo involucrado.
   - Ejemplo: `App`, `Tool`, `Library`, `API`
   - Puedes elegir entre el nombre completo o una abreviatura estándar.

3. **Grupo (Opcional):** Indica el fabricante, grupo, equipo o departamento. Este componente es opcional y debe usarse sólo cuando proporciona un valor adicional significativo.
   - Si se incluye, debe ser suficientemente claro para que cualquiera dentro de la organización pueda entender a qué grupo se refiere.

4. **Nombre del Proyecto:** Debe ser descriptivo y reflejar el propósito principal o la función del proyecto.
   - Debe ser un término que indique su función principal de su uso o características.
   
5. **Detalle (Opcional):** Indica términos que detallen más específicamente el el nombre del proyecto. Este componente es opcional y debe usarse sólo cuando proporciona un valor adicional significativo.
   - Si se incluye, debe ser suficientemente claro sin extender más el nombre del proyecto.

#### Descripción de Etiquetas

- **Plataforma**
  - Etiqueta: `Android`
    - Abreviatura: `And`
    - Descripción: Proyectos diseñados para el sistema operativo Android.
  - Etiqueta: `iOS`
    - Abreviatura: `iOS`
    - Descripción: Proyectos destinados a dispositivos de Apple.
  - Etiqueta: `Windows`
    - Abreviatura: `Win`
    - Descripción: Proyectos principalmente para sistemas Windows.
  - Etiqueta: `Linux`
    - Abreviatura: `Lin`
    - Descripción: Proyectos que funcionan en distribuciones Linux.
  - Etiqueta: `MacOS`
    - Abreviatura: `Mac`
    - Descripción: Proyectos específicamente para MacOS.
  - Etiqueta: `Web`
    - Abreviatura: `Web`
    - Descripción: Proyectos accesibles a través de navegadores web.
  - Etiqueta: `Cross-platform`
    - Abreviatura: `Cross`
    - Descripción: Proyectos diseñados para múltiples sistemas operativos.
  - Etiqueta: `General`
    - Abreviatura: `Gen`
    - Descripción: Proyectos que no se asocian a una plataforma específica o que son transversales.

- **Tipo de Proyecto**
  - Etiqueta: `Device`
    - Abreviatura: `Dev`
    - Descripción: Proyectos relacionados con hardware o firmware.
  - Etiqueta: `App`
    - Abreviatura: `App`
    - Descripción: Aplicaciones de software, ya sean móviles, de escritorio o web.
  - Etiqueta: `API`
    - Abreviatura: `API`
    - Descripción: Interfaces de programación de aplicaciones para servicios backend.
  - Etiqueta: `Tool`
    - Abreviatura: `Tool`
    - Descripción: Herramientas o utilidades, incluyendo software de línea de comandos o scripts.
  - Etiqueta: `Library`
    - Abreviatura: `Lib`
    - Descripción: Bibliotecas de código destinadas a ser utilizadas por otros proyectos o aplicaciones.
  - Etiqueta: `Framework`
    - Abreviatura: `Frm`
    - Descripción: Estructuras de trabajo predefinidas para facilitar el desarrollo de software.
  - Etiqueta: `Documentation`
    - Abreviatura: `Doc`
    - Descripción: Documentación técnica, manuales, o guías de usuario.
  - Etiqueta: `Content`
    - Abreviatura: `Cont`
    - Descripción: Proyectos enfocados en la creación de contenido no técnico, como blogs, vídeos, o cursos.

- **Grupo (Fabricante o Grupo, Opcional)**
  - Descripción: Campo opcional para especificar el equipo, la compañía o el grupo responsable del proyecto cuando es relevante.
  - Ejemplos: `Google`, `OpenAI`, `Community`, `Samsung`, `Internal`

- **Nombre del Proyecto**
  - Descripción: Debe ser un identificador único y descriptivo del propósito del proyecto.
  
- **Detalle del proyecto (Opcional)**
    - Descripción:  Información adicional que pueda ser relevante para describir más específicamente el nombre del proyecto.


#### Reglas de Formato:

- **Pascal Snake Case:** Cada elemento del nombre del debe iniciar con una letra mayúscula seguida de letras minúsculas, unidos por guiones bajos sin espacios.
  - Correcto: `Data_Analysis_Tool`
  - Incorrecto: `data_analysis_tool`, `DataAnalysisTool`
  

- **Pascal Kebab Case (Solo para el componente detalle):** 
La primera letra de cada palabra debe comenzar con mayúscula seguido letras minúsculas y separadas por guiones, sin espacios entre ellas. 
  - Correcto: `Data-Analysis-Tool` 
  - Incorrecto: `data-analysis-tool`, `data_analysis_tool`

#### Reglas Adicionales

- **Flexibilidad de Grupo:** Cuando el grupo o fabricante no es relevante para la identificación del proyecto o cuando su inclusión podría causar confusión, debería omitirse.
- **Detalle especificos:** Los detalles pueden ser opcionales siempre y cuando el nombre del proyecto sea muy especifico, se considera usar este componente bajo su propio criterio, sin embargo, se debe imitir si este extienda demasiado el nombre del proyecto y no es claro la descripción del detalle.
- **Etiquetas Abreviadas vs. Nombres Completos:** Decide sobre el uso de abreviaturas basándote en la audiencia y la prevalencia de la abreviatura dentro de tu campo. Las abreviaturas deben ser comúnmente entendidas sin necesidad de explicación adicional.


#### Ejemplos de Buenas Prácticas

- `Web_API_Payment_Processor`: Indica claramente que se trata de una API para procesar pagos en una plataforma web.
- `Android_App_Samsung_Health-Monitor`: Utiliza abreviaturas reconocidas para 'App', incluye el fabricante que es relevante para el contexto del proyecto y sigue el formato Pascal Snake Case correctamente, además el se usa correctamente el componente detalle y sigue adecuadamente el formato Pascal Kebab Case para los detalles
- `Win_Tool_Music-Downloader`: Utiliza abreviaturas reconocidas para 'Win', y sigue el formato Pascal Snake Case correctamente y Pacal Kebab Case para el componente detalle.
- `Web_Doc_User-Guide`: Utiliza adecuadamente las abreviaturas, además del formato Pascal Snake Case y describe detalles usando Pascal Kebab Case.
- `Gen_Tool_Files`Utiliza adecuadamente las abreviaturas, además del formato Pascal Snake Case, pero omite el uso de detalles.
- `Android_App_Video-Downloader`Utiliza adecuadamente el uso de componentes no abreviados y cumple con el formato Pascal Snake Case, además utiliza detalles con Pascal Kebab Case.
 
#### Ejemplos de Malas Prácticas

- `WebAPIpayment`: Falta de claridad y mal uso de Pascal Snake Case.
- `app_health_tracker`: Uso incorrecto de minúsculas y falta de especificación de plataforma.
- `web_application_openai_chat_bot`: Falta de mayúsculas en Pascal Snake Case y uso de términos genéricos sin abreviaturas claras.
- `Tool_Development_tool`: Redundante en su descripción y mal uso de Pascal Snake Case, también carece de claridad en la especificación del proyecto.
- `Linux-Tool-App`: Redundante en su descripción y mal uso de los componentes, además combina el uso de Pascal Snake y Kebab Case, también carece de claridad en la especificación del proyecto.
- `Linux_App_Extreme-4K-Downloader-For-Youtube`: Aunque utiliza adecuadamente el uso de componentes no abreviados y cumple con el formato Pascal Snake Case, el componente del nombre del proyecto no define correctamente la funcionalidad por que es muy general, además utiliza detalles con Pascal Kebab Case, pero extiende demasiado el nombre.
