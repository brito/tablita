# Tablita
Concepto minimalista de busqueda de datos en html.

Solamente hay un ejemplo en html que contiene muy poquito codigo. No depende de ninguna libreria en JavaScript ni CSS.

Hay tres partes:

  - La [tabla](https://github.com/brito/tablita/blob/master/ejemplo.html#L38) en html es la base de datos. Aqui se cambian los valores directamente.
  - El [script](https://github.com/brito/tablita/blob/master/ejemplo.html#L47) procesa la [busqueda](https://github.com/brito/tablita/blob/master/ejemplo.html#L35) y usa manipulacion de arreglos 
  para limpiar el estado anterior (si hubo busqueda) y encontrar la hilera
  que contiene el valor buscado.
  - Los [estilos](https://github.com/brito/tablita/blob/master/ejemplo.html#L6) determinan como se ve la hilera que contiene el valor,
  y las que no. En este particular caso, solamente se muestra una hilera y
  se ocultan las demas, pero en la practica es posible darle enfasis al resultado
  sin ocultar nada.

# Problemas?

  - Si hay un error en el codigo, [reporta un problema](https://github.com/brito/tablita/issues/new).
  - Si quieres hacer cambios, haz un [fork](https://github.com/brito/tablita/fork) al repositorio y experimenta.

# A ver

  - [Ejemplo](http://brito.github.io/tablita/ejemplo.html)
  - [Codigo fuente](https://github.com/brito/tablita/blob/master/ejemplo.html)
