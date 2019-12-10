# LSTM-for-Human-Activity-Recognition-using-2D-Pose_Pytorch
Based on PyTorch library, realizing human activities recognition using 2D skeleton joint points

- Basic idea is similar with [RNN-for-Human-Activity-Recognition-using-2D-Pose-Input](https://github.com/stuarteiffert/RNN-for-Human-Activity-Recognition-using-2D-Pose-Input): to classify human activities using a 2D pose time series dataset like skeleton joint points which can be detected by some software such as OpenPose.
- Realizing LSTM network by PyTorch
- Dataset is a subset of the Berkeley Multimodal Human Action Database (MHAD)
- Thanks to [RNN-for-Human-Activity-Recognition-using-2D-Pose-Input](https://github.com/stuarteiffert/RNN-for-Human-Activity-Recognition-using-2D-Pose-Input), dataset can be downloaded from [raw data](https://drive.google.com/file/d/1IuZlyNjg6DMQE3iaO1Px6h1yLKgatynt/view)
- Put the dataset into data/HAR_pose_activities/database/
- Detail is in [lstm.ipynb](https://github.com/xieyulai/LSTM-for-Human-Activity-Recognition-using-2D-Pose_Pytorch/blob/master/lstm.ipynb)
- Not bad result is realized in a 8 Minutes training (TitanXP GPU)
