# 🚚 Simulador de Costos de Transporte — Transporte Worldconect

Desafío práctico de JavaScript: sitio web para una empresa de transporte de cargas, con un simulador que calcula el costo final de un envío a partir del peso y el precio por kilo.

**🔗 Demo en vivo:** [ely1539.github.io/Rangel-desafio3-js](https://ely1539.github.io/Rangel-desafio3-js/index.html)

![Preview del proyecto](./screenshots/home.png)
<!-- Reemplazá esta imagen y las de abajo por tus propias capturas (ver instrucciones al final) -->

---

## 📋 Descripción

Sitio multi-página para "Transporte Worldconect", una plataforma que conecta clientes con transportistas de carga. El foco del desafío fue practicar JavaScript puro: manejo de eventos, funciones y manipulación del DOM para construir un simulador de costos en tiempo real.

## ✨ Funcionalidades

- 🏠 Página de inicio con la propuesta de valor de la empresa y formulario de contacto
- 👤 Sección para clientes
- 🚛 Sección para transportistas
- 🧮 **Simulador de Ganancias**: calcula automáticamente, a partir de los kilos cargados y el precio por kilo:
  - Precio final
  - IVA
  - Comisión de transporte
  - Ganancias totales

## 🛠️ Stack técnico

| Categoría | Tecnología |
|---|---|
| Estructura | HTML5 |
| Estilos | CSS3 / Bootstrap |
| Lógica | JavaScript (vanilla) |
| Deploy | GitHub Pages |

## 🧠 Qué practiqué con este desafío

- Captura de datos de formularios y validación básica de inputs.
- Funciones de cálculo encadenadas (precio final → IVA → comisión → ganancia neta).
- Manipulación del DOM para mostrar los resultados sin recargar la página.
- Organización de un sitio en múltiples páginas HTML enlazadas entre sí.

## 🚀 Cómo verlo localmente

Al ser un proyecto de HTML/CSS/JS sin build tool, alcanza con clonarlo y abrir `index.html` en el navegador:

```bash
git clone https://github.com/Ely1539/Rangel-desafio3-js.git
cd Rangel-desafio3-js
# abrí index.html en tu navegador, o usá una extensión como Live Server
```

## 👤 Autor

**Ely Rangel**
- GitHub: [@Ely1539](https://github.com/Ely1539)
- LinkedIn: [in/elyrangel](https://www.linkedin.com/in/elyrangel/)
- Email: elyrodolforangelhurtado@gmail.com

---

### 📸 Nota sobre las capturas

Este README usa una imagen de ejemplo en `./screenshots/home.png` que todavía no existe en tu repo. Para completarlo:

1. Entrá a la [demo en vivo](https://ely1539.github.io/Rangel-desafio3-js/index.html) y sacá 2-3 capturas: home y el simulador con un cálculo ya hecho.
2. Creá una carpeta `screenshots/` en la raíz del repo y subí ahí las imágenes.
3. Actualizá los nombres de archivo en este README si usás otros nombres.

### 🔧 Nota técnica pendiente

La carpeta de imágenes se llama `imagenes.css`, lo cual puede confundir (no es una carpeta de estilos). Si tenés tiempo, renombrala a `imagenes/` o `assets/` y actualizá las rutas en el HTML — es un detalle chico pero que un ojo técnico nota.
