# ✨ U4S7 · Pulido funcional, UX y simulacro de defensa

<p align="center">
  <strong>Mejoras de búsqueda, paginación, accesibilidad y experiencia de usuario</strong><br>
  Proyecto académico de Análisis y Diseño de Software
</p>

---

## 📌 Datos del proyecto

| | |
|---|---|
| **Alumno** | Jesús Francisco Madrid Rodríguez |
| **Materia** | Análisis y Diseño de Software |
| **Práctica** | Unidad 4 · Semana 7 |
| **Repositorio** | [u4s7-madrid-rodriguez-jesus-francisco](https://github.com/madridrodriguezjesusfrancisco/u4s7-madrid-rodriguez-jesus-francisco) |
| **Aplicación** | Django · Gestión de servicios |

## 📝 Descripción

Esta práctica aplica un pulido funcional y visual a una aplicación web de gestión de servicios. El listado facilita encontrar registros, navegar entre ellos y entender los resultados, manteniendo el acceso de cada usuario limitado a sus propios datos.

## 🚀 Mejoras implementadas

- Búsqueda de servicios por título, sin distinguir mayúsculas y minúsculas.
- Paginación de **cinco registros por página**, conservando el término de búsqueda.
- Orden estable con los registros más recientes primero.
- Mensajes distintos cuando no hay registros y cuando la búsqueda no encuentra coincidencias.
- Manejo seguro de números de página fuera de rango.
- Tabla adaptable a pantallas pequeñas, etiquetas accesibles y foco visible en controles.
- Conservación del filtro por usuario autenticado.

## 🧰 Tecnologías

`Python` · `Django` · `MySQL (Aiven)` · `HTML` · `Tailwind CSS` · `Gunicorn` · `WhiteNoise` · `Render`

## 💻 Instalación local

Abre una terminal en la carpeta que contiene `manage.py` y ejecuta:

```powershell
py -m venv venv
.\venv\Scripts\Activate.ps1
pip install -r requirements.txt

## 📋 Actividades de la guía

Durante esta práctica se trabajó en el pulido funcional y la experiencia de usuario del sistema:

- Se agregó búsqueda de servicios por título.
- Se organizó el listado con paginación y orden de los registros más recientes.
- Se contemplaron mensajes para listas vacías y búsquedas sin resultados.
- Se revisó la presentación del listado en pantallas pequeñas.
- Se preparó el despliegue en Render con los comandos de construcción e inicio y las variables de entorno necesarias.

### Pendiente de completar y documentar

- Probar en el sitio publicado la búsqueda, la paginación y el diseño en móvil.
- Realizar la revisión de interfaz con un compañero y registrar aquí sus observaciones y los ajustes aplicados.
- Practicar la modificación de código y preparar la defensa del proyecto.
- Agregar la URL pública definitiva de Render cuando el despliegue termine correctamente.

# U4S7 — Pulido funcional, UX y simulacro de defensa

**Alumno:** Jesús Francisco Madrid Rodríguez  
**Materia:** Análisis y Diseño de Software  
**Práctica:** Unidad 4 · Semana 7  
**Repositorio:** [u4s7-madrid-rodriguez-jesus-francisco](https://github.com/madridrodriguezjesusfrancisco/u4s7-madrid-rodriguez-jesus-francisco)  
**Demo en Render:** _Agregar aquí la URL pública cuando el servicio esté desplegado._

---

## 1. Descripción

En esta práctica se dio mantenimiento al sistema de gestión de servicios desarrollado con Django. El trabajo consistió en pulir el listado para que sea más fácil consultar los registros, revisar su funcionamiento en distintos tamaños de pantalla y preparar el proyecto para su publicación y defensa.

## 2. Mejoras funcionales

- Búsqueda de servicios por título, sin distinguir entre mayúsculas y minúsculas.
- Paginación de cinco registros por página.
- Orden de los servicios del más reciente al más antiguo.
- Conservación del texto de búsqueda al cambiar de página.
- Mensaje para indicar cuando todavía no hay servicios.
- Mensaje distinto cuando una búsqueda no encuentra coincidencias.
- Control de páginas fuera de rango para evitar errores.
- Los servicios se filtran por el usuario autenticado.

## 3. Revisión de la bitácora de Git

Para revisar el historial de cambios se utilizaron estos comandos:

```bash
git log --oneline
git log --oneline --stat
