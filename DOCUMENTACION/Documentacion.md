**Documentación metodológica del proyecto.**



Fases del proyecto



&nbsp;	Fase 1: Análisis Inicial y Gestión de Riesgos

&nbsp;		En esta fase se lleva a cabo la identificación de los riesgos técnicos, eléctricos y operativos asociados a la automatización de los subsistemas del aula. Se analiza la viabilidad del proyecto, los requerimientos técnicos de cada módulo y las posibles limitaciones que pueden afectar su desarrollo. Se elabora una matriz de riesgos con niveles de impacto y probabilidad, que sirve de base para las decisiones de diseño y para priorizar las actividades del proyecto.

&nbsp;	

&nbsp;	Fase 2: Planeación de Iteraciones y Definición de Funcionalidades

&nbsp;		En esta fase se organizan las funcionalidades del sistema en una lista priorizada de características, administrada de acuerdo con ciclos cortos de trabajo.

Se definen los objetivos de cada iteración, los componentes electrónicos necesarios, el alcance técnico de los subsistemas (iluminación, ventilación y control de acceso), y los criterios de aceptación que permitirán validar su funcionamiento.

&nbsp;	

&nbsp;	Fase 3: Desarrollo e Implementación de Prototipos

&nbsp;		Cada módulo se desarrolla de forma incremental mediante ciclos iterativos.

&nbsp;		Las actividades incluyen:

&nbsp;			Programación del microcontrolador ESP32

&nbsp;			Diseño y conexión de sensores y actuadores

&nbsp;			Construcción de prototipos funcionales por subsistema

&nbsp;			Integración parcial entre componentes

&nbsp;		Esta fase permite obtener resultados tempranos que son evaluados antes de avanzar al siguiente nivel de complejidad.



&nbsp;	Fase 4: Pruebas, Validación y Correcciones

&nbsp;		Se realizan pruebas individuales para cada subsistema y pruebas integrales cuando dos o más módulos interactúan.

&nbsp;		Las pruebas incluyen:

&nbsp;			Verificación del funcionamiento eléctrico

&nbsp;			Validación de la respuesta del sistema a comandos de control

&nbsp;			Evaluación del desempeño de los actuadores

&nbsp;			Ajustes derivados de fallas o resultados no esperados

&nbsp;		El enfoque XP garantiza que esta etapa sea recurrente, no un proceso final.



&nbsp;	Fase 5: Integración Final y Documentación

&nbsp;		Una vez que las iteraciones alcanzan los objetivos funcionales, se integran todos los subsistemas en la maqueta física final.

&nbsp;		En esta fase se generan los documentos técnicos que recopilan:

&nbsp;			Resultados de pruebas

&nbsp;			Diagrama de conexiones

&nbsp;			Requerimientos alcanzados

&nbsp;			Lecciones aprendidas

&nbsp;			Evaluación de riesgos mitigados

&nbsp;		La fase concluye con la validación final del sistema como Aula 4.0 funcional.





Entregables del proyecto



&nbsp;	Análisis inicial:

&nbsp;		Documento de requerimientos 

&nbsp;		Matriz de riesgos 

&nbsp;		Especificaciones preliminares

&nbsp;	Planeación:

&nbsp;		Cronograma de actividades 

&nbsp;		Lista priorizada de funcionalidades 

&nbsp;		Criterios de aceptación

&nbsp;		Diseño de mockups

&nbsp;	Desarrollo:

&nbsp;		Código del ESP32

&nbsp;		Desarrollo de la aplicación móvil 

&nbsp;		Prototipos individuales 

&nbsp;		Esquemas de conexión

&nbsp;	Pruebas:

&nbsp;		Reportes de pruebas 

&nbsp;		Registros de fallos 

&nbsp;		Validaciones por iteración

&nbsp;	Integración final:

&nbsp;		Maqueta final 

&nbsp;		Documentación técnica 

&nbsp;		Guía de uso

&nbsp;		Reporte de conclusión



Cronograma General de Actividades



&nbsp;	Semana 1:

&nbsp;		Análisis inicial del proyecto

&nbsp;		Identificación y clasificación de riesgos

&nbsp;		Definición de requerimientos funcionales

&nbsp;	Semana 2:

&nbsp;		Planeación de iteraciones

&nbsp;		Selección de componentes

&nbsp;		Diseño preliminar de módulos

&nbsp;	Semana 3 a 4: 

&nbsp;		Desarrollo iterativo de módulos

&nbsp;		Prototipos funcionales de iluminación, ventilación y puerta

&nbsp;		Pruebas preliminares por subsistema

&nbsp;	Semana 5:

&nbsp;		Pruebas finales por módulo

&nbsp;		Correcciones y ajustes

&nbsp;		Integración parcial

&nbsp;	Semana 6:

&nbsp;		Integración total de la maqueta

&nbsp;		Validación final

&nbsp;		Documentación metodológica y técnica



Riesgos Identificados y Clasificados



&nbsp;	Riesgos Técnicos

&nbsp;		Fallas en sensores, módulos o actuadores

&nbsp;		Errores de programación en el ESP32

&nbsp;		Incompatibilidad entre componentes electrónicos

&nbsp;	Riesgos Eléctricos

&nbsp;		Sobrecarga en relés o fuentes de alimentación

&nbsp;		Cortocircuitos por conexiones incorrectas

&nbsp;		Desgaste prematuro de actuadores mecánicos

&nbsp;	Riesgos Operativos

&nbsp;		Integración deficiente entre subsistemas

&nbsp;		Retrasos por tiempo de pruebas y ajustes

&nbsp;		Fallos de respuesta en automatizaciones

&nbsp;	Riesgos de Gestión

&nbsp;		Cambios en requerimientos

&nbsp;		Dificultad para coordinar al equipo

&nbsp;		Entregables incompletos o fuera de tiempo



Roles del Equipo



&nbsp;	Líder de Proyecto

&nbsp;		Coordinación general 

&nbsp;		Control del cronograma 

&nbsp;		Gestión de documentación

&nbsp;	Programador Principal

&nbsp;		Desarrollo del código

&nbsp;		Integración de sensores y actuadores

&nbsp;		Pruebas de software

&nbsp;	Ingeniero de Hardware

&nbsp;		Cableado

&nbsp;		Esquemas de conexión

&nbsp;		Montaje de la maqueta

&nbsp;	Responsable de Pruebas y Documentación

&nbsp;		Ejecución de pruebas

&nbsp;		Registro de resultados

&nbsp;		Apoyo en documentación metodológica



Procesos Operativos del Proyecto



&nbsp;	Proceso de Desarrollo Técnico

&nbsp;		Basado en XP, se realizan ciclos cortos que permiten:

&nbsp;			Construcción incremental del sistema

&nbsp;			Pruebas continuas

&nbsp;			Retroalimentación constante

&nbsp;			Ajustes inmediatos ante fallas

&nbsp;	Proceso de Gestión de Riesgos

&nbsp;		Propio del modelo Espiral, contemplando:

&nbsp;			Identificación temprana de riesgos

&nbsp;			Evaluación por iteración

&nbsp;			Mitigación antes de avanzar

&nbsp;			Trazabilidad de decisiones técnicas

&nbsp;	Proceso de Control de Calidad

&nbsp;		Pruebas individuales por módulo

&nbsp;		Pruebas integrales del sistema

&nbsp;		Correcciones progresivas

&nbsp;		Validación final del funcionamiento

&nbsp;	Proceso de Documentación

&nbsp;		Registro de avance por fase

&nbsp;		Evidencia de pruebas y prototipos

&nbsp;		Actualización continua del documento metodológico

&nbsp;		Preparación del reporte final





