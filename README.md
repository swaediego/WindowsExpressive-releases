# WindowsExpressive — descargas

Instaladores de **WindowsExpressive**, una capa de personalización para Windows con estética Material Expressive:
barra flotante propia, lanzador de apps, paneles rápidos, widgets de escritorio y color dinámico que sigue al sistema.

> **Estado: beta.** Aún no se ha probado en muchos equipos. Si algo falla, abre una *issue* en este repositorio.

## Descargar

Ve a [**Releases**](../../releases) y baja `WindowsExpressive-Setup-<versión>.exe`.

Requisitos: Windows 10 o 11 de 64 bits.

## Aviso de SmartScreen

El instalador **aún no está firmado**, así que Windows puede mostrar *"Windows protegió su PC"*.
Pulsa **Más información → Ejecutar de todas formas**. Cada release incluye el **SHA-256** del instalador
para que puedas comprobarlo:

```powershell
Get-FileHash .\WindowsExpressive-Setup-<versión>.exe -Algorithm SHA256
```

## Actualizaciones

La app comprueba sola este repositorio y avisa cuando hay una versión nueva ("Actualización disponible").
También puedes buscarla a mano en **Ajustes → Acerca de**.

## Desinstalar

Ajustes de Windows → Aplicaciones → WindowsExpressive. La barra de tareas de Windows se restaura sola al cerrar la app.
