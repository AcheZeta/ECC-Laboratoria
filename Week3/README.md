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

- **Append**. Agregar un nuevo caracter

- **Count**. Contar la cantidad de caracteres.

- **upperCased**. Convierte a mayúsculas

- **LoweCased**. Convierte a minúsculas.

### Interpolación de Strings

Puedes interpolar strings usando `\(variable)`.

Ejemplo:  
`var nombre = "Hame"`  
`var mensaje = "Hola \(nombre)"`

### Concatenación

Puedes concatenar strings usando el signo **+**

`var nombre = "Hame"`  
`var mensaje = "Hola" + nombre`

### Operadores ➕➗➖

**Operadores De asignación**
| Operadores | Descripción |
| ---------- | ----------- |
| = | Asigna un valor |
| += | Suma |
| -= | Resta |
| \*= | Multiplica |
| /= | Divide |

**Operadores Aritméticos**

| Operadores | Descripción  |
| ---------- | ------------ |
| +          | Suma Números |
| -          | Resta        |
| \*         | Multiplica   |
| /          | Divide       |

**Operadores Relacionales**

Ocupan al menos dos valores y estan acompañados de operadores de condición.
Se usan por ejemplo con `If Else`

| Operadores | Descripción       |
| ---------- | ----------------- |
| <          | Menor Qué         |
| <=         | Menor o Igual     |
| >          | Mayor qué         |
| >=         | Mayor o Igual     |
| ==         | Igual a           |
| !=         | Es diferente a    |
| ===        | Exactamente igual |

**Operadores Lógicos**

| Operadores | Descripción                                        |
| ---------- | -------------------------------------------------- |
| `&&`       | **AND** Verdadero solo si ambos son verdaderos     |
| `||`       | **OR** Verdadero si alguno es verdader             |
| `!`        | **NOT** Si es verdadero se torna falso y viseversa |

## Variables 📦

Las variables se definen con var.
No permite solo numeros, No permite palabras reservadas, Puede tener números y letras o Emojis.
Tambien se pueden definir como var:tipoDeDato por ejemplo:
_var nombre:string = "Hameyalli"_  
_var edad:Int_

## **Complex Types** 🗂️

### **Arrays:** 🖇️

Colecciones de objetos del tipo de datos.  
`var array : [String] = ["Jaz", "Steph", "Hame"]`

Métodos de Arrays:  
 **_Append:_**  
 Agregar un nuevo elemento.  
`array.append("Ana")`

**_Agregar +=:_**  
Agrega un nuevo elemento al array.  
`array += ["María"]`

**_IndexOf [i]:_**  
Conocer la posición de un elemento.  
`array[3]`

**_Count:_**  
Contar la cantidad de elementos en un array.  
`array.count`

**_Insert:_**  
Agregar un nuevo elemento en una posición especifica.  
`array.insert("Liz" at: 1)`

**_Remove:_**  
Remueve un elemento en una posición especifica.  
`array.remove(at: array.count-1)`

**_RemoveAll:_**  
Elimina todos los elementos del array dejando un arreglo vacío.  
`array.removeAll()`

**_removeFirst:_**  
Elimina el primer elemento del arreflo.  
`array.removeFirst()`

**_removeLast:_**  
Elimina el último elemento del arreflo.  
`array.removeLast()`

### Sets

Almacena valores de un mismo tipo, pero no permite insertar valores que ya existen ni almacenar Objetos.

`var array = [String] = ["Jaz", "Steph", "Hame"]`  
`var set = Set(array)`

`var numeros = [Int] = [1,3,5,8]`  
`var set = Set(numeros)`

### Tuples

Funcionan como los arreglos pero permite diferentes tipos de Datos.

`var tupla = ("Hello", 12, true, "Javascript")`

Permite acceder a los elementos mediante el indice.  
`tupla.3`  
Permite Modificar el valor al que accedes por uno del mismo tipo o casteandolo(?).  
`tupla.3 = "Swift"`

Puede usar Identificadores.

`var tupla = (saludo:"Hello", 12, true, "Javascript")`
`tupla.saludo`

### Arrays vs Sets vs Tuples

Funcionan como colecciones pero pueden emplearse para casos especificos dependiendo las necesidades.

### Dictionaries 💬

Son colecciones de datos que funciona como un diccionario Físico, usando una clave(identificador) y un valor.

`var diccionario : [String:String] = ["LB":"Laboratoria","JS":"Javascript", "Sw":"Swift"]`  
`diccionario[Sw]`  
`Mostrara: Swift`

`var numbers:[Int:String] = [1:"Uno", 2:"Dos"]`

## **Looping**: 🔁

### Rangos

Existen 4 Tipos de Rangos:

- **Cerrado** `1...5`  
  Contiene 1,2,3,4,5
- **Semicerrado** `1..<5`
  Contiene hasta antes de llegar al 5
- **Cerrado por un lado** `2...` `...2`
  Todo lo que esta antes o después del número declarado
- **Semicerrado por un lado** `..<5`
  Todo lo que esta antes número declarado

### For In

Recorre cada uno de los elementos del array o rango y requiere una variable temporal que almacene la información.

`for num in 1..10{`  
`print(num)`  
`}`

### While

Mientras un elemento sea verdadero se ejecutara el bloque.

```
num = 5
while num <= 8 {
print(num)
num +1
}
```

### Repeat While (Do While)

```
num = 5
repeat{
print(num)
num +1
} while num <= 8
```

## **Structs** 🧱

Similares a las clases, usan la palabra reservada **Struct**

Las estructuras hacen una copia del elemento para poder modificar.

```
struct PastelStruct{
    var nombre : String
    var peso : Float
    var sabor : String
}
```

## **Classes**: 📑

Se crean usando la palabra reservada Class acompañado del nombre y requiere un método inicializador.

Las clases hacen referencia al elemento.

```
class Pastel{
var nombre : String
var peso : Float
var sabor : String
init (nombre:String, peso:Float, sabor:String){
self.nombre = nombre
self.peso = peso
self.sabor = sabor }
}
```

Para crear un objeto de esa clase:

```
var pastelChoco = Pastel(nombre:"Choco", peso:1.0, sabor:"Chocolate")
```

Y accedemos al objeto mediante
`print(pastelChoco.sabor)`

Se puede modificar

```
pastelChoco.peso = 2.5)
```

## **Optionals**:

Son variables que pueden tener un valor nulo o definida.

`var nombre : String?`

El valor que le será asignado por defecto será _nil_.
Al reasignarlo como `nombre = "Hame"` en consola se mostrara como:
`Optional("Hame")`
Para forzar la asignación se usa un cierre de admiración `nombre = "Hame"!`

## Finalmente, investiga:

1.  Ciclo de vida de una app y haz un esquema de todos los estados por los que pasa un app.

**viewWillAppear:**

**viewWillLayoutSubviews:**

**viewDidLayoutSubviews:**

**viewDidAppear:**

**viewWillDisappear:**

**viewDidDisappear:**

**deinit:**

**didReceiveMemoryWarning()**

**viewWillTransition(to:with:)**

2.  Arquitectura Modelo Vista Controlador
