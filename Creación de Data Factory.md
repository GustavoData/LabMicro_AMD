# Creación de Data Factory y Configuración de Integration Runtime

1. Crear el servicio Data Factory (_Create a resourse -> Data Factory_)
    1. Basics
        1. Region: _(US) East US 2_
        2. Name: _wwiDF_
        3. Version: _V2_
		
		<img src="images/DF_01.png"/><br/>
    
	2. Git Configuration
        1. Habilitar _Configure Git later_
		
		<img src="images/DF_02.png"/><br/>
		
		<img src="images/DF_03.png"/><br/>
        
2. Ahora vamos a crear y configurar un Integration Runtime 
    1. Ir a la interfaz de Data Factory (_Data Factory -> Author & Monitor_)
	
	<img src="images/DF_04.png"/><br/>
	
    2. En la sección _Manage -> Integration Runtime_ crear un nuevo _Azure, Self-Hosted_
	
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