# Modelo en V

***PREGUNTAS***

### 1.¿Qué es el Modelo en V?<br><br>
El modelo en V es una metodología de desarrollo de  software que organiza el proyecto en dos ramas paralelas. En una están las 
**Fases de desarrollo** y en la otra los **Niveles de prueba** correspondientes. Cada etapa de  construcción tiene su contraparte de validación, lo que permite detectar errores de forma temprana y sistemática.

### 2.¿Cuáles son los objetipos principales de este Modelo?
El Objetivo principal de este Modelo en V es desarrollar software de calidad, detectando errores mediante pruebas planificadas, desde las primeras estapas de desarrollo y verificando que el sistema cumpla con el requisito del usuario.

### 3. ¿Qué significa Verificar y Validar?

•	La Verificación responde a la pregunta ¿Se está construyendo el producto correctamente? Consiste en una revisión realizada sin ejecutar código para comprobar que cada artefacto cumple con las especificaciones y normas acordadas.<br><br>
•	La Validación Es el proceso de evaluar el software ejecutando código tras la fase de desarrollo para determinar si cumple con la expectativa, necesidades del usuario y del negocio.}

### 4. ¿Cuáles son las estapas y nivel de prueba?

Sus estapas son :
* Analisis de requisitos---> Puebas de aceptación; <br>
Verrifican que el sistema cumpla las necesidades del usuario.Cada requisito debe tener prueba asociadas.
* Diseñodel sistema ---> Prueba del sistema; <br>
Evalua el software como un todo, comprueban funcionalidades, rendimiento, seguridad y usabilidad.
* Diseño de Arquitectonico---> Prueba d eintegración; <br>
Verifica la comunicación entre módulñlos. Detectan problemas de interfaces, APIs y compatibilidad.
* Diseño de módulo ---> Prueba unitarias; <br>
Comprueban cada función, clase o módulo individualmente. Detectan error en la lógica interna.

* Programación
### 5. ¿En que se diferencia del Módelo en Cascada?
El **Módelo v** relaciona cada etapa, del desarrollo con un etapa de prueba, mientras que el **Modelo en Cascada** organiza el trabajo en etapa secuenciales.

### 6. ¿Cuándo conviene usar el Módelo en V y cuando no conviene usarlo?


|  Conviene usarlo | NO conviene usarlo   |
|---|---|
|Los requisitos son fijos: El cliente sabe exactamente qué quiere desde el día uno y no habrá cambios.|Los requisitos son cambiantes: El cliente quiere ver avances y ajustar el rumbo sobre la marcha (proyectos dinámicos)|
|El costo de un error es altísimo: Fallar al final destruiría el presupuesto, la seguridad o el negocio (ej. software médico, bancario).|Es un producto mínimo viable (MVP): Necesitás lanzar una versión rápida al mercado para probar si funciona|
|Buscas documentación y trazabilidad: Necesitas demostrar formalmente qué diseño técnico cubre cada prueba.|El equipo es pequeño o busca agilidad: La burocracia de firmar entregables en cada fase puede retrasar el desarrollo.|
|La tecnología es conocida: El equipo domina las herramientas y no requiere experimentar o investigar sobre la marcha.|Hay alta incertidumbre técnica: Se van a integrar tecnologías nuevas o experimentales que pueden fallar.|
|Proyectos de tamaño pequeño a mediano: Donde todo el alcance se puede planificar y entender con claridad desde el inicio.|Proyectos excesivamente largos: Si el desarrollo tarda años, los requisitos definidos al principio quedarán obsoletos al subir la V.|

* Oña Joel
* Ferreyra Marco
* Donaire Marisol








