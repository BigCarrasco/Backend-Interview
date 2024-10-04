# Backend-Interview
Pretendo desarrollar una buena guia solida en Español e Ingles para formar LOS FUNDAMENTOS de una Ingenieria Backend especialmente formada en Tecnologias de Microsoft como C#.

<div align="center">
  <img height="60" src="https://edgewrapper.com/wp-content/uploads/2023/05/unnamed-4.png">
  <h1>Backend Interview</h1>
</div>

> [!NOTE]  
> Este repositorio se creó en 2024 y, por lo tanto, las preguntas proporcionadas aquí se basan en la sintaxis y el comportamiento en ese momento.Estare haciendo traducciones al Ingles, por lo que tu eres libre de añadir a tu idioma o sugerencias! Hagamos una buena comunidad 🤓. Yo sugiriría que con los temas que has visto aqui, puedas prepararte indivdualmente con tus preguntas, pero es un buen inicio para que sepas por donde empezar.
---


| Sientete libre de usar el proyecto! 😃 _Apreciaría_ de corazón  mucho que este proyecto te sirva, estare haciendolo más robusto para que tengas una buena guía.
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |

###### **1. Qué es un API?**

- A: Un API es una aplicación que muestra imágenes.
- B: Un API es un servidor de videojuegos.
- C: Un API es una forma de que dos sistemas se comuniquen.
- D: Un API es un lenguaje de programación.

<details><summary><b>Respuesta</b></summary>
<p>

#### Respuesta: C

Una API es una forma de que dos sistemas se comuniquen entre sí. Permite que las aplicaciones pidan o envíen datos a través de internet.

</p>
</details>

---
###### **2. ¿Cuáles son los protocolos más comunes que usa una API?**


- A: FTP y SMTP.
- B: HTTP/HTTPS y SOAP.
- C: SSH y TCP/IP.
- D: WebSocket y POP3.

<details><summary><b>Respuesta</b></summary>
<p>

#### Respuesta: B

Los protocolos más comunes que utilizan las APIs son HTTP/HTTPS y SOAP. HTTP/HTTPS es el estándar en la web, mientras que SOAP es un protocolo más antiguo utilizado en aplicaciones empresariales mediante comunicación XML.

</p>
</details>

---
###### **3. ¿Qué tienen en común SOAP, REST y HTTP? ¿Son APIs?**


- A: SOAP, REST y HTTP son diferentes tipos de bases de datos.
- B: SOAP, REST y HTTP son diferentes lenguajes de programación.
- C: SOAP y REST son estilos para construir APIs, y HTTP es un protocolo que las APIs utilizan.
- D: SOAP, REST y HTTP son tipos de servidores web.

<details><summary><b>Respuesta</b></summary>
<p>

#### Respuesta: C

SOAP y REST son estilos de arquitectura para construir APIs, y HTTP es un protocolo que se usa para la comunicación en estas APIs. SOAP puede usar varios protocolos, pero comúnmente utiliza HTTP. REST está basado en HTTP y se usa ampliamente para diseñar APIs web.

</p>
</details>

---
###### **4. ¿Qué es REST**


- A: Un lenguaje de programación.
- B: Un protocolo de seguridad.
- C: Un estilo de arquitectura para construir APIs.
- D: Un tipo de base de datos.

<details><summary><b>Respuesta</b></summary>
<p>

#### Respuesta: C

REST es un estilo de arquitectura para construir APIs. Utiliza métodos HTTP como `GET`, `POST`, `PUT`, y `DELETE` para acceder y manipular recursos en un servidor. Cada recurso tiene una URL especifica.


</p>
</details>

---
###### **5.¿REST y RESTful son lo mismo?**


- A: REST y RESTful son exactamente lo mismo.
- B: REST es la arquitectura, y RESTful describe APIs que siguen esa arquitectura.
- C: REST es un lenguaje de programación, y RESTful es una base de dato.
- D: RESTful es un tipo de protocolo diferente a REST.

<details><summary><b>Respuesta</b></summary>
<p>

#### Respuesta: B

REST es el estilo de arquitectura, y cuando una API sigue los principios de REST, se le llama API RESTful.


</p>
</details>

---
###### **6.¿Cuáles son los métodos HTTP compatibles con REST?(Más usados)**


- A: GET, POST, PUT, DELETE.
- B: GET, POST, MANTAIN, ERASE.
- C: GET, UPDATE, POST, TRUNCATE.
- D: GET, DELETE, PARSE, CONVERT.

<details><summary><b>Respuesta</b></summary>
<p>

#### Respuesta: A

GET: Solo recibe recursos.
POST: Envio de datos para actualizar un recurso.
UPDATE: Envía datos a la API para crear y actualizar los recursos
DELETE: Elimina los recursos del recurso especificado.


</p>
</details>

---
###### **7. ¿Qué es la autentificaciòn?**

- A: El proceso de verificar la identidad de un usuario o sistema.
- B: El proceso de proteger los datos de una base de datos.
- C: Un método para guardar contraseñas en una API.
- D: Un servicio de red que envía datos.

<details><summary><b>Respuesta</b></summary>
<p>

