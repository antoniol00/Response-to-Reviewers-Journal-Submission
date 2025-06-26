# Response to Reviewers – LaTeX Template

This repository contains a customizable LaTeX template for writing a formal response letter to the editor and reviewers after receiving peer-review feedback on an academic manuscript.

## Purpose

This template is designed to help researchers create a clear, professional, and well-structured reply to peer review comments. It supports:

- Structured responses with visually distinct formatting
- Parametrization of key fields (author, journal, manuscript title)
- Compatibility with Overleaf or local LaTeX setups

## File Structure

```
response-letter/
├── response_to_reviewers.tex   # Main LaTeX source file
├── README.md                   # Project description and usage
├── LICENSE                     # License
```

## How to Use

1. Customize Parameters

   Open `response_to_reviewers.tex` and edit the fields at the top:

   ```latex
   \newcommand{\AuthorName}{Your Name}
   \newcommand{\AuthorAffiliation}{Your Institution\\Your Department\\City, Country}
   \newcommand{\EditorName}{Editor’s Full Name}
   \newcommand{\EditorAffiliation}{Editor-in-Chief\\Journal Title\\Editor’s Institution}
   \newcommand{\ManuscriptTitle}{Title of Your Manuscript}
   \newcommand{\JournalName}{Journal Title}
   ```

2. Insert Reviewer Comments and Responses

   Use the provided structure:

   ```latex
   \textbf{Reviewer comment:} \textit{[Insert comment here]}
   \begin{tcolorbox}[title=\textbf{Response}]
   [Insert your detailed response here.]
   \end{tcolorbox}
   ```

3. Compile

   - On Overleaf: Upload the `.tex` file and click *Recompile*.
   - Locally: Use `pdflatex` or `xelatex` to compile the file into a PDF.

## Output

The final output is a formal letter addressed to the journal editor, including clearly formatted, point-by-point responses to reviewer comments, suitable for manuscript resubmission.

## License

This template is shared under the MIT License. You are free to use, modify, and distribute it.

---

2025 Antonio Lara Gutiérrez. Contributions welcome.
