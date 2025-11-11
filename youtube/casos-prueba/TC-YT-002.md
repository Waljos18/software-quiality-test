 Caso de Prueba 2: Flujo Alterno – Error por conexión inestable
Atributo	Detalle
ID	TC-YT-002
Nombre	Fallo de subida por conexión inestable
Tipo	Funcional – Flujo alterno
Precondiciones	Usuario autenticado, conexión a internet intermitente
Datos de prueba	Archivo: tutorial_javascript.mp4 (resolución 720p, duración 5 min)
Pasos	
1. Iniciar sesión
2. Iniciar subida del archivo
3. Simular pérdida de conexión durante la carga
Resultado esperado	Mensaje de error: “No se pudo completar la subida. Verifica tu conexión.” y opción para reintentar
Evidencia	Captura del mensaje de error y barra de progreso detenida o reiniciada
