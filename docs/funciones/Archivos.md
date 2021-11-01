# Archivos


## Propiedad Archivos Directorios

Scanea directorio y retorna la lista de archivos con la propiedad en formato JSON


Para crear de clic:  1. Archivos -->  2. Propiedad Archivos Directorios --> 3. indicar directorio:valor, parametros:valor, extension:*

**`classname:`** `ApiFile.GetPropertiDirectory`

```csharp
call('{
    "classname":"ApiFile.GetPropertiDirectory",
    value:
    {
        "directorio":"",
        "parametros":"",
        "extension":"*"
    }
}')
```

---


## Crear Directorio

 Crea directorio windows


Para crear de clic:  1. Archivos -->  2. Crear Directorio --> 3. indicar Directorio

**`Funci�n:`** `createdir`

**`Par�metros :`** 

Directorio: valor 


---


## Propiedad Archivo

Lista la propiedad de un archivo formato JSON


Para crear de clic:  1. Archivos -->  2. Propiedad Archivo --> 3. indicar archivo:valor, parametros:

**`classname:`** `ApiFile.GetPropertieFile`

```csharp
call('{
    "classname":"ApiFile.GetPropertieFile",
    value:
    {
        "archivo":"",
        "parametros":""
    }
}')
```

---


## Eliminar Archivo

 Elimina archivo si existe


Para crear de clic:  1. Archivos -->  2. Eliminar Archivo --> 3. indicar Archivo

**`Funci�n:`** `deletefile`

**`Par�metros :`** 

Archivo: valor 


---


## Directorio Actual

Obtiene el directorio actual


Para crear de clic:  1. Archivos -->  2. Directorio Actual --> 3. indicar Max_params

**`Funci�n:`** `getdir`

**`Par�metros :`** 

Max_params: valor 


---


## Propiedades Archivos Directorios

Scanea directorio y retorna la lista de archivos con las propiedades en formato JSON


Para crear de clic:  1. Archivos -->  2. Propiedades Archivos Directorios --> 3. indicar directorio:valor, extension:*

**`classname:`** `ApiFile.GetPropertiesDirectory`

```csharp
call('{
    "classname":"ApiFile.GetPropertiesDirectory",
    value:
    {
        "directorio":"",
        "extension":"*"
    }
}')
```

---


## Copiar

 Copia archivo de directorio a directorio


Para crear de clic:  1. Archivos -->  2. Copiar --> 3. indicar Archivo, Archivo

**`Funci�n:`** `copyfile`

**`Par�metros :`** 

Archivo: valor 
Archivo: valor 


---


## Listar Archivos Info

Scanea directorio y retorna archivos en formato JSON


Para crear de clic:  1. Archivos -->  2. Listar Archivos Info --> 3. indicar directorio:valor, extension:*

**`classname:`** `ApiFile.GetDataFiles`

```csharp
call('{
    "classname":"ApiFile.GetDataFiles",
    value:
    {
        "directorio":"",
        "extension":"*"
    }
}')
```

---


## Existe Directorio

 Verifica si existe el directorio


Para crear de clic:  1. Archivos -->  2. Existe Directorio --> 3. indicar Directorio

**`Funci�n:`** `direxists`

**`Par�metros :`** 

Directorio: valor 


---


## Listar Directorios Info

Scanea directorio y retorna directorios en formato JSON


Para crear de clic:  1. Archivos -->  2. Listar Directorios Info --> 3. indicar directorio:

**`classname:`** `ApiFile.GetDataDirectory`

```csharp
call('{
    "classname":"ApiFile.GetDataDirectory",
    value:
    {
        "directorio":""
    }
}')
```

---


## Existe Archivo

 Verifica si existe el archivo


Para crear de clic:  1. Archivos -->  2. Existe Archivo --> 3. indicar Archivo

**`Funci�n:`** `fileexists`

**`Par�metros :`** 

Archivo: valor 


---


## Eliminar Directorio

 Elimina el directorio


Para crear de clic:  1. Archivos -->  2. Eliminar Directorio --> 3. indicar Directorio

**`Funci�n:`** `removedir`

**`Par�metros :`** 

Directorio: valor 


---


## Renombrar Archivo

 Renombra archivo


Para crear de clic:  1. Archivos -->  2. Renombrar Archivo --> 3. indicar Archivo

**`Funci�n:`** `renamefile`

**`Par�metros :`** 

Archivo: valor 


---


## Ultimo Archivo

 Muestra el �ltimo archivo de un directorio


Para crear de clic:  1. Archivos -->  2. Ultimo Archivo --> 3. indicar Directorio, Extension

**`Funci�n:`** `lastfile`

**`Par�metros :`** 

Directorio: valor 
Extension: valor 


---


## Limpiar Directorio

 Limpiar todos los archivos del directorio segun la extension o filtro


Para crear de clic:  1. Archivos -->  2. Limpiar Directorio --> 3. indicar Directorio, Extension

