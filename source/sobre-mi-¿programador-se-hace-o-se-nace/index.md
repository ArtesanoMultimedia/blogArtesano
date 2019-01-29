---
title: 'Sobre mí: ¿Programador se hace o se nace?'
date: 2019-01-27 15:09:24
---

Esto es una historia autobiográfica acerca de mi relación con la programación. De cómo siempre ha estado presente en mi vida desde que yo recuerdo y de cómo se convirtió en mi trabajo.

## En la Prehistoria.

Mi pasión por la informática comenzó de muy pequeño, antes de que en las casas hubiera acceso a internet: **en la Prehistoria**. Recuerdo que _creé_ mis primeros programas copiando códigos **BASIC** de un libro en un **Amstrad de 64 bits**.

De aquel código no entendía casi nada. Mi único interés era que si conseguía copiarlo todo sin equivocarme, al final podría jugar a algo, o bien obtendría un programa que no me valía para nada. **Mi única referencia sobre lo _chulo_ que iba a ser el programa era el número de líneas que tenía que copiar.** A más líneas, suponía yo que mejor sería el juego, aunque lo cierto es que muchas veces, ni siquiera eran juegos...

## La Edad Media: Las guerras en el IRC.

Más adelante, en mi adolescencia, se popularizó el IRC, unas pocas miles de personas nos conectábamos a diario al IRC-Hispano, y fue entonces cuando descubrí el **lenguaje de scripting del mIRC**, el programa que más se utilizaba para conectarse. Los scripts del mIRC tenían muchas utilidades: mensajes automáticos, agregar menús con diversas opciones, etc. Aunque probablemente las más importantes tenían que ver con el **IRC-War**. No sé muy bien por qué ni contra quién, pero recuerdo que **había auténticas guerras en el IRC** y había scripts exclusivamente dedicados a ello: a llevar a cabo acciones tanto ofensivas como defensivas.

El código de los scripts era accesible por cualquiera, lo cual permitía **investigar**, **aprender** cómo funcionaba y **modificarlo** o crear código a tu gusto. Sea como fuere, el caso es que gracias al scripting, a base de mirar el código escrito por otros y de una forma totalmente **autodidáctica**, aprendí a dar mis primeros pasos en el mundo de la programación: asignación de variables, bucles, condicionales,...

Por aquel entonces también aprendí las bases del **HTML** y del **CSS** y creé mis primeras páginas web. Poco después, empecé también a crear páginas usando algunos CMS. En aquella época usaba PHPNuke y PostNuke, para los cuáles también podía **crear mis propios plugins** y ampliar sus funcionalidades.

## La Universidad (Primera parte).

