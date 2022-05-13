<table border=0 width=100%>
  <tr>
    <td width=30%>
      <img width="300px" height="80px" src="https://github.com/GrupoZaid/GrupoZaid/blob/main/Logo.png" align="right" alt="Logo Ibero" />
    </td>
    <td width=70%>
      <h3 align="left">Grupo Zaid</h3>
      <p align="left">Dirección de Informática</p>   
    </td>      
  </tr>
</table>

<a name="inicio"></a>
# Data Access

## Tabla de contenido
1. [Proyecto](#inicio)
2. [Descripción](#descripcion)
3. [Dependencias](#dependencias)
4. [Especificaciones](#especificaciones)
5. [Pre-Requisitos](#pre-requisitos)
6. [Ejemplos](#ejemplos)
7. [Derechos](#derechos)
8. [Autores](#autores)

<a name="descripcion"></a>
## Librería para acceso a datos:
> _- Conexiónes por medio de Sql Server._  
> _- Conexiónes por medio de Sybase._  
> _- Conexiónes por medio Ole DB._  

<a name="dependencias"></a>
## Dependencias:
#### Nombre archivo: DataAccess.dll
#### Este componente depende de los siguientes ensamblados:
* [1](https://example.com): Version 1.0.0.0
* [2](https://example.com): Version 1.0.0.0
* [3](https://example.com): Version 1.0.0.0

#### Los siguientes ensamblados dependen de este componente:
* [1](https://example.com): Version 1.0.0.0
* [2](https://example.com): Version 1.0.0.0
* [3](https://example.com): Version 1.0.0.0

<a name="especificaciones"></a>
## Especificaciones:
###### `Lenguaje de programación:` Visual Basic .NET
###### `Framework:` .NET Framework 4.8
###### `IDE:` Microsoft Visual Studio 2019

<a name="pre-requisitos"></a>
## Pre-Requisitos:
###### `1:` 
###### `2:` 
###### `3:` 

<a name="ejemplos"></a>
## Ejemplos:
Visual Basic .Net:
```vb
If Venciminento = TipoVencimiento.Obligatorio Then
	If Validar() Then
		If Not ValidarCodigo() Then Exit Sub
	Else
		Exit Sub
	End If
End If
Cerrar(DialogResult.Yes)
```
C# .Net:
```csharp
if (Venciminento == TipoVencimiento.Obligatorio)
{
	if (Validar())
	{
		if (!ValidarCodigo())
			return;
	}
	else
	{
		return;
	}
}
Cerrar(DialogResult.Yes);
```
-----
<a name="derechos"></a>
*Copyright © Universidad Iberoamericana 2014-2022.*

<a name="autores"></a>
*Carlos Héctor Díaz González (SoftwareOne).*
