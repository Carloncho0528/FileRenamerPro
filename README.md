# FileRenamerPro

**FileRenamerPro** es una aplicación de escritorio sencilla y potente para renombrar archivos en masa en una carpeta. Permite personalizar los nombres de los archivos añadiendo prefijos, numeración secuencial y/o fechas. Desarrollada en Python con una interfaz gráfica intuitiva usando `tkinter`.

## Características
- Selección de carpeta con un explorador de archivos.
- Opciones para agregar:
  - Prefijo personalizado.
  - Numeración secuencial (ej., 001, 002, ...).
  - Fecha actual en formato AAAAMMDD.
- Interfaz gráfica amigable.
- Manejo de errores con notificaciones claras.
- Compatible con cualquier tipo de archivo.

## Requisitos
- Python 3.6 o superior.
- Módulos de Python: `os`, `datetime`, `tkinter` (incluidos en la biblioteca estándar).

## Instalación
1. Clona el repositorio:
   ```bash
   git clone https://github.com/<tu-usuario>/FileRenamerPro.git


   Uso
Abre la aplicación ejecutando bulk_rename.py.
Haz clic en "Examinar" para seleccionar la carpeta con los archivos.
Configura las opciones de renombrado:
Ingresa un prefijo (opcional).
Marca las casillas para incluir numeración y/o fecha.
Haz clic en "Renombrar Archivos".
Recibirás una notificación de éxito o error.
Ejemplo
Archivos originales:

text

Copiar
foto.jpg
documento.pdf
video.mp4
Opciones seleccionadas:

Prefijo: Archivo
Numeración: Sí
Fecha: Sí (20250424)
Archivos renombrados:

text

Copiar
Archivo_20250424_001_foto.jpg
Archivo_20250424_002_documento.pdf
Archivo_20250424_003_video.mp4
Contribuciones
¡Las contribuciones son bienvenidas! Por favor, sigue estos pasos:

Haz un fork del repositorio.
Crea una rama para tu funcionalidad (git checkout -b feature/nueva-funcionalidad).
Realiza tus cambios y haz commit (git commit -m 'Agrega nueva funcionalidad').
Sube los cambios (git push origin feature/nueva-funcionalidad).
Abre un Pull Request.
Licencia
Este proyecto está bajo la .

Contacto
Creado por [Carlos Arturo Garzón]. Para preguntas o sugerencias, contacta a través de [sedsist@gmail.com].
