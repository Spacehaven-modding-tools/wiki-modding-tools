# Style
All code must be PEP8 compliant. The `pycodestyle` module can be used for this, and exceptions to the standard will be provided in the form of `setup.cfg` files at the root level of a given repository. Exceptions included here can be assumed to be the default.

Line length: 160 characters. This is longer than the default but still not so wide as to be unreasonable.  
E201: Disabled. A bit too aggressive by default but should still be avoided where possible.  
E701: Disabled. Sometimes useful to have statements on one line, for example `if (condition): continue`  
E241: Disabled. This is useful for alignment of key/value pairs in dictionary raws.  

Avoid indentation levels of more than four indents. Five indents is acceptable as long as it's only a few lines, subject to code reviewer's preference. Indents are four spaces, no exception. Configure your editor to substitute as needed if you need to.

# Functions
Functions should be concise and atomic. If a function is doing more than one thing, consider breaking it into multiple. If that one thing can't be summarized in a sentence or two, consider breaking it into multiple. If a function is too long to see on one screen, consider breaking it into multiple.

Nested functions are fine, but do not nest more than once.
