# Valor de Referencia de 1 UDI

Este proyecto muestra el valor de referencia de 1 UDI (Unidad de Inversión) al día de hoy en una página web estática, hosteada en GitHub Pages. La página se actualiza diariamente utilizando GitHub Actions para obtener los datos de la API de Banxico y actualizar el contenido de la página.

## Configuración

### 1. Crear el Repositorio en GitHub

1. Ve a tu cuenta de GitHub y crea un nuevo repositorio. Dale un nombre relevante, por ejemplo, `valor-udi`.
2. Inicializa el repositorio con un archivo `README.md`.

### 2. Crear los Archivos HTML y CSS

En tu máquina local, crea una carpeta para tu proyecto y dentro de ella crea dos archivos: `index.html` y `styles.css`.

#### index.html

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Valor de 1 UDI Hoy</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Valor de Referencia de 1 UDI al día de {fecha}</h1>
        <p id="udi-value">Cargando...</p>
    </div>
</body>
</html>
