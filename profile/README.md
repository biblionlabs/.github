# 📜 biblionlabs

> _“Βιβλίον” — del griego antiguo, “libro” o “rollo”.  
> En biblionlabs exploramos las Escrituras con precisión, código y lenguaje moderno._

## 🌍 About

**biblionlabs** es una organización dedicada al desarrollo de herramientas libres, modernas y reproducibles para el estudio, análisis y distribución de la **Biblia y sus textos relacionados**, con un enfoque en:

- **Lenguajes originales** (griego koiné, hebreo bíblico, arameo, copto)
- **Traducciones abiertas** y versiones históricas
- **Contexto histórico y lingüístico**
- **Infraestructura técnica libre**, escrita principalmente en **Rust**

Nuestra meta es construir un **ecosistema modular** que permita trabajar con el texto bíblico como si fuera **código fuente**:
indexable, relacionable, traducible, auditable y abierto.

## 🧠 Ideas principales

- 📖 **Texto como datos**  
  Cada versículo, palabra y referencia es una entidad relacional analizable.

- 🌐 **Idiomas originales incluidos**  
  Soporte completo para griego, hebreo, arameo, copto y latín.

- 🔗 **Cross References**  
  Relaciones entre versículos y libros integradas en la base de datos.

- 🧰 **Extensible por diseño**  
  Arquitectura modular (crates + servicios), para integrar nuevos módulos lingüísticos o versiones bíblicas fácilmente.

- 🦀 **100% Rust**  
  Seguridad, concurrencia y rendimiento en una sola base tecnológica.

- 🪶 **UI y visualización con Slint**  
  Aplicaciones gráficas multiplataforma para explorar y estudiar los textos bíblicos.

## ⚖️ Licencias

El ecosistema usa una **combinación de licencias abiertas** para balancear colaboración y protección de la libertad del software:

| Componente | Licencia | Propósito |
|-------------|-----------|------------|
| Core libraries (`common`, `db`) | [MPL 2.0](https://www.mozilla.org/en-US/MPL/2.0/) | Permite uso mixto (open / closed source) manteniendo apertura en los archivos modificados. |
| Servicios (`setup`, `provider`, `translate`) | [AGPL v3](https://www.gnu.org/licenses/agpl-3.0.html) | Garantiza que todo servicio derivado siga siendo libre, incluso si se ejecuta en la nube. |
| Interfaz gráfica (UI / Slint) | [GPL v3](https://www.gnu.org/licenses/gpl-3.0.html) | Requerido por Slint, asegura reciprocidad total para las herramientas visuales. |

> **Nota:** Todo código y contribución dentro de `biblionlabs` se publica bajo las mismas licencias.  
> Cualquier uso o redistribución debe cumplir con los términos correspondientes.

## 🌱 Filosofía

**biblionlabs** cree en el estudio libre, la preservación textual y la reproducibilidad.  
Nuestra misión es que el texto bíblico —en su forma más pura— sea accesible, auditable y utilizable por la comunidad académica, técnica y espiritual.

> “Open Scripture, Open Source.”

## 🤝 Contribuir

Queremos fomentar una comunidad abierta y respetuosa.  
Si deseas participar:

- Abre un **Issue** o **Discussion** con tus ideas.
- Crea un **Pull Request** con tus cambios.
- Consulta nuestro archivo [`CONTRIBUTING.md`](./CONTRIBUTING.md) (en desarrollo).

## 🏷️ Contact & Community

- 🌐 [biblionlabs.github.io](https://biblionlabs.github.io) *(futuro sitio de documentación)*
- 💬 Discussions y comunidad en GitHub
- 🧠 Proyectos experimentales y datasets abiertos

### 🕊️ _“Veritas per scripturam et codicem.”_  
> **“Verdad a través de la Escritura y el código.”**

© 2025 **biblionlabs** — Licensed under MPL 2.0 / AGPL v3 / GPL v3 where applicable.
