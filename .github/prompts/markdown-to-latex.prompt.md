# Convert Markdown to LaTeX

Convert the selected Markdown (.md) file to a LaTeX (.tex) file with the same base name.

## Instructions

1. **Create a proper LaTeX document** with appropriate document class and packages
2. **Convert Markdown syntax to LaTeX:**
   - `# Heading` → `\section{Heading}` (and subsections for ##, ###, etc.)
   - `**bold**` → `\textbf{bold}`
   - `*italic*` → `\textit{italic}`
   - Lists → `\begin{itemize}` or `\begin{enumerate}`
   - `[link](url)` → `\href{url}{link}`
   - Images → `\includegraphics{}`
   - Code blocks → `\begin{lstlisting}` or `\begin{verbatim}`
   - Tables → `\begin{tabular}`
3. **Escape LaTeX special characters** (`&`, `%`, `$`, `#`, `_`, `{`, `}`, etc.)
4. **Handle YAML frontmatter** (title, author, date) if present
5. **Ensure the LaTeX compiles** without errors

Output the converted content to a `.tex` file with the same base name as the input file.

