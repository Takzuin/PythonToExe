
Pasos para usar el código:
    Instalar dependencias: Asegúrate de tener tkinterdnd2 y pyinstaller instalados. Puedes instalarlos con:
        pip install tkinterdnd2 pyinstaller

Crear el archivo ejecutable:
    Navega hasta el directorio donde tienes tu archivo Python y ejecuta:
        pyinstaller --onefile --windowed tu_archivo.py

    --onefile crea un único archivo ejecutable.
    --windowed evita que se abra una ventana de consola (útil para aplicaciones con interfaz gráfica).

Buscar el archivo ejecutable:

Después de ejecutar el comando anterior, PyInstaller creará una carpeta dist 
en el mismo directorio donde se encuentra tu archivo Python.

Dentro de esta carpeta, encontrarás el archivo ejecutable.
Aquí tienes un ejemplo de cómo se vería el comando si tu archivo se llama traductor.py:

pyinstaller --onefile --windowed traductor.py