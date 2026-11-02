# The eight core objects

Catalog version 1.0 · Table 19.1 of the book. Every layer reads and writes these objects; the three lenses add attributes to them. Objects typed by a published schema are adopted as formats (see `schema/`); the others are framework proposals until someone other than the author has used them.

| Object | Key attributes | Typed by | Relationships |
|---|---|---|---|
| Objective | Owner; tier; tolerance (variation accepted); aggregated likelihood of being missed [2] [11] [20] | Framework proposal (no open schema) | Referenced by risks and by indicators (through its tolerance) |
| Risk | Validated statement (condition, departure, asset, consequence); taxonomy node; process; tier; category; likelihood; consequence per objective; inherent, expected and measured exposure; response with planned and actual cost; owner; status; precision; opportunity flag [11] [3] [9] [12] | Register and detail-record schemas [9], with the framework's fields as extensions | Points to one or more objectives; referenced by controls, scenarios, indicators and events |
| Control | Hierarchy level; human dependence; expected decay; mode (prevention or detection); frequency; measured effectiveness; originating response; designer; assurer; design-gate record [10] [8] [18] | Framework proposal (no open schema) | Points to the risks it modifies; referenced by events (barrier that failed) and by assurance activities |
| Scenario | Triplet with uncertainty; variant (stress, reverse stress, climate); technique; version and retraction status of every input [11] [25] [13] | Framework proposal (no open schema) | Points to the risks it quantifies; referenced by hazards |
| Event | Incident-format fields in four sections; phase; type; origin; severity on a scale; kind (loss event, near miss, incident); cause; barrier that failed; recurrence [27] [14] [17] | Incident format [27], with barrier and recurrence as extensions | Points to the risk it realized and to the control that failed |
| Hazard | Persistent identifier; type; cluster; exposure; vulnerability; capacity; georeferenced loss history [24] [7] | Hazard dictionary [24] | Points to the scenarios it parameterizes |
| Indicator | Leading or lagging; threshold; breach record; escalation path; data lineage [17] [26] | Framework proposal (no open schema) | Points to the risk it watches and to the tolerance of the objective it tracks |
| Assurance activity | Line; provider; reliance assessment; twelve-month safeguard; opinion and date [18] [4] | Framework proposal (no open schema) | Points to the control it assured, and through it to the risk |
