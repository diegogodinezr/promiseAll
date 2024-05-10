# Resumen sobre el articulo de "How to fetch data in React with performance in mind"

## Obteniendo datos en React: Una inmersión más profunda

El artículo de Developerway sobre cómo obtener datos en React con fetch profundiza en los aspectos esenciales de la gestión de datos asíncronos en aplicaciones React.

##### Fetch: La base de la obtención de datos

__*fetch*__ es la herramienta principal para realizar solicitudes HTTP y obtener datos de APIs en aplicaciones web modernas, incluyendo React. Su funcionamiento se basa en promesas, que representan el resultado eventual de una operación asíncrona.

##### Promesas: Manejando la asincronía
Las promesas tienen tres estados posibles:
* **Pendiente:** La operación aún está en curso.
* **Cumplida:** La operación se completó con éxito y se obtuvo un valor.
* **Rechazada:** La operación falló y se produjo un error.

Para manejar el resultado de una promesa, se utilizan los métodos then (para el éxito) y catch (para el error).

##### Async/await: Simplificando las promesas
__*async/await*__ es una sintaxis que facilita el trabajo con promesas, haciendo que el código asíncrono sea más legible y parecido al código síncrono.
* async: Declara una función asíncrona que devuelve una promesa.
* await: Espera la resolución de una promesa y devuelve su valor.

##### Estados de carga: Manteniendo al usuario informado
Mientras se obtienen datos de una API, es importante manejar los diferentes estados de carga para ofrecer una buena experiencia al usuario:

* loading: Se muestra un indicador de carga mientras se espera la respuesta de la API.
* success: Los datos se obtuvieron con éxito y se muestran en la interfaz.
* error: Se produjo un error al obtener los datos y se muestra un mensaje de error.

##### Ejemplo práctico: De la teoría a la acción

El artículo presenta un ejemplo práctico que ilustra cómo obtener datos de una API, manejar los estados de carga y mostrar los resultados en un componente React:

1. Realizar la solicitud: Se utiliza fetch para obtener datos de la API.
2. Manejar la respuesta: Se utiliza async/await para esperar la respuesta y convertirla a JSON.
3. Actualizar el estado: Se actualiza el estado del componente con los datos obtenidos y se establece el estado de carga correspondiente.
4. Renderizar los datos: Se renderizan los datos en la interfaz de usuario.
Conclusión: Dominando la gestión de datos

La gestión de datos asíncronos es fundamental para construir aplicaciones React interactivas y dinámicas. fetch, promesas y async/await son herramientas esenciales para este propósito, y el manejo de los estados de carga es crucial para una buena experiencia de usuario.