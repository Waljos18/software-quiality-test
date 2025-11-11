Casos de Prueba de Regresión – Saga Ripley
 Objetivo
Verificar que el flujo de compra con cupón de descuento sigue funcionando correctamente después de una actualización del módulo de pagos.

Caso de Prueba 1: Flujo Feliz – Cupón válido aplicado exitosamente
Atributo	Detalle
ID	TC-RIPLEY-001
Nombre	Compra con cupón válido
Tipo	Regresión – Flujo funcional
Precondiciones	Usuario registrado con sesión iniciada
Datos de prueba	Producto: Zapatillas Nike
Cupón: NIKE20 (20% de descuento válido)
Pasos	
1. Ingresar a www.sagarpipley.com
2. Buscar “Zapatillas Nike”
3. Agregar al carrito
4. Ir al checkout
5. Ingresar cupón “NIKE20”
6. Seleccionar método de pago
7. Confirmar compra
Resultado esperado	Descuento aplicado correctamente y compra finalizada con mensaje de éxito
Evidencia	Captura del resumen de compra con descuento aplicado y mensaje de éxito

