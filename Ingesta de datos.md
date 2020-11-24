# Ingesta de datos

En esta sección vamos a _mover_ los datos de diferentes origenes al Data Lake. En la primer parte vamos a copiar los datos de nuestro servidor on-premise al Data Lake y luego desde un Storage Account (Azure) al Data Lake 

### On-Premise --> Data Lake
Vamos a utilizar como servidor On Premise nuestra PC/Notebook donde configuramos el Integration Runtime. A continuación se detallan los pasos a realizar:

1. Descargar y descomprimir el archivo **inputs.zip** en el directorio _"C:\Laboratorio\files"_
2. Desde la interfaz de desarrollo de Data Factory nos dirigimos a Author y creamos un nuevo Pipeline
	
	<img src="images/Pipeline_city_01.png"/><br/>
	        
3. Asignamos un nombre representativo al pipeline; por ejemplo _CopyOnPrem2Azure_City_
	<img src="images/Pipeline_city_02.png"/><br/>

4. Dentro de las opciones de Actividades buscamos **Move & transform --> Copy data** y lo _arrastramos_ al area de desarrollo 
	
	<img src="images/DF_04.png"/><br/>
	
    1. L
	
		<img src="images/DF_05.png"/><br/>
		
    3. Seleccionar _Self-Hosted_
	
		<img src="images/DF_06.png"/><br/>
		
    4. Asignarle un nombre (por ejemplo _IR-OnPremise_) y crearlo
	
		<img src="images/DF_07.png"/><br/>
		
    5. Descargar el agente de Integration Runtime, opción 1 **Express setup**
	
		<img src="images/DF_08.png"/><br/>
		
	6. Instalar y validar el agente de IR
	
		<img src="images/IR_01.png"/><br/>
		
		<img src="images/IR_02.png"/><br/>
		
		<img src="images/IR_03.png"/><br/>