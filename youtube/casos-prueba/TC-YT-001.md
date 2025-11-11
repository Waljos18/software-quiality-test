Casos de Prueba – Subida de Video en YouTube
 Objetivo
Verificar el comportamiento del sistema de subida de videos en YouTube bajo diferentes condiciones: subida exitosa, error por conexión inestable y rechazo por formato no compatible.

 Caso de Prueba 1: Flujo Feliz – Video válido subido correctamente
Atributo	Detalle
ID	TC-YT-001
Nombre	Subida exitosa de video válido
Tipo	Funcional – Flujo feliz
Precondiciones	Usuario autenticado en su cuenta de YouTube
Datos de prueba	Archivo: viaje_paris.mp4 (resolución 1080p, duración 2 min)
Pasos	
1. Iniciar sesión en YouTube
2. Hacer clic en “Subir video”
3. Seleccionar archivo viaje_paris.mp4
4. Completar título y descripción
5. Establecer visibilidad como “Público”
6. Confirmar subida
Resultado esperado	Video se sube correctamente, aparece en la lista de videos del canal y es reproducible

