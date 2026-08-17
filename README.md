# Conexión 18+ (Puente 18+)

Prototipo de acompañamiento para la transición de pacientes pediátricos con
enfermedades crónicas, raras o complejas hacia los servicios de salud de
adultos. Desarrollado para la Hackatón Niño San Borja 2026 (INSN San Borja),
desafío "Puente 18+" — equipo Conexión Salud.

## Demo en vivo
https://emersonmadrid.github.io/puente18-demo/

## Qué es
Aplicación web de una sola página (`index.html`), sin dependencias externas,
sin backend y sin conexión a internet requerida. Todo el estado se guarda en
el `localStorage` del navegador. Sirve como prototipo funcional/demostrativo,
no como producto clínico terminado.

## Cómo usarlo o adaptarlo
1. Descarga `index.html` y ábrelo en cualquier navegador, o sírvelo con
   cualquier servidor estático (`python3 -m http.server`, GitHub Pages, etc.).
2. Todo el contenido, textos y datos de ejemplo están dentro del propio
   archivo (HTML + CSS + JavaScript plano), listos para leer y modificar.
3. El caso de uso demostrativo usa un paciente ficticio con Diabetes Mellitus
   tipo 1; el núcleo de navegación (ruta, checklist, autonomía, salud, citas)
   es independiente de la condición y reutilizable para otras enfermedades
   crónicas, raras o complejas.

## Documentación del producto
- [`docs/Definición de producto y alcance funcional preliminar.docx`](./docs/Definición%20de%20producto%20y%20alcance%20funcional%20preliminar.docx) — alcance, decisiones de producto y criterios de seguridad funcional.
- [`docs/Requerimientos funcionales.xlsx`](./docs/Requerimientos%20funcionales.xlsx) — lista de requerimientos funcionales (MUST/SHOULD) usados para construir el prototipo.

## Licencia
MIT — ver [LICENSE](./LICENSE). Uso, adaptación y redistribución libres,
reconociendo la autoría original.
