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

# packages and useful links
1. [NeuroKit2](https://github.com/neuropsychology/NeuroKit#contribution)<br>
生物医学信号处理很全面的包。

2. [Pythonic package for HRV Analysis](https://github.com/rhenanbartels/hrv)<br>
python实现的HRV分析工具包。

3. [Awesome Affective Computing](https://github.com/AmrMKayid/awesome-affective-computing/blob/master/README.md#affective-science)<br>


# papers

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

## wave delineation
1. Automated beat-wise arrhythmia diagnosis using modified U-net on extended electrocardiographic recordings with heterogeneous arrhythmia types <br> 
Applying modified U-Net to identify wave boundary in ECG sequence.



## HRV
1. [The pNNx files: re-examining a widely used heart rate variability measure](https://heart.bmj.com/content/heartjnl/88/4/378.full.pdf)<br>
2002年的论文。对比了PNN4~PNN100多组数据，得出结论PNN小于50ms的时候，拥有较好的区分度。

2. []()<br>

# datasets
1. [DECAF emotional states recognition dataset]<br>
[DECAF introduction PPT](https://pdfs.semanticscholar.org/8cf5/6d54df1daba47b1fc5b9347660af1ba94307.pdf)<br>
[DECAF: MEG-based Multimodal Database for Decoding Affective Physiological Responses](https://github.com/KilluaKukuroo/ECG/tree/master/paper/DECAF-2015.pdf)<br>
2015年来自University of Trento， Queen Mary University of London，Advanced Digital Sciences Center (ADSC) UIUC Singapore 等机构的研究者发布多模态
的情绪识别数据集。主要卖点在MEG。

2. [AMIGOS]