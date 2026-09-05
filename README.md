# financial-model-sanity-checker
Financial models in Excel can contain errors that are difficult to spot manually. The app allows to automatically scan an Excel model, flag suspicious issues, and use GenAI to explain those issues in simple language

 Upload a workbook and get flagged issues — broken references, error values, hard-coded numbers overriding formulas, missing assumptions — explained in plain language.

**How it works?**

**Deterministic checks (openpyxl)** — catch mechanical errors: #REF!/#DIV/0! error values, references to sheets that don't exist, external workbook links


**AI reasoning (Google Gemini)** — interprets those findings in business context, scores overall model health (0–100), and explains each issue in plain language with a suggested fix
