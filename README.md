# Aplicación de Encuesta con Envío a Hoja de Cálculo de Google

Este proyecto es un ejemplo práctico que demuestra cómo crear una sencilla aplicación web HTML para recoger datos de un formulario y enviarlos directamente a una Hoja de Cálculo de Google mediante Google Apps Script. Ha sido desarrollado como material de apoyo para el artículo: "Cómo hacer que una aplicación escriba en una hoja de cálculo de Google".

## Descripción General

La aplicación consta de dos partes principales:

1.  **Frontend (HTML):** Una página web con un formulario donde el usuario introduce su nombre y una valoración numérica (de 0 a 4) a la pregunta "¿Te ha sido útil esta información?".
2.  **Backend (Google Apps Script):** Un script alojado en Google Sheets que actúa como una API web. Recibe los datos enviados desde el formulario HTML y los añade como una nueva fila en una hoja de cálculo específica.

## Funcionalidades

* Formulario HTML simple con dos campos: nombre (texto) y valoración (botones de radio).
* Validación básica en el lado del cliente para asegurar que los campos se rellenan.
* Envío de datos de forma asíncrona usando la API `fetch` de JavaScript.
* Feedback visual al usuario sobre el estado del envío (enviando, éxito, error).
* Registro de cada envío con marca de tiempo, nombre y valoración en una Hoja de Cálculo de Google.

## Requisitos Previos

* Una cuenta de Google.
* Conocimientos básicos de HTML.
* Conocimientos básicos de Google Sheets y Google Apps Script.


