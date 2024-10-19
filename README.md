# T5-WEB

Objetivo
El objetivo de esta práctica es aplicar conceptos clave de comunicación entre componentes, enrutamiento, manejo de formularios y validación en Blazor, así como integrar Entity Framework Core para la persistencia de datos. Los estudiantes desarrollarán una aplicación que permita registrar videojuegos y personajes de videojuegos asociados, implementando un CRUD adicional para gestionar plataformas de videojuegos.

El estilo de su aplicación debe estar acorde a una consola de videojuegos.. la que ustedes prefieran.. deben hacer que las fuentes, colores, e imágenes nos acuerden a esa consola. 

📋 Instrucciones
Registro de Videojuegos usando SQLite:
Crea una página para registrar videojuegos con los siguientes campos:
Nombre (texto).
Desarrollador (texto).
Plataforma (campo de selección - Select).
Género (texto, ejemplo: Aventura, Acción, Rol).
Fecha de lanzamiento (fecha).
Imagen de portada (URL para la portada del videojuego).
Descripción (área de texto para describir el videojuego).
Gestión de Plataformas (CRUD):
Crea una página donde puedas gestionar plataformas de videojuegos, con los siguientes campos:
Nombre de la plataforma (texto, ejemplo: PC, PS5, Xbox).
Estado: Se debe poder activar o desactivar la plataforma.
Implementa un CRUD completo para las plataformas, permitiendo:
Crear nuevas plataformas.
Editar plataformas existentes.
Cambiar el estado de las plataformas (activas o inactivas).
Registro de Personajes de Videojuego:
Crea una página para registrar personajes asociados a un videojuego, con los siguientes campos:
Nombre (texto).
Alias (texto, opcional).
Rol en el juego (texto, ejemplo: Protagonista, Villano, Secundario).
Habilidad especial (texto, opcional).
Arma favorita (texto, opcional).
Nivel de poder (número, del 1 al 100).
Imagen del personaje (URL de una imagen del personaje).
Enrutamiento y Navegación:
Implementa el enrutamiento en Blazor para permitir la navegación entre las páginas de:
Registro de Videojuegos.
Gestión de Plataformas.
Registro de Personajes.
Persistencia de Datos con Entity Framework Core:
Implementa Entity Framework Core para la persistencia de datos.
Crea modelos para Videojuegos, Personajes de Videojuego y Plataformas, con las correspondientes relaciones entre ellos.
Implementa las migraciones necesarias y asegúrate de que los datos se guarden en una base de datos SQLite.
Desarrolla las operaciones CRUD (Crear, Leer, Actualizar, Borrar) para gestionar tanto los videojuegos, como los personajes y las plataformas.
