# Amigo Secreto

## Descripción

Este proyecto es una aplicación web sencilla que permite a los usuarios ingresar nombres de amigos, visualizar una lista y realizar un sorteo aleatorio para determinar quién es el "amigo secreto". La aplicación se desarrolló utilizando HTML, CSS y JavaScript, aprovechando funcionalidades nativas del navegador.

## Funcionalidades

- **Agregar Nombres:** Permite ingresar nombres a través de un campo de texto y agregarlos a una lista.
- **Validación de Entrada:** Verifica que el campo de texto no esté vacío y muestra una alerta si no se ingresa ningún nombre.
- **Visualización de la Lista:** Muestra en la interfaz los nombres ingresados de manera dinámica.
- **Sorteo Aleatorio:** Selecciona aleatoriamente uno de los nombres de la lista para designarlo como "amigo secreto".

## Estructura del Proyecto

- **index.html:** Archivo principal que contiene la estructura y el contenido de la página.
- **style.css:** Archivo de estilos para la presentación visual (puede ser personalizado según las necesidades).
- **app.js:** Archivo JavaScript que maneja la lógica de agregar nombres, actualizar la lista y realizar el sorteo.

## Instalación y Uso

1. **Clonar o Descargar el Repositorio:**

   ```bash
   git clone https://turepositorio_url.git
   ```
2. **Uso**

- **Agregar Nombres**:
    Escribe el nombre de un amigo en el campo de texto.
    Haz clic en el botón “Añadir” para agregar el nombre a la lista.
- **Visualizar la Lista**:
    Los nombres ingresados se mostrarán automáticamente en la lista ubicada debajo del campo de entrada.
- **Realizar el Sorteo**:
    Haz clic en el botón “Sortear Amigo” para ejecutar el sorteo.
     La aplicación seleccionará un nombre al azar y mostrará el resultado en pantalla.

3. **Problemas Comunes y Soluciones**

- **Campo de Entrada Vacío**:
    Problema: Se intenta agregar un nombre sin haber ingresado ningún texto.
    Solución: La aplicación mostrará una alerta solicitando ingresar un nombre válido.
- **Lista Vacía al Sortear**:
    Problema: Se intenta realizar un sorteo sin haber agregado ningún nombre.
    Solución: Se mostrará una alerta indicando que no hay amigos disponibles para sortear.
