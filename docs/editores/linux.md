# Editores
sed: Es un editor de flujo (stream editor) que se utiliza principalmente para realizar transformaciones de texto en archivos o en flujos de datos.

Ejemplo: sed 's/old_text/new_text/g' archivo.txt (sustituye 'old_text' por 'new_text' en archivo.txt).
awk: Es una herramienta para procesar y generar reportes de texto y datos estructurados.

Ejemplo: awk '{print }' archivo.txt (imprime la primera columna de archivo.txt).
cut: Se utiliza para extraer secciones de cada línea de archivos.

Ejemplo: cut -d',' -f1 archivo.csv (extrae el primer campo separado por comas en archivo.csv).
tr: Sirve para traducir o eliminar caracteres.

Ejemplo: tr '[:lower:]' '[:upper:]' < archivo.txt (convierte texto a mayúsculas en archivo.txt).
tee: Permite leer desde la entrada estándar y escribir tanto en la salida estándar como en uno o más archivos.

Ejemplo: command | tee archivo.txt (guarda la salida de 'command' en archivo.txt y la muestra por la salida estándar).
echo: Imprime texto en la salida estándar o en un archivo.

Ejemplo: echo 
