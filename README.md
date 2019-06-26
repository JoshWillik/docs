[Index](docs/00_beancount_documentation.md)

# Beancount Google Doc converter

## Requirements

* python 3
* pandoc

## Usage

Export and convert single document:

```
python export.py download "1e44jtLyVRl2H2Pj4K3WUc66otAlTOFOc90-tsrFEQdo" --name "Generating Reports.docx"
python export.py convert "Generating Reports.docx" > "Generating Reports.md"
```

Export and convert all documents:

```
python crawl.py
```
