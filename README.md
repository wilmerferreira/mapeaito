# 📍 Mapeaito: Geografía de Venezuela en Datos Abiertos

¡Epale, bienvenido a **Mapeaito**! 🇻🇪

Este es un repositorio de datos abiertos que contendrá la división geopolítica y administrativa de Venezuela (Niveles ADM0 a ADM3: País, Estados, Municipios y Parroquias), optimizado con datos geoespaciales para que cualquier desarrollador o analista pueda usarlos sin "dar tantas vueltas".

## 🎯 La Intención

En Venezuela, conseguir data geográfica actualizada, estandarizada y en formatos modernos (como [GeoJSON](https://en.wikipedia.org/wiki/GeoJSON) o JSON) suele ser un reto. La información está dispersa o en formatos cerrados que dificultan la creación de apps, mapas de calor o análisis estadísticos.

**Mapeaito** nace para centralizar este "bochinche" y ofrecer una fuente de verdad técnica, limpia y bien documentada para la comunidad.

## 📂 Contenido del Proyecto

El repositorio está organizado de forma que sea ligero y fácil de consumir.

## 🛠 Estructura de Datos

Cada entidad geográfica incluirá:

- **Nombre oficial** (con acentuación correcta).
- **Código ISO 3166-2** (para estados).
- **Códigos P-Code** (estándar humanitario para municipios y parroquias).
- **Centroides** (coordenadas de latitud y longitud).

## Fuentes

Este proyecto se nutrirá y procesará datos de fuentes confiables como por ejemplo:

- [HDX (OCHA Venezuela)](https://data.humdata.org/dataset/cod-ab-ven).
- [geoBoundaries (William & Mary University)](https://www.geoboundaries.org/).
- [Geoportal Provita](https://geoportal.provita.org.ve/).

## 🤝 ¿Cómo contribuir?

Si notas que falta una parroquia nueva, que un nombre está mal escrito o quieres agregar una capa de datos (como centros poblados o códigos postales), ¡échame una mano!

1. Haz un Fork del proyecto.
2. Crea tu rama (`git checkout -b feature/mejora-data`).
3. Haz un commit con tus cambios.
4. Abre un Pull Request.

## 📜 Licencia

Este proyecto está bajo la licencia **MIT**. Eres libre de usarlo para proyectos personales, académicos o comerciales. ¡Solo recuerda mencionar de dónde sacaste la data!

---
Hecho con ☕ y ganas de construir país por [Wilmer Ferreira](https://github.com/wilmerferreira).
