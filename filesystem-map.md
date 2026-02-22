/Roots: Es el directorio principal (raiz) del sistema, aqui comienza toda la estructura, todos los demas directorios cuelgan de aqui.
/bin: Contiene los binarios (programas ejecutables) esenciales del sistema pueden usar todos los usuarios: ls, cp, mv y bash.
/sbin: Contiene binarios de administracion del sistema que normalmente requieren privilegios de usuario root para ser ejecutados.
/etc: Aqui se almacena todos los archivos de configuracion del sistema operativo y sus servicios.
/home: Directorio que coontiene carpetas personales de los usuarios.
/var: Contiene datos variables que cambian constantemente durante la operacion, como registro de eventos (logs), colas de impresion y base de datos.
/usr: Contiene la mayoria de los programas y utilidades de los usuarios; incluye sus propios subdrectorios /bin y /lib
/tmp: Espacio para archivos temporales, este se limpia cada que se reinicia el sistema.
/opt: Destinado a la instalacion de paquetes de sofeware opcional de terceros que no siguen el estandar de linux.
/boot: Guarda los archivos necesarios para que la computadora encienda, incluyendo el Kernel de linux y configuaracion de arranque GRUB.
/dev: Contiene archivos especiales que representan los dispositivos fisicos(esto bajo la filosofia de todo es un archivo).
/proc: Sistema de archivo virtual que no ocuoa espacio en disco, expone la informacion en tiempo real sobre los procesos acticos y el estado del kernel.
/sys: Proporciona una interfaz para ver y cambiar la informacion de los dispositivos y controladores directamente en el Kernel.
/mnt: Se utiliza como un punto de mpontaje temporal para que el administrador conecte manualmente sistemas de archivos o particiones externas.

