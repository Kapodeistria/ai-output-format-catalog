# AI Output Format Catalog

A library of **116 standardized output format tags** for AI prompts. Use these codes to specify your desired output format.

## Usage

Reference any tag in your prompt:

```
"Format the output as JSNARR"          → JSON array
"Give me a CMPTBL of the options"      → Comparison table
"Show this as FLWCHT"                  → ASCII flowchart
"Write this in EMLFMT"                 → Email format
"Present as USRSTY"                    → User story format
```

## Browse Formats

- **[Playground](playground.html)** - Interactive browser with search, filtering, and examples
- **[Full Reference](ai-output-formatting-tags.md)** - Complete catalog of all 116 tags

## Categories

| Category | Count | Examples |
|----------|-------|----------|
| Structured Data | 13 | `JSNARR` `JSNOBJ` `YAMLCF` `CSVDAT` |
| Markup & Documentation | 13 | `MDTXT` `HTMLPG` `LATEXF` |
| Lists & Enumerations | 12 | `BULLST` `NUMBLST` `CHKLST` |
| Tables & Grids | 10 | `MDTABL` `CMPTBL` `KANTBL` |
| Code & Technical | 18 | `CODEBL` `APIREQ` `SQLQRY` |
| Diagrams & Visualizations | 16 | `FLWCHT` `MERMAD` `TREEDI` |
| Communication | 10 | `EMLFMT` `SLKMSG` `TICKFM` |
| Academic & Writing | 12 | `CITAPA` `ABSTRK` `ESSYFM` |
| Data & Analysis | 10 | `STATBL` `METRCF` `FORMLA` |
| Specialized | 26 | `USRSTY` `FAQFMT` `CHGLOG` |

## License

MIT
