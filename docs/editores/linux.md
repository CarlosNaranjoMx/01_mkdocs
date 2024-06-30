# Editores
sed: Es un editor de flujo (stream editor) que se utiliza principalmente para realizar transformaciones de texto en archivos o en flujos de datos.

Ejemplo: sed 's/old_text/new_text/g' archivo.txt (sustituye 'old_text' por 'new_text' en archivo.txt).
awk: Es una herramienta para procesar y generar reportes de texto y datos estructurados.

Ejemplo: awk '{print }' archivo.txt (imprime la primera columna de archivo.txt).
cut: Se utiliza para extraer secciones de cada linea de archivos.

Ejemplo: cut -d',' -f1 archivo.csv (extrae el primer campo separado por comas en archivo.csv).
tr: Sirve para traducir o eliminar caracteres.

Ejemplo: tr '[:lower:]' '[:upper:]' < archivo.txt (convierte texto a mayusculas en archivo.txt).
tee: Permite leer desde la entrada estandar y escribir tanto en la salida estandar como en uno o mas archivos.

Ejemplo: command | tee archivo.txt (guarda la salida de 'command' en archivo.txt y la muestra por la salida estandar).
echo: Imprime texto en la salida estandar o en un archivo.

Ejemplo: echo 
