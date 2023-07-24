# 2. Prueba Técnica - Programador (Back-end)
La siguiente es una prueba para evaluar a los postulantes a programador **Back-end**.

## INTRODUCCIÓN
Este repositorio contiene una serie de requerimientos de un Caso Práctico, que busca evaluar las capacidades técnicas del candidato con respecto a las principales funciones y responsabilidades que se requieren dentro del área de Desarrollo de Back-end de _LimboTeams_.

#### ¿Qué se busca evaluar?
Principalmente los siguientes aspectos:
* Creatividad para resolver los requerimientos,
* Calidad de commits y detalles dentro de los PR,
* Calidad del código entregado (estructura y buenas prácticas),
* Implementacion del

## IMPORTANTE
1. Recomendamos emplear un máximo de **2 (dos) hora** y enviar todo lo que puedas.
2. Se requiere de una **cuenta de GitHub** para realizar este ejercicio.
3. Para realizar esta prueba técnica es recomendable contar con algun IDE de preferencia personal y Git instalado.
4. **Antes de comenzar a programar:**
    * Realizar un `Fork` de este repositorio (link-del-repo).
    * Clonar el fork a su máquina local  `git clone git@github.com:USERNAME/FORKED-PROJECT.git`
    * Crear un `branch` en su cuenta de GitHub utilizando su nombre completo.
5. **Al finalizar**, existen 2 (dos) opciones para entregar su proyecto:
    * 1) Realizar un `Commit` de su proyecto, **enviar un `Pull Request` al branch con su NOMBRE**, y notificar a la siguiente dirección de correo electrónico  [interviewer@limboteams.com](interviewer@limboteams.com).
    * 2) Crear un archivo comprimido (_.zip_ o _.rar_) de su proyecto y enviar a la siguiente dirección de correo electrónico  [interviewer@limboteams.com](interviewer@limboteams.com).

## EJERCICIO

Tu objetivo es crear un sistema básico para una librería utilizando el framework NestJS. El sistema deberá permitir la gestión de libros y clientes. Deberás implementar las siguientes funcionalidades:

Gestión de libros:

1. Crear un nuevo libro con los campos: título, autor, género y año de publicación.
2. Obtener la lista completa de libros registrados.
3. Obtener un libro específico por su ID.
4. Actualizar los datos de un libro existente.
5. Eliminar un libro por su ID.

Gestión de clientes:

1. Crear un nuevo cliente con los campos: nombre, correo electrónico y número de teléfono.
2. Obtener la lista completa de clientes registrados.
3. Obtener un cliente específico por su ID.
4. Actualizar los datos de un cliente existente.
5. Eliminar un cliente por su ID.

## REQUISITOS
1. Utiliza NestJS para desarrollar el sistema, aprovechando su estructura modular y decoradores para definir rutas y controladores.
2. Conecta el sistema a una base de datos de MongoDB para almacenar los datos de libros y clientes.
3. Implementa la validación de los datos de entrada para asegurar que los campos requeridos no estén vacíos y que cumplan con ciertas restricciones (p. ej. longitud del nombre, formato del correo electrónico, etc.).
4. Asegúrate de manejar adecuadamente los errores ya sea utilizando los filtros de NestJs o usando try y catch dentro de los controladores para proporcionar respuestas con códigos de estado HTTP apropiados en caso de éxito o fallo en las operaciones.
5. (Opcional) Documenta la API con Swagger.

¡Buena suerte en el desarrollo del algoritmo!