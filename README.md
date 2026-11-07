# Polaritones para mover excitaciones (v1.1)

Simulador de **polaritones** (mezcla luz–materia) como vía para transportar excitaciones más lejos que un excitón solo.

> **Estado:** hipótesis de ingeniería / modelo de juguete. No es un resultado experimental ni un dispositivo.

## Cómo usarlo
Abre `index.html` en el navegador (o por GitHub Pages). Mueve los controles y observa los resultados en vivo. No necesita instalación.

## Qué modela
- Dos osciladores acoplados: ramas E±, fracción de luz (Hopfield), velocidad de grupo, masa efectiva del fotón de cavidad.
- Vida a partir de Q y vida del excitón; tiempo de dispersión por desorden τ_s; caminata aleatoria persistente (balístico → difusivo).
- Caso base: alcance máx. ≈ 1.8 µm; excitón solo ≈ 7 nm.

## Límites (importante)
- Modelo de orden de magnitud, no de un material concreto; el resultado es muy sensible a τ_s.
- Los alcances publicados varían mucho: ≈ 0.27 µm (Pandya, arXiv:1909.03220) a más de 100 µm (Hou, Adv. Mater. 2020). El caso base no corresponde a ninguna de esas estructuras.
- Mover una excitación no es mover electricidad: falta convertirla en carga.

## Documentación
Informe asociado: `informe-3-polaritones-transporte-energia.docx` (si está en esta carpeta).

## Autoría
Mathias Zárate Amenero, Lima, Perú. Desarrollado junto con Claude (Anthropic): el código y los informes se elaboraron con asistencia de IA y los supuestos físicos están declarados arriba.
