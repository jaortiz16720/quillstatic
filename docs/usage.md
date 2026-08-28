# Usage

The README covers the basics. This page collects the
longer examples and the notes that did not fit up front.

## Basic

```bash
mkdir posts && echo '# hello' > posts/first.md
python build.py
# site lands in dist/
```

## Notes

- RSS feed generation
- Single template, plain str.format, no Jinja
