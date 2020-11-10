# LabMicro

A continuación se detallan los pasos a realizar:

1. Crear un nuevo grupo de recursos (_Create a resourse -> Resource Group_)
    1. Resource group: _LabAzure_WWI_
    2. Region: _(US) East US 2_

**A partir de ahora todos los servicios que se den de alta se deben asignar al grupo de recurso creado**

2. Crear el data lake (_Create a resourse -> Storage account_)
    1. Baics
        1. Storage account name: _wwwdatalakeXX_ (donde XX se reemplaza por un numero)
        2. Location: _(US) East US 2_
        3. Performance: _Standard_
        4. Account kind: _StorageV2_
        5. Replication: _LRS_
     2. Advanced
        1. Data Lake Storage Gen2: _Enabled_
