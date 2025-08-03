# Document-Reference-Converter
Transform your text documents with interactive reference hover tooltips
📚 Document Reference Converter
This is a simple, single-file HTML tool that converts plain text documents into an interactive web page. It automatically identifies section numbers and their definitions, then links any references to them with hover-over tooltips.

The tool is designed for documents that use a structured, numbered format, such as technical specifications, standards, or manuals.

Features
Automatic Reference Linking: The tool scans your document for common reference patterns like (3.1), see 8.2, clause 4.5, and (8.2, 8.3, and 8.5).

Interactive Tooltips: When you hover over a reference link, a tooltip appears displaying the full definition of that section.

Single-File Simplicity: Everything—HTML, CSS, and JavaScript—is contained in one file, making it easy to use, share, and run offline.

Robust Parsing: It correctly identifies section headers whether they are on their own line (e.g., 3.1) or have a title on the same line (e.g., 3.1 Asset).

Save as HTML: You can save the converted, interactive document as a standalone HTML file.

How to Use
Open the file: Simply open index.html in any modern web browser.

Paste your text: Copy the content of your structured document and paste it into the Input Document text area.

Convert: Click the Convert to HTML button.

Interact: The Interactive HTML Output section will show your converted document. Hover over any highlighted reference to see its definition.

Save (Optional): Click the Save as HTML File button to download the converted document for future use.

Supported Reference Formats
The converter's logic is built to recognize the following patterns:

Parentheses: (3.1), (6.1.2 a), (8.2, 8.3, and 8.5)

Preceded by keywords: see 8.2, clause 4.5, section 2.1, according to 7.3, in 5.4
