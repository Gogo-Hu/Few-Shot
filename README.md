# Few-Shot
An Attention-Enhanced Prototypical Networks for Few-Shot Learning

In the project, we performed 4 different models which belong to 4 different corruption rate (i.e. *0%*, *20%*, *40%* and *60%*) on support set images. For simplicity, we just put the code for 20% corruption rate here. 

To reproduce the other three models, please adjust the class **Config** in Cell 2. For *40%* or *60%* corruption rate, change the variable **blur_probability** from *0.2* to *0.4* or *0.6*. For no corruption addition, just simply change the variable **use_blurry_training** from *True* to *False*.
