# Funciones Strings


## Texto Portapapeles

 Obtiene el texto copiado del portapapeles


Para crear de clic:  1. Funciones Strings -->  2. Texto Portapapeles

**`Funci�n:`** `textclipboard`


---


## Indice de caracter

 obtiene el indice de valor en la cadena


Para crear de clic:  1. Funciones Strings -->  2. Indice de caracter --> 3. indicar Cadena, Value

**`Funci�n:`** `charindex`

**`Par�metros :`** 

Cadena: valor 
Value: valor 


---


## Comillas

 Asigna doble comillas al texto


Para crear de clic:  1. Funciones Strings -->  2. Comillas --> 3. indicar Value

**`Funci�n:`** `comillas`

**`Par�metros :`** 

Value: valor 


---


## Cantidad de caracter

 Cuenta las veces que se repite el valor


Para crear de clic:  1. Funciones Strings -->  2. Cantidad de caracter --> 3. indicar cadena, value

**`Funci�n:`** `countchar`

**`Par�metros :`** 

cadena: valor 
value: valor 


---


## Split to variables

 Rompe la cadena por el delimitador y cada indice lo agrega a las variables columna(#)


Para crear de clic:  1. Funciones Strings -->  2. Split to variables --> 3. indicar Value, Delimiter

**`Funci�n:`** `splitlist`

**`Par�metros :`** 

Value: valor 
Delimiter: valor 


---


## Invertir Cadena

 Invierte cadena de texto por delimitador


Para crear de clic:  1. Funciones Strings -->  2. Invertir Cadena --> 3. indicar Value, Delimiter

**`Funci�n:`** `reversewords`

**`Par�metros :`** 

Value: valor 
Delimiter: valor 


---


## Extraer Ultima Linea texto

 Obtiene el valor del texto por la ultima linea en el texto


Para crear de clic:  1. Funciones Strings -->  2. Extraer Ultima Linea texto --> 3. indicar Value, Line

**`Funci�n:`** `extractlastline`

**`Par�metros :`** 

Value: valor 
Line: valor 


---


## Extraer Linea texto

 Obtiene el valor del texto por linea en el texto


Para crear de clic:  1. Funciones Strings -->  2. Extraer Linea texto --> 3. indicar Value, Line

**`Funci�n:`** `extractline`

**`Par�metros :`** 

Value: valor 
Line: valor 


---


## Extraer Texto

 Obtiene el valor del texto por el delimitador y usa key como referencia para romper la cadena resultante


Para crear de clic:  1. Funciones Strings -->  2. Extraer Texto --> 3. indicar Value, Delimiter, Key

**`Funci�n:`** `extractext`

**`Par�metros :`** 

Value: valor 
Delimiter: valor 
Key: valor 


---


## Extraer LastIndex Expresion regular

Se extrae las palabras por expresion regular


Para crear de clic:  1. Funciones Strings -->  2. Extraer LastIndex Expresion regular --> 3. indicar value:valor, key:^[0-9]+$

**`classname:`** `ApiUtils.GetLastIndexWordsExp`

```csharp
call('{
    "classname":"ApiUtils.GetLastIndexWordsExp",
    value:
    {
        "value":"",
        "key":"^
        [
            0-9
        ]+$"
    }
}')
```

---


## Split

 Obtiene el valor del arreglo por el delimitador


Para crear de clic:  1. Funciones Strings -->  2. Split --> 3. indicar Value, Delimiter, Index

**`Funci�n:`** `split`

**`Par�metros :`** 

Value: valor 
Delimiter: valor 
Index: valor 


---


## Extraer Expresion regular

Se extrae las palabras por expresion regular


Para crear de clic:  1. Funciones Strings -->  2. Extraer Expresion regular --> 3. indicar value:valor, key:^[0-9]+$

**`classname:`** `ApiUtils.GetWordsExp`

```csharp
call('{
    "classname":"ApiUtils.GetWordsExp",
    value:
    {
        "value":"",
        "key":"^
        [
            0-9
        ]+$"
    }
}')
```

---


## Extraer Index Expresion regular

Se extrae las palabras por expresion regular


Para crear de clic:  1. Funciones Strings -->  2. Extraer Index Expresion regular --> 3. indicar value:valor, key:^[0-9]+$

**`classname:`** `ApiUtils.GetIndexWordsExp`

```csharp
call('{
    "classname":"ApiUtils.GetIndexWordsExp",
    value:
    {
        "value":"",
        "key":"^
        [
            0-9
        ]+$"
    }
}')
```

---


## quitar espacios




Para crear de clic:  1. Funciones Strings -->  2. quitar espacios

**`Funci�n:`** `trim`


---


## -Obtener ruta local

Obtiene la ruta local de procesamiento


Para crear de clic:  1. Funciones Strings -->  2. -Obtener ruta local --> 3. indicar text:valor, key:

**`classname:`** `ApiShared.GetCurrentDirectory`

```csharp
call('{
    "classname":"ApiShared.GetCurrentDirectory",
    value:
    {
        "text":"",
        "key":""
    }
}')
```

---


## concat




Para crear de clic:  1. Funciones Strings -->  2. concat

**`Funci�n:`** `concat`


---


## format




Para crear de clic:  1. Funciones Strings -->  2. format

**`Funci�n:`** `format`


---


## Length




Para crear de clic:  1. Funciones Strings -->  2. Length

**`Funci�n:`** `length`


---


## lowercase




Para crear de clic:  1. Funciones Strings -->  2. lowercase

**`Funci�n:`** `lowercase`


---


## Text Containt




Para crear de clic:  1. Funciones Strings -->  2. Text Containt

**`Funci�n:`** `pos`


---


## Reemplazar

 Remplaza los valores de texto en la cadena


Para crear de clic:  1. Funciones Strings -->  2. Reemplazar --> 3. indicar Value, Old, New

**`Funci�n:`** `replace`

**`Par�metros :`** 

Value: valor 
Old: valor 
New: valor 


---


## uppercase




Para crear de clic:  1. Funciones Strings -->  2. uppercase

**`Funci�n:`** `uppercase`


---


## loadtext




Para crear de clic:  1. Funciones Strings -->  2. loadtext

**`Funci�n:`** `loadtext`


---


## Quitar salto de linea

 elimina los saltos de linea #13


Para crear de clic:  1. Funciones Strings -->  2. Quitar salto de linea --> 3. indicar value

**`Funci�n:`** `quitarsaltopagina`

**`Par�metros :`** 

value: valor 


---


