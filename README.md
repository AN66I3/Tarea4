# Tarea4
## Variables y comparación de Tareas
## Task 1
### Assign a variable with each datatypes covered in the previous workshop. The datatypes previous covered were “Boolean”, “String”, “Int”
#### Notes:
#### $BoolanVar = $True
#### $StringVar = "This is a string"
#### $IntVar = 42
### En PowerShell para definir una variable usaremos como primer carácter el símbolo de dólar($), y luego daremos un nombre
### En este ejercicio ejecutaremos  los siguientes Scripts, que son archivos de texto creamos 3 variables y el resultado es visualizado en un archivo con extensión (.ps)


# Task 2
## List all variables currently loaded in to memory.
### The noun within the cmdlet is “Variable”
### Notes:
#### Get-Variable
#### El siguiente comando nos permite visualizar las variables existentes creadas en el paso 1



# Task 3
## Multiple two Int variables together
### PowerShell can perform basic maths operators, such as “+”, “-“ and “*”
### Notes:
#### $IntVar1 = 4
#### $IntVar2 = 10
#### $IntVar1 * $IntVar2
#### En la siguiente tarea realizamos una multiplicación básica mediante la asignación
#### de valores a las variables, y podemos obtener un resultado (40)

# Task 4
## First declare two Int variables. Then divided the first
### variable by the second and assign the result to a
### variable named $VariableResult
##### The easiest way to do this is within the Integrated Scripting Environment
##### (ISE) using multiple lines of code
##### Notes:
#### $IntVar3 = 10
#### $IntVar4 = 2

#### $VariableResult = $IntVar3 / $IntVar4
#### Vemos que también podemos realizar operaciones matemáticas y estos resultados asigarlos
#### recoja la información y la almacene

# Task 5
## Typecast a Variable as a “String” and assign it a value
## of 5
## Remember to normal brackets [] rather than curly brackets {} when
#### typecasting a variable
#### Notes:
#### [String]$TypecastVar = 5
#### En PowerShell realizamos la asignación de tipo de dato con los corchetes, en este caso será tipo String
#### vemos que al realizar una operación de multiplicación el resultado no es 50, sino 10 veces 5, ya que el 5 está definido como  String.