#### Respuesta: A

La autenticación es el proceso de verificar la identidad de un usuario o sistema para asegurarse de que tiene acceso permitido a un recurso o servicio.

</p>
</details>

---
###### **8. ¿Cuántos tipos de autenticación existen?**

- A: 1.
- B: 3.
- C: 12.
- D: No hay un número fijo, existen varios tipos de autenticación.

<details><summary><b>Respuesta</b></summary>
<p>

#### Respuesta: D

Existen varios tipos de autenticación, dependiendo de cómo se verifique la identidad de un usuario o sistema. Los más comunes son:

1. **Autenticación de un solo factor (SFA)**: Requiere solo un método, como una contraseña.
2. **Autenticación de dos factores (2FA)**: Combina dos métodos, como contraseña y un código enviado al teléfono.
3. **Autenticación multifactor (MFA)**: Usa más de dos métodos, como contraseña, código y huella dactilar.
4. **Autenticación basada en tokens**: Usa tokens temporales (como JWT) para identificar a los usuarios.
5. **Autenticación biométrica**: Usa características físicas como huellas dactilares o reconocimiento facial.

</p>
</details>

---
###### **9. ¿Qué es un patrón de diseño en software?**

- A: Un lenguaje de programación.
- B: Un conjunto de reglas para crear software.
- C: Una solución reusable para resolver problemas comunes en desarrollo de software.
- D: Un tipo de base de datos.

<details><summary><b>Respuesta</b></summary>
<p>

#### Respuesta: C

Un **patrón de diseño** es una solución probada y reutilizable para resolver problemas comunes en el desarrollo de software. Son guías que los desarrolladores pueden seguir para estructurar el código de manera eficiente, facilitando el mantenimiento, escalabilidad y legibilidad.


</p>
</details>

---
###### **10. ¿En qué se asemejan y cuál es la diferencia entre un algoritmo y un patrón de diseño?**

- A: Ambos son pasos para resolver un problema específico.
- B: Un algoritmo resuelve un problema específico, mientras que un patrón de diseño es una estructura para organizar el código.
- C: Un patrón de diseño es un algoritmo de ordenamiento.
- D: No tienen nada en común.

<details><summary><b>Respuesta</b></summary>
<p>

#### Respuesta: B

Un **algoritmo** resuelve un problema específico, mientras que un **patrón de diseño** es una estrategia general para organizar el código.


</p>
</details>

---
###### **11. ¿Cuántos patrones de diseño existen?**

- A: Existen 5 patrones de diseño.
- B: Existen 15 patrones de diseño.
- C: Existen 23 patrones de diseño.
- D: Existen infinitos patrones de diseño.

<details><summary><b>Respuesta</b></summary>
<p>

#### Respuesta: C

Existen 23 **patrones de diseño** clásicos, divididos en tres categorías: **creacionales, estructurales y de comportamiento**.


</p>
</details>

---
###### **12. ¿Cuántos tipos de algoritmos existen?**

- A: Solo existen algoritmos de búsqueda y ordenamiento.
- B: Existen más de 5 tipos de algoritmos.
- C: Todos los algoritmos son recursivos.
- D: Los algoritmos de grafos son los más comunes en programación.

<details><summary><b>Respuesta</b></summary>
<p>

#### Respuesta: B

Existen más de **5 tipos de algoritmos**, que incluyen entre los más populares **búsqueda, ordenamiento, recursivos, grafos, entre otros**, como:
- Fuerza Bruta.
- Greedy.
- Algoritmos de Programación dinamica.
- Algoritmos Probabilisticos.
- Algoritmos de Inteligencia artificial.


</p>
</details>

---
###### **13. ¿En qué se enfocan los patrones creacionales (son 5) ?**

- A: Se enfocan en cómo los objetos interactúan entre sí.
- B: Se enfocan en cómo se crean y gestionan los objetos.
- C: Son usados para destruir objetos en memoria.
- D: Ayudan a conectar diferentes clases sin instanciarlas.

<details><summary><b>Respuesta</b></summary>
<p>

#### Respuesta: B

Los patrones creacionales se enfocan en cómo se crean y gestionan los objetos, facilitando un proceso de creación flexible y eficiente.

1. **Singleton**: Asegura que una clase tenga solo una instancia y proporciona un punto de acceso global a esa instancia.
2. **Factory Method**: Proporciona una interfaz para crear objetos, pero permite a las subclases decidir qué clase instanciar.
3. **Abstract Factory**: Crea familias de objetos relacionados sin especificar sus clases concretas.
4. **Builder**: Separa la construcción de un objeto complejo de su representación para poder crear diferentes representaciones.
5. **Prototype**: Permite crear nuevos objetos copiando una instancia existente (prototipo).

</p>
</details>

---
###### **14. ¿En qué se enfocan los patrones estructurales (son 7) ?**

- A: Se enfocan en la creación de objetos.
- B: Se enfocan en cómo los objetos y clases se organizan y se relacionan entre sí.
- C: Se enfocan en la destrucción de objetos.
- D: Se enfocan en la validación de datos.

<details><summary><b>Respuesta</b></summary>
<p>

#### Respuesta: B

