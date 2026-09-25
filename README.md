# Traducción de Starsector al Español

En progreso; este proyecto es un fork del proyecto de [mipsou](https://github.com/mipsou/starsector_lang_pack_fr). Muchas gracias a él y por supuesto a los desarrolladores de Starsector.

---

## Instalación

1. Descarga el archivo [ZIP con la última versión](https://github.com/carlosgmz/starsector_lang_pack_es/releases/latest)
2. Extrae el contenido en la carpeta `mods/` de Starsector
3. Activa el mod en el launcher
4. **Recomendado empezar una partida nueva**


## Qué está traducido

| Contenido | Archivos | Estado |
|---------|----------|------|
| Diálogos de la campaña | rules.csv (40.000+ líneas) | ✅ |
| Descripciones, armas, naves | descriptions.csv | ✅ |
| Habilidades (40 skills) | skill_data.csv | ✅ |
| Modificaciones del casco (120) | hull_mods.csv | ✅ |
| Armamento (182) | weapon_data.csv | ✅ |
| Sistemas de nave | ship_systems.csv | ✅ |
| Misiones de combate (14) | mission_text.txt | ❌ |
| Facciones y rangos | .faction, default_ranks.json | ✅ |
| Planetas, mercancías, industrias | planets.json, commodities.csv, etc. | ✅ |
| Codex (combate, tecnología, UI) | spacers_manual_*.txt | ✅ |
| Nombres de naves (2187+) | ship_names.json | ✅ |


## Limitaciones conocidas

Algunos textos permanecen en inglés porque están hardcodeados en el motor Java:
- Interfaz (habilidades, información...)
- Tutorial inicial
- Algunas opciones de diálogo e interacciones
- Panel de despliegue ("Your forces", "Held in reserve")
- Etiquetas del Codex ("Ships", "Logistical data")
- Etiquetas de combate (FLUX, HULL, CR)
- Creación del personaje ("Name", "Sector Age")
- Variables de género y otras ("woman", "He"/"She", etc)


## Informar de un error

[Abrir un issue](https://github.com/carlosgmz/starsector_lang_pack_es/issues)


## Contacto

También puedes enviar un correo a `carlosgmzes@proton.me`


## Licencia

[EUPL 1.2](LICENSE)
