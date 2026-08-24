# Función lineal — práctica interactiva

Aplicación web interactiva para practicar **función lineal** con estudiantes de **8.º básico / Sekundarstufe I**, orientada al currículo alemán.

La actividad genera automáticamente una prueba de **12 preguntas** que cubre distintos aspectos del tema, incluyendo interpretación algebraica, gráficos, tablas, construcción de funciones y problemas de modelación.

## Contenidos

La aplicación trabaja con la forma:

\[
y = mx + n
\]

donde:

- **m** es la pendiente.
- **n** es el **coeficiente de posición**.

Cada prueba contiene siempre las mismas 12 categorías de ejercicios, pero los datos se generan nuevamente al crear una prueba nueva.

1. Identificar pendiente, coeficiente de posición y crecimiento/decrecimiento.
2. Evaluar una función y completar una tabla de valores.
3. Obtener la ecuación a partir de un gráfico.
4. Identificar el gráfico correspondiente a una ecuación.
5. Encontrar la función a partir de dos puntos.
6. Determinar si una tabla representa una función lineal.
7. Resolver ceros y preimágenes.
8. Reconocer proporcionalidad directa.
9. Construir una recta a partir de pendiente, punto o paralelismo.
10. Problema de modelación directa.
11. Problema inverso.
12. Comparación de dos modelos lineales.

Las preguntas 10, 11 y 12 son siempre **problemas matemáticos contextualizados**.

## Banco de ejercicios

Cada categoría posee su propio generador, por lo que la estructura de la prueba se mantiene mientras cambian:

- pendientes;
- coeficientes de posición;
- puntos;
- tablas;
- gráficos;
- valores objetivo;
- alternativas;
- contextos de modelación.

El banco de problemas incluye situaciones como:

- taxis;
- depósitos de agua;
- velas;
- temperatura;
- arriendo de bicicletas;
- estacionamientos;
- ahorro;
- llenado de recipientes;
- descensos;
- baterías;
- envíos;
- recargas;
- telefonía;
- gimnasios;
- impresión;
- arriendo de herramientas;
- entre otros.

## Funcionalidades

- Generación automática de una nueva prueba.
- 12 preguntas por prueba.
- Gráficos generados directamente en el navegador.
- Corrección individual de cada pregunta.
- Corrección completa de la prueba.
- Puntaje sobre 12.
- Retroalimentación inmediata.
- Soporte para decimales con punto o coma.
- Soporte para fracciones como `3/2`.
- Diseño adaptable a computador, Chromebook, tablet y teléfono.
- Opción de impresión.
- Modo docente con visualización del banco de ejercicios.
- Sin dependencias externas.

## Compatibilidad

El proyecto utiliza solamente:

- HTML;
- CSS;
- JavaScript;
- `<canvas>` para los gráficos.

No utiliza frameworks, librerías externas, CDNs ni servicios de terceros.

Esto permite que la página funcione como un sitio estático y reduce problemas en dispositivos institucionales o redes escolares con restricciones.

## Ejecutar localmente

No se necesita instalar nada.

Descarga el repositorio y abre:

```text
index.html
```

en un navegador moderno.

También puede utilizarse mediante un servidor local, aunque no es necesario.

## Publicar con GitHub Pages

1. Sube `index.html` a la raíz del repositorio.
2. En GitHub, abre **Settings → Pages**.
3. En **Build and deployment**, selecciona publicación desde una rama.
4. Selecciona:

```text
Branch: main
Folder: / (root)
```

5. Guarda los cambios.
6. GitHub entregará una dirección similar a:

```text
https://usuario.github.io/nombre-del-repositorio/
```

Los estudiantes pueden abrir directamente esa URL desde Chrome.

## Estructura del repositorio

```text
.
├── index.html
└── README.md
```

Todo el funcionamiento de la aplicación está contenido en `index.html`.

## Modo docente

La aplicación contiene un panel docente oculto desde el cual se pueden inspeccionar:

- las 12 familias de ejercicios;
- los contextos disponibles para los problemas;
- ejemplos generados por el banco.

Este mecanismo está pensado como una comodidad de interfaz y **no como un sistema de seguridad**. Al tratarse de una aplicación completamente estática, cualquier información incluida en el código fuente puede ser inspeccionada por un usuario con conocimientos técnicos.

## Uso educativo

La aplicación está pensada principalmente para:

- preparación de pruebas;
- práctica individual;
- repaso en clases particulares;
- trabajo autónomo;
- ejercicios rápidos durante una clase;
- generación de versiones distintas de una misma evaluación formativa.

La generación aleatoria permite repetir la actividad varias veces sin recibir exactamente los mismos ejercicios.

## Licencia

Uso educativo libre. Puedes modificar y adaptar el código para tus propias clases.
