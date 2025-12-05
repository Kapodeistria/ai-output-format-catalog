# AI Output Formatting Tag Catalog

A comprehensive library of 116 standardized output format tags for quick reference. Use these codes to specify your desired output format without additional explanation.

---

## Structured Data Formats

| Code | Format Name | Description |
|------|-------------|-------------|
| `JSNARR` | JSON Array | Bracketed list of items in JSON syntax; for APIs and data interchange |
| `JSNOBJ` | JSON Object | Key-value pairs in curly braces; for structured data payloads |
| `JSNNST` | JSON Nested | Multi-level JSON with embedded objects/arrays; for complex hierarchies |
| `YAMLCF` | YAML Config | Indentation-based key-value pairs; for configuration files |
| `YAMLLST` | YAML List | Dash-prefixed items in YAML; for ordered sequences in configs |
| `XMLDOC` | XML Document | Angle-bracket tags with attributes; for markup and data exchange |
| `XMLSNP` | XML Snippet | Partial XML fragment; for showing relevant portions of XML structures |
| `TOMLCF` | TOML Config | Section headers with key=value pairs; for Rust/Python configs |
| `INICFG` | INI Config | [Section] headers with key=value; for legacy Windows-style configs |
| `CSVDAT` | CSV Data | Comma-separated values with header row; for tabular data export |
| `TSVDAT` | TSV Data | Tab-separated values; for spreadsheet-compatible tabular data |
| `ENVFIL` | ENV File | KEY=value pairs on lines; for environment variable definitions |
| `PRPFIL` | Properties File | Java-style key=value configuration; for application settings |

---

## Markup & Documentation

| Code | Format Name | Description |
|------|-------------|-------------|
| `MDTXT` | Markdown Text | Standard Markdown with headers/emphasis; for documentation and READMEs |
| `MDFMT` | Markdown Formatted | Rich Markdown with links, images, emphasis; for styled documents |
| `GFMEXT` | GitHub Flavored MD | Extended Markdown with task lists and tables; for GitHub repos |
| `HTMLFR` | HTML Fragment | Partial HTML elements; for embedding in existing pages |
| `HTMLPG` | HTML Page | Complete HTML document with head/body; for standalone web pages |
| `HTMLTB` | HTML Table | Table element with rows and cells; for structured web data |
| `RSTDOC` | reStructuredText | Python-style documentation markup; for Sphinx documentation |
| `ASCDOC` | AsciiDoc | Documentation with section titles; for technical books and manuals |
| `LATEXF` | LaTeX Formula | Math typesetting with backslash commands; for equations and papers |
| `LATEXD` | LaTeX Document | Full document class with preamble; for academic papers |
| `TEXMTH` | TeX Math Block | Inline or display math expressions; for rendering mathematics |
| `BBCODE` | BBCode | Forum-style [tag] formatting; for bulletin board posts |
| `WIKITX` | Wiki Markup | MediaWiki-style formatting; for Wikipedia-like content |

---

## Lists & Enumerations

| Code | Format Name | Description |
|------|-------------|-------------|
| `BULLST` | Bullet List | Unordered list with dash or dot markers; for non-sequential items |
| `NUMBLST` | Numbered List | Ordered list with numeric prefixes; for sequential steps |
| `ALPLST` | Alpha List | Lettered list (a, b, c); for categorical sublists |
| `ROMLST` | Roman Numeral List | i, ii, iii prefixed items; for formal outlines |
| `CHKLST` | Checklist | [ ] and [x] prefixed items; for task tracking |
| `NESTLS` | Nested List | Multi-level indented lists; for hierarchical information |
| `DEFNLS` | Definition List | Term-definition pairs; for glossaries and FAQs |
| `PROLS` | Prose List | Inline comma-separated items; for embedded enumerations |
| `ICONLS` | Icon List | Emoji or symbol prefixed items; for visual categorization |
| `TIMLST` | Timeline List | Date-prefixed chronological items; for event sequences |
| `RANKLST` | Ranked List | Numbered items with explicit ranking; for leaderboards |
| `GRPLST` | Grouped List | Categorized sublists under headers; for organized collections |

---

## Tables & Grids

