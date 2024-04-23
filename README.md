# Fun-Algebra-Lineal-Py
Estas serán mis notas personales del curso de fundamentos de álgebra lineal


## Dimensión de un escalar, vector, matriz o tensor
Porque son importantes cada una de las dimensiones de estos objetos?

Bueno, nosotros vamos a hacer cuentas en Python y algunas veces nos va a permitir hacer estas cuentas, por más que matemáticas estas fórmulas no estén definidas, por eso tenemos que presentar especial atención a que la cuenta qué estamos haciendo sea exactamente la que queremos hacer

Imaginemos que tenemos una matriz a la izquierda y un vector a la derecha

![image](https://github.com/Nyu00/Fun-Algebra-Lineal-Py/assets/79081804/8b830cf7-a7e9-4bc9-a49b-6efa600114a4)

La operación de multiplicar estos elementos ja está definida se llama producto interno, no siempre ocurre así, en Python podríamos hacer otro tipo de operación que nos daría algo que no es lo que estábamos buscando

Importamos Numpy, y escribir nuestros números, vectores, que necesitamos para poder evaluar como funciona la dimensión en cada uno de ellos

![image](https://github.com/Nyu00/Fun-Algebra-Lineal-Py/assets/79081804/d17a36ad-d31d-430b-baa9-76e9e0e92188)

Ahora la funcion que vamos a usar es .shape, esta funciona para cada unos nuestros objetos nos devuela cuales son sus dimensiones
