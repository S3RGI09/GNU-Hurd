# Características de Seguridad de GNU Hurd

1. **Mach Microkernel**: Proporciona un entorno de ejecución seguro y aísla los componentes del sistema para limitar el impacto de los fallos de seguridad.

2. **Control de Acceso Basado en Capacidad**: Utiliza un modelo de control de acceso basado en capacidades para gestionar permisos a nivel de objeto.

3. **Servidores de Autenticación y Autorización**: Responsables de verificar las credenciales de los usuarios y determinar los permisos de acceso.

4. **Traducción de Llamadas a Sistema Remoto**: Permite la ejecución de servidores de llamadas a sistema de forma remota para mejorar la seguridad.

5. **Control de Acceso a Nivel de Sistema de Archivos**: Ofrece un control de acceso a nivel de sistema de archivos para establecer permisos de acceso basados en la ubicación del archivo.

6. **Políticas de Seguridad Personalizadas**: Permite la implementación de políticas de seguridad personalizadas gracias a su diseño modular y flexible.

7. **Gestión de Procesos y Espacios de Direcciones**: Proporciona una gestión robusta de procesos y espacios de direcciones para prevenir vulnerabilidades de desbordamiento de búfer y otros ataques.

8. **Auditoría de Seguridad**: Permite configurar la auditoría de seguridad para realizar un seguimiento de las actividades del sistema y detectar posibles intrusiones.

9. **Gestión de Recursos**: Proporciona mecanismos para gestionar de forma segura los recursos del sistema, como memoria y dispositivos.

10. **Compatibilidad con SELinux**: GNU Hurd es compatible con SELinux (Security-Enhanced Linux), que proporciona políticas de seguridad mejoradas a nivel de kernel.

11. **Revisión Periódica de Seguridad**: Se puede realizar una revisión periódica de seguridad para identificar posibles vulnerabilidades y mejorar la postura de seguridad del sistema.