# Lectura-de-Archivos-Visual-Studio
Esta actividad consistió en el desarrollo de una aplicación de escritorio tipo "Bloc de Notas" en C# y Windows Forms, ampliando la funcionalidad de la práctica anterior para incluir la lectura de archivos existentes.

La aplicación permite al usuario realizar las siguientes acciones clave:

Crear y editar texto en un área de trabajo simple y responsiva.

Guardar el trabajo de forma inteligente: si el archivo es nuevo, pregunta dónde guardarlo ("Guardar como..."); si ya existe, guarda los cambios directamente en el mismo archivo ("Guardar").

Abrir archivos de texto (.txt) desde cualquier ubicación en la computadora, cargando su contenido en el editor para su visualización y modificación. Esta es la función central de "lectura" de la práctica.

Proteger al usuario contra la pérdida de información, mostrando diálogos de advertencia sobre cambios no guardados antes de abrir un nuevo archivo o cerrar el programa.

Para lograrlo, se utilizaron componentes como OpenFileDialog y SaveFileDialog para interactuar con el sistema de archivos del usuario, y métodos de la librería System.IO para leer (File.ReadAllText) y escribir (File.WriteAllText) los datos. El objetivo principal fue aplicar los conceptos de entrada y salida de datos (File I/O) en un entorno gráfico.
