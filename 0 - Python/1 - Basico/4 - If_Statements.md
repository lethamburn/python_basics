<div style="text-align: center; width: 200px;" >
  <img src="https://github.com/Hack-io-Data/Imagenes/blob/main/01-LogosHackio/logo_celeste@4x.png?raw=true" alt="logo hack(io)" />
</div>

---

# If Statements

### Crea una nueva carpeta llamada *ejercicios_if* y completa los siguientes ejercicios dentro de ella para organizar los ficheros correctamente.

### Los scripts que vamos a crear pueden llamarse *ejercicio1.py*, *ejercicio2.py*, y así sucesivamente.

---

- **1. Crea un script que verifique si una condición es verdadera e imprima un mensaje en consecuencia. En este caso, tendremos que validar *superhero_active* y si es verdadero imprimir un mensaje y si no nada.**
```python
superhero_active = True

# Tu código
# Output True:
# ¡Spider-Man está en acción!

# Output False:
# (no se imprime nada)
```
- **2. Modifica el siguiente script para que añada un signo de exclamación al final de la frase si la variable excited es verdadera. Si excited es falsa, no cambia la frase.**
```python
sentence = 'Batman ha llegado'
excited = True

# Tu código

# Output True:
# Batman ha llegado!

# Output False:
# Batman ha llegado
```
- **3. Añade una nueva variable booleana *confused* al script anterior. Si confused es verdadera, añade un signo de *interrogación* al final de la frase. Si ambas variables excited y confused son verdaderas, añade *!?*. Cambia las variables excited y confused a False y True respectivamente para ver otros resultados posibles.**
- **4. Crea un programa que convierta una frase a mayúsculas si excited es verdadera y a minúsculas si excited es falsa. Usa una frase que te guste.**
```python
sentence = 'The cake is a lie'
excited = True
# Tu código
# Output:
# THE CAKE IS A LIE

# Tu código
# Output:
# the cake is a lie
```
- **5. Crea un script que recorra una frase y añada un signo de exclamación después de cada carácter si excited es verdadera. Puedes crear una nueva variable como en anteriores ejercicios para crear esa nueva frase.**
```python
sentence = 'I am Groot'
excited = True

#Tu código
# Output:
# I! !a!m! !G!r!o!o!t!
```
- **6. Escribe un script que compare dos nombres de personajes y verifique cuál es el primero alfabéticamente. Recuerda que funciona de forma similar a los valores numéricos.**
```python
character1 = 'Mario'
character2 = 'Luigi'

# Tu código
# Output:
# Luigi está antes que Mario
```
- **7. Escribe un script que clasifique una puntuación de un videojuego y asigne un rango basado en el valor de la puntuación. Si es menor que 50 -> D. Si es menor que 70 -> C. Si es menor que 90 -> B. Si es mayor que eso -> A.**
```python
score = 85

# Tu código
# Output:
# Tu rango es: B
```
- **8. Escribe un script que tome tres valores de fuerza de personajes y determine cuál es el más fuerte. Piensa en las posibilidades de un piedra, papel o tijera para guiarte. Crea una nueva variable para almacenar el nombre del personaje si te ayuda.**
```python
characterStrength1 = 80
characterStrength2 = 95
characterStrength3 = 90

# Tu código
# Output:
# El personaje más fuerte es: Personaje 2
```
- **9. Crea un script que verifique si un agente tiene acceso a una base secreta. El agente tiene acceso si conoce la contraseña *"openSesame"* y su nivel de acceso es *mayor a 5.* Si cualquiera de estas dos cosas no se cumplen, no tendrá acceso.**
```python
password = 'openSesame'
access_level = 7

# Tu codigo con todas las opciones posibles para securizar la base secreta.
# Output:
# Acceso concedido a la base secreta.
# Output:
# Acceso denegado.
```
- **10. Escribe un script que determine el ganador entre dos personajes basado en sus puntuaciones de ataque. Si ambos tienen la misma puntuación, imprime *"Empate"*. Prueba a cambiar los valores de los ataques para ver diferentes resultados posibles.**
```python
attack1 = 85
attack2 = 90

# Output:
# El ganador es: Personaje 2
```
