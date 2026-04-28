# Geoinformatics 2026 — Jupyter Book

This repository contains the Jupyter Book for the Geoinformatics 2026 conference programme and proceedings.

## Structure

```
geoinformatics_2026/
├── _config.yml          # Book configuration
├── _toc.yml             # Table of contents
├── intro.md             # Landing page
├── programme/           # Programme overview and parallel-session slot pages
├── keynotes/            # One page per keynote speaker (keynote_01.md … keynote_07.md)
└── sessions/            # Thematic sessions
    └── session_<id>/
        ├── index.md     # Session overview
        └── paper_<id>.md  # One page per abstract/paper
```

## Building

```bash
pip install -r requirements.txt
jupyter-book build geoinformatics_2026/
# Output will be in geoinformatics_2026/_build/html/
```

## Content notes

- **Keynote speaker introductions** in `keynotes/keynote_0X.md` contain dummy placeholder text.  
  Replace the bio and abstract with content provided by each speaker.
- **Session titles** for sessions labelled `New_XX` are auto-generated keyword clusters.  
  These should be replaced with proper titles once confirmed by session chairs.
- Character encoding in abstracts has been partially cleaned; a final editorial pass is recommended.
