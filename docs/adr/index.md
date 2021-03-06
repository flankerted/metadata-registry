# Architectural Decision Records

This is a location to record all architecture decisions in the Oasis Metadata
Registry project via [Architectural Decision Records] (ADRs).

<!-- markdownlint-disable line-length -->
[Architectural Decision Records]: https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions.html
<!-- markdownlint-enable line-length -->

## Format

Each record has a unique number associated with it to make it easier to
cross-reference them. The records are stored as Markdown files in this
directory, named using the following convention:

```
<adr-number>-<short-title>.md
```

Where:

* `<adr-number>` is the assigned zero-padded ADR number.
* `<short-title>` is the ADR's title in [Kebab case].

The content of each ADR should follow [the template]. In short, an ADR should
provide:

* a changelog of all modifications so far,
* context on the relevant goals and the current state,
* proposed changes to achieve the goals,
* summary of pros and cons,
* references and
* the decision that was made.

[Kebab case]: https://en.wikipedia.org/wiki/Letter_case#Special_case_styles
[the template]: template.md

## Process for Creating New ADRs

There is a lightweight process for proposing, discussing and deciding on ADRs:

* In your branch, create a new ADR file in `docs/adr` following the convention
  and template specified above.
* Update the index of current records below.
* Create a pull request and mark it as ready for review. The commit message for
  introducing an ADR should have the title of the ADR, following by a short
  summary:

  ```
  ADR 0000: Architectural Decision Records

  Introduce architectural decision records (ADRs) for keeping track of
  architecture decisions in a transparent way.
  ```

* The ADR will be discussed by other members of the community and the project
  committers. After a sufficient amount of discussion, acceptance or rejection
  decision will be taken in accoordance with the governance process and the
  pull request will be merged, introducing a new ADR.

After the ADR is merged an implementation may be undertaken by following the
contribution process.

## Current Records

The following records currently exist:

<!-- markdownlint-disable line-length -->
* [ADR-0000](0000-architectural-decision-records.md) - Architectural Decision Records
* [ADR-0001](0001-entity-metadata.md) - Entity Metadata
<!-- markdownlint-enable line-length -->
