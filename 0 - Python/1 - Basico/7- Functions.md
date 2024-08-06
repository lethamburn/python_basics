<div style="text-align: center; width: 200px;" >
  <img src="https://github.com/Hack-io-Data/Imagenes/blob/main/01-LogosHackio/logo_celeste@4x.png?raw=true" alt="logo hack(io)" />
</div>

---

# Functions

### Crea una nueva carpeta llamada *ejercicios_functions* y completa los siguientes ejercicios dentro de ella para organizar los ficheros correctamente.

### Los scripts que vamos a crear pueden llamarse *ejercicio1.py*, *ejercicio2.py*, y así sucesivamente.

---

- **1. Modifica el siguiente script para cambiar el nombre de la función de *greet* a *say_hello* y el parámetro de *name* a *person_name*. Comprueba que todo funciona correctamente.**
```python
def greet(name):
    print(f"Hello {name}!")
    print("How are you?")

greet("Peter")
greet("Harry")
# Output:
# Hello Peter!
# How are you?
# Hello Harry!
# How are you?
```
- **2. Crea una función llamada *print_twice* que acepte un argumento x y lo imprima dos veces en dos líneas.**
```python
# Tu código
print_twice("Hello")
# Output:
# Hello
# Hello
```
- **3. Modifica la función *print_many* para que acepte primero el parámetro n y luego el parámetro thing. Ajusta la llamada a la función en consecuencia.**
```python
def print_many(thing, n):
    for _ in range(n):
        print(thing)

print_many("Hello", 3)
# Output:
# Hello
# Hello
# Hello
```
- **4. Modifica el siguiente script para crear una función llamada double que acepte un argumento x y *retorne* ese valor multiplicado por 2.**
```python
# Tu código
number = 5
twice = double(number)
print(number)  # Output: 5
print(twice)   # Output: 10
```
- **5. Crea una función llamada quadruple que acepte un argumento x y retorne ese valor multiplicado por 4, usando solo la función double. Reutiliza la solución de ejercicio anterior.**
```python 
# Tu código
number = 5
quad = quadruple(number)
print(number)  # Output: 5
print(quad)    # Output: 20
```
- **6. Crea una función llamada *is_prime* que acepte un número entero n y retorne True si el número es primo, y False en caso contrario.**
```python
# Tu código
print(is_prime(7))  # Output: True
print(is_prime(10))  # Output: False
```