| Code | Format Name | Description |
|------|-------------|-------------|
| `MDTABL` | Markdown Table | Pipe-delimited columns with alignment; for docs and READMEs |
| `ASCTBL` | ASCII Table | Box-drawn table with +|-| characters; for terminal output |
| `GRIDTB` | Grid Table | Dense grid with column separators; for fixed-width displays |
| `PIVTBL` | Pivot Table | Rows and columns with aggregated values; for data summaries |
| `CMPTBL` | Comparison Table | Side-by-side feature/option comparison; for decision matrices |
| `MATTBL` | Matrix Table | Row/column intersection grid; for cross-referencing |
| `CALEND` | Calendar Grid | Month view with day cells; for date-based planning |
| `SPRDSH` | Spreadsheet | Cell-referenced grid with formulas; for calculations |
| `KANTBL` | Kanban Board | Column-based status cards; for workflow visualization |
| `HEATMP` | Heatmap Grid | Values with intensity indicators; for density visualization |

---

## Code & Technical

| Code | Format Name | Description |
|------|-------------|-------------|
| `CODEBL` | Code Block | Fenced code with syntax highlighting; for source code display |
| `CODEIN` | Inline Code | Backtick-wrapped text; for inline technical references |
| `PSUDOC` | Pseudocode | Language-agnostic algorithm steps; for logic explanation |
| `SHLCMD` | Shell Command | Terminal commands with $ prefix; for CLI instructions |
| `SHLOUT` | Shell Output | Command results without prompt; for expected output |
| `REGEXF` | Regex Pattern | Regular expression with explanation; for pattern matching |
| `SQLQRY` | SQL Query | Formatted SELECT/INSERT statements; for database operations |
| `APIREQ` | API Request | HTTP method + endpoint + body; for REST documentation |
| `APIRES` | API Response | Status code + headers + body; for API response examples |
| `CURLCM` | cURL Command | Complete curl invocation; for API testing examples |
| `DIFFPT` | Diff Patch | +/- line prefixes showing changes; for code reviews |
| `LOGFMT` | Log Format | Timestamp + level + message; for logging output |
| `ERRFMT` | Error Format | Error type, message, and stack; for debugging output |
| `CFGBLK` | Config Block | Application configuration section; for settings documentation |
| `FNCSIG` | Function Signature | Function name + params + return type; for API references |
| `CLSDEF` | Class Definition | Class structure with methods/props; for OOP documentation |
| `TYPDEF` | Type Definition | TypeScript/type alias notation; for type system docs |
| `SCMDEF` | Schema Definition | Field definitions with types; for data structure docs |

---

## Diagrams & Visualizations

| Code | Format Name | Description |
|------|-------------|-------------|
| `ASCART` | ASCII Art | Character-based illustration; for terminal-compatible graphics |
| `BOXDIA` | Box Diagram | Connected rectangles showing flow; for architecture diagrams |
| `FLWCHT` | Flowchart | Decision/process flow with arrows; for process documentation |
| `SEQDIA` | Sequence Diagram | Actor lifelines with messages; for interaction modeling |
| `TREEDI` | Tree Diagram | Hierarchical branching structure; for file systems or org charts |
| `MERMAD` | Mermaid Diagram | Text-based diagram syntax; for rendered diagrams |
| `PLANTU` | PlantUML | UML diagram notation; for software architecture |
| `GANTCH` | Gantt Chart | Timeline bars for tasks; for project scheduling |
| `GRAPHV` | Graphviz DOT | Node-edge graph notation; for network diagrams |
| `SPARKL` | Sparkline | Inline mini trend line; for embedded data trends |
| `BARCHT` | Bar Chart ASCII | Horizontal bar visualization; for simple comparisons |
| `PIECHR` | Pie Chart Text | Percentage breakdown list; for distribution display |
| `VENNDI` | Venn Diagram | Overlapping circle descriptions; for set relationships |
| `ORGCHT` | Org Chart | Hierarchical position tree; for organizational structure |
| `ERDIAG` | ER Diagram | Entity-relationship notation; for database modeling |
| `MINDMP` | Mind Map | Central topic with radiating branches; for brainstorming |

---

## Communication Formats

