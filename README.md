# 🌊🧬🔄📦 Simulador de Modelos de Proceso de Software

Herramienta interactiva para explorar, comparar y aplicar los 4 modelos clásicos de proceso de software: **Cascada, Evolutivo, Iterativo e Incremental**.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chart.js&logoColor=white)

---

## 📖 Descripción

Este simulador es una **página web estática** diseñada como material didáctico para la cátedra **Ingeniería de Requerimientos I** (Eje Temático N.° 2 — Semana 5). Permite a los estudiantes:

- 📚 **Explorar** las características, ventajas y desventajas de cada modelo de proceso.
- 📊 **Comparar visualmente** los modelos mediante un gráfico radar interactivo.
- 🛠️ **Aplicar** los conceptos a través de un desafío práctico con escenarios reales.
- 🧭 **Seguir un roadmap** guiado con herramientas profesionales (draw.io, Jira, Uizard, Figma).

---

## ✨ Características

- 🎨 **Diseño moderno** con fondo animado, gradientes y tipografía *Space Grotesk*.
- 🃏 **Tarjetas expandibles** para cada modelo de proceso con diagramas visuales.
- 📈 **Gráfico radar comparativo** (Chart.js) basado en 5 ejes: estabilidad de requisitos, riesgo, participación del usuario, velocidad de entrega y flexibilidad al cambio.
- 🎯 **3 escenarios prácticos** (Sistema de Turnos Médicos, App de Delivery, Sistema de Inventario) con pistas para elegir el modelo adecuado.
- 🗺️ **Roadmap de 5 pasos** con instrucciones paso a paso.
- 📱 **100% responsive** — funciona en desktop, tablet y móvil.

---

## 🚀 Demo

Puedes ver el proyecto en vivo abriendo el archivo `index.html` en cualquier navegador moderno. No requiere instalación ni servidor.

```bash
# Clona el repositorio
git clone https://github.com/TU-USUARIO/simulador-modelos-proceso.git

# Entra a la carpeta
cd simulador-modelos-proceso

# Abre index.html en tu navegador
```

---

## 🧩 Estructura del Proyecto

```
simulador-modelos-proceso/
│
├── index.html        # Página completa (HTML + CSS + JS en un solo archivo)
└── README.md         # Este archivo
```

> 💡 El proyecto es **autocontenido**: todo el CSS está en un `<style>` y el JS en un `<script>` dentro del mismo HTML. Las dependencias externas (Chart.js y Google Fonts) se cargan vía CDN.

---

## 🛠️ Tecnologías Utilizadas

| Tecnología | Uso |
|------------|-----|
| **HTML5** | Estructura semántica del contenido |
| **CSS3** | Estilos, animaciones y diseño responsive |
| **JavaScript (Vanilla)** | Interactividad e inicialización del gráfico |
| **Chart.js 4.4** | Gráfico radar comparativo entre modelos |
| **Google Fonts** | Tipografía *Space Grotesk* |

---

## 📚 Contenido Didáctico

### Modelos Cubiertos

| Modelo | Icono | Ideal para... |
|--------|-------|---------------|
| **Cascada** | 🌊 | Requisitos fijos y bien definidos |
| **Evolutivo** | 🧬 | Requisitos cambiantes o poco claros |
| **Iterativo** | 🔄 | Proyectos complejos que requieren refinamiento |
| **Incremental** | 📦 | Proyectos grandes divisibles en módulos |

### Escenarios del Desafío

- 🏥 **A:** Sistema de Turnos Médicos → *requisitos cambiantes*
- 🚚 **B:** App de Delivery "Ya Llego" → *entregas por módulos*
- 📦 **C:** Sistema de Inventario "StockSeguro" → *requisitos estables*

### Herramientas sugeridas

- [draw.io](https://app.diagrams.net/) — Diagramas de flujo
- [Jira Software](https://www.atlassian.com/software/jira/free) — Tableros Kanban
- [Uizard](https://uizard.io/) — Wireframes generados con IA
- [Figma](https://www.figma.com/) — Diseño de interfaces

---

## 🎯 Objetivos de Aprendizaje

Al finalizar el uso de este simulador, el estudiante será capaz de:

1. ✅ Diferenciar los 4 modelos clásicos de proceso de software.
2. ✅ Justificar la elección de un modelo según las características del proyecto.
3. ✅ Modelar visualmente un proceso mediante diagramas de flujo.
4. ✅ Planificar tareas con metodologías ágiles (Kanban).
5. ✅ Diseñar wireframes de baja fidelidad con asistencia de IA.

---

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Si quieres mejorar el simulador:

1. Haz un **fork** del repositorio.
2. Crea una rama: `git checkout -b feature/nueva-funcionalidad`.
3. Realiza tus cambios y haz commit: `git commit -m "feat: agrega nueva funcionalidad"`.
4. Sube tu rama: `git push origin feature/nueva-funcionalidad`.
5. Abre un **Pull Request**.

---

## 📄 Licencia

Este proyecto está bajo la licencia **MIT**. Puedes usarlo, modificarlo y distribuirlo libremente citando la fuente.

---

## 👨‍🏫 Créditos

- **Cátedra:** Ingeniería de Requerimientos I
- **Eje Temático:** N.° 2 — Modelos de Proceso de Software
- **Semana:** 5

---

<div align="center">

**⭐ Si este proyecto te resultó útil, dale una estrella en GitHub ⭐**

Hecho con 💜 para la enseñanza de la Ingeniería de Software

</div>
