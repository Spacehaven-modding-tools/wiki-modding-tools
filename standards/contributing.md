# Workflow
All work MUST be done on a new branch. Once the work is done, submit a pull request to merge into the `develop` branch. Do not work off of develop directly - maintainers MAY do this occasionally for small changes such as documentation updates or typo fixes. All other contributors will have their work denied.

TODO: Branch structure/philosophy

# Commits: messages and frequency
Commit often and commit atomic. A single commit should encapsulate only a few changes at most, and it will always contain RELATED changes if it contains more than one. Commit messages should be descriptive, this does not mean commit messages should be long. "Fixed typos" or "PEP8 compliance" are good commit mesages if that's all that was changed. Longer messages start with a relevant verb and avoid exceeding 50 characters. If further information is needed, put it in the summary. Commit message summaries are done by including a blank line after the commit message and preceeding the summary:

```
Fixed implementation of broken_function()

Function was causing softlocks when called. Fixing this revealed
an issue in other_broken_function in file ./bad_file.py

Fixes: #123
```
