Atributo	Detalle
ID	TC-RIPLEY-003
Nombre	Error en pasarela de pago
Tipo	Regresión – Flujo de error
Precondiciones	Usuario registrado, cupón válido
Datos de prueba	Producto: Zapatillas Nike
Cupón: NIKE20
Tarjeta: Visa (simulada con error)
Pasos	
1. Ingresar a la web
2. Agregar producto
3. Aplicar cupón
4. Seleccionar tarjeta con error
5. Confirmar compra
Resultado esperado	Mensaje de error: “No se pudo procesar el pago. Intente nuevamente.”
Evidencia	Captura del mensaje de error en pantalla
