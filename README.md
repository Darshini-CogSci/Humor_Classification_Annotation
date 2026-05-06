# Humor_Classification_Annotation
A multi-annotator task for humor classification of one-liners based on a cognitive-technique taxonomy
This study uses the train_reddit.tsv dataset from the work of Weller & seppi (2019) which is annotated for humorous and non-humorous one-liners, building upon it with cogntitive technique-based humor classification based on classical and contemporary humor theories.

# How to Use
- annotated_data folder has annotated jokes from 3 annotators that can be used for annotation analysis. The pilot and main_study subfolders are annotated using different guidlines, please refer to the pdf of annotation guidelines of pilot and main study for further details
- for using preprocessing code, please have a copy of the original dataset (train_reddit.csv) from Weller & seppi (2019) in the main directory.
- agreement_analysis_pilot_code gives agreement table, Kippendorff's alpha, pairwise annotator and label wise agreement and disagreement data for the pilot study.
- agreement_analysis_main_study_code gives agreement table, Kippendorff's alpha, pairwise annotator and label wise agreement and disagreement data for the main study.

# Libraries required
pandas, numpy, and krippendorff

## References

* Weller, O., & Seppi, K. (2019). **Humor Detection: A transformer gets the last laugh.** *EMNLP-IJCNLP 2019*.[https://doi.org/10.48550/arxiv.1909.00252](https://doi.org/10.48550/arxiv.1909.00252)


