# Mock Kinect Bluemix
Proyecto que forma parte del starter kit de la hackathon

![](https://github.com/vicboma1/MockKinectBluemix/blob/master/assets/mockKinectNodeRED.png)


La solución muestra un escenario con una conexión mockeada del dispositivo Kinect hacia un IoT Watson input.
Los siguientes nodos describen los siguiente:
  * Inject : Es un nodo que injecta llamadas. Automáticamente cuando se haga 'Deploy', lanza un pulso cada 'x' segundos.
  * Mock All Documentes : Es un nodo que mockea nuestra kinect.
  * IoT Watson ouput : Es el nodo publicador que lanza los mensajes a través del protocolo MQTT que usa la kinect.
  * IoT Watson input : Es un nodo IoT Watson que escucha los paquetes enviados por la kinect. consumidor.
  

![](https://github.com/vicboma1/MockKinectBluemix/blob/master/assets/_mockKinectNodeRED.gif)

## Pasos a seguir
1.   Copiar la ![Plantilla txt](https://raw.githubusercontent.com/vicboma1/MockKinectBluemix/master/assets/_mockKinectNodeRED.txt) con "Control A" + "Control C"

2.   Ir al menú contextual de nuestra aplicación Node-RED

3.   Importar

4.   Clipboard

5.   Import Nodes -> "Control V" para pegar la template

6.   Aceptar pulsando el botón de "Import"

7.   Para renderizar los componentes del dashboard necesitas instalar la dependencia "node-red-dashboard"

8.   Ir al menú contextual de nuestra aplicación Node-Red -> "Manage Palette" -> Install

9.  Escribimos -> "node-red-dashboard" para Web | "node-red-dashboard-es" para mobile



@Author: [Victor Bolinches Marin](https://github.com/vicboma1)  

@Documento Principal [CoEValencia - Hackathon 2017](https://goo.gl/vmuVXH)

