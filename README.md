<p align="center">
  <strong>AI Output Format Catalog</strong><br>
  <em>116 standardized tags for consistent AI output formatting</em>
</p>

<p align="center">
  <a href="#quick-start">Quick Start</a> •
  <a href="https://kapodeistria.github.io/ai-output-format-catalog/playground.html">Playground</a> •
  <a href="ai-output-formatting-tags.md">Full Reference</a> •
  <a href="#categories">Categories</a>
</p>

---

> A library of **116 standardized output format tags** for AI prompts. Use these codes to specify your desired output format without additional explanation.

## Quick Start

Reference any tag in your prompt:

```
"Format the output as JSNARR"          → JSON array
"Give me a CMPTBL of the options"      → Comparison table
"Show this as FLWCHT"                  → ASCII flowchart
"Write this in EMLFMT"                 → Email format
"Present as USRSTY"                    → User story format
```

**Most used tags:**

| Tag | Output | Use Case |
|-----|--------|----------|
| `JSNARR` | JSON Array | API responses, data interchange |
| `MDTABL` | Markdown Table | Documentation, comparisons |
| `BULLST` | Bullet List | Quick summaries, options |
| `CODEBL` | Code Block | Source code with syntax highlighting |
| `NUMBLST` | Numbered List | Sequential steps, instructions |

