<div align="justify">



## Descripción

  - Una	 biblioteca	 tiene	 copias	 de	 libros.	 Estos	 últimos se	 caracterizan	 por	 su	 nombre,	 tipo	(ingeniería,	literatura,	informática,	historia	...),	editorial,	año	y	autor.
  - Los	autores	se	caracterizan	por	su	nombre,	nacionalidad	y	fecha	de nacimiento.
  - Cada	 copia	 tiene	 un	identificador,	y	 puede	estar	en	la	 biblioteca,	 prestada, con	 retraso	 o	en	 reparación.
  - Los	lectores	pueden	tener	un	máximo	de	3	libros	en	préstamo.
  - Cada	libro	se	presta	un	máximo	de	30	días,	y	por	cada	día	de	retraso,	se impone	una	“multa” de	dos	días	sin	posibilidad	de	coger	un	nuevo	libro.
  - Realiza	 un	 diagrama	 de	 clases	 y	 añade	 los	 métodos	 necesarios	 para realizar	 el	 préstamo	 y devolución	de	libros.
  Realiza	un	diagrama	de	casos	de	usos.


## Actores

|  Actor | Lector |
|---|---|
| Descripción  | El usuario que acude a la libreria a pedir o devolver libros  |
| Características  | Cantidad de libros en prestamo, cantidad de multas |
| Relaciones | Pedir Libro, Devolver Libro, Comprobar Máximo Libros Prestados, Comprobar Ausencia de Multas, Cancelar Prestamo |
| Referencias | [Casos de uso](https://github.com/jpexposito/docencia/blob/master/Primero/ETS/DIAGRAMAS/DIAGRAMAS-CLASES/Ejemplos/biblioteca.md) |   
|  Notas |   |
| Autor  | JonayKB|
|Fecha | 03-12-2023 |


|  Actor | Libro |
|---|---|
| Descripción  | Objeto que recibe y comprueba sus atributos  |
| Características  | Identificador, tipo, editorial, año y autor(nombre, nacionalidad, fecha de nacimiento), estado |
| Relaciones | Entregar Libro, Comprobar Devolución, Añadir Multas |
| Referencias | [Casos de uso](https://github.com/jpexposito/docencia/blob/master/Primero/ETS/DIAGRAMAS/DIAGRAMAS-CLASES/Ejemplos/biblioteca.md) |   
|  Notas |   |
| Autor  | JonayKB|
|Fecha | 03-12-2023 |
</div>