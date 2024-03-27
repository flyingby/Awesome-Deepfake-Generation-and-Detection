<p align="center">
  <h1 align="center">Deepfake Generation and Detection: 
  <p align="center">
  A Benchmark and Survey</h1>
   <p align="center">
    <a href="https://scholar.google.com.hk/citations?user=1yhGS5sAAAAJ&hl=zh-CN"><strong>Gan Pei <sup>*</sup></strong></a>
    .
    <a href="https://zhangzjn.github.io/"><strong>Jiangning Zhang <sup>*</strong></a>
    .
    <a href="https://scholar.google.com.hk/citations?user=8-Vo9cUAAAAJ&hl=zh-CN"><strong>Menghan Hu</strong></a>
    .
    <a href="https://scholar.google.com.hk/citations?user=E6zbSYgAAAAJ&hl=zh-CN"><strong>Guangtao Zhai</strong></a>
    .
    <a href="https://scholar.google.com.hk/citations?hl=zh-CN&user=fqte5H4AAAAJ"><strong>Chengjie Wang</strong></a>
    .
    <a href="https://scholar.google.com.hk/citations?hl=zh-CN&user=4daxK2AAAAAJ"><strong>Zhenyu Zhang</strong></a>.
    <p align="center">
    <a href="https://scholar.google.com.hk/citations?hl=zh-CN&user=6CIDtZQAAAAJ"><strong>Jian Yang</strong></a>
    .
    <a href="https://scholar.google.com.hk/citations?user=Ljk2BvIAAAAJ&hl=zh-CN&oi=ao"><strong>Chunhua Shen</strong></a> 
    .
    <a href="https://scholar.google.com.hk/citations?user=RwlJNLcAAAAJ&hl=zh-CN&oi=ao"><strong>Dacheng Tao</strong></a>
</p>
    
<p align="center">
    <a href='https://arxiv.org/abs/2403.17881'>
      <img src='https://img.shields.io/badge/arXiv-PDF-green?style=flat&logo=arXiv&logoColor=green' alt='arXiv PDF'>
         </a>
  

# We research Deepfake Generation and Detection

This work focuses on the aspect of facial manipulation in Deepfake, encompassing **Face swapping**, **Face reenactment**,  **Talking Face Generation**, **Face attribute editing** and **Foreign Detection**. We believe this will be the most comprehensive survey to date on facial manipulation and detection technologies. Please stay tuned!😉😉😉

### ✨You are welcome to provide us your work with a topic related to deepfake generation or detection!!!

