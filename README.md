
ISARDVDI: Virtualización de escritorio.

Autor: Mario García Salado.

Introducción:

Las empresas gastan tiempo, dinero y recursos en preparar dispositivos portátiles o sobremesa para sus empleados. Si hay trabajadores en remoto y estos necesitan cambiar su equipo por cualquier tipo de defecto, deficiencia u obsolescencia, dependiendo de donde vivan, la empresa puede tardar días o semanas en enviar el equipo sustituto y pasará todo ese tiempo hasta que el empleado pueda volver a realizar sus funciones en su puesto de trabajo.

Todo esto tiene una solución, isardVDI.


Finalidad:

Con esta plataforma, pretendemos no solo agilizar los procesos de incorporación del empleado a su puesto de trabajo, sino eliminar el problema de raíz. Solo será necesario un dispositivo electrónico (móvil, tablet, portátil o sobremesa de bajos recursos) y una buena conexión a internet.
De esta manera, cuando el empleado no tenga su equipo a disposición y ponga al tanto a su superior de la situación, inmediatamente se le habilitará un escritorio virtual a partir de una plantilla pensada en concreto para el departamento al que pertenezca. Todo a través de la web.


Medios hardware y software a utilizar:

El hardware empleado para este proyecto será emulado en una máquina virtual desde mi propio PC-sobremesa, a modo de servidor, de donde se usarán los recursos para construir isardVDI.
Para la demostración final, usaremos un teléfono móvil, un ordenador portátil y un PC de sobremesa.

Respecto al software, utilizaremos la plataforma isardVDI, un entorno de virtualización de escritorios y servidores en el cloud. Esta plataforma la componen:

- Docker para empaquetar el proyecto.

- Docker-compose para ejecutar aplicaciones docker.

- Apache Guacamole como administrador web de las máquinas y la infraestructura de la empresa

- Grafana para tener un control y administración del análisis de uso de los recursos del hardware.

- openVPN para tener una red segura y privada.


Planificación:


Este proyecto tendrá una duración aproximada de un mes y se organizará de la siguiente manera:

-	Instalación de los servicios y programas.

-	Configuración de la plataforma

-	Creación y configuración de la estructura de la empresa.

-	Creación y configuración de la VPN de la empresa

-	Organización de las plantillas por departamento

-	Optimización de los recursos para cada plantilla.

-	Demo en los diferentes dispositivos:

	1.- PC-sobremesa
	2.- Portátil
	3.- Móvil




