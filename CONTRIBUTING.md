# How to challenge a component, and how to contribute

The framework claims to have invented nothing: every component cites the source it came from. That claim is testable, and this page is where it is tested.

## Challenging a component

Open an issue with the label `challenge` and the component's code in the title. A challenge succeeds when it shows one of three things:

1. **The provenance is wrong.** The source cited does not say what the component says it says. Quote the clause or page of the source; the catalog does not reproduce sources, so the challenge should cite, not paste.
2. **A more prescriptive source exists.** Another of the twenty-seven sources, or a revision of one, names fields, scales, thresholds or prohibitions where the cited source only describes (second principle: the most prescriptive version wins).
3. **The component conflicts with another.** Two components cannot both be satisfied by one register, one control or one process; show the conflict with an example.

A challenge that proposes a component no source supports is answered but not adopted: that would be the first invented component.

## What happens next

The maintainer answers every challenge in the issue. A successful challenge produces a patch, minor or major release under the rules in `catalog/README.md`, with the change and the challenger credited in `CHANGELOG.md`. A failed challenge stays open for thirty days for others to add evidence, then is closed with the reason recorded.

## Contributing

- **Mapping sheets** (`mappings/`): a filled sheet for an entry program you run, as a pull request.
- **Schema adoption** (`schema/`): if you have used one of the proposed schemas in a running register, open an issue labelled `schema-adopted`; the proposal is promoted when someone other than the author has used it.
- **Research results** (`research-agenda.md`): a result that confirms or refutes a claim, as an issue labelled `result`, with the design, the data and the finding.
- **Corrections** to text: pull request.

By contributing you agree that your contribution is released under the repository's licences (CC BY 4.0 for text, CC0 1.0 for schemas).
