---
name: pdf-to-latex
version: 0.2.0
description: >
  Convert PDF documents to LaTeX source code using MinerU-powered parsing. Transform academic papers, research articles, technical documents, and mathematical content from PDF into editable LaTeX/TeX files preserving equations, figures, tables, and bibliography. PDF转LaTeX, 学术论文转换, PDF转TeX源码, 论文格式转换.

  Supports PDF to LaTeX conversion, PDF to TeX transformation, academic paper conversion, research document reconstruction, mathematical typesetting recovery, equation extraction to LaTeX, bibliography conversion, figure and table preservation, document class detection, and scientific paper reformatting.

  Use when asked to "convert this PDF to LaTeX", "get LaTeX source from this paper", "turn this academic PDF into TeX", "extract LaTeX equations from PDF", "recreate this document in LaTeX", "reverse engineer this PDF to source", "I need the TeX code for this paper". Also handles "how do I edit this published paper in LaTeX", "can you reconstruct the LaTeX source", "convert my professor's PDF notes to LaTeX".

  Solves problems like: lost original LaTeX source files, need to edit a published paper, want to reformat academic document for different journal, PDF equations need to be in LaTeX syntax, collaborator sent PDF but need editable source, scanned paper needs LaTeX reconstruction. Powered by MinerU for accurate structure recognition preserving mathematical notation, cross-references, and academic formatting.
tags:
  - pdf
  - latex
  - tex
  - academic
  - conversion
  - equations
  - research
  - mineru
  - typesetting
  - mathematics
  - paper
  - document-conversion
---

# PDF To LaTeX

Convert PDF documents to LaTeX source code.

## System Prompt

You are a PDF to LaTeX conversion specialist. Use the MinerU tool to parse PDFs and reconstruct LaTeX source.

When the user provides a PDF for LaTeX conversion:
1. Use MinerU to parse the PDF structure, text, equations, figures, and tables
2. Reconstruct the LaTeX source preserving document structure and formatting
3. Convert mathematical equations to proper LaTeX notation
4. Preserve figure references, table formatting, and bibliography entries

Handle errors gracefully:
- If MinerU fails to parse certain elements, flag them with TODO comments
- If equations are complex or ambiguous, provide best-effort with notes
- Always output compilable LaTeX when possible
