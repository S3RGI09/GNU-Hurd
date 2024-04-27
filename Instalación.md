# Guía de Instalación de GNU Hurd en disco fisico

Esta guía te llevará a través del proceso de instalación de GNU Hurd en tu sistema. Asegúrate de seguir los pasos con cuidado y consultar la documentación oficial si necesitas ayuda adicional.

## Requisitos del Sistema

Antes de comenzar, asegúrate de que tu sistema cumpla con los siguientes requisitos:

- Un ordenador compatible con arquitectura x86.
- Al menos 512 MB de RAM (se recomienda 1 GB o más).
- Un disco duro con suficiente espacio disponible para la instalación.
- Acceso a internet para descargar los archivos necesarios.

## Pasos de Instalación

### 1. Descarga la Imagen de Instalación

Visita el [sitio web oficial de GNU Hurd](https://www.gnu.org/software/hurd/) y encuentra la sección de descargas. Descarga la imagen de instalación más reciente para tu arquitectura de sistema.

### 2. Crea un Medio de Instalación

Graba la imagen de instalación en un CD/DVD o crea un USB de arranque con la imagen utilizando una herramienta como Rufus (Windows) o Balena Etcher (Linux/Mac).

### 3. Arranca desde el Medio de Instalación

Inserta el medio de instalación en tu ordenador y arranca desde él. Puede que necesites cambiar la secuencia de arranque en la BIOS/UEFI para que el ordenador arranque desde el medio de instalación.

### 4. Inicia la Instalación

Una vez que el medio de instalación haya arrancado, sigue las instrucciones en pantalla para iniciar el instalador de GNU Hurd. Selecciona la opción de instalación y elige el idioma y la distribución del teclado según tus preferencias.

### 5. Configura la Instalación

Sigue las instrucciones en pantalla para configurar la instalación de GNU Hurd. Esto puede incluir la configuración de la zona horaria, la partición del disco duro y la configuración de la red.

### 6. Instala el Sistema Operativo

Una vez que hayas configurado todos los ajustes, procede con la instalación de GNU Hurd. Esto puede tardar un tiempo dependiendo de la velocidad de tu sistema y el tamaño de la instalación.

### 7. Reinicia tu Ordenador

Una vez que la instalación haya terminado, reinicia tu ordenador y retira el medio de instalación. Tu sistema ahora debería arrancar en GNU Hurd.

## Conclusiones

¡Felicidades! Has completado la instalación de GNU Hurd en tu sistema. Ahora puedes empezar a explorar y utilizar este sistema operativo libre y colaborativo. Si necesitas ayuda adicional, consulta la documentación oficial o únete a la comunidad en los foros de discusión y listas de correo electrónico.


# Guía de Instalación de GNU Hurd en VirtualBox

Esta guía te llevará a través del proceso de instalación de GNU Hurd en una máquina virtual utilizando VirtualBox. Asegúrate de seguir los pasos con cuidado y consultar la documentación oficial si necesitas ayuda adicional.

## Requisitos del Sistema

Antes de comenzar, asegúrate de que tu sistema cumpla con los siguientes requisitos:

- Una computadora con VirtualBox instalado.
- Al menos 1 GB de RAM disponible para asignar a la máquina virtual.
- Espacio suficiente en el disco duro para la máquina virtual y la imagen de instalación de GNU Hurd.

## Pasos de Instalación

### 1. Descarga la Imagen de Instalación

Visita el [sitio web oficial de GNU Hurd](https://www.gnu.org/software/hurd/) y encuentra la sección de descargas. Descarga la imagen de instalación más reciente para tu arquitectura de sistema.

### 2. Crea una Nueva Máquina Virtual

Abre VirtualBox y haz clic en "Nueva" para crear una nueva máquina virtual. Sigue las instrucciones en pantalla para configurar la máquina virtual, incluyendo la asignación de memoria RAM, la creación de un disco duro virtual y la configuración del sistema operativo invitado como "Other/Unknown".

### 3. Configura la Máquina Virtual

Selecciona la máquina virtual recién creada y haz clic en "Configuración". Ajusta la configuración de la máquina virtual según tus preferencias, incluyendo la asignación de memoria, la configuración de red y la habilitación de la aceleración por hardware si es compatible con tu sistema.

### 4. Adjunta la Imagen de Instalación

Haz clic en "Almacenamiento" en la configuración de la máquina virtual y selecciona el controlador de almacenamiento "Controlador IDE Secundario" (o el que prefieras). Haz clic en el icono del disco óptico y selecciona "Seleccionar archivo de disco óptico virtual". Elige la imagen de instalación de GNU Hurd que descargaste previamente.

### 5. Inicia la Máquina Virtual

Haz clic en "Iniciar" para arrancar la máquina virtual. La imagen de instalación de GNU Hurd se cargará y comenzará el proceso de instalación.

### 6. Completa la Instalación

Sigue las instrucciones en pantalla para completar la instalación de GNU Hurd en la máquina virtual. Esto puede incluir la configuración de la zona horaria, la partición del disco duro y la creación de usuarios.

### 7. Reinicia la Máquina Virtual

Una vez que la instalación haya terminado, reinicia la máquina virtual. GNU Hurd ahora debería arrancar en la máquina virtual dentro de VirtualBox.

## Conclusiones

¡Felicidades! Has completado la instalación de GNU Hurd en una máquina virtual utilizando VirtualBox. Ahora puedes comenzar a explorar y utilizar este sistema operativo libre y colaborativo dentro de un entorno virtualizado. Si necesitas ayuda adicional, consulta la documentación oficial o únete a la comunidad en los foros de discusión y listas de correo electrónico.