# Mind2Matter: Creating 3D Models from EEG Signals
Official PyTorch Implementation for the "Mind2Matter: Creating 3D Models from EEG Signals" paper.
<p align="center">
    🌐 <a href="https://sddwwww.github.io/Mind2Matter/" target="_blank">Project</a> | 📃 <a href=" " target="_blank">Paper</a> 
</p>
Authors：<a href="https://scholar.google.com/citations?user=SSKS1dkAAAAJ&hl=zh-CN" target="_blank">Xia Deng</a><sup>*</sup>,
<a href="https://scholar.google.com/citations?user=IbztFUkAAAAJ&hl=zh-CN" target="_blank">Shen Chen</a><sup>*</sup>,
<a href="https://scholar.google.com/citations?hl=zh-CN&view_op=list_works&gmla=AJsN-F5yGRJxWWcHNRcFDqNfhHQ3QOduf8VZZhrsHCD4jrqBtny5WX5iE2gOKA0CNuEKyxiSIXvI_r7BXW6CI7OXcy0KKNDHDkaOyYowEUuNJl9FvX9DcGQ&user=caYfi18AAAAJ" target="_blank">Jiale Zhou</a><sup>†</sup>,
<a href="https://scholar.google.com/citations?user=DOyVxx0AAAAJ&" target="_blank">Lei Li</a><sup>†</sup></span>


## Abstract
The reconstruction of 3D objects from brain signals has gained significant attention in brain-computer interface (BCI) research. Current research predominantly utilizes functional magnetic resonance imaging (fMRI) for 3D reconstruction tasks due to its excellent spatial resolution. Nevertheless, the clinical utility of fMRI is limited by its prohibitive costs and inability to support real-time operations. In comparison, electroencephalography (EEG) presents distinct advantages as an affordable, non-invasive, and mobile solution for real-time brain-computer interaction systems. While recent advances in deep learning have enabled remarkable progress in image generation from neural data, decoding EEG signals into structured 3D representations remains largely unexplored. In this paper, we propose a novel framework that translates EEG recordings into 3D object reconstructions by leveraging neural decoding techniques and generative models. Our approach involves training an EEG encoder to extract spatiotemporal visual features, fine-tuning a large language model to interpret these features into descriptive multimodal outputs, and leveraging generative 3D Gaussians with layout-guided control to synthesize the final 3D structures. Experiments demonstrate that our model captures salient geometric and semantic features, paving the way for applications in braincomputer interfaces (BCIs), virtual reality, and neuroprosthetics.  


## Demo
### EEG-to-Text Generation
### Text-to-3D Generation

