# Anomaly_Detection_in_a_new_way

Code can be downloaded from: https://www.yunpan.com/surl_ytiB6bB8kbe (Code：6d18, Password: The name of our paper)

# Inference: 
python data/ShanghaiTech/pose/multi_cls_auc.py

Directory including trajectories and sequences of poses:

# Training: 
python train_statespace.py --smooth_or_predwithsmoothed_or_predwithunsmoothed train

Inference for human class: python train_statespace.py --smooth_or_predwithsmoothed_or_predwithunsmoothed predwithunsmoothed

Revise sequence length: revise input_frame in train_statespace.py

Implementation of combining postures with displacement: def normalize_data_transformed in models/training_state.py

# Citation:
@article{jiang2023reasonable,
  title={Reasonable Anomaly Detection in Long Sequences},
  author={Jiang, Yalong and Li, Changkang},
  journal={arXiv preprint arXiv:2309.03401},
  year={2023}
}
