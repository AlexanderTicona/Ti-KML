# 🌍 Ti-KML para Civil 3D

**Ti-KML** es una herramienta para Autodesk Civil 3D que permite exportar elementos de AutoCAD y Civil 3D al formato KML compatible con Google Earth.

Desarrollado para facilitar la interoperabilidad entre modelos CAD y plataformas geoespaciales como Google Earth, QGIS y más.

---

## 🚀 Características principales

### 🎯 Exportación desde AutoCAD
- **Puntos AutoCAD a KML**
- **Polilíneas 2D y 3D a KML**

### 🏗️ Exportación desde Civil 3D
- **COGO Points a KML**
- **Alineamientos a KML**

### 🏷️ Funciones adicionales
- Exportar **geometrías** personalizadas (`Ti-KML-Geometría`)
- Exportar **etiquetas y textos** como anotaciones en KML (`Ti-KML-Etiquetas`)

---

## 🧭 Cómo usar

### 🧩 1. Cargar el plugin en Civil 3D

1. Abre Autodesk Civil 3D.
2. Escribe `NETLOAD` en la línea de comandos.
3. Selecciona el archivo `GenerarKML.dll`.
4. Accede a la nueva pestaña en el Ribbon: **`Ti-KML`**

---

### 📂 2. Interfaz del Ribbon

| 🧱 Panel | Botón | Acción |
|---------|--------|--------|
| **Elementos CAD a KML** | `Puntos AutoCAD a KML` | Exporta puntos de AutoCAD |
|  | `Polilínea 2D & 3D a KML` | Exporta polilíneas simples |
| **Elementos Civil 3D a KML** | `COGO Point a KML` | Exporta puntos COGO |
|  | `Alineamiento a KML` | Exporta rutas de alineamiento |

---

## 💻 Comandos disponibles

También puedes ejecutar los comandos directamente desde la línea de comandos:

| Comando | Acción |
|--------|--------|
| `Ti-KML-PuntosCAD` | Exportar puntos AutoCAD |
| `Ti-KML-Polilineas` | Exportar polilíneas 2D o 3D |
| `Ti-KML-CogoPoints` | Exportar puntos COGO |
| `Ti-KML-Alineamiento` | Exportar alineamientos |
| `Ti-KML-Geometría` | Exportar geometrías varias |
| `Ti-KML-Etiquetas` | Exportar etiquetas o textos como anotaciones |

---

## 📦 Requisitos

- Civil 3D 2023 o superior
- Dibujo debe estar georreferenciado
- Uso de coordenadas latitud/longitud (sistema geográfico)

---

## 🧪 En desarrollo

- Exportación de superficies a KML
- Exportación a KMZ (KML comprimido)
- Opciones de estilo, color y etiquetas dinámicas
- Integración con mapas web y Leaflet/Mapbox

---

## 🛠️ Instalación recomendada

Para uso frecuente:
1. Agrega la ruta del `.dll` al archivo `PackageContents.xml` dentro de un `.bundle`.
2. Copia el bundle a:  
   `C:\ProgramData\Autodesk\ApplicationPlugins\TiKML.bundle`

---

## 📜 Licencia

Este proyecto está bajo licencia MIT (o la que definas).

---

## 🙌 Créditos

Desarrollado por: **[Tu nombre o equipo]**  
GitHub: [github.com/tuusuario/Ti-KML](https://github.com/tuusuario/Ti-KML)  
Versión: `v1.0`
