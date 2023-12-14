# VectorTalker
VectorTalker: SVG Talking Face Generation with Progressive Vectorisation

Abstract
High-fidelity and efficient audio-driven talking head generation has been a key research topic in computer graphics and computer vision.In this work, we study vector image based audio-driven talking head generation.Compared with directly animating the raster image that most widely used in existing works, vector image enjoys its excellent scalability being used for many applications.There are two main challenges for vector image based talking head generation: the high-quality vector image reconstruction {\it w.r.t.} the source portrait image and the vivid animation {\it w.r.t.} the audio signal.To address these, we propose a novel scalable vector graphic reconstruction and animation method, dubbed VectorTalker.
Specifically, for the high-fidelity reconstruction, VectorTalker hierarchically reconstructs the vector image in a coarse-to-fine manner.
For the vivid audio-driven facial animation, we propose to use facial landmarks as intermediate motion representation and propose an efficient landmark-driven vector image deformation module.
Our approach can handle various styles of portrait images within a unified framework, including Japanese manga, cartoon, and photorealistic images. 
We conduct extensive quantitative and qualitative evaluations and the experimental results demonstrate the superiority of VectorTalker in both vector graphic reconstruction and audio-driven animation.
