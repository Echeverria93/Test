
<img alt="Terraform" src="https://cdn.rawgit.com/hashicorp/terraform-website/master/content/source/assets/images/logo-hashicorp.svg"
 width="400px" high="200xp"> 

Pre-requisitos 
==============

Descargar el paquete adecuado para su sistema operativo y arquitectura.

- Website: https://www.terraform.io

Instalación  
===========
 
 - **Linux** : Descomprimir el archivo terraform y mover la carpeta a la ruta /usr/local/bin/

Para verificar si la instalación fue correcta ejecutar el comando:

 - terraform -v 


Comandos básicos  
================

 
- **terraform init** : El comando terraform init se utiliza para inicializar una configuración de Terraform. Este es el primer comando que se debe ejecutar para cualquier configuración de Terraform.

- **terraform plan** : El siguiente comando es utilizado para deshacer la infraestructura creada con terraform.

- **terraform apply** : El comando terraform plan se utiliza para crear un plan de ejecución. 

- **terraform destroy** : El siguiente comando es utilizado para deshacer la infraestructura creada con terraform.

- **terrafrom validate** : Este comando permite validar la sintaxis de los archivos con formato .tf

- **terraform show** : El comando permite visualizar el estado actual de la infraestructura a través del archivo terraform.tfstate.

- **terraform graph** : El comando permite generar una imagen en formato png con la representación grafica de la infraestructura.

Archivos iniciales de  terraform 
================================

- **resource-provider.tf** : En el siguiente archivo se especifica el tipo de proveedor donde se crearan los recursos con terraform, entre ellos pueden ser GCP, AWS y Microsoft Azure. El archivo puede variar en su sintaxis dependiendo del proveedor.

- **resource-environment.tf** : En este archivo se definirán las diferentes variables que utilizaran los diferentes recursos que se vayan creando.

- **terraform.tfvars** : Este tipo de archivos es utilizado para manejar información delicada dentro de la infraestructura, credencial de conexión, usuarios, contraseñas y claves ssh.  

Ejemplo  
==============

- [**Terraform Reseta Base**](http://www.google.com)

<img alt="Terraform" src="https://www.paradigmadigital.com/wp-content/uploads/2015/03/CloudPlatform_HorizontalLockup.png"
 width="500px" high="200xp">

Ejemplos Recursos GCP  
=====================

- [**Cluster**](http://www.google.com)
- [**Instancias de VM**](http://www.google.com)
- [**LoadBalancer HTTPS**](http://www.google.com)
- [**PostgresQL**](http://www.google.com)
- [**Cloud SQL MYSQL 1 Generación**](http://www.google.com)
- [**Cloud SQL MYSQL 2 Generación**](http://www.google.com)
- [**Pubsub**](http://www.google.com)
- [**Storage**](http://www.google.com)
- [**Memory Store Redis**](http://www.google.com)


<p align="center"> <img alt="Terraform" src="https://www.zentagroup.com/images/logotipos/logotipo-zenta-c.svg"
 width="200px" high="200xp" align="middle"></p>
