# google-drive-bakcup
Script para hacer respaldos de posgres y subirlos automaticamente a google drive 
============================

COMO FUNCIONA
============================
El código son dos archivos
- generarBackupPostgresql.py
  Toma las bases de datos de postgresql y les hace un respaldo agregando la fecha al archivo bak (rutas harcodeadas por vaqueton)

- uploadToDrive.py
  Recibe como parametro la lista de archivos generados (en generarBackupPostgresql.py) crea una carpeta en google drive y sube los
  archivos a esa carpeta
  
COMO EJECUTAR
============================
python generarBackupPostgresql.py
