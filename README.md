# textbook-ner

## Dataset

This repo contains the TextbookNER dataset.

## Format

The files are in CoNLL format: each line contains one token and its corresponding gender label separated by a tab. Document boundaries are denoted by blank lines.

### Tag set:
1. `Other` - `Other` / `Out` (not part of a named entity)
2. `Person` - `Person` named entity
3. `Location` - `Location` named entity
4. `Organization` - 'Organization` named entity

## Pre-processing & Annotation

Annotated using the IO tagging scheme.

## Citing

If you find this dataset useful, please cite:

```
@phdthesis
{das2023genderbias,
  title={Automated Gender Bias Identification in Textbooks},
  author={Das, Sudeshna},
  year={2023},
  school={IIT Kharagpur}
}
```
