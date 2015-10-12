# Tablita
Concepto minimalista de busqueda de datos en html.

Solamente hay un archivo en html que contiene muy poquito codigo. No depende de ninguna libreria en JavaScript ni CSS.

Hay tres partes:

  - La tabla en html es la base de datos.
  - El script procesa la busqueda y usa manipulacion de arreglos 
  para limpiar el estado anterior (si hubo busqueda) y encontrar la hilera
  que contiene el valor buscado.
  - Los estilos determinan como se ve la hilera que contiene el valor,
  y las que no. En este particular caso, solamente se muestra una hilera y
  se ocultan las demas, pero en la practica es posible darle enfasis al resultado
  sin ocultar nada.

# Problemas?

  - Si hay un error en el codigo, reporta un problema.
  - Si quieres hacer cambios, haz un fork al repositorio y experimenta.
