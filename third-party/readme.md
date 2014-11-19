*Third-party resources*

To minimize total repository size and respect potentially incongruous terms of 
redistribution, documentation and software produced by third-parties is not
checked into this repository. However, all sources are/were available on the public
internet. To retrieve third-party documentation, either:

  1.  Manually visit the URLs listed in the plain-text document `_documents.txt`
  2.  Run the Python script `_fetch.py` with the plain-text document as its
      single argument. 
      * On Windows machines, drag-n-dropping `_sources.txt` onto `_fetch.py` is
        generally sufficient. 
      * On other platforms, it may need to explicitly specified: 
        `python _fetch.py _sources.txt`

To retrieve no-cost software, substitute `_software.txt` in place of 
`_documents.txt` in the above steps.

Both `.txt` documents contain many lines of url/file name pairs. To be
parsed correctly: (1) only a single pair is allowed per line and (2) the file
name must follow the URL separated by *precisely* four spaces.