If you discover any missing work or have any suggestions, please feel free to submit a [pull request](https://github.com/flyingby/Awesome-Deepfake-Generation-and-Detection/issues) or [contact us](#contact). We will promptly add the missing papers to this repository.

###  ✨Highlight!!!

[1]  A comprehensive survey for visual Deepfake, including Deepfake generation/detection.

[2]  It also contains several related domains. 

[3]  We list detailed results for the most representative works.

### ✨Survey pipeline
<img src="https://github.com/flyingby/Awesome-Deepfake-Generation-and-Detection/blob/main/structure.png" width.="1000px">


## Introduction

This survey presents a detailed survey on generation and detection tasks about face-related generation, including **Face swap**, **Face reenactment**, **Talking Face Generation**, and **Face attribute editing**. In addition, we also introduce several related fields such as Head Swap, Face Super-resolution, Face Reconstruction, Face Inpainting, etc., and select some of them to expand.

</p>
<img src="https://github.com/flyingby/Awesome-Deepfake-Generation-and-Detection/blob/main/task.png" width.="1000px">

## Summary of Contents
- [Introduction](#introduction)
- [Summary of Contents](#summary-of-contents)
- [Methods: A Survey](#methods-a-survey)
  - [Face Swapping](#Face-Swapping)
  - [Face Reenactment](#Face-Reenactment)
  - [Talking Face Generation](#Talking-Face-Generation)
  - [Face Attribute Editing](#Face-Attribute-Editing)
  - [Detection Modal](#Detection-Modal)
  - [Related Domains and Beyond](#related-domains-and-beyond)
- [Cite The Survey](#Cite-The-Survey)
- [Contact](#contact)


## Methods: A Survey

### Face Swapping
|Year|Venue|Category|Paper Title|Code|
|:-:|:-:|:-:|-|-|
|2024|arXiv|Difussion|Towards a Simultaneous and Granular Identity-Expression Control in Personalized Face Generation|[Code](https://diffsfsr.github.io/)|
|2024|TMM|Other|An Efficient Attribute-Preserving Framework for Face Swapping|-|
|2024|TMM|GANs+3D|StableSwap: Stable Face Swapping in a Shared and Controllable Latent Space|-|
|2023|arXiv|GANs|FlowFace++: Explicit Semantic Flow-supervised End-to-End Face Swapping|-|
|2023|CVPR|GANs+3DMM|StyleIPSB: Identity-Preserving Semantic Basis of StyleGAN for High Fidelity Face Swapping|[Code](https://github.com/a686432/StyleIPSB)|
|2023|CVPR|GANs+3DMM|3D-Aware Face Swapping|[Code](https://lyx0208.github.io/3dSwap/)|
|2023|CVPR|GANs|Fine-Grained Face Swapping via Regional GAN Inversion|[Code](https://github.com/e4s2022/e4s)|
|2023|WACV|GANs|FastSwap: A Lightweight One-Stage Framework for Real-Time Face Swapping|[Code](https://github.com/sahngmin/fastswap)|
|2023|TECS|GANs+VAEs |XimSwap: many-to-many face swapping for TinyML|-|
|2023|WACV|GANs|FaceDancer: Pose- and Occlusion-Aware High Fidelity Face Swapping|[Code](https://github.com/felixrosberg/FaceDancer)|
|2023|ICCV|GANs|BlendFace: Re-designing Identity Encoders for Face-Swapping|[Code](https://github.com/mapooon/BlendFace)|
|2023|ICCV|GANs+3DMM|Reinforced Disentanglement for Face Swapping without Skip Connection|-|
|2023|CVPR|GANs|Attribute-preserving Face Dataset Anonymization via Latent Code Optimizatio|[Code](https://github.com/chi0tzp/FALCO)|
|2023|AAAI|GANs+3DMM|FlowFace: Semantic Flow-Guided Shape-Aware Face Swapping|-|
|2023|CVPR|Transformers|Face Transformer: Towards High Fidelity and Accurate Face Swapping|-|
|2023|ACM MM|GANs+3D|High Fidelity Face Swapping via Semantics Disentanglement and Structure Enhancement|-|
|2023|arXiv|GANs|High-Fidelity Face Swapping with Style Blending|-|
|2023|arXiv|GANs|End-to-end Face-swapping via Adaptive Latent Representation Learning|-|
|2023|FG|Transformers|TransFS: Face Swapping Using Transformer|-|
|2023|arXiv|Cycle triplets|ReliableSwap: Boosting General Face Swapping Via Reliable Supervision|[Code](https://github.com/ygtxr1997/ReliableSwap)|
|2023|CVPR|Difussion|DiffSwap: High-Fidelity and Controllable Face Swapping via 3D-Aware Masked Diffusion|[Code](https://github.com/wl-zhao/DiffSwap)|
|2023|arXiv|Difussion|A Generalist FaceX via Learning Unified Facial Representation|[Code](https://diffusion-facex.github.io/)|
|2022|AAAI|GANs|MobileFaceSwap: A Lightweight Framework for Video Face Swapping|[Code](https://github.com/Seanseattle/MobileFaceSwap)|
|2022|PAMI|GANs |FSGANv2: Improved Subject Agnostic Face Swapping and Reenactment|[Code](https://github.com/YuvalNirkin/fsgan)|
|2022|ICME|GANs|Migrating face swap to mobile devices: a lightweight framework and a supervised training solution|[Code](https://github.com/HoiM/MobileFSGAN)|
|2022|ECCV|GANs|StyleSwap: Style-Based Generator Empowers Robust Face Swapping|[Code](https://github.com/Seanseattle/StyleSwap)|
|2022|ECCV|GANs|Designing One Unified Framework for High-Fidelity Face Reenactment and Swapping|[Code](https://github.com/xc-csc101/UniFace)|
|2022|ECCV|GANs+3DMM|MFIM: Megapixel Facial Identity Manipulation|-|
|2022|CVPR|GANs|Region-Aware Face Swapping|[Code](https://github.com/xc-csc101/RAFSwap)|
|2022|CVPR|Difussion|Smooth-Swap: A Simple Enhancement for Face-Swapping with Smoothness|-|
|2022|arXiv|Difussion|DiffFace: Diffusion-based Face Swapping with Facial Guidance|[Code](https://hxngiee.github.io/DiffFace/)|
|2022|CVPR|GANs|High-resolution Face Swapping via Latent Semantics Disentanglement|[Code](https://github.com/cnnlstm/FSLSD_HiRes)|
|2021|CVPR|GANs+3DMM|FaceInpainter: High Fidelity Face Adaptation to Heterogeneous Domains|-|
|2021|CVPR|GANs|Information Bottleneck Disentanglement for Identity Swapping|-|
|2021|CVPR|GANs |One Shot Face Swapping on Megapixels|[Code](https://github.com/zyainfal/One-Shot-Face-Swapping-on-Megapixels)|
|2021|MMM|GANs |Deep Face Swapping via Cross-Identity Adversarial Training|-|
|2021|Neurocomputing|GANs |Unnoticeable synthetic face replacement for image privacy protection|-|
|2021|IJCAI|GANs+3DMM|HifiFace: 3D Shape and Semantic Prior Guided High Fidelity Face Swapping|[Code](https://github.com/johannwyh/HifiFace)|
|2020|CVPR|GANs|FaceShifter: Towards High Fidelity And Occlusion Aware Face Swapping|[Code](https://lingzhili.com/FaceShifterPage/)|
|2020|CVPR|GANs|DeepFaceLab: Integrated, flexible and extensible face-swapping framework|[Code](https://github.com/iperov/DeepFaceLab)|
|2020|NeurIPS|GANs|AOT: Appearance Optimal Transport Based Identity Swapping for Forgery Detection|[Code](https://github.com/zhuhaozh/AOT)|
|2020|ACM MM|GANs+VAEs |SimSwap: An Efficient Framework For High Fidelity Face Swapping|[Code](https://github.com/neuralchen/SimSwap)|
|2020|AAAI|GANs+VAEs |Deepfakes for Medical Video De-Identification: Privacy Protection and Diagnostic Information Preservation|-|


### Face Reenactment
|Year|Venue|Paper Title|Code|
|:-:|:-:|-|-|
|2024|AAAI|Learning Dense Correspondence for NeRF-Based Face Reenactment|-|
|2024|IJCV|One-shot Neural Face Reenactment via Finding Directions in GAN's Latent Space|-|
|2023|CVPR|High-Fidelity and Freely Controllable Talking Head Video Generation|[Code](https://yuegao.me/PECHead)|
|2023|TPAMI|Free-headgan: Neural talking head synthesis with explicit gaze control|-|
|2023|ICCV|HyperReenact: One-Shot Reenactment via Jointly Learning to Refine and Retarget Faces|[Code](https://github.com/StelaBou/HyperReenact)|
|2023|CVPR|MetaPortrait: Identity-Preserving Talking Head Generation with Fast Personalized Adaptation|-|
|2023|CVPR|One-shot high-fidelity talking-head synthesis with deformable neural radiance field|[Code](https://www.waytron.net/hidenerf/)|
|2023|FG|Stylemask: Disentangling the style space of stylegan2 for neural face reenactment|[Code](https://github.com/StelaBou/StyleMask.)|
|2022|ECCV|Face2Faceρ: Real-Time High-Resolution One-Shot Face Reenactment|-|
|2022|CVPR|Dual-Generator Face Reenactment|-|
|2021|ICCV|PIRenderer: Controllable Portrait Image Generation via Semantic Neural Rendering|[Code](https://github.com/RenYurui/PIRender)|
|2021|ICCV|Headgan: One-shot neural head synthesis and editing|-|
|2020|CVPR|FReeNet: Multi-Identity Face Reenactment|-|
|2020|FG|Head2Head: Videobased neural head synthesis|-|
|2020|ECCV|Fast bilayer neural synthesis of one-shot realistic head avatars|-|
|2020|AAAI|MarioNETte: Few-Shot Face Reenactment Preserving Identity of Unseen Targets|-|
|2019|ACM TOG|Deferred Neural Rendering: Image Synthesis using Neural Textures|-|
|2019|ACM TOG|Neural style-preserving visual dubbing|-|
|2019|ICCV|Few-Shot Adversarial Learning of Realistic Neural Talking Head Models|-|
|2018|CVPR|X2Face: A network for controlling face generation using images, audio, and pose codes|-|
|2018|ACM TOG|Deep video portraits|-|
|2018|NeurIPS|Video to video synthesis|[Code](https://github.com/NVIDIA/vid2vid)|
|2016|CVPR|Face2Face: Real-time Face Capture and Reenactment of RGB Videos|-|



### Talking Face Generation
|Year|Venue|Category|Paper Title|Code|
|:-:|:-:|:-:|-|-|
|2024|WACV|Diffusion|Diffused Heads: Diffusion Models Beat GANs on Talking-Face Generation|[Code](https://mstypulkowski.github.io/diffusedheads/)|
|2024|ICAART|Diffusion|DiT-Head: High-Resolution Talking Head Synthesis using Diffusion Transformers|-|
|2024|WACV|Audio|DR2: Disentangled Recurrent Representation Learning for Data-Efficient Speech Video Synthesis|-|
|2024|WACV|Audio|RADIO: Reference-Agnostic Dubbing Video Synthesis|-|
|2024|CVPR|NeRF|SyncTalk: The Devil is in the Synchronization for Talking Head Synthesis|[Code](https://github.com/ZiqiaoPeng/SyncTalk)|
|2024|AAAI|Audio|AE-NeRF: Audio Enhanced Neural Radiance Field for Few Shot Talking Head Synthesis|-|
|2024|AAAI|Audio|Mimic: Speaking Style Disentanglement for Speech-Driven 3D Facial Animation |[Code](https://github.com/huifu99/Mimic)|
|2023|CVPR|Multimodal|High-Fidelity Generalized Emotional Talking Face Generation With Multi-Modal Emotion Space Learning|-|
|2023|CVPR|Multimodal|LipFormer: High-fidelity and Generalizable Talking Face Generation with A Pre-learned Facial Codebook|-|
|2023|CVPR|Audio|Sadtalker: Learning realistic 3d motion coefficients for stylized audio-driven single image talking face animation|[Code](https://sadtalker.github.io/)|
|2023|CVPR|Audio|Seeing What You Said: Talking Face Generation Guided by a Lip Reading Expert|-|
|2023|ICCV|Audio|Speech2Lip: High-fidelity Speech to Lip Generation by Learning from a Short Video|[Code](https://github.com/CVMI-Lab/Speech2Lip)|
|2023|ICCV|Audio|EMMN: Emotional Motion Memory Network for Audio-driven Emotional Talking Face Generation|-|
|2023|TNNLS|Audio|Talking Face Generation With Audio-Deduced Emotional Landmarks|-|
|2023|ICASSP|Audio|Memory-augmented contrastive learning for talking head generation|[Code](https://github.com/Yaxinzhao97/MACL.git)|
|2023|CVPR|Audio|Identity-Preserving Talking Face Generation with Landmark and Appearance Priors|[Code](https://github.com/Weizhi-Zhong/IP_LAP)|
|2023|TCSVT|Audio|Stochastic Latent Talking Face Generation Towards Emotional Expressions and Head Poses|-|
|2023|ICCV|Audio|Efficient Emotional Adaptation for Audio-Driven Talking-Head Generation|[Code](https://github.com/yuangan/EAT_code)|
|2023|arXiv|Audio|GMTalker: Gaussian Mixture based Emotional talking video Portraits|[Code](https://bob35buaa.github.io/GMTalker)|
|2023|Displays|Audio|Talking face generation driven by time–frequency domain features of speech audio|-|
|2023|arXiv|Diffusion|DreamTalk: When Expressive Talking Head Generation Meets Diffusion Probabilistic Models|[Code](https://dreamtalk-project.github.io/)|
|2023|ICCV|Diffusion|Talking Head Generation with Probabilistic Audio-to-Visual Diffusion Priors|[Code](https://github.com/zxYin/TH-PAD)|
|2023|arXiv|Diffusion|DREAM-Talk: Diffusion-based Realistic Emotional Audio-driven Method for Single Image Talking Face Generation|[Code](https://magic-research.github.io/dream-talk/)|
|2023|ICCV|Audio|SPACE : Speech-driven Portrait Animation with Controllable Expression|[Code](https://research.nvidia.com/labs/dir/space/)|
|2023|Displays|Multimodal|Flow2Flow: Audio-visual cross-modality generation for talking face videos with rhythmic head|[Code](-)|
|2023|ICCV|Audio|EmoTalk: Speech-Driven Emotional Disentanglement for 3D Face Animation|[Code](https://github.com/psyai-net/EmoTalk_release)|
|2023|arXiv|Text|TalkCLIP: Talking Head Generation with Text-Guided Expressive Speaking Styles|-|
|2023|ACM MM|Diffusion|DAE-Talker: High Fidelity Speech-Driven Talking Face Generation with Diffusion Autoencoder|[Code](https://daetalker.github.io/)|
|2022|CVPR|Multimodal|Expressive Talking Head Generation with Granular Audio-Visual Control|-|
|2022|TMM|Multimodal|Multimodal Learning for Temporally Coherent Talking Face Generation With Articulator Synergy|[Code](http://imcc.ustc.edu.cn/project/tfgen/.)|
|2022|CVPR|Text|Talking Face Generation with Multilingual TTS|[Code](https://huggingface.co/spaces/CVPR/ml-talking-face)|
|2022|ECCV|Audio|Learning Dynamic Facial Radiance Fields for Few-Shot Talking Head Synthesis|[Code](https://sstzal.github.io/DFRF/)|
|2021|ICCV|Audio|FACIAL: Synthesizing Dynamic Talking Face with Implicit Attribute Learning|[Code](https://github.com/zhangchenxu528/FACIAL)|
|2021|CVPR|Multimodal|Pose-Controllable Talking Face Generation by Implicitly Modularized Audio-Visual Representation|[Code](https://github.com/Hangz-nju-cuhk/Talking-Face_PC-AVS)|
|2021|ICCV|Audio|AD-NeRF: Audio Driven Neural Radiance Fields for Talking Head Synthesis|[Code](https://github.com/YudongGuo/AD-NeRF)|
|2021|CVPR|Audio|Audio-driven emotional video portraits|[Code](https://github.com/jixinya/EVP)|
|2020|ICMR|Audio|A Lip Sync Expert Is All You Need for Speech to Lip Generatio In The Wild|[Code](https://github.com/Rudrabha/Wav2Lip)|
|2020|ACM TOG|Audio|MakeItTalk: Speaker-Aware Talking-Head Animation|[Code](https://github.com/adobe-research/MakeItTalk)|




### Face Attribute Editing
|Year|Venue|Category|Paper Title|Code|
|:-:|:-:|:-:|-|-|
|2023|CVPR|Diffusion|Collaborative Diffusion for Multi-Modal Face Generation and Editing|[Code](https://github.com/ziqihuangg/Collaborative-Diffusion)|
|2023|ICCV|GANs|Conceptual and Hierarchical Latent Space Decomposition for Face Editing|-|
|2023|NN|GANs|IA-FaceS: A bidirectional method for semantic face editing|[Code](https://github.com/CMACH508/IA-FaceS)|
|2023|TPAMI|GANs+NeRF|CIPS-3D++: End-to-End Real-Time High-Resolution 3D-Aware GANs for GAN Inversion and Stylization|-|
|2023|SIGGRAPH|GANs+3DMM|ClipFace: Text-guided Editing of Textured 3D Morphable Models|[Code](https://github.com/shivangi-aneja/ClipFace)|
|2023|ICCV|GANs|Towards High-Fidelity Text-Guided 3D Face Generation and Manipulation Using only Images|-|
|2023|TPAMI|GANs|Image-to-Image Translation with Disentangled Latent Vectors for Face Editing|[Code](https://yusufdalva.github.io/vecgan/)|
|2023|CVPR|GANs|DPE: Disentanglement of Pose and Expression for General Video Portrait Editing|[Code](https://github.com/Carlyx/DPE)|
|2023|ACM MM|GANs|PixelFace+: Towards Controllable Face Generation and Manipulation with Text Descriptions and Segmentation Masks|[Code](https://github.com/qazwsx671713/PixelFace-Plus)|
|2022|CVPR|GANs+NeRF|FENeRF: Face Editing in Neural Radiance Fields|[Code](https://github.com/MrTornado24/FENeRF)|
|2022|Neural Networks|GANs|GuidedStyle: Attribute Knowledge Guided Style Manipulation for Semantic Face Editing|-|
|2022|SIGGRAPH|GANs+NeRF|FDNeRF: Few-shot Dynamic Neural Radiance Fields for Face Reconstruction and Expression Editing|[Code](https://fdnerf.github.io)|
|2022|CVPR|GANs|AnyFace: Free-style Text-to-Face Synthesis and Manipulation|-|
|2022|CVPR|GANs|TransEditor: Transformer-Based Dual-Space GAN for Highly Controllable Facial Editing|[Code](https://github.com/BillyXYB/TransEditor)|
|2022|SIGGRAPH|GANs+NeRF|NeRFFaceEditing: Disentangled Face Editing in Neural Radiance Fields|-|
|2022|TVCG|GANs +3D|Cross-Domain and Disentangled Face Manipulation With 3D Guidance|[Code](https://cassiepython.github.io/cddfm3d/index.html)|
|2021|ICCV|GANs |A Latent Transformer for Disentangled Face Editing in Images and Videos|[Code](https://github.com/InterDigitalInc/latent-transformer)|
|2021|CVPR|GANs|High-Fidelity and Arbitrary Face Editing|[Code](https://github.com/hologerry/HifaFace)|
|2020|JAS|GANs|MU-GAN: Facial Attribute Editing Based on Multi-Attention Mechanism|[Code](https://github.com/SuSir1996/MU-GAN)|
|2020|CVPR|GANs|Interpreting the Latent Space of GANs for Semantic Face Editing|[Code](https://github.com/genforce/interfacegan)|
|2020|ACCV|GANs|MagGAN: High-Resolution Face Attribute Editing with Mask-Guided Generative Adversarial Network|-|


### Detection Modal
|Year|Venue|Category|Paper Title|Code|
|:-:|:-:|:-:|-|-|
|2018|WIFS|Data Driven|In Ictu Oculi: Exposing AI Generated Fake Face Videos by Detecting Eye Blinking|[Code](https://github.com/yuezunli/WIFS2018_In_Ictu_Oculi)|
|2019|ICIP|Space Domain|Detection of Fake Images Via The Ensemble of Deep Representations from Multi Color Spaces|-|
|2019|ICIP|Space Domain|Detecting GAN-Generated Imagery Using Saturation Cues|[Code](https://github.com/yuezunli/CVPRW2019_Face_Artifacts)|
|2019|ICCV|Data Driven|Attributing Fake Images to GANs: Learning and Analyzing GAN Fingerprints|[Code](https://github.com/ningyu1991/GANFingerprints)|
|2019|CVPRW|Space Domain|Exposing DeepFake Videos By Detecting Face Warping Artifacts|[Code](https://github.com/yuezunli/CVPRW2019_Face_Artifacts)|
|2019|ICASSP|Time Domain|Exposing deep fakes using inconsistent head poses|-|
|2019|ICASSP|Space Domain|Capsule-forensics: Using Capsule Networks to Detect Forged Images and Videos|[Code](https://github.com/nii-yamagishilab/Capsule-Forensics)|
|2020|IJCAI|Data Driven|FakeSpotter: A Simple yet Robust Baseline for Spotting AI-Synthesized Fake Faces|-|
|2020|CVPR|Space Domain|Global Texture Enhancement for Fake Face Detection in the Wild|[Code](https://github.com/liuzhengzhe/Global_Texture_Enhancement_for_Fake_Face_Detection_in_the-Wild)|
|2020|CVPR|Data Driven|On the Detection of Digital Face Manipulation|[Code](https://cvlab.cse.msu.edu/project-ffd.html)|
|2020|Signal Processing|Space Domain|Identification of Deep Network Generated Images Using Disparities in Color Components|[Code](https://github.com/lihaod/GAN_image_detection)|
|2020|CVPR|Space Domain|Face X-ray for More General Face Forgery Detection|-|
|2020|ICML|Space Domain|Leveraging Frequency Analysis for Deep Fake Image Recognition|[Code](https://github.com/RUB-SysSec/GANDCTAnalysis)|
|2020|ECCV|Space Domain|Thinking in Frequency: Face Forgery Detection by Mining Frequency-aware Clues|-|
|2020|ECCV|Space Domain|Two-Branch Recurrent Network for Isolating Deepfakes in Videos|-|
|2020|ECCV|Space Domain|What makes fake images detectable? Understanding properties that generalize|[Code](https://github.com/chail/patch-forensics)|
|2021|CVPR|Space Domain|Multi-attentional Deepfake Detection|[Code](https://github.com/yoctta/multiple-attention)|
|2021|TPAMI|Space Domain|DeepFake Detection Based on Discrepancies Between Faces and their Context|-|
|2021|ICCV|Data Driven|Learning Self-Consistency for Deepfake Detection|-|
|2021|CVPR|Space Domain|Frequency-aware Discriminative Feature Learning Supervised by Single-Center Loss for Face Forgery Detection|-|
|2021|ICCV|Time Domain|Exploring Temporal Coherence for More General Video Face Forgery Detection|[Code](https://github.com/yinglinzheng/FTCN)|
|2021|CVPR|Time Domain|Lips Don’t Lie: A Generalisable and Robust Approach to Face Forgery Detection|[Code](https://github.com/ahaliassos/LipForensics)|
|2021|CVPR|Time Domain|Detecting Deep-Fake Videos from Aural and Oral Dynamics|-|
|2022|TIFS|Space Domain|FakeLocator: Robust Localization of GAN-Based Face Manipulations|-|
|2022|CVPR|Space Domain|Detecting Deepfakes with Self-Blended Images|[Code](https://github.com/mapooon/SelfBlendedImages)|
|2022|CVPR|Space Domain|End-to-End Reconstruction-Classification Learning for Face Forgery Detection|[Code](https://github.com/VISION-SJTU/RECCE)|
|2022|ECCV|Space Domain|Explaining Deepfake Detection by Analysing Image Matching|-|
|2022|TIFS|Space Domain|Hierarchical Frequency-Assisted Interactive Networks for Face Manipulation Detection|-|
|2022|ICMR|Time Domain|M2TR: Multi-modal Multi-scale Transformers for Deepfake Detection|[Code](https://github.com/wangjk666/M2TR-Multi-modal-Multi-scale-Transformers-for-Deepfake-Detection)|
|2022|AAAI|Time Domain|Delving into the Local: Dynamic Inconsistency Learning for DeepFake Video Detection|-|
|2022|CVPR|Time Domain|Leveraging Real Talking Faces via Self-Supervision for Robust Forgery Detection|[Code](https://github.com/ahaliassos/RealForensics)|
|2022|AAAI|Data Driven|FInfer: Frame Inference-Based Deepfake Detection for High-Visual-Quality Videos|-|
|2023|CVPR|Data Driven|Implicit Identity Driven Deepfake Face Swapping Detection|-|
|2023|TMM|Data Driven|Narrowing Domain Gaps with Bridging Samples for Generalized Face Forgery Detection|-|
|2023|CVPR|Data Driven|Hierarchical Fine-Grained Image Forgery Detection and Localization|[Code](https://github.com/CHELSEA234/HiFi_IFDL)|
|2023|CVPR|Time Domain|Learning on Gradients: Generalized Artifacts Representation for GAN-Generated Images Detection|[Code](https://github.com/chuangchuangtan/lgrad)|
|2023|ICCV|Data Driven|Towards Generic Image Manipulation Detection with Weakly-Supervised Self-Consistency Learning|-|
|2023|ICCV|Data Driven|Quality-Agnostic Deepfake Detection with Intra-model Collaborative Learning|-|
|2023|TIFS|Space Domain|Constructing New Backbone Networks via Space-Frequency Interactive Convolution for Deepfake Detection|[Code](https://github.com/EricGzq/SFIConv)|
|2023|ICCV|Data Driven|Controllable Guide-Space for Generalizable Face Forgery Detection|-|
|2023|AAAI|Space Domain|Noise Based Deepfake Detection via Multi-Head Relative-Interaction|-|
|2023|TIFS|Time Domain|Dynamic Difference Learning With Spatio–Temporal Correlation for Deepfake Video Detection|-|
|2023|TIFS|Time Domain|Masked Relation Learning for DeepFake Detection|[Code](https://github.com/zimyang/MaskRelation)|
|2023|CVPR|Time Domain|Audio-Visual Person-of-Interest DeepFake Detection|[Code](https://github.com/gripunina/poi-forensics.)|
|2023|CVPR|Time Domain|Self-Supervised Video Forensics by Audio-Visual Anomaly Detection|[Code](https://cfeng16.github.io/audio-visual-forensics/)|
|2023|Applied Soft Computing|Time Domain|AVFakeNet: A unified end-to-end Dense Swin Transformer deep learning model for audio–visual​ deepfakes detection|-|
|2023|TCSVT|Time Domain|PVASS-MDD: Predictive Visual-audio Alignment Self-supervision for Multimodal Deepfake Detection|-|
|2023|TIFS|Time Domain|AVoiD-DF: Audio-Visual Joint Learning for Detecting Deepfake|-|
|2023|arXiv|Time Domain|AV-Lip-Sync+: Leveraging AV-HuBERT to Exploit Multimodal Inconsistency for Video Deepfake Detection|-|
|2024|arXiv|Space Domain|Diffusion Facial Forgery Detection|-|
|2024|WACV|Space Domain|Deepfake Detection by Exploiting Surface Anomalies: The SurFake Approach|-|

## Cite The Survey
If you find our survey and repository useful for your research project, please consider citing our paper:

```bibtex

```
## Contact

```
51265904018@stu.ecnu.edu.cn
```
```
186368@zju.edu.cn
```
