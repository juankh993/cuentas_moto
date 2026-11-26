# Cuentas Moto

Control diario de ganancias y gastos para domiciliarios en moto. Funciona en el navegador del celular, sin cuenta ni servidor propio.

## Funciones

- Ganancias por aplicación: Uber, Didi, servicios por fuera y las que agregues (InDrive, Rappi, etc.).
- Gastos: gasolina, aceite, llantas, mantenimiento y otros.
- Neto del día, movimientos por fecha y resumen del mes.
- Respaldo: copiar los datos como texto y restaurarlos.
- Modo claro y oscuro según el celular.

## Cómo usarla

```bash
git clone https://github.com/juankh993/cuentas_moto.git
```

Abre `index.html` en el navegador.

Para usarla desde el celular, activa GitHub Pages en *Settings > Pages* (rama `main`, carpeta raíz).

## Dónde quedan los datos

En `localStorage`, solo en el navegador y dispositivo donde la usas. Si borras los datos del navegador o cambias de celular, se pierden, así que haz respaldo con frecuencia. La app no envía tus movimientos a ningún servidor.

## Tecnología

Un solo archivo HTML con CSS y JavaScript, sin compilación. Las fuentes Barlow se cargan desde Google Fonts.

## Pendiente

- Resumen semanal y gráfico de ganancias contra gastos.
- Filtros por aplicación y categoría.
- Exportar a CSV.
- Editar o borrar aplicaciones agregadas.

El detalle está en [PLAN.md](PLAN.md).
