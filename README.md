# Rethinking-the-Masking-Strategy-for-Pre-Training-Molecule-Graphs-from-a-Data-Centric-View
##Installation
The chemistry dataset can be download from [GitHub Pages]([https://pages.github.com/](http://snap.stanford.edu/gnn-pretrain/data/chem_dataset.zip)).
##Pre-training and Fine-tuning
1.Self-supervised pre-training
```
python pretrain_masking.py --output_model_file OUTPUT_MODEL_PATH
```
2.Fine-tuning
```
python finetune.py --model_file INPUT_MODEL_PATH --dataset DOWNSTREAM_DATASET --filename OUTPUT_FILE_PATH
```
