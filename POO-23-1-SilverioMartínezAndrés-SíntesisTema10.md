# Azucar Sintáctica, Wrappers y Migración de Sistema
## Azucar Sintáctica
- Término para referirse a los añadidos a la sintaxis de un lenguaje de programación
- Dichos están diseñados para hacer algunas construcciones más fáciles de leer o expresar
- Es una forma de escribir la sintaxis que se usa al momento de programar
- En cada lenguaje existe una azúcar sintáctica para facilitar el trabajo de los códigos, y cada sintaxis es distinta a las demás, aunque siguen la misma idea
### Ejemplos de esto son:
#### En Java
- `a += b`
- `a++` y `a--`
#### En Cobol
- `MOVE A TO B`
#### En Perls
- `unless (condition) {...}`
#### En Python
- `a [x * x for in range(10)]`

## Idiom en programación
- Se refiere a expresiones propias de una lengua que no se ajustan a las reglas gramaticales
- En programación son técnicas comunes específicas de un lenguaje de programación
- En lugar de tener que almacenar valores en muchas variables para poder cambiar valores, podemos simplemente hacer: `b, a = a, b`
- Con idioms se puede hacer: `for i, x in enumerate(l):`

## Wrappers
- También conocidas como clases envolventes
- Proveen una serie de mecanismos que nos permiten envolver a un tipo de dato primitivo permitiéndonos con ello el tratarlos como si fueran objetos
- Dichas clases se encuentran en el paquete `java.lang`
### Atributos de los Wrappers
- Son las características individuales que diferencian un objeto de otro y determinan su apariencia, estado u otras cualidades
- Los principales atributos de los Wrappers son estáticos, es decir, para utilizarlos se deberá nombrar a la clase
#### Ejemplos de estos atributos son:
##### SIZE
- Devuelve el tamaño del objeto en bites
##### MAX_VALUE
- Devuelve el máximo
##### MIN_VALUE
- Devuelve el mínimo
### Métodos de los Wrappers
- Un método en Java es una porción de código que realiza tareas asociadas a un objeto 
- A través de un método se les da a los objetos funcionalidades y características comunes a su clase
#### Ejemplos de estos son:
##### `compare(x, y)`
- Compara dos primitivos
##### `compareTo(wrapper)`
- Recibe una clase envolvente y la compara
##### `min(x, y)`
- Devuelve el mínimo entre dos primitivos
##### `max(x, y)`
- Devuelve el máximo entre dos primitivos
##### `parseXXXX(String)`
- Recibe un string, convierte cadenas en tipos de datos numéricos
##### `valueOf(String s)`
- Recibe un string, convierte cadenas en tipos de datos numéricos
##### `valueOf(primitive)`
- Recibe un primitivo
### Tipos de Wrappers en Java
#### Existen 8 tipos, de los cuales son (Tipo primitivo, Wrapper):
##### byte
- Byte
##### short
- Short
##### int
- Integer
##### long
- Long
##### boolean
- Boolean
##### float
- Float
##### double
- Double
##### char
- Character

