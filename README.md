# Coder-trabajo

Opté por la configuración de **Red Interna** debido a que para este ejercicio no resultaba imprescindible conectar la máquina virtual a Internet. Si bien el modo **NAT** ofrece acceso a la red externa sin permitir tráfico entrante no solicitado, la conexión a la red resultaba innecesaria ya que el objetivo se limitaba a configurar el sistema en sí. Del mismo modo, descarté la opción de **Adaptador Puente** porque, además de brindar acceso a la red, expone la máquina virtual como un dispositivo visible dentro de la red local, comprometiendo el aislamiento del laboratorio sin aportar ninguna ventaja técnica. La modalidad de Red Interna resguarda el equipo anfitrión (*host*) al mantenerlo completamente separado de la máquina virtual, lo que habilita un entorno de pruebas seguro donde cualquier falla no afectará al sistema físico.
![image alt](https://github.com/melgarejomartin2006-create/Coder-trabajo1/blob/56afc883d431099e35bddfe93dfc57d17c9934d1/Captura%201.jpeg)

Captura de cuentas de usuario: Es importante tener una cuenta de usuario sin permisos de administrador para el uso cotidiano, eso incrementa la seguridad al no permitir hacer modificaciones que puedan acarrear un peligro a la maquina
 ![image alt](https://github.com/melgarejomartin2006-create/Coder-trabajo1/blob/8f6de5f4d225d0049a8a915793c81c618fecc12d/Captura%206.jpeg)

**Permisos de archivos:** Es indispensable asignar los permisos adecuados a la información sensible, garantizando que usuarios no autorizados no puedan acceder ni modificar los archivos, o que solo puedan hacerlo con la autorización explícita del propietario del recurso.
 ![image alt](https://github.com/melgarejomartin2006-create/Coder-trabajo1/blob/08135517a60af4828c79ab6204df30714d3738b0/Captura%202.jpeg)

**Actualización de paquetes en Linux:** Al igual que en Windows, mantener los paquetes del sistema al día es clave para corregir fallas y vulnerabilidades de seguridad. En entornos Linux, este procedimiento se lleva a cabo ejecutando el comando `sudo apt update`.
 ![image alt](https://github.com/melgarejomartin2006-create/Coder-trabajo1/blob/9de50a43481522795ad8c81f08e17c64c63ce797/Captura%203.jpeg)

**Captura del Snapshot:** Contar con una instantánea (*Snapshot*) guardada tras realizar el bastionado (*hardening*) inicial proporciona un punto de restauración seguro. Si surge algún inconveniente durante configuraciones posteriores, es posible revertir la máquina virtual a este estado limpio en cualquier momento, permitiendo experimentar de manera segura.
 ![image alt](https://github.com/melgarejomartin2006-create/Coder-trabajo1/blob/9de50a43481522795ad8c81f08e17c64c63ce797/Captura%204.jpeg)
