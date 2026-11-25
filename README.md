# UNO62 en 3D

Visor web de UNO62 Apartaestudios (Bogotá) y su barrio, y el diseño interior del apartaestudio.

- Ciudad: https://cubillos22.github.io/uno62-3d/
- Diseño interior: https://cubillos22.github.io/uno62-3d/interior/
- Modelo BIM (IFC4 y Revit 2026) del conjunto y del apto 317: https://cubillos22.github.io/uno62-3d/bim/ (botón «Fotos y Revit» con las vistas exportadas desde Revit)

Hecho con software libre (three.js, Blender) y datos abiertos.

## Fuentes y licencias
- Foto aérea: Ortoimagen urbana 2025 de Bogotá (5 cm), Secretaría Distrital de Planeación, publicada por IDECA. Licencia CC BY 4.0.
- Edificios: Catastro Bogotá / IDECA, capa Construcción (huella y número de pisos). La altura se estima a 2,8 m por piso.
- Calles, parques, río y árboles: © colaboradores de OpenStreetMap, ODbL.
- Relieve: Terrain Tiles (AWS Open Data, derivado de SRTM).
- Texturas de materiales: ambientCG (CC0). Fachadas en textura de los edificios lejanos: generadas con IA.
- Cielo (HDRI) y árbol (jacaranda): Poly Haven (CC0); el árbol se renderizó en Blender como sprite.
- Fotos: renders de Blender Cycles con la geometría del visor; la versión «como foto» es el render retocado con IA (ChatGPT), con personas, carros, árboles y cielo ilustrativos.
- UNO62: modelado a partir del ayudaventas publicado por el proyecto (representación aproximada, no planos de obra).
- Parqueaderos, bloque comunal y cerramiento de UNO62: planta general del ayudaventas (la altura del muro es supuesta).
- Lote de atrás (otro predio): ramadas y carros donde se ven en la ortoimagen 2025; los carros son ilustrativos.
- Carros, postes, tanques, nubes y los árboles de los parques son ilustrativos.
- Modelo BIM: generado con IfcOpenShell a partir del ayudaventas (planta general y renders), el plano de tipología 217-317-417 y los correos de entrega. El conjunto va como BIM general (torres, zonas comunes, parqueaderos, patio y cerramiento); el apto 317 lleva el diseño D completo, pieza por pieza. Cada elemento trae su fuente y su precisión. Los .rvt salen de importar el IFC en Revit 2026 por su API (importación de referencia) y llevan texturas CC0 de ambientCG teñidas con los colores del diseño; las texturas apuntan a la carpeta local del proyecto, así que en otro equipo se ven los colores. Es un modelo de referencia, no un plano de obra.
