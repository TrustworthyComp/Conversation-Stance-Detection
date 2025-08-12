# Conversational Stance Detection
Dataset and Codes for the accepted paper in IEEE transactions on computational social systems: "Improved Target-specific Stance Detection on Social Media Platform by Delving into Conversation Threads"

# Environment Requirements
* Google colab or Jupyter notebook

# Resources
* [CSD-dataset] is CSD_dataset.xlsx in this repository;
* [Pre-trained Branch-BERT model and Baselines] (https://drive.google.com/drive/folders/1LkhbESCnak6lkX0JCx2lARouyJCfPoJj?usp=sharing);
* [Chinese word embedding] (https://github.com/Embedding/Chinese-Word-Vectors);
* [transformers] (https://github.com/huggingface/transformers).

# Usage
## Training
1. Run all the codes in the Section "0. Preparation" (in Conversational_Stance_Detection.ipynb)
2. Run all the codes in the Section "1. Branch Model" 

## Testing
1. Download the Branch_BERT.ckpt model file at the link (https://drive.google.com/drive/folders/1LkhbESCnak6lkX0JCx2lARouyJCfPoJj?usp=sharing) 
2. Run all the codes in Section "0. Preparation."
3. Run all the codes in Section "5. Testing." 

note:
all file paths in the code need to be adjusted to your own environment

## Reference
```
@ARTICLE{10285715,
  author={Li, Yupeng and He, Haorui and Wang, Shaonan and Lau, Francis C. M. and Song, Yunya},
  journal={IEEE Transactions on Computational Social Systems}, 
  title={Improved Target-Specific Stance Detection on Social Media Platforms by Delving Into Conversation Threads}, 
  year={2023},
  volume={10},
  number={6},
  pages={3031-3042},
  keywords={Message systems;Task analysis;Oral communication;Social networking (online);Vaccines;COVID-19;Context modeling;Target recognition;Conversation threads;opinion mining;social media platform;target-specific stance detection},
  doi={10.1109/TCSS.2023.3320723}}
'''