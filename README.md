# new-jekyll-site-cookiecutter

## What's it for

This repository is a **Python *cookiecutter***; that is, a template with placeholders to be replaced when processed.

This particular template is for a git repository contianing everything required for a basic website using Github-Pages. It is possible to theme the website using one of several white listed [Jekyll](https://jekyllrb.com/) themes, but uses _minima_ by default.

## Installation

### Prerequisites

- Python
- cookiecutter
  ```pip
  pip install cookiecutter
  ```
## Usage

You can use this _cookiecutter_ from the command line by calling 

```python
cookiecutter bill-richards/new-jekyll-site-cookiecutter
```

you will be presented with a series of prompts asking for the values to use when applying the template.

Ideally however, this _cookicutter_ will be called by the [Jekyll Site Template](bill-richards/jekyll-site-template).
