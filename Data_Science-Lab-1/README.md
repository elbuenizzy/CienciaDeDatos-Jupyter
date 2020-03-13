[![IBM Cloud powered][img-ibmcloud-powered]][url-ibmcloud]
# Data Science-Lab 1
Aprende en este laboratorio a crear una instancia de Watson Studio y cargar un dataset!
# Pre-requisitos
* Tener instalado [**github Desktop**](https://desktop.github.com) o [**git cli**](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).
* Tener instalado el [**CLI de IBM Cloud**](https://cloud.ibm.com/docs/cli?topic=cloud-cli-getting-started) (Si tienes problemas con este paso, da clic [**aquí**](https://cloud.ibm.com/docs/cli?topic=cloud-cli-install-ibmcloud-cli) para descargar la versión “STANDALONE”).
* Descargar el repositorio del siguiente [**enlace**](https://github.com/ibmdevelopermx/DataScience).


## 1. Crear una instancia de Cloud Object Storage.
1.	Realizamos login a IBM Cloud
http://cloud.ibm.com
2.	Seleccionamos “Catalog” (Catálogo) en el menú superior.
3.	En las categorías de la izquierda, seleccionamos “Storage”.
4.	Seleccionamos el servicio de “Object Storage”.
![](img/1.png)
5.	Seleccionamos el plan “Lite”, le damos un nombre a nuestra instancia de servicio y damos clic en “Create”.
![](img/2.png)
## 2. Crear una instancia de Watson Studio:
1.	Realizamos login a IBM Cloud
http://cloud.ibm.com
2.	Seleccionamos “Catalog” (Catálogo) en el menú superior.
3.	En las categorías de la izquierda, seleccionamos “AI”.
4.	Seleccionamos el servicio de “Watson Studio”
![](img/3.png)
5.	Una vez dentro del servicio, seleccionamos la región “Dallas”.
6.	Seleccionamos el plan “Lite”.
![](img/4.png)
7.	En la parte inferior de la página, escribir el “Nombre de la instancia del Servicio”. (Es recomendable agregar etiquetas o “tags”)
8.	En grupo de recursos, dejamos el valor “Default”. 
9.	Dar clic en “Create”.
![](img/5.png)
10.	En la pestaña que se despliegue, damos clic en “Get Started” de la pestaña “Manage”.
![](img/6.png)
## 3. Crear un proyecto:
1.	Una vez en la página principal de nuestra instancia, damos clic en “Create a project”.
![](img/7.png)
2.	Seleccionamos la opción “Create an empty project”.
![](img/8.png)
3.	Ahora, le damos un nombre al proyecto, comprobamos que nuestra instancia de “Cloud Object Storage” sea correcta y damos clic en “Create”.
![](img/9.png)
## 4. Cargar un data asset:
1.	Una vez dentro del proyecto que acabamos de crear, damos clic en “Assets”. Del lado derecho, en el apartado de “Find and add data”, seleccionamos “Browse” o arrastramos y soltamos el archivo “Telco-Customer-Churn.csv” de la carpeta “Data” del repositorio que recién clonamos.
![](img/10.png)

[url-academic]: https://my15.digitalexperience.ibm.com/b73a5759-c6a6-4033-ab6b-d9d4f9a6d65b/dxsites/151914d1-03d2-48fe-97d9-d21166848e65/home/
[img-ibmcloud-powered]: https://img.shields.io/badge/IBM%20Cloud-Powered-blue.svg
[url-ibmcloud]: https://www.ibm.com/cloud/

Y listo! Puedes continuar con el siguente lab.


Te invitamos a explorar otros talleres y manuales en el siguiente enlace de Github.
https://github.com/ibmdevelopermx