[↑ Back to top](#ai-output-format-catalog)

---

## Categories

<details>
<summary><strong>📊 Structured Data</strong> (13 tags)</summary>

| Tag | Name | Description |
|-----|------|-------------|
| `JSNARR` | JSON Array | Bracketed list of items; for APIs |
| `JSNOBJ` | JSON Object | Key-value pairs; for data payloads |
| `JSNNST` | JSON Nested | Multi-level JSON; for hierarchies |
| `YAMLCF` | YAML Config | Indentation-based; for configs |
| `YAMLLST` | YAML List | Dash-prefixed items; for sequences |
| `XMLDOC` | XML Document | Angle-bracket tags; for markup |
| `XMLSNP` | XML Snippet | Partial XML fragment |
| `TOMLCF` | TOML Config | Section headers; for Rust/Python |
| `INICFG` | INI Config | [Section] headers; legacy configs |
| `CSVDAT` | CSV Data | Comma-separated; for export |
| `TSVDAT` | TSV Data | Tab-separated; for spreadsheets |
| `ENVFIL` | ENV File | KEY=value; for environment vars |
| `PRPFIL` | Properties File | Java-style key=value |

</details>

<details>
<summary><strong>📝 Markup & Documentation</strong> (13 tags)</summary>

| Tag | Name | Description |
|-----|------|-------------|
| `MDTXT` | Markdown Text | Standard Markdown; for docs |
| `MDFMT` | Markdown Formatted | Rich Markdown with links/images |
| `GFMEXT` | GitHub Flavored MD | Task lists and tables |
| `HTMLFR` | HTML Fragment | Partial HTML elements |
| `HTMLPG` | HTML Page | Complete HTML document |
| `HTMLTB` | HTML Table | Table with rows and cells |
| `RSTDOC` | reStructuredText | Python-style; for Sphinx |
| `ASCDOC` | AsciiDoc | Section titles; for manuals |
| `LATEXF` | LaTeX Formula | Math typesetting |
| `LATEXD` | LaTeX Document | Full document with preamble |
| `TEXMTH` | TeX Math Block | Inline/display math |
| `BBCODE` | BBCode | Forum-style [tag] formatting |
| `WIKITX` | Wiki Markup | MediaWiki-style |

</details>

<details>
<summary><strong>📋 Lists & Enumerations</strong> (12 tags)</summary>

| Tag | Name | Description |
|-----|------|-------------|
| `BULLST` | Bullet List | Unordered with dash/dot markers |
| `NUMBLST` | Numbered List | Ordered with numeric prefixes |
| `ALPLST` | Alpha List | Lettered list (a, b, c) |
| `ROMLST` | Roman Numeral List | i, ii, iii prefixed |
| `CHKLST` | Checklist | [ ] and [x] for task tracking |
| `NESTLS` | Nested List | Multi-level indented |
| `DEFNLS` | Definition List | Term-definition pairs |
| `PROLS` | Prose List | Inline comma-separated |
| `ICONLS` | Icon List | Emoji/symbol prefixed |
| `TIMLST` | Timeline List | Date-prefixed chronological |
| `RANKLST` | Ranked List | Explicit ranking |
| `GRPLST` | Grouped List | Categorized sublists |

</details>

<details>
<summary><strong>📈 Tables & Grids</strong> (10 tags)</summary>

| Tag | Name | Description |
|-----|------|-------------|
| `MDTABL` | Markdown Table | Pipe-delimited columns |
| `ASCTBL` | ASCII Table | Box-drawn with +\|-\| |
| `GRIDTB` | Grid Table | Dense grid; fixed-width |
| `PIVTBL` | Pivot Table | Aggregated values |
| `CMPTBL` | Comparison Table | Side-by-side features |
| `MATTBL` | Matrix Table | Row/column intersection |
| `CALEND` | Calendar Grid | Month view with days |
| `SPRDSH` | Spreadsheet | Cell-referenced with formulas |
| `KANTBL` | Kanban Board | Column-based status cards |
| `HEATMP` | Heatmap Grid | Values with intensity |

</details>

<details>
<summary><strong>💻 Code & Technical</strong> (18 tags)</summary>

| Tag | Name | Description |
|-----|------|-------------|
| `CODEBL` | Code Block | Fenced with syntax highlighting |
| `CODEIN` | Inline Code | Backtick-wrapped |
| `PSUDOC` | Pseudocode | Language-agnostic algorithm |
| `SHLCMD` | Shell Command | Terminal commands with $ |
| `SHLOUT` | Shell Output | Command results |
| `REGEXF` | Regex Pattern | Regular expression explained |
| `SQLQRY` | SQL Query | Formatted statements |
| `APIREQ` | API Request | HTTP method + endpoint + body |
| `APIRES` | API Response | Status + headers + body |
| `CURLCM` | cURL Command | Complete curl invocation |
| `DIFFPT` | Diff Patch | +/- line prefixes |
| `LOGFMT` | Log Format | Timestamp + level + message |
| `ERRFMT` | Error Format | Type, message, stack |
| `CFGBLK` | Config Block | Configuration section |
| `FNCSIG` | Function Signature | Name + params + return |
| `CLSDEF` | Class Definition | Structure with methods |
| `TYPDEF` | Type Definition | TypeScript notation |
| `SCMDEF` | Schema Definition | Field definitions with types |

</details>

<details>
<summary><strong>📐 Diagrams & Visualizations</strong> (16 tags)</summary>

| Tag | Name | Description |
|-----|------|-------------|
| `ASCART` | ASCII Art | Character-based illustration |
| `BOXDIA` | Box Diagram | Connected rectangles |
| `FLWCHT` | Flowchart | Decision/process flow |
| `SEQDIA` | Sequence Diagram | Actor lifelines |
| `TREEDI` | Tree Diagram | Hierarchical branching |
| `MERMAD` | Mermaid Diagram | Text-based syntax |
| `PLANTU` | PlantUML | UML notation |
| `GANTCH` | Gantt Chart | Timeline bars |
| `GRAPHV` | Graphviz DOT | Node-edge notation |
| `SPARKL` | Sparkline | Inline mini trend |
| `BARCHT` | Bar Chart ASCII | Horizontal bars |
| `PIECHR` | Pie Chart Text | Percentage breakdown |
| `VENNDI` | Venn Diagram | Overlapping sets |
| `ORGCHT` | Org Chart | Hierarchical positions |
| `ERDIAG` | ER Diagram | Entity-relationship |
| `MINDMP` | Mind Map | Radiating branches |

</details>

<details>
<summary><strong>💬 Communication</strong> (10 tags)</summary>

| Tag | Name | Description |
|-----|------|-------------|
| `EMLFMT` | Email Format | To/From/Subject + body |
| `MEMOFM` | Memo Format | Formal internal communication |
| `LETTFM` | Letter Format | Salutation/body/closing |
| `CHATFM` | Chat Format | Username: message style |
| `SLKMSG` | Slack Message | Rich text with mentions |
| `TWTTXT` | Tweet Format | Character-limited + hashtags |
| `PRSSRL` | Press Release | Headline/dateline/body |
| `NTFCTN` | Notification | Alert title + message |
| `SMSFRM` | SMS Format | Short conversational |
| `TICKFM` | Ticket Format | ID/summary/status |

</details>

<details>
<summary><strong>🎓 Academic & Writing</strong> (12 tags)</summary>

| Tag | Name | Description |
|-----|------|-------------|
| `ABSTRK` | Abstract | Concise summary paragraph |
| `CITAPA` | APA Citation | Author-date reference |
| `CITMLA` | MLA Citation | Author-page reference |
| `CITBIB` | BibTeX Entry | @type{key, fields} |
| `OUTLNE` | Outline | Hierarchical numbered |
| `FOOTNT` | Footnote | Superscript + note |
| `BLCKQT` | Block Quote | Indented passage |
| `THESST` | Thesis Statement | Single assertive sentence |
| `ANNBIB` | Annotated Bibliography | Citation + summary |
| `EXCSM` | Executive Summary | Key points + recommendations |
| `LITRVW` | Literature Review | Source synthesis |
| `ESSYFM` | Essay Format | Intro/body/conclusion |

</details>

<details>
<summary><strong>📉 Data & Analysis</strong> (10 tags)</summary>

| Tag | Name | Description |
|-----|------|-------------|
| `STATBL` | Statistics Block | Mean/median/mode/std |
| `SUMTBL` | Summary Table | Aggregated metrics |
| `KEYVAL` | Key-Value Pairs | Label: Value lines |
| `METRCF` | Metrics Format | KPI + value + trend |
| `FORMLA` | Formula Display | Mathematical expression |
| `ALGTHM` | Algorithm Block | Numbered steps |
| `MATRXF` | Matrix Format | Space-separated rows |
| `VECFMT` | Vector Format | Bracketed values |
| `HISTGR` | Histogram Text | Frequency bars |
| `SCTTXT` | Scatter Text | (x,y) coordinate pairs |

</details>

<details>
<summary><strong>⚙️ Specialized</strong> (12 tags)</summary>

| Tag | Name | Description |
|-----|------|-------------|
| `RCPEFM` | Recipe Format | Ingredients + instructions |
| `PRDLST` | Product Listing | Name/price/description |
| `FAQFMT` | FAQ Format | Q: / A: pairs |
| `TUTFMT` | Tutorial Steps | Numbered how-to |
| `REVFMT` | Review Format | Rating + pros/cons |
| `PRSCRD` | Scorecard | Category + score grid |
| `AGRFMT` | Agenda Format | Time + topic list |
| `MINFMT` | Minutes Format | Attendees/decisions/actions |
| `PROJPL` | Project Plan | Phases/tasks/owners |
| `USRSTY` | User Story | As a/I want/So that |
| `REQFMT` | Requirements | ID + description + priority |
| `TCASFT` | Test Case | Given/When/Then |

</details>

<details>
<summary><strong>📄 Documentation</strong> (14 tags)</summary>

| Tag | Name | Description |
|-----|------|-------------|
| `CHGLOG` | Changelog | Version + date + changes |
| `READMF` | README | Project overview template |
| `LCNSFM` | License Block | Copyright + terms |
| `CREDTS` | Credits | Role: Name list |
| `GLOSSY` | Glossary | Term: Definition entries |
| `FRSTCK` | Feature Spec | Problem/solution/acceptance |
| `SWOTFM` | SWOT Analysis | Strengths/Weaknesses grid |
| `PROSCO` | Pros/Cons | Advantages/disadvantages |
| `QAFRMT` | Q&A Thread | Nested question-answers |
| `CMDREF` | Command Reference | Command + options |
| `APIDOC` | API Documentation | Endpoint/params/response |
| `ERRMSG` | Error Message | Code + message + resolution |
| `GUIDLN` | Guideline List | Do/Don't rules |
| `RFPTPL` | RFP Template | Proposal sections |

</details>

[↑ Back to top](#ai-output-format-catalog)

---

## Resources

- **[Interactive Playground](https://kapodeistria.github.io/ai-output-format-catalog/playground.html)** — Search, filter, and explore all 116 tags with examples
- **[Full Reference](ai-output-formatting-tags.md)** — Complete documentation of every tag

---

## License

MIT
