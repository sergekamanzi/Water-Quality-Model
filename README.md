# Water-Quality-Model
## Project Overview 
### This project develops a machine learning model to predict water potability based on various chemical and physical characteristics. 
#### The primary goal is to classify water samples as potable or non-potable using key features such as pH, hardness, chloramines, and solids
## The Video Presentation and the Doc
##video=
##Doc=https://docs.google.com/document/d/1cmJRIFkxvJqln_G5pVhyeymOF_ETF56ZcHz-L_Wzef8/edit?tab=t.0

## The model implementation

1. Nadam + L1 + gradient clipping = Serge
2. RMSprop + L2 + Early stopping = purity 
3. Adam + Batch Optimization =Kuir 

## Table of Model Comparisons
| Train Instance | Engineer Name | Regularizer | Optimizer | Early Stopping | Dropout Rate | Accuracy| F1 Score | Recall| Precision |
|-------|-------|-------|-------|-------|-------|-------|-------|-------|--------|
| 70% | Purity Kihiu | L2  | RMSprop | Yes | No |0.681 | 0.576 | 0.557 | 0.597 |
| 70%  | Kamanzi serge  | L1  | Nadam  | yes  | 20% | 0.685	 | 0.5849 | 0.848958 | 0.450276 |
| R3C1  | R3C2  | R3C3  | R3C4  | R3C5  | R3C6  | R3C7  | R3C8  | R3C9  | R3C10  |

