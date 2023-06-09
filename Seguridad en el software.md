- Defensa en profundidad
- Man-In-The-Middle
- guias normalizadas de estilo en la codificación y ejemplo
- OSVD
- Desbordamiento de buffer
- Cross-Site Scripting
- condiciones de carrera
- path traversal

El software es cada vez mas complejo por lo que los fallos se vuelven más difíciles de descubrir. Las aplicaciones presentan [[Error, Defecto y Falla#Defecto|defectos]], debilidades de diseño y configuraciones inseguras.

## Causas de la aparición de vulnerabilidades
- Tamaño excesivo y complejidad de aplicaciones
- Mezcla de código de varios orígenes
- Integración de los componentes del software defectuosa, estableciendo relaciones inadecuadas.
- Debilidades y fallos en la especificación de requisitos y diseño
- Falta de pruebas de seguridad basadas en el riesgo
- Entornos de ejecución con componentes que contienen [[Vulnerabilidad|vulnerabilidades]] o código malicioso embebido
- Falta de herramientas y un entorno de prueba adecuados que simulen adecuadamente el entorno real de ejecución
- Cambios de requisitos durante la etapa de codificación
- Mezcla de equipos de desarrolladores
- Falta de conocimiento de prácticas de programación segura de los desarrolladores
- No control de la cadena de suministro de software
- No seguimiento de guías normalizadas de estilo de codificación
- Fechas límite de entrega de proyectos inamovibles
- Cambio en la codificación en base a requerimiento de nuevas funcionalidades
- Aplicaciones desactualizadas en producción con parches correspondientes, configuraciones erróneas, etc.

Las aplicaciones son amenazadas y atacadas no solo en su fase de operación sino en todas las fases de su ciclo de vida

## Fases
- Desarrollo: un desarrollador puede alterar de forma intencionada o no el software bajo desarrollo de forma que se comprometa su fiabilidad futura durante la fase de operación
- Distribución e instalación: Ocurre cuando no se protege el software evitando manipulaciones antes de enviarlo o publicarlo, Del mismo modo si el instalador del software no bastiona la plataforma en la que lo instala o configura de manera insegura, queda vulnerable a merced de los atacantes
- Operación: cualquier software que se ejecute en una plataforma conectada a la red tiene sus vulnerabilidades expuestas durante su funcionamiento. El nivel de exposición variará dependiendo de si la red es privada o pública, conectada o no a Internet y si el entorno de ejecución ha sido configurado para minimizar las vulnerabilidades
- Mantenimiento: No publicación de parches de las vulnerabilidades  detectadas en el momento oportuno

- Vulnerabilidades de alto riesgo

## Vulnerabilidades y su clasificación

## Fuentes 
- Fallos de implementación: fallos provenientes de la codificacion de los diseños del softweare realizado
- Fallos de diseño: los sistemas hardware o software continen frecuentemente fallos de diseño o debilidades que pueden ser utilizados para realizar un ataque
- Fallos de configuración: la instalación de software por defecto implica por lo general la instalacion de servicios que no se usan pero que pueden presentar debilidades que comprometan la máquina

## Factores que definen una vulnerabilidad
- Producto: productos a los que afecta
- Donde: Componente o módulo del programa donde se localiza
- Causa y consecuencia: Fallo técnico concreto que cometió el programador a la hora de crear la aplicacion