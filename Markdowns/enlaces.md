<h1> Enlaces </h1>

Existen dos maneras de crear enlaces: 

* **ENLACE EN LÍNEA:**

		[Título del link](url)

Ejemplo:

![enlaceEnLínea](https://megaweb27.files.wordpress.com/2017/05/enlacelinea.png)

Resultado:

[Enlace](https://github.com/sole27/Markdown)


* **POR REFERENCIAS:**

		[Link][id]     [id]: http://ejemplo.com "Título"



 Ejemplo:

 ![Enlace](https://megaweb27.files.wordpress.com/2017/05/enlaces.png)

 Resultado:

 [Enlace 1][1], [Enlace 2][2], [Enlace 3][3]



 [1]: https://github.com/sole27/Markdown

 [2]: https://github.com/sole27/Markdown

 [3]: https://github.com/sole27/Markdown

* **ENLACES INTERNOS:**

Se pueden crear enlaces a distintas partes del contenido, como por ejemplo a cabeceras.
Se hace colocando un id en la parte del contenido a la que queremos enlazar, por ejemplo, a una cabecera:


			### Cabecera con id {#cabecera1}
			[Enlace a esa cabecera](#cabecera1)
            
            
###### Esto es una cabecera con un Id {#cabecera1}
[Enlace a esa cabecera](#cabecera1)

* **ENLACES AUTOMÁTICOS:**

Por último, existe otra forma mucho más sencilla en la que se crean enlaces automáticos para direcciones URL:

				

     					<URL>

Resultado:

https://github.com/sole27/Markdown 
