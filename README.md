# PG2-P1
# Práctica - Calculadora con POO

En esta práctica se implementa una calculadora en Python utilizando los principios de Programación Orientada a Objetos (POO), como **abstracción**, **encapsulamiento** y **herencia**.

Se incluyen dos tipos de calculadoras:

- Una calculadora estándar que permite realizar operaciones aritméticas básicas.
- Una calculadora factorial que hereda de la clase base y extiende su funcionalidad.

## Preparación del entorno y ejecución

1. Clonar el repositorio:

```bash
git clone https://github.com/usuario/tu-repositorio.git
cd tu-repositorio

2. Crear un entorno virtual:

bash
Copiar
Editar
python -m venv env

3. Activar el entorno virtual:

En Windows:

bash
Copiar
Editar
.\env\Scripts\activate
En Linux o Mac:

bash
Copiar
Editar
source env/bin/activate

4. Ejecutar el script principal:

bash
Copiar
Editar
python main.py

5. Desactivar el entorno virtual:

bash
Copiar
Editar
deactivate

## Implementación - Calculadora Estándar
Este módulo define una clase Calculadora con los métodos:

sumar(a, b)

restar(a, b)

multiplicar(a, b)

dividir(a, b)

Ejemplo de uso:

python
Copiar
Editar
from calculadora_poo import Calculadora

calculadora = Calculadora()

print(calculadora.sumar(10, 5))
print(calculadora.restar(10, 5))
print(calculadora.multiplicar(10, 5))
print(calculadora.dividir(10, 5))

## Implementación - Calculadora Factorial

La clase CalculadoraFactorial hereda de Calculadora y agrega un método para calcular el factorial de un número entero.

Ejemplo de uso:

python
Copiar
Editar
from calculadora_poo import CalculadoraFactorial

calculadora_factorial = CalculadoraFactorial(numero=5)
print(calculadora_factorial.calcular())