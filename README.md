# Uso de ML5 y Teachable Machine para Machine Learning

Se trata de un proyecto que utiliza la librería ml5.js, p5.js y Teachable Machine para crear modelos de aprendizaje automático que pueden reconocer gestos y objetos a través de la cámara web.

## Requisitos

- Visual Studio Code.
- Extensión Live Server.
- Navegador Google Chrome.
- Cámara web.
- Conexión a Internet para cargar las librerías CDN.

## Tecnologías

- HTML5
- CSS3
- JavaScript
- p5.js
- ml5.js
- Teachable Machine

## Instalación
1. Clona este repositorio en tu máquina local.
```bash
    git clone https://github.com/mewi08/ml5.git
```
2. Abrir un archivo html con Open with Live Server en Visual Studio Code.

3. Abre la terminal para saber tu ip local

```bash
    ipconfig
```
4. Copia este comando en el navegador Chrome

```text
    chrome://flags/#unsafely-treat-insecure-origin-as-secure
```

5. Habilita la opción y agrega tu ip local con el puerto 5500, por ejemplo:

```text
    http://192.168.1.7:5500
```
6. Reinicia Chrome para aplicar los cambios.

## Advertencias

- Es necesario habilitar el acceso a la cámara para utilizar los modelos.
- La configuración `unsafely-treat-insecure-origin-as-secure` permite utilizar funciones que requieren un contexto seguro en una dirección HTTP local.
- Esta configuración reduce las protecciones de seguridad del navegador. Se recomienda utilizarla únicamente durante el desarrollo y deshabilitarla cuando ya no sea necesaria.