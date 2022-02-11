## Notas e consideracións (deseño)

* Creación dunha demo da aplicación do Servizo de Orientación Laboral do Concello de Vigo.
* Esta aplicación previa vai constar de 5 pantallas: 
  * a de inicio de sesión, que nos vai permitir realizar un *log in* cos usuarios e contrasinais designados na BBDD;
  * unha de inicio ou *dashboard*, que conta cunha táboa coas próximas citas asignadas á persoa que iniciou sesión e cun apartado de notas rápidas;
  * citas, onde se poderán agregar novas reunións coas persoas usuarias do sistema cunha hora de comezo e outra de finalización. Estas aparecerán na táboa do inicio;
  * persoas, onde se mostrará o listado de persoas dadas de alta no sistema, podendo eliminar, editar e agregar novas;
  * empresas o mesmo que as persoas pero coas empresas colaboradoras.
* A maioría destas páxinas contan cun *header* e un *footer* que foron realizados como compoñentes con tecnoloxía JavaScript para permitir a súa reutilización:
  * o *header* ten unha icona de usuario, as distintas páxinas do sitio, un botón de saír que fai *logout* e unha barra de busca;
  * no *footer* atópase o *copyright*, accesos directos ao portal do empregado e ao servizo de correo Zimbra e o logotipo da concellería de Emprego.
* As fontes empregadas son Roboto para os títulos e Libre Franklin para o resto do texto, que foron seleccionadas coa axuda de https://www.fontpair.co/ para comprobar a compatibilidade estética.
* A paleta de cores baséase na do propio Concello de Vigo, onde predominan os vermellos e brancos, aos que se lle suman grises para determinados compoñentes coma o footer e os fondos das táboas, co obxectivo de contrastar os distintos elementos.
* Botouse man do framework de CSS Bootstrap mediante CDN para axudar a manter unha estética uniforme en todas as páxinas.
