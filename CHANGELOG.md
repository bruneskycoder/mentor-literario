# Changelog

Todos los cambios notables en este proyecto serán documentados en este archivo.

El formato está basado en [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
y este proyecto adhiere a [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.2.0] - 2026-11-24

### Added

- «Huella de la IA»: lo que agrega o cambia la IA se marca (negrita y tachado en el chat, azul en el archivo), con una línea de conteo por texto. Es del autor todo lo que él escribe, aunque nazca de un diagnóstico de la IA.
- «Texto a la vista»: antes de analizar o preguntar, el texto se muestra entero en el chat, con todas sus versiones.

### Changed

- Edición: la versión pulida pasa a ser una versión de referencia. Va marcada y explicada para que el autor reescriba las mejoras con sus palabras, se guarda dentro del análisis y nunca como «Última edición», que es la que escribe o aprueba el autor. Cuando el autor trae su reescritura, se compara con la referencia.

## [1.1.0] - 2026-11-24

### Added

- Sección «Archivo y versiones»: un único archivo compartido entre entornos de Claude, formato fijo por texto (última edición, decisiones abiertas, análisis, versiones anteriores, versión en crudo), crudo intocable, ninguna versión se borra, y alta de textos nuevos en el mapa del libro en curso.
- Las ubicaciones concretas se leen de una página privada del archivo del autor («Reglas del archivo literario»), no de la skill.

### Fixed

- Erratas de la copia del repositorio («reconstituí», «Diferencí», «comparacione») alineadas con la versión instalada.

## [1.0.0] - 2026-09-10

### Added

- Initial release of mentor-literario skill
- Complete analysis methodology with 11 analysis axes:
  - Núcleo temático
  - Arquitectura
  - Imágenes dominantes
  - Campos semánticos
  - Tensiones internas
  - Ritmo y musicalidad
  - Sintaxis
  - Densidad
  - Subtexto
  - Cierre
  - Voz
- Support for multiple genres: poetry, prose poetry, narrative, theatre
- Didactic component: technical concept + tension exercise for every analysis
- Corpus analysis mode for detecting patterns across multiple texts
- Inspiration mode for creative stimulation without replacing author's voice
- Preservation of Argentine cultural markers and regional language
- CC-BY-4.0 open license

### Documentation

- README.md with full skill description
- COMO-USAR.md with installation and usage guide
- CONTRIBUTORS.md with contribution guidelines
- .gitignore for common unnecessary files

---

## Planned for Future Releases

### v1.1.0

- [ ] Example analyses (before/after cases)
- [ ] Corpus analysis examples with real literary material
- [ ] Expanded guidance for non-fiction and academic writing

### v2.0.0

- [ ] Specialized variants (mentor-no-ficción, mentor-dramaturgia)
- [ ] Integration with other platforms
- [ ] Multi-language support

---

**Format Note**: Dates are in ISO 8601 format (YYYY-MM-DD).
