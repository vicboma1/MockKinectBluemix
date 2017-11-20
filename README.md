# Mock Kinect Bluemix
Proyecto que forma parte del starter kit de la hackathon

![](https://github.com/vicboma1/MockKinectBluemix/blob/master/assets/_mockKinectNodeRED.png)


La solución mostrada apunta a una base de datos que mockea nuestro dispositivo Kinect.
Se puede visualizar en el esquema la omisión del "nodo IoT Watson" por dos nuevos componentes.
  * TimeStamp : Es un nodo que injecta llamadas. Automáticamente cuando se haga 'Deploy', lanza un pulso cada 'x' segundos.
  * All Documents : Es el nodo que representa la base de datos. Punto de salida de la información de la kinect.
  

![](https://github.com/vicboma1/MockKinectBluemix/blob/master/assets/_mockKinectNodeRED.gif)

## Pasos a seguir
1.   Copiar la ![Plantilla txt](https://raw.githubusercontent.com/vicboma1/MockKinectBluemix/master/assets/_mockKinectNodeRED.txt) con "Control A" + "Control C"

2.   Ir al menú contextual de nuestra aplicación Node-RED

3.   Importar

4.   Clipboard

5.   Import Nodes -> "Control V" para pegar la template

6.   Aceptar pulsando el botón de "Import"

7.   Configura el nodo IBM IoT Input con la Api Key de tu Universidad.

8.   Para renderizar los componentes del dashboard necesitas instalar la dependencia "node-red-dashboard"

9.   Ir al menú contextual de nuestra aplicación Node-Red -> "Manage Palette" -> Install

10.  Escribimos -> "node-red-dashboard" para Web | "node-red-dashboard-es" para mobile



@Author: [Victor Bolinches Marin](https://github.com/vicboma1)  

@Documento Principal  [CoEValencia - Hackathon 2017](https://github.com/CoEValencia/Hackathon_2017)

