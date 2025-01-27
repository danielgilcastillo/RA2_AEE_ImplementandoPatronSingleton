Resumen sobre la constitucion y funcionamiento del proyecto:
Se trata de una clase UsuarioManager que:
○ Sigue el patrón Singleton.
○ Carga datos de la tabla usuarios al acceder por primera vez.
○ Mantiene los datos en una lista en memoria.
○ Proporciona métodos para acceder a los usuarios cargados.
2. Hay una tabla usuarios que tenga los siguientes campos:
○ id (INT, PRIMARY KEY)
○ nombre (VARCHAR)
○ email (VARCHAR)
3. Main que llame a UsuarioManager dos veces y permite
verificar que la carga de datos se realiza solo en la primera llamada mediante puntos
de interrupción.
