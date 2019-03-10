
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



iniciar Terraform   
=================

1. Crear  carpeta que contendra los archivos terraform para su ejecucion.
2. Crear los archivos principales llamados resource-provider.tf, resource-environment.tf y terraform.tfvars.
3. Ejecutar el comando terraform init para detectar el tipo de proveedor ingresado en el archivo resource-provider.tf y descargar  las dependencias del proveedor.
 
<img alt="Terraform" src="https://www.zentagroup.com/images/logotipos/logotipo-zenta-c.svg"
 width="200px" high="200xp" align="middle">

<p align="center"> <img alt="Terraform" src="https://github.com/Echeverria93/Test/blob/master/test.png"
 width="200px" high="200xp" align="middle"></p>
