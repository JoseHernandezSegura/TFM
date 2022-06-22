# DISEÑO DE UN SISTEMAS DE DETECCION DE INTRUSIONES BASADO EN MODELOS DE INTELIGENCIA ARTIFICIAL EXPLICATIVA 
## Trabajo Fin de Máster Universitario en Ingeniería de Redes y Servicios Telemáticos  
Autor: Jose Hernández Segura Tutor: Xavier Larriva Novo
 
## Despliegue del proyecto:

Antes de abrir cualquier archivo del proyecto sera necesario instalar una serie de librerias de Pyton para ello se ejecutaran los siguientes comandos dentro del entorno en el que se haya decidido realizar el despliegue, en nuestro caso se trada de anaconda por lo que ejecutariamos los siguientes comandos en la consola Conda:

``pip install imblearn``

``pip install sklearn``

``pip install shap``

``pip install lime`` 

Librerias como pandas, numpy o matplotlib ya vienen incluidas con anaconda.
 
 El segundo paso sería descargar el dataset CIC-IDS 2017 que se puede encontrar en el siguiente enlace: http://205.174.165.80/CICDataset/CIC-IDS-2017/
 
 Una vez ya se tenga todo instalado y preparado se debera descargar primero el notebook llamado AjustadoDataset y realizar los siguientes pasos:
* Cambiar la ruta donde se encuentra el daset CICIDS 2017.
* Ejecutar todo el Notebook.
* Guardar el csv que se obtiene como salida donde se desee.

Como último paso deberemos descargar o el archivo llamado ClasificacionBinaria o el de ClasificacionMulticase antes de ejecutar dichos archivos es muy importante habilitar la siguiente opción en el notebook ya que si no como se puede comprobar cuando observamos dichos archivos en linea no se mostrarn muchas de las graficas de SHAP Y DE LIME, se adjunta una captura de pantalla de la opción a activar en Jupyter Notebook:

![image](https://user-images.githubusercontent.com/95879899/175115121-59724bf8-441f-44ad-8771-64114d200704.png)