| Code | Format Name | Description |
|------|-------------|-------------|
| `EMLFMT` | Email Format | To/From/Subject headers + body; for email composition |
| `MEMOFM` | Memo Format | Formal internal communication; for business memos |
| `LETTFM` | Letter Format | Salutation/body/closing structure; for formal correspondence |
| `CHATFM` | Chat Format | Username: message style; for conversation logs |
| `SLKMSG` | Slack Message | Rich text with mentions/emojis; for team chat |
| `TWTTXT` | Tweet Format | Character-limited with hashtags; for social media |
| `PRSSRL` | Press Release | Headline/dateline/body/contact; for announcements |
| `NTFCTN` | Notification | Alert title + brief message; for push notifications |
| `SMSFRM` | SMS Format | Short conversational text; for mobile messaging |
| `TICKFM` | Ticket Format | ID/summary/description/status; for issue tracking |

---

## Academic & Writing

| Code | Format Name | Description |
|------|-------------|-------------|
| `ABSTRK` | Abstract | Concise summary paragraph; for paper introductions |
| `CITAPA` | APA Citation | Author-date reference format; for academic papers |
| `CITMLA` | MLA Citation | Author-page reference format; for humanities papers |
| `CITBIB` | BibTeX Entry | @type{key, fields}; for LaTeX bibliographies |
| `OUTLNE` | Outline | Hierarchical numbered sections; for document planning |
| `FOOTNT` | Footnote | Superscript number + note text; for citations/asides |
| `BLCKQT` | Block Quote | Indented quoted passage; for extended citations |
| `THESST` | Thesis Statement | Single assertive sentence; for argument papers |
| `ANNBIB` | Annotated Bibliography | Citation + summary paragraph; for research papers |
| `EXCSM` | Executive Summary | Key points and recommendations; for business reports |
| `LITRVW` | Literature Review | Source synthesis paragraphs; for research context |
| `ESSYFM` | Essay Format | Intro/body/conclusion structure; for academic writing |

---

## Data & Analysis

| Code | Format Name | Description |
|------|-------------|-------------|
| `STATBL` | Statistics Block | Mean/median/mode/std values; for data summaries |
| `SUMTBL` | Summary Table | Aggregated metrics in rows; for analysis results |
| `KEYVAL` | Key-Value Pairs | Label: Value on each line; for simple data display |
| `METRCF` | Metrics Format | KPI name + value + trend; for dashboards |
| `FORMLA` | Formula Display | Mathematical expression; for calculations |
| `ALGTHM` | Algorithm Block | Numbered steps with conditions; for process definition |
| `MATRXF` | Matrix Format | Rows of space-separated numbers; for linear algebra |
| `VECFMT` | Vector Format | Bracketed comma-separated values; for array display |
| `HISTGR` | Histogram Text | Frequency distribution bars; for data distribution |
| `SCTTXT` | Scatter Text | (x,y) coordinate pairs; for point data |

---

## Specialized Formats

| Code | Format Name | Description |
|------|-------------|-------------|
| `RCPEFM` | Recipe Format | Ingredients + instructions; for cooking directions |
| `PRDLST` | Product Listing | Name/price/description; for e-commerce |
| `FAQFMT` | FAQ Format | Q: / A: paired entries; for help documentation |
| `TUTFMT` | Tutorial Steps | Numbered how-to instructions; for learning guides |
| `REVFMT` | Review Format | Rating + pros/cons + summary; for evaluations |
| `PRSCRD` | Scorecard | Category + score grid; for assessments |
| `AGRFMT` | Agenda Format | Time + topic list; for meeting planning |
| `MINFMT` | Minutes Format | Attendees/decisions/actions; for meeting records |
| `PROJPL` | Project Plan | Phases/tasks/owners/dates; for project management |
| `USRSTY` | User Story | As a/I want/So that; for agile development |
| `REQFMT` | Requirements | ID + description + priority; for specifications |
| `TCASFT` | Test Case | Given/When/Then structure; for BDD testing |
| `CHGLOG` | Changelog | Version + date + changes; for release notes |
| `READMF` | README | Project overview template; for repository docs |
| `LCNSFM` | License Block | Copyright + terms; for legal notices |
| `CREDTS` | Credits | Role: Name list; for acknowledgments |
| `GLOSSY` | Glossary | Term: Definition entries; for terminology |
| `FRSTCK` | Feature Spec | Problem/solution/acceptance; for product specs |
| `SWOTFM` | SWOT Analysis | Strengths/Weaknesses/Opportunities/Threats grid; for strategic planning |
| `PROSCO` | Pros/Cons | Two-column advantages/disadvantages; for decision support |
| `QAFRMT` | Q&A Thread | Nested question-answer pairs; for forum-style content |
| `CMDREF` | Command Reference | Command + options + examples; for CLI documentation |
| `APIDOC` | API Documentation | Endpoint/params/response/example; for developer guides |
| `ERRMSG` | Error Message | Code + message + resolution; for troubleshooting |
| `GUIDLN` | Guideline List | Do/Don't paired rules; for best practices |
| `RFPTPL` | RFP Template | Sections for proposals; for procurement |

