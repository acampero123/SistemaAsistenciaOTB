# Sistema de Control de Asistencia, Faltas y Multas en una OTB

## Descripción
Este proyecto es una aplicación de consola en Java que simula un sistema de control de asistencia a reuniones en una Organización Territorial de Base (OTB). El sistema registra si un vecino asistió o faltó a la reunión, aplicando una multa de 50 Bs en caso de falta, y notifica a los dirigentes suscritos al sistema. Al finalizar, muestra un reporte resumen con el estado y multas aplicadas a cada vecino.

## Patrones de Diseño Usados

- **Singleton**: Garantiza que solo exista una instancia del sistema para controlar registros y notificaciones.
- **Observer**: Implementa la notificación automática a los observadores (dirigentes) sobre eventos de asistencia o falta.
- **Decorator**: Permite agregar la multa a un registro de falta como una extensión sin modificar el objeto original.

## Casos de Uso

- Registrar la asistencia o falta de vecinos a reuniones.
- Notificar a dirigentes cuando un vecino asiste o falta.
- Aplicar multas automáticamente en caso de falta.
- Mostrar un reporte final con estado y multas.

## Instrucciones para ejecutar el proyecto

1. Clonar o descargar el repositorio.
2. Abrir la carpeta del proyecto y compilar el archivo `OTBMain.java`:
