# AI Coding Agent Instructions

## Project Overview

AI Output Format Catalog: 116 standardized tags for formatting AI outputs consistently.

## File Structure

```
README.md                    # Overview with collapsible category tables
ai-output-formatting-tags.md # Complete 116-tag reference
playground.html              # Interactive browser (single-file, no dependencies)
llms.txt                     # LLM navigation file
```

## Tag Format

Tags are 4-8 uppercase letters. Examples:
- `JSNARR` = JSON Array
- `MDTABL` = Markdown Table
- `CODEBL` = Code Block

## Usage Pattern

Users include tags in prompts:
```
"Format this as JSNARR"
"Give me a CMPTBL comparing X and Y"
```

## When Modifying

1. Update `ai-output-formatting-tags.md` for tag definitions
2. Update `playground.html` JavaScript `formats` array for interactive browser
3. Update `README.md` collapsible category tables
4. Keep all three in sync

## Code Style

- HTML: Single-file, inline CSS/JS, no external dependencies
- Markdown: GitHub Flavored Markdown, consistent heading hierarchy
- No build process required

## Boundaries

- Never remove existing tags without explicit request
- Never add tags that duplicate existing functionality
- Keep playground.html as single self-contained file
