# FauxHate Social Media Corpus

## Overview

The FauxHate Social Media Corpus is a publicly available annotated dataset designed for multi-task natural language processing research on harmful and misleading social media content.

The dataset supports the following tasks:

* Fake Content Detection
* Hate Speech Detection
* Target Identification
* Severity Classification

## Dataset Statistics

* Total Samples: 21,011
* Data Format: CSV
* Domain: Social Media Comments
* Language: English

## Annotation Tasks

### Fake Content Detection

Binary classification:

* 0 = Non-Fake
* 1 = Fake

### Hate Speech Detection

Binary classification:

* 0 = Non-Hate
* 1 = Hate

### Target Identification

Multi-class classification:

* I = Individual
* O = Other
* R = Religion

### Severity Classification

Multi-class classification:

* L = Low
* M = Medium
* H = High

## Repository Structure

dataset/
documentation/
sample/

## Potential Applications

* Fake News Detection
* Hate Speech Detection
* Multi-task Learning
* Transformer-based NLP
* Social Media Analytics
* Content Moderation

## Citation

If you use this dataset, please cite the associated research publication.

## License

MIT License
