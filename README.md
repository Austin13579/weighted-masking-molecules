# Rethinking-the-Masking-Strategy-for-Pre-Training-Molecule-Graphs-from-a-Data-Centric-View
## Installation
The chemistry dataset can be downloaded from [Chem Data](http://snap.stanford.edu/gnn-pretrain/data/chem_dataset.zip).
## Pre-training and Fine-tuning
1.Self-supervised pre-training
```
python pretrain_masking.py --output_model_file OUTPUT_MODEL_PATH
```
2.Fine-tuning
```
python finetune.py --model_file INPUT_MODEL_PATH --dataset DOWNSTREAM_DATASET --filename OUTPUT_FILE_PATH
```
## Citation

If you find our work helpful to your research, please cite:
```
@article{lin2024rethinking,
  title={Rethinking the Masking Strategy for Pretraining Molecular Graphs from a Data-Centric View},
  author={Lin, Wei and Fung, Chi Chung Alan},
  journal={ACS omega},
  volume={9},
  number={19},
  pages={20832--20838},
  year={2024},
  publisher={ACS Publications}
}
```
