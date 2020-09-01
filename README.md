# ECG
Get all you need about ECG!

# Contents
* [code package](#packages-and-useful-links)
* [papers](#papers)
	- [review](##review)
	- [wave delineation](##wave-delineation)
	- [HRV](##HRV)
* [datasets](#datasets)

## papers, notes, books, codes about ECG


#scholars
[Ali Etemad](https://www.ece.queensu.ca/people/a-etemad/index.html) AP at Queen's University, AI+wearable device+signals<br>



# packages and useful links
1. [NeuroKit2](https://github.com/neuropsychology/NeuroKit#contribution)<br>
生物医学信号处理很全面的包。

2. [Pythonic package for HRV Analysis](https://github.com/rhenanbartels/hrv)<br>
python实现的HRV分析工具包。

3. [Awesome Affective Computing](https://github.com/AmrMKayid/awesome-affective-computing/blob/master/README.md#affective-science)<br>


# papers

## post
1.[心电比赛方法总结](https://mp.weixin.qq.com/s/jki1eJ18w-gWOQKKxHYa3w)<br>

## review
1. [*Opportunities and Challenges in Deep Learning Methods on Electrocardiogram Data: A Systematic Review*](https://arxiv.org/pdf/2001.01550.pdf)<br>
2019年的综述，从模型和应用的角度综述了深度学习在ECG领域的研究现状。作者来自佐治亚理工，北大，IQVIA和UIUC 的Jimeng Sun. 


## ECG generation by GANs
1.[Synthesis of Realistic ECG using Generative Adversarial Networks](https://arxiv.org/abs/1909.09150)<br>
2019, 
**summary**: 生成两个连续心拍, 

2.[Improving ECG Classification using Generative Adversarial Networks](http://www.kiraradinsky.com/files/ECG_GAN_generation_AAAI20.pdf)<br>
2020 AAAI, 
**summary**: 生成新拍,辅助分类; <br>


3.[PGANs: Personalized Generative Adversarial Networks for ECG Synthesis to Improve Patient-Specific Deep ECG Classification](https://www.aaai.org/ojs/index.php/AAAI/article/view/3830/3708)<br>
2019 AAAI,
**summary**: 生成心拍; <br>

4.[ECG Generation With Sequence Generative Adversarial Nets Optimized by Policy Gradient](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8887504)<br>
2019, IEEE Access,   <br>

5.[Electrocardiogram generation with a bidirectional LSTM-CNN generative adversarial network](https://www.nature.com/articles/s41598-019-42516-z.pdf)<br>
2019, Scientific Reports; <br>

6.[BeatGAN: Anomalous Rhythm Detection using Adversarially Generated Time Series](https://www.ijcai.org/Proceedings/2019/0616.pdf)<br>
2019 IJCAI, Bin Zhou, Shenghua Liu, Bryan Hooi, Xueqi Cheng and Jing Ye from **Chinese Academy of Science, NUS and Nanfang Hospital, Sourthern Medical U**, citation=2; <br>

7.[Quick and Easy Time Series Generation with Established Image-based GANs](https://arxiv.org/pdf/1902.05624.pdf)<br>
2019,   Eoin Brophy, Zhengwei Wang, Tomas E. Ward from **Dublin City University**, citation=8; <br>




## wave delineation
1. Automated beat-wise arrhythmia diagnosis using modified U-net on extended electrocardiographic recordings with heterogeneous arrhythmia types <br> 
Applying modified U-Net to identify wave boundary in ECG sequence.



## HRV
1. [The pNNx files: re-examining a widely used heart rate variability measure](https://heart.bmj.com/content/heartjnl/88/4/378.full.pdf)<br>
2002年的论文。对比了PNN4~PNN100多组数据，得出结论PNN小于50ms的时候，拥有较好的区分度。
2. []()<br>

## TO BE READ...

[1985-New method for assessing cardiac parasympathetic activity using 24 hour electrocardiograms](paper/1985-New method for assessing cardiac parasympathetic activity using 24 hour electrocardiograms.pdf)



[2002-The pNNx files- re-examining a widely used heart rate variability measure](paper/2002-The pNNx files- re-examining a widely used heart rate variability measure.pdf)



[2010-Affect detection-An Interdisciplinary Review of Models, Methods, and Their Applications](paper/2010-Affect detection-An Interdisciplinary Review of Models, Methods, and Their Applications.pdf)



[2015_Recognizing Emotions Induced by Affective sounds through HRV](paper/2015_Recognizing Emotions Induced by Affective sounds through HRV.pdf)



[2019-Automated beat-wise arrhythmia diagnosis using modified U-net on extended electrocardiographic recordings with heterogeneous arrhythmia types](paper/2019-Automated beat-wise arrhythmia diagnosis using modified U-net on extended electrocardiographic recordings with heterogeneous arrhythmia types.pdf)



[2019-Classification of Cognitive Load and Expertise for adaptive simulation using deep multitask learning](paper/2019-Classification of Cognitive Load and Expertise for adaptive simulation using deep multitask learning.pdf)



[2019-Heart sound signals can be used for emotino recognition](paper/2019-Heart sound signals can be used for emotino recognition.pdf)



[2019-Opportunities and Challenges in Deep Learning Methods on ECG data-a systemmatic  review](paper/2019-Opportunities and Challenges in Deep Learning Methods on ECG data-a systemmatic  review.pdf)



[2020-Designing Network Design Spaces](paper/2020-Designing Network Design Spaces.pdf)

# datasets
1. [DECAF emotional states recognition dataset]<br>
[DECAF introduction PPT](https://pdfs.semanticscholar.org/8cf5/6d54df1daba47b1fc5b9347660af1ba94307.pdf)<br>
[DECAF: MEG-based Multimodal Database for Decoding Affective Physiological Responses](https://github.com/KilluaKukuroo/ECG/tree/master/paper/DECAF-2015.pdf)<br>
2015年来自University of Trento， Queen Mary University of London，Advanced Digital Sciences Center (ADSC) UIUC Singapore 等机构的研究者发布多模态
的情绪识别数据集。主要卖点在MEG。

2. [AMIGOS]

   多模态情绪数据库，人脸、心电、脑电；

3. [PTB-XL-PhysioNet](https://www.physionet.org/content/ptb-xl/1.0.1/)

   2020年发布，超过2万个，12导联ECG数据；

4. [LUDB](https://physionet.org/content/ludb/1.0.0/)

   2020年发布，Lobachevsky University， 200多条12导联数据集；