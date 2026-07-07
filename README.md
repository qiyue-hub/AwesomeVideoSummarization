
# Progress on Video Highlight and Video Summarization (and probably Video Caption)

## Dataset

(Summarization) TVSum

**Tvsum: Summarizing web videos using titles**, Yale Song, Jordi Vallmitjana, Amanda Stent, and Alejandro Jaimes, CVPR2015.

50 videos, avg duration 251.64s~=4min12s, fps~=28, (News, documentaries, vlogs)

[[pdf](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Song_TVSum_Summarizing_Web_2015_CVPR_paper.pdf)] [[code](https://github.com/yalesong/tvsum)] [[resource](https://drive.google.com/drive/folders/1rqXEIelRzq4mb7NaBk3GXxh7jlfP_Snm) by A2Summ (original from [Category-specific-videosummarization](https://github.com/kezhang-cs/Video-Summarization-with-LSTM?tab=readme-ov-file))]

(Summarization) SumMe

**Creating Summaries from User Videos**, Michael Gygli, Helmut Grabner, Hayko Riemenschneider, and Luc Van Gool, ECCV2014.

25 videos, avg duration 2min40s, (Events, holidays, sports)

[[pdf](https://link.springer.com/chapter/10.1007/978-3-319-10584-0_33)] [[resource](https://drive.google.com/drive/folders/1rqXEIelRzq4mb7NaBk3GXxh7jlfP_Snm) by A2Summ (original from [Category-specific-videosummarization](https://github.com/kezhang-cs/Video-Summarization-with-LSTM?tab=readme-ov-file))]

(Summarization) Instruct-V2Xum

**V2Xum-LLM: Cross-Modal Video Summarization with Temporal Prompt Instruction Tuning**, Hang Hua*, Yunlong Tang*, Chenliang Xu, Jiebo Luo, AAAI2025.

30000 videos, avg duration 3min3s (183s), duration 40-940s, Open domain, avg text summary length 239 tokens, avg video summary length 30 frames, avg compression ratio 16.39%.

[[pdf](https://ojs.aaai.org/index.php/AAAI/article/view/32374)] [[resource](https://huggingface.co/datasets/hhua2/Instruct-V2Xum)] [[homepage](https://hanghuacs.github.io/v2xum/)]

(Summarization) VideoXum

14001 videos, Activities

**VideoXum: Cross-modal Visual and Textural Summarization of Videos**, Lin, Jingyang and Hua, Hang and Chen, Ming and Li, Yikang and Hsiao, Jenhao and Ho, Chiuman and Luo, Jiebo, TMM2023

[[pdf](https://arxiv.org/pdf/2303.12060)] [[resource](https://huggingface.co/datasets/jylins/videoxum)] [[homepage](https://videoxum.github.io/)]

(V2T Summarization) Shot2Story20K

42958 videos

**Shot2Story20K: A New Benchmark for Comprehensive Understanding of Multi-shot Videos**, Mingfei Han, Linjie Yang, Xiaojun Chang, Lina Yao, Heng Wang, ICLR2025

[[pdf](https://arxiv.org/pdf/2312.10300)] [[resource](https://mingfei.info/shot2story/)] [[homepage](https://mingfei.info/shot2story/)]

(Summarization) MED Summaries

**Category-specific video summarization**, Danila Potapov, Matthijs Douze, Zaid Harchaoui, and Cordelia Schmid, ECCV2014

[[pdf](https://link.springer.com/content/pdf/10.1007/978-3-319-10599-4_35.pdf)] [[resource](https://lear.inrialpes.fr/people/potapov/med_summaries.php.html)]

(Summarization) QFVS

**Query-Focused Video Summarization: Dataset, Evaluation, and A Memory Network Based Approach**, Sharghi, Aidean and Laurel, Jacob S. and Gong, Boqing, CVPR2017.

[[pdf](https://openaccess.thecvf.com/content_cvpr_2017/papers/Sharghi_Query-Focused_Video_Summarization_CVPR_2017_paper.pdf)] [No resource found]

[Summarizaiton2T] MM-AVS

**MM-AVS: A Full-Scale Dataset for Multi-modal Summarization**, Fu, Xiyan and Wang, Jun and Yang, Zhenglu, NAACL2021

[[pdf](https://aclanthology.org/2021.naacl-main.473.pdf)] [[resource](https://github.com/xiyan524/MM-AVS)]

(Highlight) PHD2

**PHD-GIFs: Personalized Highlight Detection for Automatic GIF Creation**, Ana Garcia del Molino and Michael Gygli, MM2018.

[[pdf](https://dl.acm.org/doi/10.1145/3240508.3240599)] [[code](https://github.com/gifs/personalized-highlights-dataset)]

(Hightlight) Video2GIF

**Video2GIF: Automatic Generation of Animated GIFs from Video**, Michael Gygli, Yale Song, and Liangliang Cao, CVPR2016

[[pdf](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gygli_Video2GIF_Automatic_Generation_CVPR_2016_paper.pdf)] [[code](https://github.com/gyglim/video2gif_dataset)]

(Highlight) DSH

**Ranking Domain-Specific Highlights by Analyzing Edited Videos**, Min Sun, Ali Farhadi, and Steve Seitz, ECCV2014.

[[pdf](http://vigir.ee.missouri.edu/~gdesouza/Research/Conference_CDs/ECCV_2014/papers/8689/86890787.pdf)] [[code](https://github.com/aliensunmin/DomainSpecificHighlight)]

## 2025

**V2Xum-LLM: Cross-Modal Video Summarization with Temporal Prompt Instruction Tuning**, Hang Hua*, Yunlong Tang*, Chenliang Xu, Jiebo Luo, AAAI2025.

Summarization; video, text

[[pdf](https://ojs.aaai.org/index.php/AAAI/article/view/32374)] [[code](https://github.com/hanghuacs/V2Xum-LLM)] [[homepage](https://hanghuacs.github.io/v2xum/)]

**SummDiff: Generative Modeling of Video Summarization with Diffusion**, Kwanseok Kim*, Jaehoon Hahm*, Sumin Kim, Jinwhan Sul, Byunghak Kim, Joonseok Lee, ICCV2025

Summarization; Fully-supervised; SumMe, TVSum, Mr. HiSum

[[pdf](https://openaccess.thecvf.com/content/ICCV2025/papers/Kim_SummDiff_Generative_Modeling_of_Video_Summarization_with_Diffusion_ICCV_2025_paper.pdf)] [[code](https://github.com/Kwanseok-K/SummDiff)]

**(H-SMAE) Hybrid Siamese Masked Autoencoders as Unsupervised Video Summarizer**, Yifei Xu; Zaiqiang Wu; Li Li; Siqi Li; Wenlong Li; Mingqi Li, TCSVT2025

Summarization; Unsupervised

[[pdf](https://ieeexplore.ieee.org/abstract/document/10947580)] [[code](https://github.com/wzq0214/H-SMAE)]

**Capturing spatiotemporal dependencies with competitive set attention for video summarization**, Md Hasnat Hosen Arafat & Kavinder Singh, VisualComputer2025

Summarization; Supervised

[[pdf](https://link.springer.com/article/10.1007/s00371-025-03865-1)] [[code](https://github.com/ara-47/STSA)] [[dataset](https://drive.google.com/drive/folders/1KTpftiMchP0q-pdcJ4K7HaARJloOwQA6?usp=sharing)]

**Training-Free Language-Guided Video Summarization via Multi-Grained Saliency Scoring**, Wei Ge, Yongwei Nie, Fei Ma, Keke Tang, Fei Richard Yu, Hongmin Cai & Ping Li, CVM2025

Summarization; Unupervised

[[pdf](https://link.springer.com/chapter/10.1007/978-981-96-5815-2_6)] [[code](https://github.com/scut-201930340437/language-guided-video-summarization-with-LLM)]

**QANet: quaternion attention network for video summarization**, Vaani Garg, Anil Singh Parihar, JEI2025

[[pdf](https://www.spiedigitallibrary.org/journals/journal-of-electronic-imaging/volume-34/issue-2/023028/QANet-quaternion-attention-network-for-video-summarization/10.1117/1.JEI.34.2.023028.short)]

Summarization; Supervised; SumMe, TVSum

**HierSum: A Global and Local Attention Mechanism for Video Summarization**, 

[[pdf](https://arxiv.org/pdf/2504.18689)] [code will be released]

Summarization; Supervised; TVSum, BLiSS, Mr.HiSum

**CMFF_VS: A Video Summarization Extraction Model based on Cross-modal Feature Fusion**, Chaoqun Xin, Mingyang Wang & Xianhao Zhao, CECS2025

Summarization; Supervised; SumMe, TVSum, Daily_Mail and BLiSS; video, text

[[pdf](https://link.springer.com/article/10.1007/s13369-025-10133-w)]

**Prompts to Summaries: Zero-Shot Language-Guided Video Summarization**, Mario Barbara, Alaa Maalouf, arXiv2025

Summarization; Unsupervised; SumMe, TVSum, Daily_Mail and BLiSS; video, text

[[pdf](http://arxiv.org/pdf/2506.10807)] [[code](https://github.com/mario998-hash/ZeroShotVideoSummary)]

**Shot2Story20K: A New Benchmark for Comprehensive Understanding of Multi-shot Videos**, Mingfei Han, Linjie Yang, Xiaojun Chang, Lina Yao, Heng Wang, ICLR2025

V2T Summarization; video, text

[[pdf](https://arxiv.org/pdf/2312.10300)] [[resource](https://mingfei.info/shot2story/)] [[homepage](https://mingfei.info/shot2story/)] [[code](https://github.com/bytedance/Shot2Story)]

## 2024

**TimeChat: A Time-sensitive Multimodal Large Language Model for Long Video Understanding**, Shuhuai Ren, Linli Yao, Shicheng Li, Xu Sun, Lu Hou, CVPR2024

Video Highlight Detection, Temporal Video Grounding, Dense Video Captioning; YouCook2, Charades-STA, QVHighlights; 

[[pdf](https://openaccess.thecvf.com/content/CVPR2024/papers/Ren_TimeChat_A_Time-sensitive_Multimodal_Large_Language_Model_for_Long_Video_CVPR_2024_paper.pdf)] [[code](https://github.com/RenShuhuai-Andy/TimeChat)]

**CSTA: CNN-based Spatiotemporal Attention for Video Summarization**, Son, Jaewon and Park, Jaehun and Kim, Kwangsu, CVPR2024

Summarization; Fully-supervised; SumMe, TVSum

[[pdf](https://openaccess.thecvf.com/content/CVPR2024/papers/Son_CSTA_CNN-based_Spatiotemporal_Attention_for_Video_Summarization_CVPR_2024_paper.pdf)] [[code](https://github.com/thswodnjs3/CSTA/tree/master)]

**Exploring Domain Incremental Video Highlights Detection with the LiveFood Benchmark**, Sen Pei, Shixiong Xu, Xiaojie Jin, AAAI2024

[[pdf](https://ojs.aaai.org/index.php/AAAI/article/view/28880)] [[code](https://github.com/ForeverPs/IncrementalVHD_GPE)]

**VideoSAGE Video Summarization with Graph Representation Learning**, Jose M. Rojas Chaves, Subarna Tripathi, CVPRW2024

Summarization; Fully-supervised; SumMe, TVSum

[[pdf](https://openaccess.thecvf.com/content/CVPR2024W/SG2RL/papers/Chaves_VideoSAGE_Video_Summarization_with_Graph_Representation_Learning_CVPRW_2024_paper.pdf)] [[code](https://github.com/IntelLabs/GraVi-T)]

**M3Sum: A Novel Unsupervised Language-guided Video Summarization**, Hongru Wang∗, Baohang Zhou∗, Zhengkun Zhang, Yiming Du, David Ho, Kam-Fai Wong, ICASSP2024

Summarization; Unsupervised; SumMe, TVSum; video, text, sound

[[pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10447504)] [[code](https://github.com/ZovanZhou/M3Sum)]

**Multimodal Video Summarization using Attention based Transformers (MVSAT)**, Kushagra Singh; Pranav R; Pavan Kumar Nuthi; Nikhil Raju Mohite; Mamatha H R, IATMSI2024

Summarization; Supervised; SumMe, TVSum; video, text

[[pdf](https://ieeexplore.ieee.org/document/10503010)]

**Language-Guided Self-Supervised Video Summarization Using Text Semantic Matching Considering the Diversity of the Video**, T Sugihara, S Masuda, L Xiao, T Yamasaki, MMASIA2024

Summarization; Self-supervised; SumMe; vodeo, text

[[pdf](https://dl.acm.org/doi/pdf/10.1145/3696409.3700273)] [[code](https://github.com/sugitomoo/PDL)]

**Multi-modal Video Summarization**, Jia-Hong Huang, ICMR2024

V2T Summarization

[[pdf](https://dl.acm.org/doi/10.1145/3652583.3657582)]

**Spatiotemporal Feature Fusion for Video Summarization**, Shamal Kashid, Lalit K. Awasthi, Krishan Berwal, Parul Saini, IEEE MultiMedia2024

[[pdf](https://ieeexplore.ieee.org/abstract/document/10601605/authors#authors)] [No code]

**Does spatio-temporal information benefit the video summarization task?**, Aashutosh Ganesh, Mirela Popa, Daan Odijk, Nava Tintarev, CEURW2024

[[pdf](https://cris.maastrichtuniversity.nl/en/publications/does-spatio-temporal-information-benefit-the-video-summarization--2/?__cf_chl_f_tk=sIekIzfKdcHTF.n8VeptSO5VBhXxgqpoO_7fQS5DYKo-1783435833-1.0.1.1-itUYQ3.BvR_jdvSjk0EAyilWUC7E_sDH3L8Ja.jwcUM)]

## 2023

**VideoXum: Cross-modal Visual and Textural Summarization of Videos**, Lin, Jingyang and Hua, Hang and Chen, Ming and Li, Yikang and Hsiao, Jenhao and Ho, Chiuman and Luo, Jiebo, TMM2023

Summarization; Supervised; video, text

[[pdf](https://arxiv.org/pdf/2303.12060)] [[code](https://github.com/jylins/videoxum)] [[homepage](https://videoxum.github.io/)]

**Collaborative Noisy Label Cleaner: Learning Scene-Aware Trailers for Multi-Modal Highlight Detection in Movies**, Bei Gan, Xiujun Shu, Ruizhi Qiao, Haoqian Wu, Keyu Chen, Hanjun Li, Bo Ren, CVPR2023.

[[pdf](https://openaccess.thecvf.com/content/CVPR2023/papers/Gan_Collaborative_Noisy_Label_Cleaner_Learning_Scene-Aware_Trailers_for_Multi-Modal_Highlight_CVPR_2023_paper.pdf)] [[code](https://github.com/TencentYoutuResearch/HighlightDetection-CLC)]

**(A2Summ) Align and Attend: Multimodal Summarization with Dual Contrastive Losses**, Bo He, Jun Wang, Jielin Qiu, Trung Bui, Abhinav Shrivastava, Zhaowen Wang, CVPR2023.

Summarization; Supervised; video, text, sound

[[pdf](https://arxiv.org/pdf/2303.07284)] [[code](https://github.com/boheumd/A2Summ)] [[project](https://boheumd.github.io/A2Summ/)]

**Self-Supervised Adversarial Video Summarizer With Context Latent Sequence Learning**, Yifei Xu , Xiangshun Li, Litong Pan, Weiguang Sang, Pingping Wei, and Li Zhu, TCSVT2023.

Summarization; Unsupervised

## 2022

**(iPTNet) Joint video summarization and moment localization by cross-task sample transfer**, Hao Jiang and Yadong Mu, CVPR2022

Summarization; Supervised

**Show Me What I Like: Detecting User-Specific Video Highlights Using Content-Based Multi-Head Attention**, Uttaran Bhattacharya, Gang Wu, Stefano Petrangeli, Viswanathan Swaminathan, and Dinesh Manocha, MM2022

[[pdf](https://dl.acm.org/doi/abs/10.1145/3503161.3547843)]

**Use of Affective Visual Information for Summarization of Human-Centric Videos**, Berkay Köprü, Engin Erzin, TAC2023

Summarization

[[pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9954146)]

**Relational reasoning over spatial-temporal graphs for video summarization**, Wencheng Zhu, Yucheng Han, Jiwen Lu, and Jie Zhou, TIP2022

Summarization; Supervised

**Summarizing videos using concentrated attention and considering the uniqueness and diversity of the video frames**， Evlampios Apostolidis, Georgios Balaouras, Vasileios Mezaris, and Ioannis Patras, ICMR2022

Summarization; Unsupervised

**M3l: Languagebased video editing via multi-modal multi-level transformers**, Tsu-Jui Fu, Xin Eric Wang, Scott T Grafton, Miguel P Eckstein, and William Yang Wang, CVPR2022

Edit; video, text

**Unsupervised video summarization via deep reinforcement learning with shotlevel semantics**, Ye Yuan and Jiawan Zhang, TCVST2022.

Summarization; Unsupervised

**Multi-modal segment assemblage network for ad video editing with importance-coherence reward**, Tang, Y.; Xu, S.; Wang, T.; Lin, Q.; Lu, Q., ACCV2022.

Summarization; Supervised; segment-level

**Progressive Video Summarization via Multimodal Self-supervised Learning**, Haopeng, L.; Qiuhong, K.; Mingming, G.; and Drummond, T., arXiv2022

Summarization; Self-Supervised

## 2021

**Clip-it! language-guided video summarization**, Medhini Narasimhan, Anna Rohrbach, Trevor Darrell, NIPS2021.

[[pdf](https://papers.nips.cc/paper_files/paper/2021/file/7503cfacd12053d309b6bed5c89de212-Paper.pdf)] [[code](https://github.com/medhini/clip_it)]

Summarization; Unsupervised; video, text

**(PGL-Sum) Combining Global and Local Attention with Positional Encoding for Video Summarization**, Evlampios ApostolidisGeorgios Balaouras, Vasileios Mezaris, Ioannis Patras, International Symposium on Multimedia (ISM)2021.

[[pdf](https://www.iti.gr/~bmezaris/publications/ism2021a_preprint.pdf)] [[code](https://github.com/e-apostolidis/PGL-SUM)]

**HighlightMe: Detecting Highlights from Human-Centric Videos**, Uttaran Bhattacharya, Gang Wu, Stefano Petrangeli, Viswanathan Swaminathan, Dinesh Manocha, ICCV2021.

[[pdf](https://openaccess.thecvf.com/content/ICCV2021/papers/Bhattacharya_HighlightMe_Detecting_Highlights_From_Human-Centric_Videos_ICCV_2021_paper.pdf)]

**Detecting Moments and Highlights in Videos via Natural Language Queries**, Jie Lei, Tamara L Berg, Mohit Bansal, NIPS2021.

[[pdf](https://proceedings.neurips.cc/paper/2021/file/62e0973455fd26eb03e91d5741a4a3bb-Paper.pdf)] [[code](https://github.com/jayleicn/moment_detr)]

**Supervised video summarization via multiple feature sets with parallel attention**, Junaid Ahmed Ghauri, Sherzod Hakimov, and Ralph Ewerth.

Summarization; Supervised

**Reconstructive sequence-graph network for video summarization**, Bin Zhao, Haopeng Li, Xiaoqiang Lu, and Xuelong Li, TPAMI2021.

Summarization; Supervised & Unsupervised

**DSNet: A Flexible Detect-to-Summarize Network for Video Summarization**, Wencheng Zhu, Jiwen Lu, Jiahao Li, and Jie Zhou, TIP2021

Summarization; Supervised; anchor-based / anchor-free

[[pdf](https://ieeexplore.ieee.org/document/9275314)] [[code](https://github.com/li-plus/DSNet)]

**Supervised video summarization via multiple feature sets with parallel attention**, Ghauri, J. A.; Hakimov, S.; and Ewerth, R., ICME2021

Summarization; Supervised

**MM-AVS: A Full-Scale Dataset for Multi-modal Summarization**, Fu, Xiyan and Wang, Jun and Yang, Zhenglu, NAACL2021

Multimodal2T Summarization; Supervised

**Gpt2mvs: Generative pre-trained transformer-2 for multimodal video summarization**, Huang, J.-H.; Murn, L.; Mrak, M.; and Worring, M., ICMR2021

Multimodal Summarization

## 2020

**Sumgraph: Video summarization via recursive graph modeling**, Jungin Park, Jiyoung Lee, Ig-Jae Kim, and Kwanghoon Sohn, ArXiv2020

Summarization; Supervised

**Ac-sum-gan: Connecting actor-critic and generative adversarial networks for unsupervised video summarization**, Evlampios Apostolidis, Eleni Adamantidou, Alexandros I Metsai, Vasileios Mezaris, and Ioannis Patras, TCVST2020

Summarization; Unsupervised

**Unsupervised video summarization via attentiondriven adversarial learning**, Evlampios Apostolidis, Eleni Adamantidou, Alexandros I Metsai, Vasileios Mezaris, and Ioannis Patras, MultiMedia Modeling2020.

Summarization; Unsupervised

**Transforming Multi-Concept Attention into Video Summarization**, Yen-Ting Liu, Yu-Jhe Li, Yu-Chiang Frank Wang, ACCV2020.

Summarization; Supervised

[[pdf](https://openaccess.thecvf.com/content/ACCV2020/papers/Liu_Transforming_Multi-Concept_Attention_into_Video_Summarization_ACCV_2020_paper.pdf)]

**Multi-modal Summarization for Video-containing Documents**, Xiyan Fu, Jun Wang, Zhenglu Yang, arXiv2020

Summarization; Supervised

[[pdf](https://arxiv.org/pdf/2009.08018)]

## 2019

**Summarizing videos with attention**, Jiri Fajtl, Hajar Sadeghi Sokeh, Vasileios Argyriou, Dorothy Monekosso, and Paolo Remagnino, ACCVW2018.

Summarization; Supervised

**Property-constrained dual learning for video summarization**, Bin Zhao, Xuelong Li, and Xiaoqiang Lu, TNNLS2019.

Summarization; Unsupervised

**Unsupervised video summarization with attentive conditional generative adversarial networks**, Xufeng He, Yang Hua, Tao Song, Zongpu Zhang, Zhengui Xue, Ruhui Ma, Neil Robertson, and Haibing Guan, MM2019

Summarization; Unsupervised

**Enhanced deep video summarization network**, N Gonuguntla, B Mandal, NB Puhan, et al., BMVC2019.

Summarization; Unsupervised

**Stacked memory network for video summarization**, Wang, J.; Wang, W.; Wang, Z.; Wang, L.; Feng, D.; and Tan, T., MM2019

Summarization; Supervised

**Video summarization with attention-based encoder–decoder networks**, Zhong Ji, Kailin Xiong, Yanwei Pang, and Xuelong Li, ITCSVT2019

Summarization; Supervised; shot-level

**Susinet: See, understand and summarize it**, Koutras, P.; and Maragos, P., CVPRW2019

Summarization; Supervised; Segment-level

## 2018

**Hsa-rnn: Hierarchical structure-adaptive rnn for video summarization**, Bin Zhao, Xuelong Li, and Xiaoqiang Lu, CVPR2018

Summarization; Supervised

**Discriminative feature learning for unsupervised video summarization**, Yunjae Jung, Donghyeon Cho, Dahun Kim, Sanghyun Woo, and In-So Kweon, ArXiv2018

Summarization; Unsupervised

**Deep reinforcement learning for unsupervised video summarization with diversity-representativeness reward**, Kaiyang Zhou, Yu Qiao, and Tao Xiang

Summarization; Unsupervised

**Video summarization via semantic attended networks**, Huawei Wei, Bingbing Ni, Yichao Yan, Huanyu Yu, Xiaokang Yang, and Chen Yao, AAAI2018

Summarization; Unsupervised

**Deep Reinforcement Learning for Unsupervised Video Summarization with Diversity-Representativeness Reward**, Zhou, Kaiyang and Qiao, Yu and Xiang, Tao, AAAI2018

[[code](https://github.com/KaiyangZhou/pytorch-vsumm-reinforce/tree/master)] [[pdf](https://arxiv.org/abs/1801.00054)]

**Extractive video summarizer with memory augmented neural networks**, Feng, L.; Li, Z.; Kuang, Z.; and Zhang, W, MM2018

Summarization; Supervised; shot-level

**Retrospective encoders for video summarization**, Zhang, K.; Grauman, K.; and Sha, F., ECCV2018.

Summarization; Supervised; shot-level

## 2017

**Unsupervised video summarization with adversarial lstm networks**, Behrooz Mahasseni, Michael Lam, and Sinisa Todorovic, CVPR2017.

Summarization; Unsupervised

**Query-Focused Video Summarization: Dataset, Evaluation, and A Memory Network Based Approach**, Sharghi, Aidean and Laurel, Jacob S. and Gong, Boqing, CVPR2017.

Summarization

[[pdf](https://openaccess.thecvf.com/content_cvpr_2017/papers/Sharghi_Query-Focused_Video_Summarization_CVPR_2017_paper.pdf)]

**Multi-modal Summarization for Asynchronous Collection of Text, Image, Audio and Video**, Haoran Li, Junnan Zhu, Cong Ma, Jiajun Zhang, Chengqing Zong, EMNLP2017

Multimodal2T Summarization

## 2016

**Video Summarization with Long Short-term Memory**, Ke Zhang, Wei-Lun Chao, Fei Sha, Kristen Grauman, ECCV2016.

[[pdf](https://arxiv.org/pdf/1605.08110)] [[code](https://github.com/kezhang-cs/Video-Summarization-with-LSTM)]

## 2014

**(KTS/KVS) Category-specific video summarization**, Danila Potapov, Matthijs Douze, Zaid Harchaoui, Cordelia Schmid, ECCV2014

Summarization, MED-Summaries

[[pdf](https://inria.hal.science/hal-01022967/PDF/video_summarization.pdf)] [code not available]

## Other Resources

2020. Video-summarization. [[github](https://github.com/pujols/Video-summarization)]
2019. Awesome-Video-Summarization. [[github](https://github.com/daicoolb/Awesome-Video-Summarization)]
2018. Video Summarization Dataset, Papers, Codes. [[github](https://github.com/robi56/video-summarization-resources)]


