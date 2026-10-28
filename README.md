---
license: cc0-1.0
language:
- en
- de
---
# Biographical Relation Extraction Dataset

Welcome to the repository of datasets tailored for biographical relation extraction, crafted utilizing Guided Distant Supervision (GDS). Explore datasets available in both English and German, which facilitate extensive research in relation extraction from biographical data. Below you can find an overview of the datasets currently available, as well as the relations that are in each set. Please note there are different sets for each language, which denote how they were compiled. In short, normal followed GDS, coref added coreference resolution and skip skipped certain parts of the text. For a more extensive explanation how this worked, please refer to [[1]](#1).

**The data has moved to (huggingface)[https://huggingface.co/datasets/plumaj/biographical]

## English Dataset

### Overview

The detailed description of how the _English_ part of the dataset was created can be found in [[1]](#1). (Please cite this paper if you use the English part)

| Relation   | Normal Set  | Coref Set   | Skip Set    |
|------------|-------------|-------------|-------------|
| Birthdate  | 51,524      | 47,977      | 45,211      |
| Birthplace | 50,226      | 46,551      | 17,537      |
| Deathdate  | 17,197      | 14,500      | 5,925       |
| Deathplace | 18,944      | 20,430      | 10,790      |
| Occupation | 18,114      | 18,111      | 8,716       |
| Parent     | 6,352       | 10,291      | 5,596       |
| Educated   | 5,639       | 9,415       | 3,858       |
| Child      | 2,209       | 4,053       | 2,123       |
| Sibling    | 2,083       | 3,601       | 1,997       |
| Other      | 173,969     | 175,916     | 103,248     |
| **Total**  | **346,257** | **350,845** | **205,001** |

## German Dataset

### Overview

The detailed description of how the _German_ part of the dataset was created can be found in [[2]](#2). (Please cite this paper if you use the German part)

| Relation   | Normal Set | Skip Set   |
|------------|------------|------------|
| Birthdate  | 8,777      | 770        |
| Birthplace | 12,833     | 5,816      |
| Child      | 718        | 701        |
| Deathdate  | 922        | 454        |
| Deathplace | 4,059      | 3,263      |
| Educated   | 610        | 607        |
| Occupation | 10,861     | 4,836      |
| Other      | 39,782     | 20,469     |
| Parent     | 3,704      | 3,565      |
| Sibling    | 917        | 890        |
| **Total**  | **83,183** | **41,380** |


## References

<a id="1">[1]</a> 
Alistair Plum, Tharindu Ranasinghe, Spencer Jones, Constantin Orasan, Ruslan Mitkov (2022). 
Biographical Semi-Supervised Relation Extraction Dataset.
Proceedings of the 45th International ACM SIGIR Conference on Research and Development in Information Retrieval.
</br>
<a id="2">[2]</a>
Alistair Plum, Tharindu Ranasinghe, Christoph Purschke (2024). 
Guided Distant Supervision for Multilingual Relation Extraction Data: Adapting to a New Language.
Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024).
