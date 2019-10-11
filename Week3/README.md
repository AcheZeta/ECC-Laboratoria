# Week 3: Prework III

### Preguntas de Prework

\*\* Todos los ejercicios de código háganlos en un Swift Playground o en http://online.swiftplayground.run/ si no tienes Mac. \*\*

1. Si tienes Mac, abre el libro **App Development with Swift** dentro de la aplicación de Libros y realiza los ejercicios siguientes:

   1. **Lección 2.3: Structures**
   2. **Lección 2.5: Classes, Inheritance**
   3. **Lección 2.5: Collections**
   4. **Lección 2.6: Loops**
   5. **Lección 3.1: Optionals**
   6. **Lección 3.3: Guard**

2. Si no tienes Mac, entra a https://www.hackingwithswift.com/sixty y realiza los siguientes ejercicios:

## Tipos de Datos ✍️

| NOMBRE | TIPO                                |
| ------ | ----------------------------------- |
| INT    | Entero                              |
| DOUBLE | Flotante 64 bits hasta 15 decimales |
| FLOAT  | Flotante 32 bits hasta 15 decimales |
| BOOL   | Booleano                            |
| STRING | Cadena de caracteres                |

Puedes conocer el tipo de dato usando:
`type(of: variable)`

### Comentarios 📝

`// Doble Diagonal para una línea`

`/* Comentarios`  
`multilínea /*`

### Unicode & Emojis 🔮

Las variables pueden contener emojis y unicodes.

`var omega = "\u{03A9}"`  
`var pulpo = "🐙"`

Por defecto la variable pulpo es un string, pero se debe tratar como caracter asignandole el tipo ya que ocupa menos espacio en memoria.

`var pulpo:Character = "🐙"`

### Métodos de String

- Append. Agregar un nuevo caracter

- Count. Contar la cantidad de caracteres.

- Append. Agregar un nuevo caracter.

- upperCased. Convierte a mayúsculas

- LoweCased. Convierte a minúsculas.

### Interpolación de Strings

Puedes interpolar strings usando `\(variable)`.

Ejemplo:  
`var nombre = "Hame"`  
`var mensaje = "Hola \(nombre)"`

### Concatenación

Puedes concatenar strings usando el signo **+**

`var nombre = "Hame"`  
`var mensaje = "Hola" + nombre`

### Operadores

- *=* Asigna.
- *+=* Suma
- *-=* Resta
- *\** Multiplica
- */=* Divide

Operadores Aritméticos

- *+* Suma Enteros (Strings se concatenan)
- *-* Resta
- *\** Multiplicacion
- */* Division 

Operadores Relacionales

- *If* Condicional
- **

## Variables

Las variables se definen con var.
No permite solo numeros, No permite palabras reservadas, Puede tener números y letras o Emojis.
Tambien se pueden definir como var:tipoDeDato por ejemplo:
_var nombre:string = "Hameyalli"_  
_var edad:Int_

## **Complex Types**

1. Arrays
2. Set
3. Tuples
4. Arrays vs Sets vs Tuples
5. Dictionaries

## **Looping**:

1. Todos los ejercicios

## **Structs**

1. Todos los ejercicios

## **Classes**:

1. Todos los ejercicios

## **Optionals**:

1. Todos los ejercicios

## Finalmente, investiga:

1.  Ciclo de vida de una app y haz un esquema de todos los estados por los que pasa un app.
2.  Arquitectura Modelo Vista Controlador

    | NOMBRE | TIPO                                |
    | ------ | ----------------------------------- |
    | INT    | Entero                              |
    | DOUBLE | Flotante 64 bits hasta 15 decimales |
    | FLOAT  | Flotante 32 bits hasta 15 decimales |
    | BOOL   | Booleano                            |
    | STRING | Cadena de caracteres                |
