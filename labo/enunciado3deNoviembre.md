Crear un sistema de Alta-Baja-Modificacion (ABM), es decir, un sistema
que sirva para ingresar mascotas (alta), para eliminar mascotas (baja)
y para modificar información de las mascotas:

Las mascotas pueden ser:

- Perros 
- Gatos
- Pajaritos
- Peces

Todas las mascotas tienen un nombre y un dueño
(el nombre de la mascota debe ser único)

Cada una tiene un saludo en particular:

- Para los perros el saludo es “guau”
- Para los gatos el saludo es “miau”
- Para los pajaritos el saludo es “pio”


El alta de mascotas implica que se se indique el nombre, 
dueño y tipo.

Dentro del menú de la aplicación debe existir la opción “Saludar”,
la misma solicita el nombre al usuario y el nombre de la mascota.

El programa debe responder:

- Si el usuario es el dueño de la mascota: se saluda con el saludo de la
mascota (por ejemplo: guau)

- Si el usuario no es el dueño de la mascota: se saluda con el saludo
de la mascota en mayúsculas y con un signo de exclamación (por ejemplo: GUAU!)

En el caso de los pajaritos la situación cambia, si el usuario no es el dueño
no debe responder nada.

Los peces no tienen saludo, pero cada vez que los saluda el dueño
pierden una vida, y si los saluda un NO dueño, mueren.

Para sumar vidas deben alimentarse mediante el método alimentar,
cada vez que se llama a dicho método se suma una vida.

Si el pez se queda sin vida se debe eliminar automáticamente
del listado de mascotas.

Vidas iniciales de cada pez: 10

Para los perros, gatos y pajaritos también existe un método alimentar.
Ese método suma alegría a la mascota. Por cada punto de alegría que
tenga la mascota el saludo se prolonga.

Por ejemplo, para un gato que tiene 3 puntos de alegría el saludo
es “miau miau miau”.

Cada tipo de mascota debe tener un método el cual devuelve qué tipo
de mascota es (Perro, Gato, Pajarito o Pez).
