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
