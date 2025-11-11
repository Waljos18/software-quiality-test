Caso de Prueba Exploratorio – Comentarios en Facebook
 Objetivo
Explorar cómo Facebook maneja comentarios que contienen:
•	Texto extenso (más de 1000 caracteres)
•	Emojis variados
•	Menciones a otros usuarios
Descripción:
Este caso de prueba tiene como objetivo explorar el comportamiento de la funcionalidad de comentarios en publicaciones públicas de Facebook, enfocándose en escenarios con texto extenso, emojis variados y menciones a otros usuarios.
 Pasos Exploratorios
1.	Acceder a una publicación pública
o	Iniciar sesión en Facebook
o	Navegar a una publicación propia o de otro usuario que permita comentarios
2.	Redactar un comentario extenso
o	Escribir un texto de más de 1000 caracteres (párrafos, narración, etc.)
o	Incluir al menos 10 emojis distribuidos en el texto
o	Mencionar a 2 usuarios usando @nombre (ej. @Juan Pérez, @María López)
3.	Publicar el comentario
o	Verificar si el comentario se publica sin errores
o	Observar si se trunca visualmente (con opción “Ver más”)
o	Confirmar que las menciones se convierten en enlaces al perfil
o	Validar que los emojis se rendericen correctamente
4.	Interacciones posteriores
o	Verificar si otros usuarios pueden reaccionar o responder al comentario
o	Editar el comentario y agregar más emojis o texto
o	Eliminar el comentario y observar el comportamiento

Comportamientos Esperados
Componente	Comportamiento esperado
Texto largo	Se muestra parcialmente con opción “Ver más”; no hay pérdida de contenido
Emojis	Se renderizan correctamente en todos los dispositivos y navegadores
Menciones	Se convierten en enlaces al perfil mencionado; el usuario recibe notificación
Edición	El comentario puede editarse sin perder formato ni menciones
Eliminación	El comentario se elimina completamente sin dejar rastro visible
Reacciones	Otros usuarios pueden reaccionar y responder sin errores
