# XSLT

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
