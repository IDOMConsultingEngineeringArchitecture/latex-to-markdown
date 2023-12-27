# LatexToMarkdownConverter

## Overview
`LatexToMarkdownConverter` is a Python class designed to efficiently convert LaTeX documents into Markdown format. This tool is particularly useful for academics, researchers, and anyone working with LaTeX who needs to port their documents to a Markdown-friendly environment, such as GitHub or Jekyll blogs.

## Features
- **File Reading and Writing**: Reads LaTeX files and writes converted content to Markdown files.
- **Robust Conversion**: Converts various LaTeX elements including figures, headers, tables, and special characters to their Markdown equivalents.
- **Content Processing**: Handles complex LaTeX features like citations, Greek letters, special commands, and glossary headings.
- **Table of Contents Creation**: Generates a Markdown Table of Contents based on document headings.
- **Efficient and Structured**: Optimized for performance with a clear, maintainable code structure.

## How to Use
1. **Initialization**: Create an instance of the `LatexToMarkdownConverter` class by passing the path to your LaTeX file.
   
   ```python
   from LatexToMarkdownConverter import LatexToMarkdownConverter

   converter = LatexToMarkdownConverter("/path/to/latex/file.tex")
