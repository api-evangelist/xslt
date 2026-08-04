# XSLT

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

XSLT (Extensible Stylesheet Language Transformations) is a W3C standard language for transforming XML documents into other formats such as HTML, plain text, or different XML structures. It uses template-based rules and XPath expressions to select and restructure XML data. The current version is XSLT 3.0, a W3C Recommendation since June 2017. XSLT is commonly used in data integration, document publishing, and enterprise data exchange pipelines. The primary production implementation is Saxon by Saxonica, which supports XSLT 3.0, XQuery 3.1, and XPath 3.1.

**Type:** Standard
**Website:** [https://www.w3.org/TR/xslt/](https://www.w3.org/TR/xslt/)
**Specification:** [XSLT 3.0 W3C Recommendation](https://www.w3.org/TR/xslt-30/)

## Specifications

| Version | Status | Published | XPath Version |
|---------|--------|-----------|---------------|
| [XSLT 3.0](https://www.w3.org/TR/xslt-30/) | W3C Recommendation | June 8, 2017 | XPath 3.1 |
| [XSLT 2.0](https://www.w3.org/TR/xslt20/) | W3C Recommendation | January 23, 2007 | XPath 2.0 |
| [XSLT 1.0](https://www.w3.org/TR/xslt-10/) | W3C Recommendation | November 16, 1999 | XPath 1.0 |

## JSON Schemas

Formal schemas documenting XSLT concepts:

| Schema | Description |
|--------|-------------|
| [xslt-stylesheet-schema.json](json-schema/xslt-stylesheet-schema.json) | Schema for XSLT stylesheet metadata and structure |
| [xslt-transformation-schema.json](json-schema/xslt-transformation-schema.json) | Schema for an XSLT transformation request/job |

## JSON Structures

| Structure | Description |
|-----------|-------------|
| [xslt-stylesheet-structure.json](json-structure/xslt-stylesheet-structure.json) | Document structure reference for XSLT stylesheets |
| [xslt-transformation-structure.json](json-structure/xslt-transformation-structure.json) | Structural reference for an XSLT transformation request |

## JSON-LD

| Context | Description |
|---------|-------------|
| [xslt-context.jsonld](json-ld/xslt-context.jsonld) | JSON-LD context mapping XSLT vocabulary to W3C and schema.org terms |

## Examples

| Example | Description |
|---------|-------------|
| [xslt-stylesheet-example.json](examples/xslt-stylesheet-example.json) | Example XSLT 3.0 stylesheet metadata document |
| [xslt-transformation-example.json](examples/xslt-transformation-example.json) | Example XSLT transformation request |

## Vocabulary

| File | Description |
|------|-------------|
| [xslt-vocabulary.yml](vocabulary/xslt-vocabulary.yml) | Normative vocabulary for XSLT specification terms, constructs, and implementations |

## Key Implementations

- **[Saxon-HE](https://github.com/Saxonica/Saxon-HE)** - Open-source XSLT 3.0 processor by Saxonica (Java/.NET/C)
- **[Xalan](https://xalan.apache.org/)** - Apache XSLT 1.0 processor for Java and C++
- **libxslt** - C library for XSLT 1.0, used widely in Linux environments

## Maintainers

**Kin Lane** - kin@apievangelist.com
