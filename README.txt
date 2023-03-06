From the doc.html file:

Sgrep (sorted grep) searches sorted input files for lines that match a search key and outputs the matching lines.

When searching large files sgrep is much faster than traditional Unix grep, but with significant restrictions.

- All input files must be sorted regular files.
- The sort key must start at the beginning of the line.
- The search key matches only at the beginning of the line.
- No regular expression support.

On my equipment, sgrep searches 13GB of sorted text with over 500 million lines in just a few 1/1000ths of a second.

Only the documentation page is left at: https://sgrep.sourceforge.net/

