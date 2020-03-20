# Ventilador
VENTILADOR  PULMONAR    
FABRICACION DE EMERGENCIA

En estas fechas en situación de pandemia global es preciso obtener maquinas que auxilien la respiración,  ya que por la cantidad de afectados , la disponibilidad de los hospitales es insuficiente tal como se ha visto en Italia , país que nos precede en la situación.

A través de Internet se ha formado un equipo de voluntarios con capacidad de obtener piezas realizadas con impresoras 3D
para efectuar unos aparatos de ventilación de emergencia.

Incluyo a continuación la información del prototipo para que sea comprobada por personas mas conocedoras del funcionamiento de estas maquinas .

Los grupos de componentes serian :

1-  BOLSA DE SILICONA   
2-  BRAZOS DE COMPRESION EXTERNA DE LA BOLSA    
3-  EQUIPO DE CONTROL CON ARDUINO

![Image 1](/PICS/respirador1.png)

BOLSA DE SILCONA

La bolsa se puede obtener previa fabricación de un molde fabricado con material de plástico impreso  .
El molde seria formado por dos piezas desmontables  para
la forma exterior y un núcleo interior.
El material que formaría la bolsa seria Silicona de dos componentes de uso medico no toxica

![Image 2](/PICS/respirador2.png)

![Image 3](/PICS/Bolsa.png)

BRAZOS DE COMPRESION    

El accionamiento de los brazos de compresión se realiza mediante 
el giro de un piñón , accionado por un motor paso a paso.
Este sistema invierte el sentido de un carro respecto al otro
Y permite el movimiento cíclico de apertura y cierre de los brazos

![Image 4](/PICS/Movimiento1.png)  

![Image 5](/PICS/Movimiento2.png?raw=true)  

![Image 6](/PICS/Movimiento3.png)

El guiado de cada carro se realiza con columnas y rodamientos lineales , que al igual que el motor paso a paso son un material estándar de las maquinas de impresión y por tanto fácil de obtener. Los rodamientos pueden ser sustituidos
por casquillos de teflón 10-19-20  

SISTEMA DE CONTROL

![Image 7](/PICS/Control.png)

El sistema de control de Arduino  programado con leguaje “C” con la placa Mega 2560 proporcionaría el control de los movimientos de los brazos mediante tres potenciómetros.

- Potenciómetro de ajuste de la velocidad de los brazos   
- Potenciómetro de ajuste de la carrera de los brazos 
- Potenciómetro de ajuste de tiempo de ciclo completo aspiración + expiración 

![Image 8](/PICS/dimensiones.png)

 Las dimensiones del equipo son  400 x 380  altura  340 mm

RESUMEN 

Nuestro compromiso en el proyecto consistirá en la realización de un prototipo con el mecanismo expuesto . La mascara,  la válvula PEEP   y las válvulas  de entrada de aire & oxigeno, son  las utilizadas en los dispositivos de reanimación AMBU y tendrían que ser acoplados a los manguitos correspondientes.

Este proyecto esta destinado a personas con disponibilidad de una impresora 3D y conocimientos del sistema Arduino de control.

Para personas que desconozcan el tema de control con Arduino , sigo con un segundo proyecto en que los carros de empuje son accionados por un motor de c,c, y mecanismo de biela –manivela . Esta opción mantiene a los elementos básicos del proyecto actual  dejando libre la opción de ataque del mecanismo del motor y las bielas.

