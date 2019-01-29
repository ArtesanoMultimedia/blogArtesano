---
title: 'Sobre mí: ¿Programador se hace o se nace? (parte 2 de 3)'
date: 2019-01-29 09:13:03
---

Si te perdiste la primera parte, tal vez te interese [empezar por aquí](/blogArtesano/sobre-mi-programador-se-hace-o-se-nace-parte-1-de-3).

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

Continúa en [la tercera parte](/blogArtesano/sobre-mi-programador-se-hace-o-se-nace-parte-3-de-3/)