## Migración de sistemas
- Consiste en trasladar datos o software de un sistema a otro
- La migración de la TI puede implicar uno o varios tipos de traslados
- Los proyectos de migración de la TI implican muchos factores y requisitos muy específicos para las necesidades de una empresa
### Algunos ejemplos comunes de migración de la TI son:
- Actualización de una aplicación o un sistema operativo (SO)
- Traslado de datos entre distintos tipos de bases de datos
- Sustitución de un sistema de almacenamiento de datos por otrO
- Traslado de una infraestructura on-premise a una infraestructura de nube
- Reemplazo de una aplicación monolítica por servicios en contenedores
### Migración de datos
- Consiste en trasladar los datos de un tipo de almacenamiento a otro
- Se hace como parte de una actualización para ampliar la capacidad de almacenamiento, mejorar el rendimiento, reducir los costos y el espacio físico
- Las migraciones de datos se desarrollan en tres etapas: planificación, ejecución y validación
- Las migraciones variarán en función de la cantidad de datos involucrados, la rapidez con la que haya que completarlas, los tipos de cargas de trabajo y los aspectos que deban considerarse en relación con la seguridad
#### Los datos se pueden trasladar de dos maneras:
##### Migración en linea
- Se transfieren a través de Internet o de una red privada
##### Migración sin conexión
- Se traslada físicamente un dispositivo de almacenamiento de un lugar a otro
### Migración de bases de datos
- Es un tipo específico de migración de datos
- Muchos proveedores de bases de datos en la nube ofrecen herramientas para automatizar este proceso
- Una migración de bases de datos requiere una planificación previa a la migración y una validación posterior a ella
### Migración de aplicaciones
- Consiste en trasladar las aplicaciones de software de un sistema de TI a otro
#### Estos suelen dividirse en cuatro categorías:
##### Realojamiento
- Consiste en trasladar una aplicación de una plataforma a otra sin realizar cambios significativos
##### Rediseño o reestructuración
- Implica hacer cambios significativos en una aplicación para poder ejecutarla en un nuevo entorno
##### Cambio de plataforma
- Consiste en la migración a un nuevo entorno que requiere algunos cambios en la aplicación
##### Retiro o sustitución
- Se reemplaza una aplicación por otro recurso mejor, como una solución de SaaS (software como servicio)
### Migración de los sistemas operativos
- Consiste en trasladar un sistema de TI gestionado por un sistema operativo a otro
- Esto puede implicar la actualización a una versión más reciente, como sucede cuando un producto deja de recibir soporte técnico oficialmente
- También puede significar pasar de un sistema operativo a otro, como en la migración de Windows a Linux
- Este tipo de migraciones puede exigir mucho tiempo y presentar riesgos, como un posible downtime, incompatibilidad entre las aplicaciones y pérdida de las configuraciones personalizadas
#### Los pasos a seguir para llevarlo a cabo son:
##### Preparación
- Antes de la migración, se realizan análisis para identificar posibles complicaciones con las cargas de trabajo, las configuraciones o las aplicaciones
- Se utiliza una serie de pautas sobre cómo solucionar los problemas de manera anticipada
- Muchos sistemas operativos, incluido Red Hat Enterprise Linux®, ofrecen herramientas y soporte para que la migración a un sistema operativo diferente se realice de la manera más sencilla posible
##### Automatización
- El uso de controles automatizados puede reducir el riesgo que implica un proyecto de migración
- Así como ayuda a que se mantengan las configuraciones, los ajustes personalizados y las preferencias actuales
##### Migración
- Siga el proceso que mejor se adapte a su entorno, ya sea una actualización integrada o una implementación totalmente nueva
### Migración a la nube
- Consiste en trasladar los sistemas de TI de los centros de datos on-premise tradicionales a los entornos de nube, o de un entorno de nube a otro diferente
- Las nubes públicas actuales forman parte de una mezcla heterogénea de entornos que genera más seguridad y mejor rendimiento
- La nube híbrida es una arquitectura de TI que incorpora cierto grado de gestión, organización y portabilidad de las cargas de trabajo en dos o más entornos
- Una migración a la nube no tiene por qué llevarse a cabo en un solo paso
- Muchas veces, implica un proceso piloto para probar los sistemas de forma limitada
#### Proceso de una migración a la nube:
##### Diseñe su plan de migración
- En esta etapa se realiza un análisis de su infraestructura y aplicaciones actuales
##### Ejecute una prueba piloto
- Si prueba un entorno listo para la producción durante varios meses, podrá asegurarse de que cumpla con sus requisitos
##### Lleve a cabo la migración
- Este paso consiste en trasladar las cargas de trabajo actuales al nuevo entorno, en función de un cronograma que satisfaga las necesidades de sus usuarios
### Migración de SAP
- Algunas migraciones de TI están impulsadas por la necesidad de adaptarse a los nuevos requisitos de los proveedores de software
- SAP®, el principal proveedor de software de ERP, exige que los clientes adopten SAP HANA® y SAP S/4HANA® antes de 2027, para que puedan seguir recibiendo soporte
- Para muchos clientes, esta actualización requiere que migren sus sistemas de SAP a nuevos entornos de TI
- La automatización se ha convertido en la clave para que este tipo de migración se realice de forma rápida, eficiente y confiable
### La migración y Red Hat Ansible Automation Plataform
- En una migración de TI, la automatización puede ayudar a que los proyectos sean más rápidos y fluidos, y así reducir los errores que pueden resultar de los procesos manuales y repetitivos
- Red Hat Ansible Automation Platform guía en el proceso de automatización de sus migraciones
- Una vez que defina cada uno de los elementos y pasos del proceso de migración, podrá asociarlos en un playbook de Ansible repetible, y empezar a aplicarlo al nuevo entorno
- Como resultado, se obtiene un proceso mucho más fluido mediante el cual puede tomar las piezas de su sistema y trasladarlas a donde quiera
#### Para lograrlo, es necesario llevar a cabo los siguentes pasos:
##### Definición
- Determine todos los elementos que se van a automatizar por separado, teniendo en cuenta el orden y el proceso
##### Implementación
- Utilice las definiciones y las automatizaciones de los elementos para realizar una implementación y probarla
##### Descubrimiento
- Cada vez que aplique sus automatizaciones, pruebe la aplicación o el software tal como se ha implementado y descubra qué inconvenientes hay
