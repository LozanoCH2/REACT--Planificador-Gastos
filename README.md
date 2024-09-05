# Proyecto Planificador de Gastos - useReducer y Context API

Este proyecto es un planificador de gastos que permite a los usuarios gestionar su presupuesto y registrar los gastos que han tenido o que planean tener. La aplicación está desarrollada con **React**, **TypeScript** y **Tailwind CSS**, utilizando el hook `useReducer` para la gestión eficiente del estado y **Context API** para englobar y manejar el reducer de manera global.

Puedes ver la aplicación en acción [aquí](https://react-planificador-gastos.netlify.app).

## Tabla de Contenidos

- [Descripción del Proyecto](#descripción-del-proyecto)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Instalación](#instalación)
- [Funcionalidades](#funcionalidades)
- [Aprendizaje Clave: useReducer y Context API](#aprendizaje-clave-usereducer-y-context-api)
- [Créditos](#créditos)
- [Conclusión](#conclusión)

## Descripción del Proyecto

La aplicación de **Planificador de Gastos** permite a los usuarios ingresar un presupuesto inicial y luego agregar gastos a ese presupuesto mediante un modal que despliega un formulario para ingresar los detalles del gasto. A medida que los gastos se van agregando, la aplicación muestra:

- El **presupuesto inicial**.
- El **dinero disponible**.
- El **dinero gastado**.

Además, se incluye una gráfica circular que representa el porcentaje de dinero gastado respecto al presupuesto total, permitiendo una visión clara de los gastos. También se pueden **filtrar los gastos por categoría** y **resetear la aplicación** para comenzar de nuevo.

## Tecnologías Utilizadas

- **React**: Biblioteca de JavaScript para construir interfaces de usuario.
- **TypeScript**: Lenguaje que añade tipado estático a JavaScript.
- **Tailwind CSS**: Framework CSS para diseñar interfaces rápidamente.
- **useReducer**: Hook de React utilizado para manejar el estado de manera eficiente.
- **Context API**: API de React utilizada para manejar el estado de la aplicación de forma global.
- **Datepicker, Swipeable, Progressbar, Calendar, Heroicons**: Librerías adicionales utilizadas para mejorar la funcionalidad y la interfaz del proyecto.

## Instalación

Para ejecutar este proyecto localmente, sigue estos pasos:

1. Clona el repositorio:
    ```bash
    git clone https://github.com/tuusuario/planificador-gastos.git
    ```
2. Navega al directorio del proyecto:
    ```bash
    cd planificador-gastos
    ```
3. Instala las dependencias:
    ```bash
    npm install
    ```
4. Inicia el servidor de desarrollo:
    ```bash
    npm run dev
    ```

## Funcionalidades

- **Ingreso de Presupuesto**: El usuario puede definir un presupuesto inicial.
- **Agregar Gastos**: Los gastos se pueden agregar a través de un modal que permite ingresar el detalle del gasto.
- **Visualización de Gastos**: La aplicación muestra el presupuesto, el disponible y lo gastado en tiempo real.
- **Gráfica Circular**: Representación visual del porcentaje de dinero gastado.
- **Filtrado por Categorías**: Los gastos pueden filtrarse por tipo o categoría.
- **Resetear Aplicación**: Posibilidad de reiniciar todos los datos de la aplicación.

## Aprendizaje Clave: useReducer y Context API

El uso de `useReducer` en este proyecto permitió una mejor estructuración y manejo del estado, especialmente para acciones como agregar y eliminar gastos, calcular el presupuesto restante, y actualizar los datos de la gráfica circular. Las ventajas de `useReducer` incluyen:

- **Gestión del Estado Compleja**: Permite manejar múltiples acciones en un solo lugar, facilitando la escalabilidad del código.
- **Manejo Predecible de Acciones**: Con `useReducer`, es más fácil estructurar y prever cómo se manejarán las acciones (como agregar, eliminar o resetear).

Adicionalmente, **Context API** se utilizó para compartir el estado y las acciones del reducer de manera global en toda la aplicación, evitando el paso de props innecesarios y simplificando la estructura de los componentes.

## Créditos

Este proyecto fue desarrollado como parte del curso de React y TypeScript de [codigoconjuan](https://codigoconjuan.com). Agradezco los conocimientos adquiridos a lo largo del curso que me permitieron implementar y optimizar esta aplicación.

## Conclusión

Este proyecto fue una gran oportunidad para seguir profundizando en el uso de `useReducer` y `Context API`, dos herramientas clave para mejorar la organización y eficiencia en las aplicaciones de React. Además, la integración de varias librerías de React permitió una experiencia de usuario más rica y funcional.
