# mids-w266-fall2025-vishnu-geon
Part of a competion from Nicholas Card et al.'s challenge via kaggle: https://www.kaggle.com/competitions/brain-to-text-25\
Baseline github: https://github.com/Neuroprosthetics-Lab/nejm-brain-to-text/tree/main\
Baseline publication: 10.1056/NEJMoa2314132\
Data gathered from : https://datadryad.org/dataset/doi:10.5061/dryad.dncjsxm85

# Contents
- data_ingest.ipynb: Parsing data downloaded from dryad into input phonemes and ground truth labels
- baseline_test.ipynb: Gather baseline results
- t5_training.ipynb: T5 Model testing
- VG_Cleaned_266_Final.ipynb: Xbert Model testing
- Brain2Text_ A Comparison Study of T5 Transformers and XPhoneBert for the Translation of Phonemes to Text.pdf: Report summarizing the models that were run

# Abstract
Individuals with severe speech impairments often retain language comprehension but cannot produce speech. Recent brain-computer interface (BCI) research suggests that neural activity correlates more strongly with phonemes than with words, motivating a two-stage decoding pipeline: neural signals → phonemes → text. This project focuses on the second stage. We investigate whether a lightweight sequence-to-sequence transformer, T5-small, can translate phoneme sequences into coherent English sentences. T5’s performance is also compared against a custom Seq2Seq model. Both models are trained on paired phoneme sentence data and evaluated using BLEU, Word Error Rate (WER), and qualitative error analysis. Results show that both approaches capture phonetic structures and produce fluent, semantically accurate text.