Los patrones estructurales se enfocan en cómo los objetos y clases se organizan y se relacionan entre sí para formar estructuras más complejas, facilitando la composición de estructuras flexibles y reutilizables.

### Ejemplos de patrones estructurales:
1. **Adapter**: Permite que dos interfaces incompatibles trabajen juntas. Convierte la interfaz de una clase en otra que el cliente espera.
2. **Bridge**: Desacopla una abstracción de su implementación para que ambas puedan evolucionar de manera independiente.
3. **Composite**: Permite tratar objetos individuales y compuestos de manera uniforme. Es útil para representar jerarquías de objetos.
4. **Decorator**: Añade funcionalidad adicional a un objeto de manera dinámica sin modificar su estructura original.
5. **Facade**: Proporciona una interfaz simplificada para un sistema complejo de clases, ocultando su complejidad.
6. **Flyweight**: Minimiza el uso de memoria al compartir el estado común de los objetos en lugar de duplicarlos.
7. **Proxy**: Proporciona un sustituto o intermediario para controlar el acceso a otro objeto.


</p>
</details>

---
###### **15. ¿En qué se enfocan los patrones de comportamiento (son 11)?**

- A: Se enfocan en la creación de objetos.
- B: Se enfocan en la organización de objetos y clases.
- C: Se enfocan en la interacción y comunicación entre objetos.
- D: Se enfocan en destruir objetos al finalizar el programa.

<details><summary><b>Respuesta</b></summary>
<p>

#### Respuesta: C

Los patrones de comportamiento se enfocan en la interacción y comunicación entre objetos, distribuyendo las responsabilidades de manera flexible y eficiente.

### Ejemplos de patrones de comportamiento:
1. **Chain of Responsibility**: Permite que varios objetos tengan la oportunidad de manejar una solicitud, evitando el acoplamiento entre el emisor y el receptor.
2. **Command**: Encapsula una solicitud como un objeto, permitiendo parametrizar a los clientes con diferentes solicitudes, colas o registros.
3. **Interpreter**: Define una gramática para un lenguaje y usa esta representación para interpretar sentencias.
4. **Iterator**: Proporciona una manera de acceder secuencialmente a los elementos de una colección sin exponer su estructura interna.
5. **Mediator**: Define un objeto que controla la comunicación entre objetos, reduciendo la interdependencia entre ellos.
6. **Memento**: Permite capturar y restaurar el estado interno de un objeto sin violar su encapsulamiento.
7. **Observer**: Define una dependencia uno-a-muchos entre objetos, de modo que cuando uno cambia su estado, todos sus dependientes son notificados automáticamente.
8. **State**: Permite a un objeto cambiar su comportamiento cuando cambia su estado interno.
9. **Strategy**: Define una familia de algoritmos, encapsula cada uno y los hace intercambiables, permitiendo cambiar el algoritmo independientemente del cliente que lo usa.
10. **Template Method**: Define el esqueleto de un algoritmo en una clase base, permitiendo que las subclases redefinan ciertos pasos sin cambiar la estructura del algoritmo.
11. **Visitor**: Permite definir nuevas operaciones sobre una estructura de objetos sin cambiar las clases de los elementos sobre los que opera.


</p>
</details>


---
###### **16. ¿Qué es un ORM ?**

- A: Un ORM es un tipo de base de datos.
- B: Un ORM es una técnica que permite mapear objetos a bases de datos relacionales.
- C: Un ORM es un motor de búsqueda para bases de datos.
- D: Un ORM es una herramienta para diseñar interfaces gráficas.

<details><summary><b>Respuesta</b></summary>
<p>

#### Respuesta: B

Un **ORM** es una técnica que permite mapear objetos a bases de datos relacionales, facilitando la interacción entre el código orientado a objetos y las bases de datos.

</p>
</details>

---

###### **17. ¿Qué es una migración ?**

- A: Una migración es cuando una base de datos se traslada de un servidor a otro.
- B: Una migración es un archivo de respaldo de la base de datos.
- C: Una migración es la actualización de datos en una tabla.
- D: Una migración es el proceso de cambiar la estructura de la base de datos de manera organizada y segura.

<details><summary><b>Respuesta</b></summary>
<p>

#### Respuesta: D

Una **migración** es el proceso de cambiar la estructura de la base de datos de manera organizada y segura, como agregar nuevas tablas o modificar columnas existentes.

Las migraciones permiten modificar o actualizar la base de datos de forma incremental sin perder datos existentes, y aseguran que la estructura de la base de datos esté sincronizada con la versión del código de la aplicación

</p>
</details>

---

---

###### **17. ¿Qué es GIT?**

- A: Git es una herramienta para gestionar bases de datos.
- B: Git es un lenguaje de programación para servidores.
- C: Git es un sistema de control de versiones utilizado para rastrear cambios en proyectos.
- D: Git es una herramienta de diseño gráfico.

<details><summary><b>Respuesta</b></summary>
<p>

#### Respuesta: C

Git es un **sistema de control de versiones** utilizado para rastrear cambios en proyectos de software, permitiendo la colaboración y el manejo eficiente del código.

</p>
</details>
