```
Usage: xgrep <XPath expression> [<file> ...]

Options:
  -h  Treat input as HTML
  -d  Don't strip off default namespaces
  -s  Preserve whitespace in XML mode
  -c  Only show a count of matching nodes, not the nodes themselves
  -r  Don't recurse into result nodes for output
  -f  Suppress printing of filenames when multiple files are searched
  -?  Display this help text
  -nprefix=href  Register a namespace prefix

Options may be specified at any point in the command; they will apply to all
subsequent files.  All options are toggles, and so can be used multiple times
to alter behaviour per file.
```
