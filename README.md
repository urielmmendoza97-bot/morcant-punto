# Morcant Uno

Punto de venta instalable de **U Morcant & Co.** para pequeños negocios.

## Funciones

- Registro de ventas en efectivo y cálculo automático del cambio.
- Cobros por transferencia con QR local, monto y referencia por venta.
- Inventario con existencias, alertas, SKU, categorías y fotografías.
- Historial de ventas y tickets imprimibles.
- Anulación, eliminación individual y limpieza completa del historial.
- Apariencia oscura o clara guardada en el dispositivo.
- Resumen diario de ingresos, unidades y productos vendidos.
- Respaldo e importación de datos en JSON.
- Funcionamiento sin conexión e instalación como PWA.

## Uso

Abre `index.html` mediante un servidor web. Para desarrollo local:

```bash
python3 -m http.server 8080
```

Después visita `http://localhost:8080`.

Los datos se almacenan en el navegador del dispositivo. Exporta respaldos regularmente desde **Ajustes**.

Para transferencias se guarda únicamente la CLABE, el banco y el beneficiario en el dispositivo. La app nunca solicita contraseñas, NIP ni códigos bancarios. El comerciante debe comprobar el depósito en su banca antes de confirmar la venta.

## Identidad

U MORCANT & CO. — Campeche, México.
