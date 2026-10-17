# EduTwin · Laboratorio Digital de Simulación Pedagógica

Landing page interactiva para el proyecto de investigación y desarrollo **EduTwin** — Laboratorio Digital de Simulación Pedagógica con Gemelos Digitales de Aprendizaje (HDT - Human Digital Twins).

---

## 🌐 Demo en Vivo

Puedes acceder a la versión web en funcionamiento a través de GitHub Pages:
**[https://strawberry200421.github.io/edutwin-landing/](https://strawberry200421.github.io/edutwin-landing/)**

---

## 🚀 Características Principales

- **Visualización 3D e Interactiva**: Malla y partículas animadas que representan los nodos y estados cognitivos/socioemocionales.
- **Simulador de Gemelo Digital en Vivo**: Módulo interactivo que permite ajustar variables de un estudiante modelo y predecir el impacto de intervenciones pedagógicas en tiempo real.
- **Modos Claro y Oscuro**: Sistema adaptativo con selector de tema y paletas visuales modernas.
- **Fundamentación Pedagógica y Metodológica**: Explicación de los marcos teóricos, dimensiones analizadas y arquitectura del laboratorio.

---

## 📂 Estructura del Proyecto

```text
├── index.html           # Página principal de entrada (GitHub Pages)
├── Main.dc.html         # Archivo fuente del componente interactivo
├── support.js           # Motor de renderizado y lógica del componente
├── vendor/              # Dependencias de React y ReactDOM en runtime
├── assets/              # Recursos gráficos y multimedia
└── .github/workflows/   # Despliegue automatizado continuo a GitHub Pages
```

---

## 🛠️ Ejecución Local

Si deseas probar el proyecto de forma local:

1. Clona el repositorio:
   ```bash
   git clone https://github.com/strawberry200421/edutwin-landing.git
   cd edutwin-landing
   ```

2. Inicia un servidor web local (por ejemplo con Python):
   ```bash
   python -m http.server 8000
   ```

3. Abre en tu navegador `http://localhost:8000`.
