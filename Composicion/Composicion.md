# Composicion

# Composición en Programación Orientada a Objetos (POO)

La **composición** es una relación fuerte en la que la clase parte no puede existir sin la clase todo.

- La clase "todo" es responsable de crear y destruir a las partes.
- Representa una relación de "parte de" muy fuerte.
- Si la clase "todo" se elimina, las partes también.

**Ejemplo:**  
Una `Casa` tiene `Habitaciones`. Si la casa se elimina, las habitaciones también desaparecen.

---

### Características:
- Relación fuerte y de dependencia
- Vida dependiente de las partes
- Representada en UML con un rombo negro en el lado del "todo"
