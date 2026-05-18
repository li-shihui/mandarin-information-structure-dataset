# mandarin_Chinese_information_structure_dataset

This repository contains a Mandarin Chinese minimal-pair dataset targeting form--meaning mappings in information structure constructions.

The dataset includes five paradigms involving the *ba* and *bei* constructions:

- BA_le
- BA_negation
- BEI_negation
- BA_BEI_SVO_conversion
- Infelicitous_BA

Each paradigm contains 300 minimal pairs.

## Data Format

Each `.jsonl` entry has the following format:

```json
{
  "UID": "BA_negation",
  "phenomenon": "BA",
  "sentence_good": "...",
  "sentence_bad": "...",
  "pairID": 0
}
``` 
## Dataset Construction
The dataset was adapted from paradigms in ZhoBLiMP through sentence structural transformations.

## Paper
Li, S., Tan, X., and Bloem, J.  
*Examining Large Language Models' form-meaning mappings of information structure constructions in Mandarin Chinese* (in press).

https://openreview.net/forum?id=Vktj6eXtDm#

## Citation
If you use this dataset, please cite our paper.
