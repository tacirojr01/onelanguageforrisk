# Appendix B · The component catalog

**Version 1.0** · the version described by the first edition of *One Language for Risk* (2026).

| File | Content |
|---|---|
| `components/C0.1.md` … `components/C6.5.md` | The forty-seven components: code, name, layer, what it requires, provenance, specification |
| `catalog.json` | The same forty-seven components as data (code, name, layer, requirement, provenance, source keys) |
| `lenses.md` | The three lenses: artificial intelligence; climate and physical hazards; third parties and components |
| `objects.md` | The eight core objects with their attributes, how each is typed and its relationships |
| `principles.md` | The seven principles of construction |
| `sources.md` | The twenty-seven sources: edition cited and date last checked |
| `glossary.md` | The resolved vocabulary, with retired terms kept as aliases |

## Layers

| Layer | Components |
|---|---|
| L0 Govern | C0.1, C0.2, C0.3, C0.4, C0.5 |
| L1 Frame | C1.1, C1.2, C1.3, C1.4, C1.5, C1.6, C1.7 |
| L2 Identify | C2.1, C2.2, C2.3, C2.4, C2.5, C2.6, C2.7 |
| L3 Analyze | C3.1, C3.2, C3.3, C3.4, C3.5, C3.6, C3.7, C3.8, C3.9 |
| L4 Respond | C4.1, C4.2, C4.3, C4.4, C4.5, C4.6, C4.7 |
| L5 Monitor | C5.1, C5.2, C5.3, C5.4, C5.5, C5.6, C5.7 |
| L6 Record, Assure and Report | C6.1, C6.2, C6.3, C6.4, C6.5 |

## Versioning

The catalog carries a three-part version number. The third number rises for a patch (a citation renumbered, a wording corrected, nothing an adopter built having to change). The second rises for a minor release (a field, a scale or a prohibition differs while the component keeps its code and purpose). The first rises for a major release (a component retired, replaced or added; a lens added; an object changed). Nothing is deleted: a retired component stays, marked retired, with the release that retired it and the reason. Nothing changes silently: every release has a note in `CHANGELOG.md`. The sources decide: the catalog moves when a source moves or when a challenge succeeds under `CONTRIBUTING.md`.
