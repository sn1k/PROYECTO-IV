## **ALJALO PROJETC. Proyecto de IV junto con DAI** ##


### **Participantes:** ###

### Lorenzo Manuel Rosas Rodríguez  ###
### Javier Ruiz César ###
### Alberto Romero Cañadas ###

**Breve Descripción/Introducción:**

El proyecto consiste en una plataforma de compra/venta de productos on-line. La plataforma contiene varias secciones para la venta de todo tipo de productos. La plataforma consiste en una página web donde cualquiera podra ver los productos que se venden, pero para poder vender o comprar será necesario registro. Si el vendedor se encuentra conectado, cualquier comprador potencial podrá chatear con el para preguntarle sobre el productos.

Cada anuncio vendra acompañado de una foto y una descripcion del producto que se ajuste a la realidad. Cada producto deberá estar bien situado en su sección correspondiente.

Cada usuario podrá tener una lista de productos favoritos.

Habrá moderadores que podrán eliminar cualquier anuncio de material fuera de la ley o que no se ajuste a la política de la plataforma.

La plataforma albergará un foro donde poder opinar sobre las diferentes transacciones.

## Requisitos básicos de nuestro proyecto

* Sesiones de usuarios y moderadores

* Chat entre usuarios.

* Foro sobre opiniones de transacciones.

* Gestión de anuncios.

* Gestión de listas de productos favoritos. 

* Gestion de compra.


****Se irán añadiendo funcionalidades extras en el transcurso del proyecto, debido a que actualmente se encuentra en una fase muy tempranada.

## Herramientas

* Flask como framework para la aplicación.

* HTML5 y CSS3 para la página web.

* MySQL para la base de datos de usuarios y eventos.

* Python para las funcionalidaes de la web y el servidor.


**Organización de los miembros( gestión del trabajo):**

Dividiremos el proyecto en tres módulos, estos tres módulos tendrán cada uno su correspondiente subdirectorio accesibles desde un directorio [principal](https://github.com/sn1k/PROYECTO-IV):

**Módulo 1:**  [(Javier Ruiz César)](https://github.com/javiexfiliana7/submodulo-javi): Este módulo se centrará en los servicios que el servidor de nuestro sistema web va a ofrecer. Conectaremos la aplicación con la base de datos, se procesarán todo lo relacionado con usuarios, anuncios, ventas, etc.. Y despliegue y configuración de la palicación. Usaremos Flask.

**Módulo 2:** [(Alberto Romero Cañadas)](https://github.com/sn1k/submodulo-Alberto): Este módulo abarcará el servidor de la base de datos en el cual se almacenarán los anuncios, mensajes del foro, usuarios, moderadores, lista de productos favoritos, registro de compras, etc.. Todo esto ser realizará en MySQL.

**Módulo 3:** [(Lorenzo Manuel Rosas Rodríguez)](https://github.com/lorenmanu/submodulo-lorenzo): Este módulo implementará el sistema web, por lo que se encargará de la interfaz gráfica de la misma así como de la parte que lanzará peticiones de operaciones a la base de datos.



**NOTA: que el proyecto este dividido en varios módulos no quiere decir que los correspondientes miembros del grupo no colaboren conjuntamente en el proyecto, ya que el objetivo principal de esta asignatura es la virtualización de recursos así como el despliegue de una aplicación de manera automática, por lo que todos los módulos son importantes.

Este proyecto está inscrito en el certamen de proyectos de la UGR organizado por la OSL con el nombre de ALJALO PROJECT.

