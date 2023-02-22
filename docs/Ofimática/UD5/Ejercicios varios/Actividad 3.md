## Ejercicio 3
Cliente como entidad
- Usuario
- Nº tarjeta
- Contraseña

Entidad relacionada con cliente, Persona, relacionados con "es"
- Atributos del anterior (No se escriben)
- DNI
- Nombre
- Apellidos
- Teléfono
- Email

Entidad relacionada con persona y billete mediante "viaja"
- origen
- destino
- fechaEmisión
- precio
- categoría

Entidad relacionada con 

- vuelo(*codVuelo*, ...)
- billete(*idBillete*, ...)
- cliente(*usuario*, contraseña, DNI)
- persona(*DNI*, ...)
- contiene(*idBillete*, *codVuelo*, nºasiento)

## Ejercicio 4
- categoria(*genero*)
- url(*dominio*)
- titulo(ISBN, ...)
- usuario(nick, ...)
- pertenece(*idCategoria*, *ISBN*)
- se encuentra(*dominio*, *ISBN*)
- lee(*ISBN*, *nick*, nºestrellas, reseña)

