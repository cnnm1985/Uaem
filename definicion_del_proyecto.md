# Proyecto para Arquitectura de Backend

## Objetivo
Crear un sistema WEB para almacenamiento de DataSet's.



## Requerimientos del cliente

1. Descripción General
La Universidad Autónoma del Estado de México requiere un sistema web que permita el almacenamiento, gestión y descarga de datasets en diversas áreas del conocimiento.
 El portal estará dirigido a estudiantes, investigadores y cualquier usuario con acceso a la plataforma, brindando una herramienta para la difusión y análisis de información
 estructurada.

El sistema debe permitir la carga de datasets con información detallada sobre su contenido, ofrecer una vista previa de los datos,
 y facilitar la interacción entre los usuarios a través de comentarios y discusiones sobre los resultados obtenidos a partir del uso de los datasets.

2. Características Principales
	2.1 Gestión de Usuarios
		Sistema de registro e inicio de sesión para gestionar el acceso a la plataforma.
		Perfiles de usuario con datos básicos como nombre, correo y actividad dentro de la plataforma.
	Roles de usuario:
		Administrador: gestión de datasets, usuarios y control de contenido.
		Usuario registrado: puede subir, comentar y descargar datasets.
		Visitante: puede explorar datasets pero no subir ni comentar.
	2.2 Carga y Gestión de Datasets
		Posibilidad de subir datasets en formatos como CSV, JSON y Excel.
		Opción para actualizar o eliminar un dataset por un administrador.
		Cada dataset debe incluir una tabla de especificaciones con información como:
	Título del dataset
		Descripción general
		Fecha de publicación
		Categoría/Área del conocimiento
		Etiquetas o palabras clave
		Fuente o autor del dataset
		Tamaño del archivo
		Formato del archivo
   
	
	2.3 Vista Previa de Datasets
		Muestra parcial del dataset con un número limitado de filas y columnas (ejemplo: las primeras 10 filas).
		Posibilidad de aplicar filtros básicos para inspeccionar datos sin necesidad de descarga.
		Descarga completa del dataset en su formato original.

	2.4 Comentarios y Discusión
		Espacio para que los usuarios puedan comentar y discutir sobre el dataset.
		Posibilidad de calificar la utilidad del dataset.
		Filtro de comentarios para destacar los más relevantes o recientes.

	2.5 Búsqueda y Filtrado de Datasets
		Barra de búsqueda para localizar datasets por nombre, categoría, etiquetas o autor.
		Filtros avanzados para encontrar datasets por fecha de publicación.

	2.6 Seguridad y Control de Contenido
		Verificación de archivos subidos para evitar formatos no permitidos o archivos dañados.
		Control de permisos según el rol del usuario.

	
