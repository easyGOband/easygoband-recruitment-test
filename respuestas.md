# Preguntas Test


- �Has aplicado los principios SOLID?

En general, dentro de lo posible en esta aplicaci�n, s� se han aplicado.



- �Cu�nto tiempo has estado pensando y escribiendo los tests del c�digo? Si hubieras tenido mucho m�s tiempo... �que habr�as a�adido?

Probablemente dediqu� al menos una hora para organizar las ideas, decidir las tecnolog�as que iba a necesitar y planificar el proyecto. Una vez hecho esto, comenc� con el desarrollo. Al verse interrumpido por unos d�as, no sabr�a decir con exactitud el tiempo total que me llev�, pero aproximadamente calculo que le dediqu� unas 8 horas.

En general, al tratarse de una aplicaci�n con una funci�n bastante sencilla no le a�adir�a m�s cosas como tal. Mejorar�a como se muestran los datos, aspectos est�ticos y, principalmente, la lista de proveedores de acceso. En este �ltimo caso, se obtiene de la API todos los proveedores. Si la cantidad de proveedores fuera muy grande, se tendr�an que obtener todos a la vez y se mostrar�an en una lista inmensa. Una soluci�n ser�a que la API permitiera hacer peticiones con paginaci�n, limitando el n�mero de elementos de la colecci�n que puede devolver.



- �Por qu� motivo has elegido el lenguaje que has usado para este test?

Dentro de los lenguajes m�s comunes en la programaci�n para Android, Java es probablemente el lenguaje con el que me siento m�s c�modo y con el que estoy acostumbrado a trabajar en el desarrollo de aplicaciones m�viles.



- �C�mo mejorar�as la API que has usado?

Se podr�a permitir obtener los datos filtrados, aplicar paginaci�n o, para este caso, obtener los datos ordenados en base a alg�n campo espec�fico, como por ejemplo el de nombre o fecha de modificaci�n.
Tambi�n se podr�a plantear cambiar el m�todo de autentificaci�n de Basic authentication por otro que pueda garantizar mayor seguridad.



- �Qu� framework y lenguaje crees que se ha usado para exponer esta API REST? Consejo: En el protocolo HTTP viaja mucha informaci�n

Consultando la informaci�n del encabezado HTTP con el comando curl, se puede ver que el framework utilizado es Express.js. El lenguaje utilizado debe ser Javascript.



- �Crees que esta API soporta peticiones CORS? �C�mo has llegado a esa conclusi�n?

Creo que s�. Al utilizar el comando �curl -I� he obtenido en la respuesta a la petici�n la cabecera CORS �access-control-allow-origin: *�, que indica que se permite a cualquier origen el acceso a los recursos.



- �En qu� infraestructura crees que est� alojada la API? �Por qu� crees que hemos tomado esa decisi�n?

Est� almacenada en Amazon Web Service (AWS).  Probablemente sea por la gran variedad de servicios que ofrece, siendo de f�cil uso y teniendo bastante documentaci�n de apoyo. Adem�s es escalable y los precios se ajustan al uso. 



- �C�mo rastrear�as un problema de rendimiento en producci�n? �Alguna vez has tenido que hacerlo?

Para detectar problemas de rendimiento llevar�a a cabo al menos alguno de los cuatro tipos de test siguientes, destinados a ese fin: test de carga, de estr�s, de capacidad o de rendimiento.

La verdad, no he tenido que hacerlo antes. Siempre las pruebas que he realizado se han centrado en que el c�digo no falle y cumpla su funci�n, pero no tanto en su rendimiento. Es por ello, que tengo bastante inter�s en ampliar mi experiencia en ese aspecto.



- Descr�bete a ti mismo usando JSON.

{
�nombre�: �V�ctor�,
�apellido�: �Colejo�,
�genero�: �hombre�,
�edad�: 24,
�ciudad�: �Ponferrada�,
�intereses�: [�videojuegos�, �arte�, �series�, �deporte�, �gatos�],
�estudios�: [{�t�tulo�: �Grado en Dise�o y Desarrollo de Videojuegos�,
			�universidad�: �Universidad Jaume I�,
                �a�o�: 2019
        },
        {�t�tulo�: �M�ster en Ingenier�a Inform�tica�,
        �universidad�: �Universidad de Le�n�,
                �a�o�: 2021
        }]
}










}