---

## Quick Reference Index

### By Category

| Category | Codes |
|----------|-------|
| **JSON/Data** | `JSNARR` `JSNOBJ` `JSNNST` `CSVDAT` `TSVDAT` |
| **Config Files** | `YAMLCF` `YAMLLST` `TOMLCF` `INICFG` `ENVFIL` `PRPFIL` |
| **XML** | `XMLDOC` `XMLSNP` |
| **Markdown** | `MDTXT` `MDFMT` `GFMEXT` |
| **HTML** | `HTMLFR` `HTMLPG` `HTMLTB` |
| **Documentation** | `RSTDOC` `ASCDOC` `WIKITX` `BBCODE` |
| **LaTeX/Math** | `LATEXF` `LATEXD` `TEXMTH` `FORMLA` |
| **Lists** | `BULLST` `NUMBLST` `ALPLST` `ROMLST` `CHKLST` `NESTLS` `DEFNLS` `PROLS` `ICONLS` `TIMLST` `RANKLST` `GRPLST` |
| **Tables** | `MDTABL` `ASCTBL` `GRIDTB` `PIVTBL` `CMPTBL` `MATTBL` `CALEND` `SPRDSH` `KANTBL` `HEATMP` |
| **Code** | `CODEBL` `CODEIN` `PSUDOC` `SHLCMD` `SHLOUT` `REGEXF` `SQLQRY` `DIFFPT` `LOGFMT` `ERRFMT` |
| **API** | `APIREQ` `APIRES` `CURLCM` `APIDOC` |
| **Type/Schema** | `FNCSIG` `CLSDEF` `TYPDEF` `SCMDEF` `CFGBLK` |
| **Diagrams** | `ASCART` `BOXDIA` `FLWCHT` `SEQDIA` `TREEDI` `MERMAD` `PLANTU` `GANTCH` `GRAPHV` `ORGCHT` `ERDIAG` `MINDMP` |
| **Charts** | `SPARKL` `BARCHT` `PIECHR` `VENNDI` `HEATMP` `HISTGR` |
| **Communication** | `EMLFMT` `MEMOFM` `LETTFM` `CHATFM` `SLKMSG` `TWTTXT` `PRSSRL` `NTFCTN` `SMSFRM` `TICKFM` |
| **Academic** | `ABSTRK` `CITAPA` `CITMLA` `CITBIB` `OUTLNE` `FOOTNT` `BLCKQT` `THESST` `ANNBIB` `EXCSM` `LITRVW` `ESSYFM` |
| **Data Analysis** | `STATBL` `SUMTBL` `KEYVAL` `METRCF` `ALGTHM` `MATRXF` `VECFMT` `SCTTXT` |
| **Business** | `SWOTFM` `PROSCO` `PROJPL` `AGRFMT` `MINFMT` `RFPTPL` |
| **Dev/Agile** | `USRSTY` `REQFMT` `TCASFT` `CHGLOG` `READMF` `CMDREF` |
| **General** | `RCPEFM` `PRDLST` `FAQFMT` `TUTFMT` `REVFMT` `PRSCRD` `LCNSFM` `CREDTS` `GLOSSY` `FRSTCK` `QAFRMT` `GUIDLN` `ERRMSG` |

---

## Usage

Reference any tag in your prompt to specify output format:

```
"Format the output as JSNARR"          → JSON array
"Give me a CMPTBL of the options"      → Comparison table
"Show this as FLWCHT"                  → ASCII flowchart
"Write this in EMLFMT"                 → Email format
"Present as USRSTY"                    → User story format
```

---

## Version

- **Catalog Version:** 1.0
- **Total Tags:** 116
- **Last Updated:** 2025-12-05

---

## License

This catalog is provided for free use in AI prompting workflows.
