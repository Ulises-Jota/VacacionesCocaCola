# VacacionesCocaCola
Proyecto final curso Java Desde Cero - Sistema de control vacacional

Proyecto realizado en el curso online Java Desde Cero por La Geekipedia De Ernesto.

Se aplicaron los contenidos vistos en el curso para realizar una aplicación de escritorio que simula un sistema de control vacacional, hasta el empaquetado del programa.

El desarrollo se realizó en bloc de notas para aprender (y aprehender) la sintaxis básica de Java, sin la "ayuda" de un IDE. El compilado, la ejecución y el empaquetado, se realizó íntegramente desde consola.

Las tres pantallas del sistema ('Bienvenida', 'Licencia de uso' y 'Principal'), están seteadas para que no puedan ser modificadas de tamaño y para que siempre aparezcan en el centro del escritorio, aunque luego puedan moverse libremente.

El programa inicia con la pantalla de Bienvenida, que solicita ingresar el nombre. En caso de no ingresarlo, arroja un mensaje avisando que se debe ingresar el nombre:

<img src="screenshots/1 - Pantalla bienvenida.png" width="300">     <img src="screenshots/2 - Validar ingresar nombre.png" width="300">

Una vez ingresado el nombre, cierra la pantalla de Bienvenida y pasa a la pantalla de Licencia de uso, donde se debe tildar la aceptación para habilitar el botón de
Continuar. El nombre ingresado en la pantalla de Bienvenida se pasa a esta pantalla, pudiéndose visualizar en el texto del JCheckBox. En caso de no tildar la aceptación,
solo queda habilitado el botón de No Acepto, en cuyo caso si se cliquea en el mismo, cierra la pantalla de Licencia de uso y vuelve a abrir la de Bienvenida.

<img src="screenshots/3 - Pantalla TyC.png" width="450">     <img src="screenshots/4 - Validar Acepto TyC.png" width="450">

Una vez aceptados los términos y condiciones, se cierra esa pantalla y se abre la pantalla Principal. Aquí se solicitan los datos pertinentes para poder hacer los
cálculos de vacaciones, y a su vez se valida que todos los campos estés completados.

<img src="screenshots/5 - Pantalla Principal.png" width="400">     <img src="screenshots/6 - Listo para calcular vacaciones.png" width="400">

<img src="screenshots/7 - Resultado cálculo vacaciones.png" width="400">      <img src="screenshots/8 - Validar Completar todos los campos.png" width="400">

Hay tres menús que corresponden a las 'Opciones' (desde donde se puede cambiar el color de fondo de la pantalla, se pueden limpiar los campos para hacer un nuevo cálculo
o se puede salir de la pantalla principal, cerrando la misma y volviendo a la pantalla de Bienvenida), otro menú con 'Calcular' desde donde se ejecuta el cálculo de las
vacaciones y un último menú 'Acerca de' donde se puede acceder a los detalles del desarrollador.

<img src="screenshots/9 - Menu Opciones.png" width="400">      <img src="screenshots/Pantalla Principal Morada.png" width="400">

<img src="screenshots/Pantalla Principal Negra.png" width="400">

