# Rethinking-the-Masking-Strategy-for-Pre-Training-Molecule-Graphs-from-a-Data-Centric-View
1.Self-supervised pre-training
'''
python pretrain_masking.py --output_model_file OUTPUT_MODEL_PATH
'''
2.Fine-tuning
'''
python finetune.py --model_file INPUT_MODEL_PATH --dataset DOWNSTREAM_DATASET --filename OUTPUT_FILE_PATH
'''
