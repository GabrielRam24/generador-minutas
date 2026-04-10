# 📋 Generador de Minutas de Reunión

Aplicación de escritorio para generar minutas institucionales en formato Word (.docx) y PDF, desarrollada para uso interno del Estado Provincial.

---

## ¿Qué es?

Una aplicación nativa de escritorio (Windows) que permite completar un formulario estructurado y generar automáticamente una minuta de reunión con formato institucional, lista para archivar o distribuir.

No requiere conexión a internet. No envía datos a ningún servidor. Todo ocurre en la computadora del usuario.

---

---

## Funcionalidades

- Formulario completo con todos los campos de una minuta formal
- **Datos de la reunión:** organismo, fecha, hora, modalidad y lugar
- **Participantes:** tabla dinámica con nombre, rol y organismo
- **Temas tratados y Acuerdos:** ítems con agregar/eliminar
- **Compromisos:** descripción, responsable y plazo con selector de fecha
- **Próxima reunión:** fecha definida o a definir, con observaciones
- Generación de **.docx** con formato institucional (tipografías Faustina y Archivo, color verde institucional)
- Generación de **.pdf** automática si el equipo tiene Microsoft Word instalado
- Carpeta de destino configurable: local, Google Drive, OneDrive, Dropbox o red interna
- Nomenclatura automática: `Organismo_DDMMAAAA_HHMM.docx`
- Botones para abrir el archivo o la carpeta de destino directamente desde la app

---

## Instalación

No requiere instalar Python ni ningún otro software.

**1.** Descargar `MinutasApp_Desktop.zip`

**2.** Extraer el ZIP en cualquier carpeta de la PC

**3.** Dentro de la carpeta extraída, hacer doble clic en `MinutasApp.exe`

**4.** La aplicación abre directamente como ventana de escritorio

> Sin navegador. Sin servidor. Sin configuración previa.

---

## Configuración de carpeta de guardado

Por defecto las minutas se guardan en la subcarpeta `minutas/` junto al ejecutable. Para cambiar la carpeta de destino:

**1.** Hacer clic en **⚙ Configuración** (esquina superior derecha)

**2.** Ingresar la ruta deseada o usar el botón **Examinar...**

**3.** Ejemplos de rutas válidas:
```
G:\Mi unidad\Minutas
C:\Users\nombre\OneDrive\Minutas
\\servidor\compartida\Minutas
```

**4.** Hacer clic en **Guardar**

> Si se apunta a una carpeta de Google Drive u otro servicio de sincronización instalado localmente, las minutas quedan disponibles para todo el equipo de forma automática.

---

## Posibilidades de uso

- Equipos que trabajan con información sensible y no pueden usar herramientas en la nube
- Organismos sin conexión a internet permanente o con redes internas cerradas
- Generación estandarizada de minutas con formato institucional uniforme
- Distribución a múltiples usuarios sin instalar Python ni dependencias
- Integración con carpetas compartidas de red para centralizar el archivo de minutas
- Compatible con cualquier PC Windows sin configuración adicional

---

## Desarrollo

Desarrollado por el **Equipo de Planificación | Secretaría General de Gobernación de la Provincia de Entre Ríos**

---

*Herramienta de uso interno. Sin fines comerciales.*
