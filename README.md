# Beancount Documentation

* [Index](docs/00_beancount_documentation.md)

These documents in markdown format are automatically generated from [official Beancount Documentation](http://furius.ca/beancount/doc/index).

## Beancount Google Doc converter

### Installation

Install dependencies (python 3 is required):

```
pip install -r requirements.txt
```

### Usage

Export and convert single document:

```
python export.py document "100tGcA4blh6KSXPRGCZpUlyxaRUwFHEvnz_k9DyZFn4" doubleentry.docx
python export.py drawings "100tGcA4blh6KSXPRGCZpUlyxaRUwFHEvnz_k9DyZFn4" drawings
python export.py convert doubleentry.docx doubleentry.md --drawing-dir=drawings
```

Export and convert all documents:

```
python crawl.py
```
