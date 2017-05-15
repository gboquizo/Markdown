## <a name="Inicio"> Elementos y sintaxis </a>

Markdown dispone de una amplia variedad de elementos. 

A continuación se muestra una lista de ellos:

- <a href="#Enlaces">Enlaces</a>

- <a href="#Listas">Listas</a>
- [Imágenes](imagenes.md)

- [Citas en bloque](citas.md)

- [Párrafos y saltos de línea](parrafos.md)

- [Tablas](tablas.md)

- [Vídeos](video.md)

- [Resaltado (negrita, cursiva, etc)](Resaltado.md)

- [Código con resaltado de sintaxis](Resaltado_Codigo.md)

- [Referencias](Referencias.md)

- [Emojis](Emojis.md)

- [Notas a pie de página](piePagina.md)

- [Abreviaturas](abreviaturas.md)

- [Lineas Horizontales](lineasHorizontales.md)

- [Escapar caracteres](caracteresEscape.md)



* * *

<a name="Enlaces"> <h1> Enlaces </h1> </a>

Existen dos maneras de crear enlaces: 

* **Enlace en línea:** 

		[Título del link](url)

Ejemplo:

![enlaceEnLínea](https://megaweb27.files.wordpress.com/2017/05/enlacelinea.png)

Resultado:

[Enlace](https://github.com/sole27/Markdown)

* **Por referencias:**

		[Link][id]    [id]: http://ejemplo.com "Título"


 Ejemplo:

 ![Enlace](https://megaweb27.files.wordpress.com/2017/05/enlaces.png)

 Resultado:

 [Enlace 1][1], [Enlace 2][2], [Enlace 3][3]



 [1]: https://github.com/sole27/Markdown

 [2]: https://github.com/sole27/Markdown

 [3]: https://github.com/sole27/Markdown



Por último, existe otra forma mucho más sencilla en la que se crean enlaces automáticos para direcciones URL:

				

     					<URL>

Resultado:

https://github.com/sole27/Markdown 

* * *

<a name="Listas"> <h1> Listas </h1> </a>

    

Existen varios tipos de listas:

- **LISTAS ORDENADAS:**

		Lista numerada (ordenada)

		1. Línea 1

		2. Línea 2

		3. Línea 3
Resultado:

	1. Línea 1
	2. Línea 2
	3. Línea 3

* **LISTAS DESORDENADAS:**

		Lista de puntos (desordenada)
		* Línea 1
		* Línea 2
		* Línea 3
		
        NOTA: Pueden utilizarse "*", "-" o "+".
	Resultado:
	* Línea 1
	* Línea 2
	* Línea 3

* **LISTAS ANIDADAS:**
Pueden mezclarse los tipos de listas y anidarlas.

		1. Lista ordenada
		2. Línea 2 de la lista ordenada
    		1. Lista ordenada anidada 
        		* Lista desordenada anidada
        		* Seguna línea de la lista desordenada
    		2. Segunda línea de la lista ordenada anidada
Resultado:

1. Lista ordenada
2.  Línea 2 de la lista ordenada
	1. Lista ordenada anidada 
		* Lista desordenada anidada
       		* Seguna línea de la lista desordenada
	2. Segunda línea de la lista ordenada anidada
   	 

* **LISTAS DE TAREAS:**

		- [x] Tarea completa

		- [ ] Tarea incompleta 

Resultado:

- [x] Tarea completa

- [ ] Tarea incompleta 


<a href="#Inicio">Volver al inicio </a>