Llegué a la Universidad de Santiago de Compostela con 17 años para estudiar la **Licenciatura en Matemáticas**. Allí me encontré con una asignatura de Informática en la que se estudiaba estructura y funcionamiento del ordenador, **metodología de la programación** y se aprendía **pseudocódigo**, **Fortran 77** y **Matlab**. He intentado buscar el programa, pero en el más antiguo que he encontrado, que es [éste](http://www.usc.es/es/centros/matematicas/materia.html?materia=6909&ano=3&idioma=1), de apenas unos años después, ya se estudiaba Fortran 90.

Yo partía con ventaja, porque ya tenía unas buenas nociones de programación. Sin embargo, el **estudio formal**, la **comprensión del funcionamiento matemático subyacente** y el análisis del **costo computacional** de los algoritmos, me sirvieron para dar un gran salto en mi **capacidad analítica y resolutiva.**

## Psicotécnicos y Administración Pública.

Antes de terminar los estudios de matemáticas, me vi en la necesidad de incorporarme al mercado laboral. Aposté por **preparar oposiciones** y me presenté a las de **Auxiliar Administrativo del Estado**, que aprobé a la primera. A decir verdad, también partía con mucha ventaja, porque un tercio del examen era **psicotécnico**, que venían a ser matemáticas bastante básicas. Aproximadamente otro tercio era **informática, casi todo ofimática** e informática básica. Por lo que sólo tuve que preparar la parte de legislación, que era el otro tercio.

Al incorporarme a mi nuevo puesto de trabajo, me empecé a encontrar con tareas monótonas y repetitivas. Empecé entonces a implementar algunos programas que automatizaban aquellas tareas, lo que llamó la atención de mis superiores, que inmediatamente comprendieron la **capacidad  transformadora de la programación.** Me dieron bastante vía libre para programar y automatizar todo lo que se me ocurría, y también me supieron encargar **desarrollos específicos.** Era una relación muy interesante, porque por una parte tenía el input de los objetivos que marcaban los jefes y por otra parte el input de los compañeros que serían los usuarios finales y **yo era quien analizaba todos los requerimientos y planteaba la solución.**

### Levantamiento, caída y resurrección de un Coloso.

Debido a una reorganización, nos juntaron con otra oficina más grande y se creó una unidad nueva. Tras unas negociaciones entre jefes, a esa nueva unidad se le asignaron unas tareas y un personal. Creo que mi jefe, que sería el Director de esa nueva unidad, cedió en algunos aspectos, anticipando la posibilidad de crear un software para **automatizar gran parte del trabajo** que hasta entonces realizaban 5 personas, prácticamente a jornada completa. Accedió a asumir ese trabajo y calculó que 3 personas seríamos suficientes.

Me encargó crear un programa que permitiese a **distintos usuarios trabajar al mismo tiempo sobre la misma base de datos**, introducir unos datos de entrada, realizar cálculos matemáticos y generar una resolución que se debía imprimir. Cuando le pregunté en qué lenguaje lo tenía que programar, me dio **vía libre** para desarrollarlo usando la tecnología que creyese conveniente. Pensé que, básicamente **lo que necesitábamos era una web,** como una tienda online en la que compran varios usuarios reduciendo el número de elementos de un mismo stock. Así que **decidí hacerlo con PHP y MySQL.**

#### Levantamiento.

Yo no tenía unos conocimientos sólidos de PHP ni de MySQL, así que me compré un libro: _Desarrollo Web con PHP 6 y MySQL 5.1_. **Me lo estudié de pé a pá.** Con eso y lo que pude investigar por internet, al cabo de unos meses tenía al Coloso en pie: Monté un **servidor web Apache** que admitía conexiones sólamente desde las IPs de los usuarios autorizados, que además tenían que hacer **loggin**. Usaba **sesiones** para mantener el acceso y **formularios** para la entrada de datos. Se conectaba a la **base de datos** para guardar expedientes y cálculos y permitía **generar un pdf** con la resolución que se remitía al interesado. **Todo funcionaba de maravilla.**

#### Caída.

El problema es que montar un servidor Apache no era algo que el departamento de informática viera con buenos ojos y me invitaron a migrar la aplicación a los recursos corporativos: **Microsoft Access.** :(

#### Resurrección.

Aunque yo usaba habitualmente **vba** para **programar en Excel**, nunca había hecho nada muy elaborado en **Access**. Tras varios libros de Access Avanzado y muchas consultas a internet, acabé montando una aplicación completísima. **Mucho más completa que la anterior.** Integrada con Word para generar las resoluciones a partir de **plantillas word** (.dotx) modificables por el usuario, utilizando tablas en las que **se combinan celdas al vuelo** y automatizando el **envío de emails con Outlook.** Al final le acabé cogiendo el gusto y todo a los Recordsets de Access. Actualmente, sólo se necesita **un funcionario** dedicado a esa labor, aquella que antaño ocupaba a 5, y además dedica sólo una pequeña fracción de su tiempo a ello, ya que tiene asignadas también muchas otras funciones. Es decir, que **el programa redujo aproximadamente 30 o 50 veces la carga de trabajo.**

## La Universidad (Segunda parte)

A los pocos años de estar en Girona, decidí reemprender los estudios de matemáticas. Hice traslado de expediente a la UNED y fui cogiendo asignaturas sueltas, haciendo poco a poco. Aunque en Santiago había tocado algo de **LaTeX**, siempre me había quedado con las ganas de ponerme a fondo con ello. Lo hice en esta época. Además cursé asignaturas como **Programación Lineal y Entera**, en donde se estudiaban algoritmos de optimización, **Programación**, en la que básicamente se estudiaba **C++**, o **Análisis Numérico Matricial**, en la que se estudiaba la representación numérica en el ordenador y los algoritmos y métodos de optimización: cómo prever y evitar que los errores de redondeo se propaguen y crezcan al realizar cálculos, cómo representar y operar con grandes conjuntos de datos dispersos, etc.

## Hosting, dominios y páginas web.

Aprovechando que en aquella época disponía de bastante tiempo libre, inicié un modesto negocio de **alojamiento, dominios y diseño y desarrollo web**. Al poco de empezar, recibí un encargo de un comercial que hacía de intermediario entre el cliente final y yo. Quedó tan satisfecho, que me propuso asociarnos, así que durante un tiempo tuve un socio que me consiguió bastantes clientes. Normalmente **negocios locales** que necesitaban una página web, aunque también **emprendedores** que querían montar **su propio negocio online.** Él contactaba con el cliente y me trasladaba los encargos con los requisitos. Yo hacía la web y configuraba el hosting, el dominio y los e-mails.

Tiempo después, el socio decidió abandonar el proyecto y yo exploré otras opciones. Nunca abandoné el proyecto y a día de hoy sigue funcionando, aunque ya no invierto tiempo ni dinero en promocionarlo y conseguir nuevos clientes. Me limito a utilizar los servidores para mis propios proyectos y para seguir dando servicio a antiguos clientes. Con el tiempo contraté distintos servidores, trabajé con diferentes proveedores de dominios,... y hasta **dejé de usar WHMCS** (el software más utilizado para automatizar negocios de hosting) para crear **mi propia solución en Laravel**, consumiendo las APIs de CPanel y de mis proveedores de dominios, gestionando los cobros a través de Stripe y PayPal, etc.

## Oposiciones de Informática.

En el año 2018 me presenté a las oposiciones de Promoción Interna para el grupo C1 de informática del Estado (Convocatoria de 2017). A estas oposiciones se presentaban también informáticos del grupo C2.

Por suerte para mí, que tenía bastante **experiencia tanto en desarrollo como en administración de sistemas y redes**, en 2018 cambiaron la forma del examen y de poder elegir el bloque de desarrollo o el de administración, pasó a no poderse elegir, ya que en la parte teórica entraba todo.

La fecha del examen me cogió por sorpresa y **compré los temarios a un mes vista** del examen. Sin embargo, al realizar los primeros simulacros, sacaba una nota como para aprobar con margen. Debido a problemas de salud, no pude viajar a Madrid con tiempo, tal y como tenía previsto. Viajé finalmente por la noche, llegando al examen _de reenganche_.

El examen fue bastante complicado. Da muestra de ello el hecho de que **sólo 20 opositores lo superamos,** cuando había 100 plazas convocadas. Es decir: **quedaron plazas desiertas** por falta de aspirantes que consiguieran aprobar el examen...

En julio de 2018 se publicaron las notas y supe que había aprobado con la 5ª mejor nota, pero actualmente todavía estamos a la espera de la toma de posesión.

Aquí puede consultarse:

* [Los temas que entraban (últimas 3 páginas)](https://sede.inap.gob.es/alfresco/alfresco?pathInfo=%2Fd%2Fd%2Fworkspace%2FSpacesStore%2Fad18978e-5623-4dc8-8cca-b286b6e822c2%2FTAI-PI.pdf)
* [El examen.](https://sede.inap.gob.es/alfresco/alfresco?pathInfo=%2Fd%2Fd%2Fworkspace%2FSpacesStore%2F83a0c987-7ef1-49ac-a189-85cffa21e3fe%2FTAI%252520PI%2525202017.pdf)
* [La lista definitiva de aprobados](https://sede.inap.gob.es/alfresco/alfresco?pathInfo=%2Fd%2Fd%2Fworkspace%2FSpacesStore%2F2afc1780-60d6-4fe5-bae5-6423d533fdbf%2F2-TAI-SUFC-PT_PG_154AB89SD658.pdf) _Aunque obtuve la 5ª mejor nota en la oposición, en la fase concurso bajé un puesto por puntos._

##  Estudios de Multimedia en la UOC.

Al comprobar **lo fácil** que me había resultado **aprobar las oposiciones de informática**, le eché un vistazo al examen de acceso al siguiente cuerpo al que me podría presentar y no me pareció muy complicado tampoco, pero requiere que antes obtenga un **título de grado.** Pensé entonces que sería una buena opción empezar de cero el grado o la ingeniería informática, ya que seguro que me resultaría más fácil y más relevante para mi futuro laboral que la de matemáticas.

Tras valorar las distintas opciones, tanto en la UNED como en la UOC, me topé con otras dos titulaciones que me llamaban la atención: **Grado en Diseño y Creación Digital** y **Grado en Multimedia**, ambas de la UOC. Tenían algo que le faltaba a la carrera de informática: La parte artística. El **Photoshop**, el **After Effects**, el **modelado 3D**,... una parte de la informática que me apasiona y que en el Grado en Informática no se toca. De hecho, muchos estudiantes del Grado en Informática hacen un minor de Multimedia consistente en 2 o 4 asignaturas (hay varios minors distintos) para estudiar desarrollo web, ya que en su carrera les falta: **Diseño gráfico, HTML, CSS, PHP, Javascript,...**

De modo que tras valorar las distintas opciones, aparqué temporalmente la carrera matemáticas y **me matriculé del primer semestre completo del Grado en Multimedia de la UOC** y aunque requirió un gran sacrificio, tanto mío como de mi familia, conseguí entregar todas las prácticas a tiempo, obteniendo en todas ellas la **máxima calificación.** Poco a poco las iré publicando en este mismo blog.

## Cuanto todo se parece alinear: Cambio de rumbo laboral

Afincados desde hace 10 años en Girona, una tierra en la que nos hemos sentido como en casa, mi mujer y yo hemos notado en muchas ocasiones **la distancia de la familia.** Sobre todo desde que somos padres y vemos que no contamos con un tejido familiar al que recurrir en ciertos momentos.

Dado que conseguir un traslado laboral se venía mostrando **imposible**, no teníamos ninguna esperanza de volver a Galicia en un futuro próximo. Sin embargo, nos vemos en la obligación de **mudarnos** del piso en el que llevamos viviendo los 3 últimos años y vemos que la oferta de alquiler ahora mismo es **excasa** y además **los precios se han vuelto a disparar.** Al mismo tiempo, un piso familiar queda vacío en Santiago. Así que, una de cuatro:

* Consigo un **traslado** a Santiago o alrededores.
* Encuentro trabajo en la **privada**.
* Me pongo como **Freelance**.
* Mi mujer encuentra trabajo en la privada _(Es **Auxiliar de Veterinaria**)._

Sea como sea, está decidido: **nos volvemos para Santiago de Compostela.**