**`Funci�n:`** `cleandir`

**`Par�metros :`** 

Directorio: valor 
Extension: valor 


---


## Primer Archivo

 Muestra el primer archivo de un directorio


Para crear de clic:  1. Archivos -->  2. Primer Archivo --> 3. indicar Directorio, Extension

**`Funci�n:`** `firstfile`

**`Par�metros :`** 

Directorio: valor 
Extension: valor 


---


## Archivo to Base64

 Convierte en base64 el archivo


Para crear de clic:  1. Archivos -->  2. Archivo to Base64 --> 3. indicar Archivo

**`Funci�n:`** `tobase64`

**`Par�metros :`** 

Archivo: valor 


---


## Archivo por nombre

 Busca en el directorio el archivo que contenga el nombre dado


Para crear de clic:  1. Archivos -->  2. Archivo por nombre --> 3. indicar Directorio, NombreArchivo, Extension

**`Funci�n:`** `firstfilebyname`

**`Par�metros :`** 

Directorio: valor 
NombreArchivo: valor 
Extension: valor 


---


## Imprimir archivo

Se envia a imprimir el archivo a impresora por default


Para crear de clic:  1. Archivos -->  2. Imprimir archivo --> 3. indicar archivorigen:

**`classname:`** `ApiUtils.PrinterFile`

```csharp
call('{
    "classname":"ApiUtils.PrinterFile",
    value:
    {
        "archivorigen":""
    }
}')
```

---


## Base64 to Archivo

 conviente en archivo binario el base64


Para crear de clic:  1. Archivos -->  2. Base64 to Archivo --> 3. indicar Base64, Archivo

**`Funci�n:`** `base64to`

**`Par�metros :`** 

Base64: valor 
Archivo: valor 


---


## Propiedades Archivo

Lista todas las propiedades de un archivo formato JSON


Para crear de clic:  1. Archivos -->  2. Propiedades Archivo --> 3. indicar archivo:

**`classname:`** `ApiFile.GetPropertiesFile`

```csharp
call('{
    "classname":"ApiFile.GetPropertiesFile",
    value:
    {
        "archivo":""
    }
}')
```

---


## Append data

 Adiciona texto a archivo


Para crear de clic:  1. Archivos -->  2. Append data --> 3. indicar Archivo, Texto

**`Funci�n:`** `appendfile`

**`Par�metros :`** 

Archivo: valor 
Texto: valor 


---


## Cargar Texto Archivo

 Carga en texto el contenido del archivo


Para crear de clic:  1. Archivos -->  2. Cargar Texto Archivo --> 3. indicar Archivo

**`Funci�n:`** `loadtext`

**`Par�metros :`** 

Archivo: valor 


---


## Obtener Nombre Archivo

 Obtiene el nombre del proceso en ejecuci�n


Para crear de clic:  1. Archivos -->  2. Obtener Nombre Archivo --> 3. indicar Archivo

**`Funci�n:`** `filename`

**`Par�metros :`** 

Archivo: valor 


---


## Remover Directorio

 Remueve directorio y todos sus elementos


Para crear de clic:  1. Archivos -->  2. Remover Directorio --> 3. indicar Directorio

**`Funci�n:`** `removedirectory`

**`Par�metros :`** 

Directorio: valor 


---


## Xml To Csv

Convierte archivo XML a CSV


Para crear de clic:  1. Archivos -->  2. Xml To Csv --> 3. indicar directorio:valor, archivodestino:

**`classname:`** `ApiFile.XmlsToCsv`

```csharp
call('{
    "classname":"ApiFile.XmlsToCsv",
    value:
    {
        "directorio":"",
        "archivodestino":""
    }
}')
```

---


## Directorio Ejecuci�n

 Obtiene el directorio del proceso en ejecuci�n


Para crear de clic:  1. Archivos -->  2. Directorio Ejecuci�n --> 3. indicar Directorio

**`Funci�n:`** `filepath`

**`Par�metros :`** 

Directorio: valor 


---


## Mover Archivo

 Corta y pega el archivo entre directorios


Para crear de clic:  1. Archivos -->  2. Mover Archivo --> 3. indicar Archivo, Archivo

**`Funci�n:`** `movefile`

**`Par�metros :`** 

Archivo: valor 
Archivo: valor 


---


## Cargar Archivo




Para crear de clic:  1. Archivos -->  2. Cargar Archivo


---


## Listar Archivos




Para crear de clic:  1. Archivos -->  2. Listar Archivos

**`Funci�n:`** `listararchivos`


---


## Leer




Para crear de clic:  1. Archivos -->  2. Leer


---


## Buscar contenido




Para crear de clic:  1. Archivos -->  2. Buscar contenido


---


## Abrir




Para crear de clic:  1. Archivos -->  2. Abrir


---


## Reemplazar Contenido




Para crear de clic:  1. Archivos -->  2. Reemplazar Contenido


---


