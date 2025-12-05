# 🛒 Asistente Virtual Inteligente para Supermercados

Este proyecto es un prototipo funcional de un chatbot desarrollado en Python, diseñado para gestionar consultas de stock, precios y promociones en tiempo real.

## 🚀 Funcionalidades Principales
- **Búsqueda Inteligente (Fuzzy Logic):** Implementación de algoritmos de distancia de Levenshtein (vía librería `thefuzz`) para detectar la intención del usuario incluso con errores de ortografía (ej: "arros" -> detecta "Arroz Gallo").
- **Gestión de Datos SQL:** Base de datos relacional (`sqlite3`) normalizada que administra el inventario, precios y reglas de negocio.
- **Interfaz Gráfica:** Frontend interactivo construido con `Gradio`, permitiendo una experiencia de usuario fluida vía web.
- **Lógica de Negocio:** El sistema identifica automáticamente productos con bajo stock y destaca las ofertas vigentes.

## 🛠️ Stack Tecnológico
- **Lenguaje:** Python 3.10+
- **Datos:** SQLite, Pandas
- **NLP / Lógica:** TheFuzz (String Matching)
- **Frontend:** Gradio

---
*Proyecto realizado como parte de mi formación continua en Data Analytics e Inteligencia Artificial.*
