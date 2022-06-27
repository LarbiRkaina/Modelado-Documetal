

### <u>Práctica Modelado:</u>



En este proyecto he trabajado con una relación de uno a muchos, es decir, en el modelado he considerado que una categoría puede tener muchos cursos.

He creado dos documentos, el de ***Lección*** y el de ***Autor***. Al de **Lección**, le he añadido los campos  *id* que es de tipo objectid y también los campos *nombre*, *idVideo*  e *idArticulo* que son todos de tipo string. Al documento **Autor** le he añadido como campos el i*d* que es de tipo objectId y el *nombre* que es de tipo string.

Para la **collection Curso**, le he pasado la **collection  Categoría** en una relación de  uno a muchos, le he añadido como campos un array de Autores(que es un array del *document Autor*) y un array de Lecciones(que es un array de *document Lección*).



En definitiva quedaría así:



![model](model.png)
