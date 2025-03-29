# Conversor de Decimal a Hexadecimal en C

Este es un programa simple en lenguaje C que convierte un número en base 10 (decimal) a su equivalente en base 16 (hexadecimal).

## 🧠 Descripción

El programa solicita al usuario que ingrese un número decimal. Luego convierte ese número a hexadecimal mediante divisiones sucesivas entre 16 y guarda los residuos. Los valores del 10 al 15 se representan con las letras A a F. El resultado se imprime en orden inverso para formar el número hexadecimal correcto.

## 🚀 Cómo usar

### 1. Guarda el archivo

Guarda el código fuente en un archivo llamado `decimal_a_hexadecimal.c`.

### 2. Compila el programa

Utiliza un compilador de C como GCC:

```bash
gcc decimal_a_hexadecimal.c -o decimal_a_hexadecimal
```
3. Ejecuta el programa

```bash
./decimal_a_hexadecimal
```
4. Ingresa un número
El programa te pedirá que ingreses un número decimal y mostrará su equivalente en hexadecimal.

📦 Ejemplo
```yaml
Ingresar un numero: 255
Hexadecimal: FF
```
📌 Notas
El programa solo admite números enteros no negativos.

No incluye validación para entradas no numéricas.

Puedes mejorarlo agregando:

Validación de entrada

Soporte para números negativos

Un menú para realizar múltiples conversiones
