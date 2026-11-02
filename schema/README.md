# Appendix C · The open register schema

**Version 1.0** · the version described by the first edition of *One Language for Risk* (2026).

The framework's third principle: where a schema exists, adopt the schema. Four objects are typed by published formats and are adopted as formats, not paraphrased as ideas; five have no open schema and are published here as proposals.

| Object | Typed by | Here |
|---|---|---|
| Risk (register row and detail record) | NIST IR 8286 Rev. 1 JSON schemas [9] | `register-row-extensions.schema.json`: the framework's extension fields; the base schemas are NIST's and are referenced, not copied |
| Event | FSB Format for Incident Reporting Exchange (FIRE), April 2025 [27] | adopted as published; barrier and recurrence as extensions (to be added in 1.1) |
| Hazard | UNDRR/ISC Hazard Information Profiles, June 2025 [24] | adopted as published; the dictionary's persistent identifiers are the values of `hazard_codes` |
| Software component | CISA SBOM minimum elements, draft August 2025 [15] | adopted as published (SPDX or CycloneDX) |
| Objective | framework proposal | `proposals/objective.schema.json` |
| Control | framework proposal | `proposals/control.schema.json` |
| Scenario | framework proposal | `proposals/scenario.schema.json` |
| Indicator | framework proposal | `proposals/indicator.schema.json` |
| Assurance activity | framework proposal | `proposals/assurance-activity.schema.json` |

A proposal stays a proposal until someone other than the author has used it in a running register; tell us in an issue labelled `schema-adopted`.

`examples/PAY-014.json` is the worked example of chapters 17 and 18 as a register row with the framework's extensions.

## Versioning

Same rule as the catalog: patch, minor, major, with a note for every release in `CHANGELOG.md`. A record carries the schema version it validates against (`schema_version`) and the catalog version it was scored under.

## Licence

The schemas are released under CC0 1.0 so that nothing stands between an implementer and the file.
