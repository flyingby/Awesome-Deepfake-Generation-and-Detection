<p align="center">
 <img src="https://github.com/flyingby/Awesome-Deepfake-Generation-and-Detection/blob/main/proj%20logo.png" style="width: 15%; display: inline-block; margin-bottom: -10000px; vertical-align: middle;">
  <h1 align="center"> Deepfake Generation and Detection: 
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

[2]  It also contains several related domains, including Heas Swapping, Face Super-resolution, Face Reconstruction, Face Inpainting, Body Animation, Portrait Style Transfer, Makeup Transfer and Adversarial Sample Detection. 

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
  - [Facial Attribute Editing](#Facial-Attribute-Editing)
  - [Foreign Detection](#Foreign-Detection) 
- [Related Research Domains](#Related-Research-Domains)
  - [Face Super-resolution](#Face-Super-resolution) 
  - [Portrait Style Transfer](#Portrait-Style-Transfer)
  - [Body Animation](#Body-Animation)
  - [Makeup Transfer](#Makeup-Transfer)
- [Cite The Survey](#Cite-The-Survey)
- [Contact](#contact)


## Methods: A Survey

### Face Swapping
|Year|Venue|Category|Paper Title|Code|
|:-:|:-:|:-:|-|-|
|2024|arXiv|3DGS|ImplicitDeepfake: Plausible Face-Swapping through Implicit Deepfake Generation using NeRF and Gaussian Splatting|[Code](https://github.com/quereste/implicit-deepfake)|
|2024|arXiv|GANs|LatentSwap: An Efficient Latent Code Mapping Framework for Face Swapping|-|
|2024|arXiv|Difussion|Face Swap via Diffusion Model|-|
|2024|arXiv|Difussion|Towards a Simultaneous and Granular Identity-Expression Control in Personalized Face Generation|[Code](https://diffsfsr.github.io/)|
|2024|arXiv|GANs|E4S: Fine-grained Face Swapping via Editing With Regional GAN Inversion|[Code](https://e4s2024.github.io/)|
|2024|ICIP|Graphic|RID-TWIN: An end-to-end pipeline for automatic face de-identification in videos|[Code](https://github.com/AnirbanMukherjeeXD/RID-Twin)|
|2024|TCSVT|VAE|Identity-Aware Variational Autoencoder for Face Swapping|-|
|2024|ICASSP|GANs+3D|Attribute-Aware Head Swapping Guided by 3d Modeling|-|
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
|2023|arXiv|GANs|End-to-end Face-swapping via Adaptive Latent Representation Learning|-|
|2023|FG|Transformers|TransFS: Face Swapping Using Transformer|-|
|2023|arXiv|Cycle triplets|ReliableSwap: Boosting General Face Swapping Via Reliable Supervision|[Code](https://github.com/ygtxr1997/ReliableSwap)|
|2023|CVPR|Difussion|DiffSwap: High-Fidelity and Controllable Face Swapping via 3D-Aware Masked Diffusion|[Code](https://github.com/wl-zhao/DiffSwap)|
|2023|arXiv|Difussion|A Generalist FaceX via Learning Unified Facial Representation|[Code](https://diffusion-facex.github.io/)|
|2022|AAAI|GANs|MobileFaceSwap: A Lightweight Framework for Video Face Swapping|[Code](https://github.com/Seanseattle/MobileFaceSwap)|
|2022|T-PAMI|GANs|FSGANv2: Improved Subject Agnostic Face Swapping and Reenactment|[Code](https://github.com/YuvalNirkin/fsgan)|
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
|2021|CVPR|GANs|One Shot Face Swapping on Megapixels|[Code](https://github.com/zyainfal/One-Shot-Face-Swapping-on-Megapixels)|
|2021|MMM|GANs|Deep Face Swapping via Cross-Identity Adversarial Training|-|
|2021|Neurocomputing|GANs |Unnoticeable synthetic face replacement for image privacy protection|-|
|2021|IJCAI|GANs+3DMM|HifiFace: 3D Shape and Semantic Prior Guided High Fidelity Face Swapping|[Code](https://github.com/johannwyh/HifiFace)|
|2020|CVPR|GANs|FaceShifter: Towards High Fidelity And Occlusion Aware Face Swapping|[Code](https://lingzhili.com/FaceShifterPage/)|
|2020|CVPR|GANs|DeepFaceLab: Integrated, flexible and extensible face-swapping framework|[Code](https://github.com/iperov/DeepFaceLab)|
|2020|NeurIPS|GANs|AOT: Appearance Optimal Transport Based Identity Swapping for Forgery Detection|[Code](https://github.com/zhuhaozh/AOT)|
|2020|ACM MM|GANs+VAEs|SimSwap: An Efficient Framework For High Fidelity Face Swapping|[Code](https://github.com/neuralchen/SimSwap)|
|2020|AAAI|GANs+VAEs|Deepfakes for Medical Video De-Identification: Privacy Protection and Diagnostic Information Preservation|-|


### Face Reenactment
|Year|Venue|Paper Title|Code|
|:-:|:-:|-|-|
|2024|arXiv|Superior and Pragmatic Talking Face Generation with Teacher-Student Framework|[Code](https://superfacelink.github.io/)|
|2024|arXiv|DiffusionAct: Controllable Diffusion Autoencoder for One-shot Face Reenactment|[Code](https://stelabou.github.io/diffusionact/)|
|2024|ICASSP|Expression Domain Translation Network for Cross-Domain Head Reenactment|-|
|2024|AAAI|Learning Dense Correspondence for NeRF-Based Face Reenactment|-|
|2024|AAAI|FG-EmoTalk: Talking Head Video Generation with Fine-Grained Controllable Facial Expressions |-|
|2024|IJCV|One-shot Neural Face Reenactment via Finding Directions in GAN's Latent Space|-|
|2023|CVPR|High-Fidelity and Freely Controllable Talking Head Video Generation|[Code](https://yuegao.me/PECHead)|
|2023|T-PAMI|Free-headgan: Neural talking head synthesis with explicit gaze control|-|
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
|2024|arXiv|Audio|EDTalk: Efficient Disentanglement for Emotional Talking Head Synthesis|[Code](https://tanshuai0219.github.io/EDTalk/)|
|2024|arXiv|Audio|FlowVQTalker: High-Quality Emotional Talking Face Generation through Normalizing Flow and Quantization|-|
|2024|arXiv|Audio|Talk3D: High-Fidelity Talking Portrait Synthesis via Personalized 3D Generative Prior|[Code](https://ku-cvlab.github.io/Talk3D/)|
|2024|arXiv|Diffusion|MoDiTalker: Motion-Disentangled Diffusion Model for High-Fidelity Talking Head Generation|-|
|2024|arXiv|Audio|ReliTalk: Relightable Talking Portrait Generation from a Single Video|[Code](https://github.com/arthur-qiu/ReliTalk)|
|2024|ICLR|Audio|Real3D-Portrait: One-shot Realistic 3D Talking Portrait Synthesis|[Code](https://real3dportrait.github.io/)|
|2024|IJCV|Multimodal|FlowVQTalker: High-Quality Emotional Talking Face Generation through Normalizing Flow and Quantization|-|
|2024|ICASSP|Text|Text-Driven Talking Face Synthesis by Reprogramming Audio-Driven Models|-|
|2024|ICASSP|Audio|Speech-Driven Emotional 3d Talking Face Animation Using Emotional Embeddings|-|
|2024|ICASSP|Audio|Exploring Phonetic Context-Aware Lip-Sync for Talking Face Generation|-|
|2024|ICASSP|Audio|Talking Face Generation for Impression Conversion Considering Speech Semantics|-|
|2024|ICASSP|NeRF|DT-NeRF: Decomposed Triplane-Hash Neural Radiance Fields For High-Fidelity Talking Portrait Synthesis|-|
|2024|ICASSP|Multimodal|Talking Face Generation for Impression Conversion Considering Speech Semantics|-|
|2024|ICAART|Diffusion|DiT-Head: High-Resolution Talking Head Synthesis using Diffusion Transformers|-|
|2024|WACV|Diffusion|Diffused Heads: Diffusion Models Beat GANs on Talking-Face Generation|[Code](https://mstypulkowski.github.io/diffusedheads/)|
|2024|WACV|Audio|DR2: Disentangled Recurrent Representation Learning for Data-Efficient Speech Video Synthesis|-|
|2024|WACV|Audio|RADIO: Reference-Agnostic Dubbing Video Synthesis|-|
|2024|CVPR|NeRF|SyncTalk: The Devil is in the Synchronization for Talking Head Synthesis|[Code](https://github.com/ZiqiaoPeng/SyncTalk)|
|2024|AAAI|Audio|AE-NeRF: Audio Enhanced Neural Radiance Field for Few Shot Talking Head Synthesis|-|
|2024|AAAI|Audio|Mimic: Speaking Style Disentanglement for Speech-Driven 3D Facial Animation |[Code](https://github.com/huifu99/Mimic)|
|2024|AAAI|Audio|Style2Talker: High-Resolution Talking Head Generation with Emotion Style and Art Style |-|
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




### Facial Attribute Editing
|Year|Venue|Category|Paper Title|Code|
|:-:|:-:|:-:|-|-|
|2024|arXiv|GANs|Reference-Based 3D-Aware Image Editing with Triplane|[Code](https://three-bee.github.io/triplane_edit)|
|2024|arXiv|GANs|3D-aware Image Generation and Editing with Multi-modal Conditions|-|
|2024|arXiv|Diffusion|DiffFAE: Advancing High-fidelity One-shot Facial Appearance Editing with Space-sensitive Customization and Semantic Preservation|-|
|2024|arXiv|Diffusion|DreamSalon: A Staged Diffusion Framework for Preserving Identity-Context in Editable Face Generation|-|
|2024|ICASSP|GANs|Semantic Latent Decomposition with Normalizing Flows for Face Editing|[Code](https://github.com/phil329/SDFlow)|
|2024|AAAI|GANs|SDGAN: Disentangling Semantic Manipulation for Facial Attribute Editing|-|
|2023|CVPR|Diffusion|Collaborative Diffusion for Multi-Modal Face Generation and Editing|[Code](https://github.com/ziqihuangg/Collaborative-Diffusion)|
|2023|ICCV|GANs|Conceptual and Hierarchical Latent Space Decomposition for Face Editing|-|
|2023|NN|GANs|IA-FaceS: A bidirectional method for semantic face editing|[Code](https://github.com/CMACH508/IA-FaceS)|
|2023|TPAMI|GANs+NeRF|CIPS-3D++: End-to-End Real-Time High-Resolution 3D-Aware GANs for GAN Inversion and Stylization|-|
|2023|SIGGRAPH|GANs+3DMM|ClipFace: Text-guided Editing of Textured 3D Morphable Models|[Code](https://github.com/shivangi-aneja/ClipFace)|
|2023|ICCV|GANs|Towards High-Fidelity Text-Guided 3D Face Generation and Manipulation Using only Images|-|
|2023|T-PAMI|GANs|Image-to-Image Translation with Disentangled Latent Vectors for Face Editing|[Code](https://yusufdalva.github.io/vecgan/)|
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


### Foreign Detection
|Year|Venue|Category|Paper Title|Code|
|:-:|:-:|:-:|-|-|
|2024|arXiv|Other|Real, fake and synthetic faces -- does the coin have three sides?|-|
|2024|arXiv|Space Domain|Diffusion Facial Forgery Detection|-|
|2024|arXiv|Space Domain|Masked Conditional Diffusion Model for Enhancing Deepfake Detection|-|
|2024|IJCV|Time Domain|Learning Spatiotemporal Inconsistency via Thumbnail Layout for Face Deepfake Detection|[Code](https://github.com/rainy-xu/TALL4Deepfake)|
|2024|NAACL|Time Domain|Heterogeneity over Homogeneity: Investigating Multilingual Speech Pre-Trained Models for Detecting Audio Deepfake|-|
|2024|CVPR|Time Domain|Exploiting Style Latent Flows for Generalizing Deepfake Detection Video Detection|[Code](https://openaccess.thecvf.com/)|
|2024|ICASSP|Space Domain|Selective Domain-Invariant Feature for Generalizable Deepfake Detection|-|
|2024|AAAI|Space Domain|Frequency-Aware Deepfake Detection: Improving Generalizability through Frequency Space Domain Learning|[Code](https://github.com/chuangchuangtan/FreqNet-DeepfakeDetection)|
|2024|AAAI|Space Domain|Exposing the Deception: Uncovering More Forgery Clues for Deepfake Detection|[Code](https://github.com/QingyuLiu/Exposing-the-Deception)|
|2024|WACV|Space Domain|Deepfake Detection by Exploiting Surface Anomalies: The SurFake Approach|-|
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
|2022|TIFS|Space Domain|FakeLocator: Robust Localization of GAN-Based Face Manipulations|-|
|2022|CVPR|Space Domain|Detecting Deepfakes with Self-Blended Images|[Code](https://github.com/mapooon/SelfBlendedImages)|
|2022|CVPR|Space Domain|End-to-End Reconstruction-Classification Learning for Face Forgery Detection|[Code](https://github.com/VISION-SJTU/RECCE)|
|2022|ECCV|Space Domain|Explaining Deepfake Detection by Analysing Image Matching|-|
|2022|TIFS|Space Domain|Hierarchical Frequency-Assisted Interactive Networks for Face Manipulation Detection|-|
|2022|ICMR|Time Domain|M2TR: Multi-modal Multi-scale Transformers for Deepfake Detection|[Code](https://github.com/wangjk666/M2TR-Multi-modal-Multi-scale-Transformers-for-Deepfake-Detection)|
|2022|AAAI|Time Domain|Delving into the Local: Dynamic Inconsistency Learning for DeepFake Video Detection|-|
|2022|CVPR|Time Domain|Leveraging Real Talking Faces via Self-Supervision for Robust Forgery Detection|[Code](https://github.com/ahaliassos/RealForensics)|
|2022|AAAI|Data Driven|FInfer: Frame Inference-Based Deepfake Detection for High-Visual-Quality Videos|-|
|2021|CVPR|Space Domain|Multi-attentional Deepfake Detection|[Code](https://github.com/yoctta/multiple-attention)|
|2021|T-PAMI|Space Domain|DeepFake Detection Based on Discrepancies Between Faces and their Context|-|
|2021|ICCV|Data Driven|Learning Self-Consistency for Deepfake Detection|-|
|2021|CVPR|Space Domain|Frequency-aware Discriminative Feature Learning Supervised by Single-Center Loss for Face Forgery Detection|-|
|2021|ICCV|Time Domain|Exploring Temporal Coherence for More General Video Face Forgery Detection|[Code](https://github.com/yinglinzheng/FTCN)|
|2021|CVPR|Time Domain|Lips Don’t Lie: A Generalisable and Robust Approach to Face Forgery Detection|[Code](https://github.com/ahaliassos/LipForensics)|
|2021|CVPR|Time Domain|Detecting Deep-Fake Videos from Aural and Oral Dynamics|-|
|2020|IJCAI|Data Driven|FakeSpotter: A Simple yet Robust Baseline for Spotting AI-Synthesized Fake Faces|-|
|2020|CVPR|Space Domain|Global Texture Enhancement for Fake Face Detection in the Wild|[Code](https://github.com/liuzhengzhe/Global_Texture_Enhancement_for_Fake_Face_Detection_in_the-Wild)|
|2020|CVPR|Data Driven|On the Detection of Digital Face Manipulation|[Code](https://cvlab.cse.msu.edu/project-ffd.html)|
|2020|Signal Processing|Space Domain|Identification of Deep Network Generated Images Using Disparities in Color Components|[Code](https://github.com/lihaod/GAN_image_detection)|
|2020|CVPR|Space Domain|Face X-ray for More General Face Forgery Detection|-|
|2020|ICML|Space Domain|Leveraging Frequency Analysis for Deep Fake Image Recognition|[Code](https://github.com/RUB-SysSec/GANDCTAnalysis)|
|2020|ECCV|Space Domain|Thinking in Frequency: Face Forgery Detection by Mining Frequency-aware Clues|-|
|2020|ECCV|Space Domain|Two-Branch Recurrent Network for Isolating Deepfakes in Videos|-|
|2020|ECCV|Space Domain|What makes fake images detectable? Understanding properties that generalize|[Code](https://github.com/chail/patch-forensics)|
|2019|ICIP|Space Domain|Detection of Fake Images Via The Ensemble of Deep Representations from Multi Color Spaces|-|
|2019|ICIP|Space Domain|Detecting GAN-Generated Imagery Using Saturation Cues|[Code](https://github.com/yuezunli/CVPRW2019_Face_Artifacts)|
|2019|ICCV|Data Driven|Attributing Fake Images to GANs: Learning and Analyzing GAN Fingerprints|[Code](https://github.com/ningyu1991/GANFingerprints)|
|2019|CVPRW|Space Domain|Exposing DeepFake Videos By Detecting Face Warping Artifacts|[Code](https://github.com/yuezunli/CVPRW2019_Face_Artifacts)|
|2019|ICASSP|Time Domain|Exposing deep fakes using inconsistent head poses|-|
|2019|ICASSP|Space Domain|Capsule-forensics: Using Capsule Networks to Detect Forged Images and Videos|[Code](https://github.com/nii-yamagishilab/Capsule-Forensics)|
|2018|WIFS|Data Driven|In Ictu Oculi: Exposing AI Generated Fake Face Videos by Detecting Eye Blinking|[Code](https://github.com/yuezunli/WIFS2018_In_Ictu_Oculi)|

## Related Research Domains

### Face Super-resolution
|Year|Venue|Paper Title|Code|
|:-:|:-:|-|-|
|2024|arXiv|Efficient Diffusion Model for Image Restoration by Residual Shifting|-|
|2024|arXiv|PFStorer: Personalized Face Restoration and Super-Resolution|-|
|2024|arXiv|DiffBIR: Towards Blind Image Restoration with Generative Diffusion Prior|[Code](https://github.com/XPixelGroup/DiffBIR)|
|2024|AAAI|ResDiff: Combining CNN and Diffusion Model for Image Super-Resolution|-|
|2024|AAAI|Low-Light Face Super-resolution via Illumination, Structure, and Texture Associated Representation|[Code](https://github.com/wcy-cs/IC-FSRDENet)|
|2024|AAAI|SkipDiff: Adaptive Skip Diffusion Model for High-Fidelity Perceptual Image Super-resolution|-|
|2024|WACV|Arbitrary-Resolution and Arbitrary-Scale Face Super-Resolution With Implicit Representation Networks|-|
|2024|ICASSP|Adaptive Super Resolution for One-Shot Talking-Head Generation|[Code](https://github.com/Songluchuan/AdaSR-TalkingHead/)|
|2023|CVPR|Spatial-Frequency Mutual Learning for Face Super-Resolution|[Code](https://github.com/wcy-cs/SFMNet)|
|2023|TIP|CTCNet: A CNN-Transformer Cooperation Network for Face Image Super-Resolution|[Code](https://github.com/IVIPLab/CTCNet)|
|2023|TIP|Semi-Cycled Generative Adversarial Networks for Real-World Face Super-Resolution|[Code](https://github.com/HaoHou-98/SCGAN)|
|2023|TMM|An Efficient Latent Style Guided Transformer-CNN Framework for Face Super-Resolution|[Code](https://github.com/FVL2020/ELSFace)|
|2023|TMM|Exploiting Multi-Scale Parallel Self-Attention and Local Variation via Dual-Branch Transformer-CNN Structure for Face Super-Resolution|-|
|2023|NN|Self-attention learning network for face super-resolution|-|
|2023|PR|A Composite Network Model for Face Super-Resolution with Multi-Order Head Attention Facial Priors|-|
|2022|CVPR|GCFSR: A Generative and Controllable Face Super Resolution Method Without Facial and GAN Priors|[Code](https://github.com/hejingwenhejingwen/GCFSR)|
|2022|ECCV|From Face to Natural Image: Learning Real Degradation for Blind Image Super-Resolution|[Code](https://github.com/csxmli2016/ReDegNet)|
|2022|TCSVT|Propagating Facial Prior Knowledge for Multitask Learning in Face Super-Resolution|[Code](https://github.com/wcy-cs/KDFSRNet)|
|2022|NN|Multi-level landmark-guided deep network for face super-resolution|[Code](https://github.com/zhuangcheng31/MLG_Face.git/)|

### Portrait Style Transfer
|Year|Venue|Paper Title|Code|
|:-:|:-:|-|-|
|2024|arXiv|ToonAging: Face Re-Aging upon Artistic Portrait Style Transfer|-|
|2024|ICASSP|A Framework for Portrait Stylization with Skin-Tone Awareness and Nudity Identification|-|
|2024|ICASSP|Learning Discriminative Style Representations for Unsupervised and Few-Shot Artistic Portrait Drawing Generation|[Code](https://github.com/AiArt-HDU/Co-GAN)|
|2024|TMM|FaceRefiner: High-Fidelity Facial Texture Refinement with Differentiable Rendering-based Style Transfer|-|
|2024|CVPR|Deformable One-shot Face Stylization via DINO Semantic Guidancen|[Code](https://github.com/zichongc/DoesFS)|
|2024|AAAI|MagiCapture: High-Resolution Multi-Concept Portrait Customization|-|
|2024|AAAI|ArtBank: Artistic Style Transfer with Pre-trained Diffusion Model and Implicit Style Prompt Bank|[Code](https://github.com/Jamie-Cheung/ArtBank)|
|2024|TNNLS|Few-Shot Face Stylization via GAN Prior Distillation|-|
|2023|TNNLS|Unpaired Artistic Portrait Style Transfer via Asymmetric Double-Stream GAN|-|
|2023|arXiv|PP-GAN : Style Transfer from Korean Portraits to ID Photos Using Landmark Extractor with GAN|-|
|2023|CVPR|Inversion-Based Style Transfer With Diffusion Models|[Code](https://github.com/zyxElsa/InST)|
|2023|ICCV|General Image-to-Image Translation with One-Shot Image Guidance|[Code](https://github.com/CrystalNeuro/visual-concept-translator)|
|2023|ACM TOG|A Unified Arbitrary Style Transfer Framework via Adaptive Contrastive Learning|[Code](https://github.com/zyxElsa/CAST_pytorch)|
|2023|Neurocomputing|Caster: Cartoon style transfer via dynamic cartoon style casting|-|
|2023|IJCV|Learning Portrait Drawing with Unsupervised Parts|-|
|2022|CVPR|Pastiche Master: Exemplar-Based High-Resolution Portrait Style Transfer|[Code](https://github.com/williamyang1991/DualStyleGAN)|
|2022|ACM TOG|VToonify: Controllable High-Resolution Portrait Video Style Transfer|[Code](https://www.mmlab-ntu.com/project/vtoonify/)|
|2022|ACM TOG|DCT-net: domain-calibrated translation for portrait stylization|[Code](https://github.com/menyifang/DCT-Net)|
|2022|ACM TOG|SofGAN: A Portrait Image Generator with Dynamic Styling|-|

### Body Animation
|Year|Venue|Paper Title|Code|
|:-:|:-:|-|-|
|2024|arXiv|Large Motion Model for Unified Multi-Modal Motion Generation|[Code](https://mingyuan-zhang.github.io/projects/LMM.html)|
|2024|arXiv|Champ: Controllable and Consistent Human Image Animation with 3D Parametric Guidance|[Code](https://fudan-generative-vision.github.io/champ)|
|2024|AAAI|PTUS: Photo-Realistic Talking Upper-Body Synthesis via 3D-Aware Motion Decomposition Warping|[Code](https://github.com/cooluoluo/PTUS)|
|2024|CVPR|Emotional Speech-driven 3D Body Animation via Disentangled Latent Diffusion|[Code](https://amuse.is.tue.mpg.de/)|
|2024|CVPR|DISCO: Disentangled Control for Realistic Human Dance Generation|[Code](https://disco-dance.github.io/)|
|2024|CVPR|MagicAnimate: Temporally Consistent Human Image Animation using Diffusion Model|[Code](https://showlab.github.io/magicanimate)|
|2024|CVPR|GaussianAvatar: Towards Realistic Human Avatar Modeling from a Single Video via Animatable 3D Gaussians|[Code](https://huliangxiao.github.io/GaussianAvatar)|
|2024|arXiv|Champ: Controllable and Consistent Human Image Animation with 3D Parametric Guidance|[Code](https://fudan-generative-vision.github.io/champ/#/)|
|2023|WACV|Physically Plausible Animation of Human Upper Body From a Single Image|-|
|2023|ICCV|Towards Multi-Layered 3D Garments Animation|[Code](www.mmlab-ntu.com/project/layersnet/index.html)|
|2023|ICCV|Make-An-Animation: Large-Scale Text-conditional 3D Human Motion Generation|[Code](https://azadis.github.io/make-an-animation/)|
|2023|CVPR|Learning anchor transformations for 3d garment animation|-|
|2023|arXiv|TADA! Text to Animatable Digital Avatars|[Code](https://tada.is.tue.mpg.de/)|
|2022|IJCAI|Text/Speech-Driven Full-Body Animation|[Code](https://github.com/YadiraF/SCARF)|
|2022|SIGGRAPH|Capturing and Animation of Body and Clothing from Monocular Video|-|
|2022|NeurIPS|CageNeRF: Cage-based Neural Radiance Field for Generalized 3D Deformation and Animation|[Code](https://pengyicong.github.io/CageNeRF/)|

### Makeup Transfer
|Year|Venue|Paper Title|Code|
|:-:|:-:|-|-|
|2024|arXiv|Stable-Makeup: When Real-World Makeup Transfer Meets Diffusion Model|-|
|2024|arXiv|Toward Tiny and High-quality Facial Makeup with Data Amplify Learning|-|
|2024|CVPR|Makeup Prior Models for 3D Facial Makeup Estimation and Applications|[Code](https://yangxingchao.github.io/makeup-priors-page/)|
|2024|ICASSP|Skin tone disentanglement in 2D makeup transfer with graph neural networks|-|
|2023|TNNLS|SSAT++: A Semantic-Aware and Versatile Makeup Transfer Network With Local Color Consistency Constraint|[Code](https://gitee.com/sunzhaoyang0304/ssat-msp)|
|2023|CVPR|BeautyREC: Robust, Efficient, and Component-Specific Makeup Transfer|[Code](https://li-chongyi.github.io/BeautyREC_files/)|
|2023|TCSVT|Hybrid Transformers with Attention-guided Spatial Embeddings for Makeup Transfer and Removal|-|
|2023|arXiv|SARA: Controllable Makeup Transfer with Spatial Alignment and Region-Adaptive Normalization|-|
|2022|ICCV|EleGANt: Exquisite and Locally Editable GAN for Makeup Transfer|[Code](https://github.com/Chenyu-Yang-2000/EleGANt)|
|2022|AAAI|SSAT: A Symmetric Semantic-Aware Transformer Network for Makeup Transfer and Removal|[Code](https://gitee.com/sunzhaoyang0304/ssat-msp)|
|2022|Knowledge-Based Systems|TSEV-GAN: Generative Adversarial Networks with Target-aware Style Encoding and Verification for facial makeup transfer|-|
|2022|Knowledge-Based Systems|CUMTGAN: An instance-level controllable U-Net GAN for facial makeup transfer|-|
|2021|CVPR|Lipstick ain’t enough: beyond color matching for in-the-wild makeup|[Code](https://github.com/VinAIResearch/CPM)|
|2021|T-PAMI|Psgan++: Robust detail-preserving makeup transfer and removal|[Code](https://github.com/wtjiang98/PSGAN)|
|2020|CVPR|PSGAN: Pose and Expression Robust Spatial-Aware GAN for Customizable Makeup Transfer|[Code](https://github.com/wtjiang98/PSGAN)|
|2019|CVPR|Beautyglow : On-demand makeup transfer framework with reversible generative network|[Code](https://github.com/BeautyGlow/BeautyGlow.github.io)|
|2019|ICCV|Ladn: Local adversarial disentangling network for facial makeup and de-makeup|[Code](https://georgegu1997.github.io/LADN-projectpage)|
|2018|ACM MM|BeautyGAN: Instance-level Facial Makeup Transfer with Deep Generative Adversarial Network|[Code](http://liusi-group.com/projects/BeautyGAN )|
|2018|CVPR|Pairedcyclegan: Asymmetric style transfer for applying and removing makeup|-|
|2017|AAAI|Examples-rules guided deep neural network for makeup recommendation|-|


## Cite The Survey
If you find our survey and repository useful for your research project, please consider citing our paper:

```bibtex
@article{pei2024deepfake,
  title={Deepfake Generation and Detection: A Benchmark and Survey},
  author={Pei, Gan and Zhang, Jiangning and Hu, Menghan and Zhai, Guangtao and Wang, Chengjie and Zhang, Zhenyu and Yang, Jian and Shen, Chunhua and Tao, Dacheng},
  journal={arXiv preprint arXiv:2403.17881},
  year={2024}
}
```
## Contact

```
51265904018@stu.ecnu.edu.cn
```
```
186368@zju.edu.cn
```
