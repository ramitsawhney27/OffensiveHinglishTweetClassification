# OffensiveHinglishTweetClassification
Code and Data for our work on Offensive Hinglish Tweet Classification - EMNLP 2018

# Abstract
The use of code-switched languages (e.g., Hinglish, which is derived by the blending of Hindi with the English language) is getting
much popular on Twitter due to their ease of communication in native languages.
However, spelling variations and absence of grammar rules introduce ambiguity and make it difficult to understand the text automatically.
This paper presents the Multi-Input Multi-Channel Transfer Learning based model (MIMCT) to detect offensive (hate speech or
abusive) Hinglish tweets from the proposed Hinglish Offensive Tweet (HOT) dataset using transfer learning coupled with multiple
feature inputs. 
Specifically, it takes multiple primary word embedding along with secondary extracted features as inputs to train a multi-channel CNN-LSTM architecture that has been pre-trained on English tweets through
transfer learning.
The proposed MIMCT model outperforms the baseline supervised classification models, transfer learning basedCNN and LSTM models to establish itself as the state of the art in the unexplored domain of Hinglish offensive text classification.

If using any of our resources, please cite using:
@inproceedings{mathur2018did,
  title={Did you offend me? classification of offensive tweets in hinglish language},
  author={Mathur, Puneet and Sawhney, Ramit and Ayyar, Meghna and Shah, Rajiv},
  booktitle={Proceedings of the 2nd Workshop on Abusive Language Online (ALW2)},
  pages={138--148},
  year={2018}
}
