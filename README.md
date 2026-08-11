# Python Exceptions, Decoded

A searchable field guide to Python's built-in exceptions, grouped by cause, with what triggers each one and how to fix it. One self-contained HTML page, no build step.

**Live:** https://shazmoghaddam.github.io/python-exceptions/

## What it does

- Search every exception by name or meaning, with the matching text highlighted in the results
- Filter by cause, with shareable per-category links (for example `.../#io` for the file and OS errors)
- A "Most common" filter for the ones you hit again and again
- Keyboard: press `/` to jump to search, `Esc` to clear it
- Share button (uses the native share sheet, or copies the link) and Save as PDF
- Colour-coded classes and a link-preview card for social posts

## What's inside

42 exceptions across 7 classes:

- **Syntax & indentation** — the parse-time ones (SyntaxError, IndentationError, TabError)
- **Name & attribute** — names and attributes that do not resolve (NameError, AttributeError)
- **Type & value** — wrong type or wrong value (TypeError, ValueError, the Unicode errors)
- **Lookup & index** — missing keys and out-of-range indexes (KeyError, IndexError)
- **Arithmetic** — number errors (ZeroDivisionError, OverflowError)
- **Import, file & OS** — imports and the filesystem (ModuleNotFoundError, FileNotFoundError, PermissionError)
- **Runtime, iteration & system** — everything else, plus the base classes (RuntimeError, StopIteration, KeyboardInterrupt, Exception, BaseException)

Each card gives a one-line trigger and a plain-English explanation with the usual fix. The base classes (LookupError, ArithmeticError, OSError, Exception, BaseException) and the newer ExceptionGroup (Python 3.11+) are included so the hierarchy reads top to bottom.

## Put it live on GitHub Pages

1. Create a new public repo named `python-exceptions`.
2. Add `index.html` and `preview.png` to the root of the repo.
3. Settings, then Pages. Source: "Deploy from a branch", branch `main`, folder `/ (root)`, Save.
4. Give it a minute, then open https://shazmoghaddam.github.io/python-exceptions/

If you name the repo something else, update the three absolute URLs near the top of `index.html` (`canonical`, `og:url`, `og:image`).

## Files

- `index.html` — the page
- `preview.png` — the 1200x630 card shown when the link is shared

Made by Shaz Moghaddam.
