I'm Farzana. I work on medical image analysis, and most of my research comes back to one question: do the numbers we report actually hold up? I'm a research collaborator at the Big-Matrix R&D Lab at North South University, and I work as a software engineer at Ternary Solutions, where I build LLM systems that a person reviews before anything goes out. Before that I was a remote research intern at the Kamaleswaran Lab at Duke.

More about me and my research: [farzanasupti.github.io](https://farzanasupti.github.io). I'm on [LinkedIn](https://www.linkedin.com/in/farzana-rahman-supti/) and [ResearchGate](https://www.researchgate.net/profile/Farzana-Supti), or email me at farzanasupti@gmail.com.

### What I'm working on

[Brain-Tumor-Segmentation](https://github.com/farzanasupti/Brain-Tumor-Segmentation) is a pre-registered study of whether telling a U-Net the tumour type helps it segment brain MRI. So far it doesn't, even when the model is given the true type. Along the way I measured how much splitting by slice instead of by patient inflates the scores, and I found a shortcut that our own augmentation was creating. I'm doing this with MD Mahi Sarkar and Farhana Rahman Elma, and the paper is in preparation.

[skin-disease-classification](https://github.com/farzanasupti/skin-disease-classification) started as a benchmark of eight models on a public skin-condition dataset. Then I found that its 9,548 images come from only 341 photographs, each saved with 27 augmented copies. The project now groups each photograph with its copies, scores only on the originals, and shows how much an ordinary image-level split overstates accuracy. This one is also with Mahi and Elma, and also in preparation.

I'm also starting a bilingual (English and Bangla) brain-MRI question-answering benchmark whose answers come straight from expert masks, so every answer can be checked.

### Earlier work

- A first-author paper comparing a small custom CNN with seven pretrained models for skin disease classification, under review at *Scientific Reports*.
- A replication of PP-SAM (CVPR Workshops 2024), few-shot SAM adaptation on Kvasir-SEG, squeezed onto a small GPU.
- A U-Net with Mamba blocks for 2D BraTS slices.
- River erosion classification from satellite images with the Civil & Environmental Engineering department at NSU.
- [Virtual-TryOn](https://github.com/farzanasupti/Virtual-TryOn) and [BashaBari](https://github.com/farzanasupti/BashaBari), from my undergrad.

Day to day I write Python and PyTorch for research, and TypeScript, FastAPI and React at work. Most of my industry code is in private repositories.
