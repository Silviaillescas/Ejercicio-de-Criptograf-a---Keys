# Ejercicio Criptográfico con Llaves (Key)

**Autora:** Silvia Illescas  
**Carné:** 22376  

---

## Descripción

Esta tarea consiste en la implementación manual de un sistema de cifrado basado en la operación XOR utilizando llaves ASCII.  

Se desarrollan tres componentes principales:
- Generación de llaves dinámicas
- Cifrado con llave de tamaño fijo (k fijo)
- Cifrado con llave de tamaño dinámico

Todo el proceso se realiza sin utilizar librerías externas para cifrado, trabajando directamente con conversiones ASCII y representaciones binarias.

---

## Funcionalidades Implementadas

### 1. Generación de Llaves Dinámicas

Se genera una llave compuesta por caracteres ASCII imprimibles.  
La longitud de la llave puede definirse manualmente o adaptarse al tamaño del mensaje.

---

### 2. Cifrado con Llave de Tamaño Fijo

- Se ingresa una llave ASCII de tamaño k.
- La llave se repite hasta cubrir la longitud del mensaje.
- Se convierte el mensaje y la llave a binario.
- Se aplica XOR bit a bit.
- El resultado se convierte manualmente a Base64 para obtener un cipher en ASCII imprimible.

---

### 3. Cifrado con Llave de Tamaño Dinámico

- Se genera automáticamente una llave ASCII del mismo tamaño que el mensaje.
- Se aplica el proceso de conversión a binario.
- Se realiza la operación XOR.
- El resultado se convierte manualmente a Base64.
- La llave generada es necesaria para el descifrado.

---

## Estructura

- `Criptografia-key.ipynb`  
  Contiene la implementación completa del algoritmo, incluyendo:
  - Conversión ASCII ↔ Binario
  - Operación XOR
  - Conversión manual a Base64
  - Funciones de cifrado y descifrado

---

## Requisitos

- Python 3.x  
- Jupyter Notebook  

---

## Ejecución

1. Abrir Jupyter Notebook.
2. Cargar el archivo `Criptografia-key.ipynb`.
3. Ejecutar las celdas en orden.
4. Ingresar el mensaje y la llave cuando el programa lo solicite.


Aplicar los principios básicos de criptografía simétrica mediante la implementación manual de operaciones binarias y generación de llaves, reforzando la comprensión del funcionamiento interno de los algoritmos de cifrado.
