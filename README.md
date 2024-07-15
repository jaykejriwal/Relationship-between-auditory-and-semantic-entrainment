# Relationship between auditory and semantic entrainment
Python program for understanding the relationship between auditory and semantic entrainment.

## Dataset
We utilized state-of-the-art DNN embeddings such as BERT and TRIpLet Loss network (TRILL) vectors to extract features for measuring semantic and auditory similarities of turns within dialogues in two comparable spoken corpora of two different languages, namely Columbia Games corpus and Slovak Games corpus. 

The input folder shows the necessary files required for processing.

Columbia Games corpus can be downloaded from https://catalog.ldc.upenn.edu/LDC2021S02

Slovak Games corpus is available upon request by mailing it to the authors

## Required Software
ffmpeg (Download from https://www.ffmpeg.org/download.html)

sentence-transformers (pip install sentence-transformers)

tensorflow (pip install tensorflow)

textgrid (Install textgrid from https://github.com/kylebgorman/textgrid)

TRILL vectors model (Download from https://tfhub.dev/google/nonsemantic-speech-benchmark/trill/3)

## Execution instruction
Two Jupyter Notebook files are uploaded. Each file presents a step-by-step procedure for extracting features and measuring entrainment in different languages. 

## Citation
Kejriwal, J., Beňuš, Š. (2023) Relationship between auditory and semantic entrainment using Deep Neural Networks (DNN). Proc. INTERSPEECH 2023, 2623-2627, doi: 10.21437/Interspeech.2023-1947
