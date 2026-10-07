# Hi, I'm Indra 👋

AI researcher and engineer in Seoul, from Surabaya, Indonesia. I hold a Ph.D. in Computer Engineering and I work on **vision–language models**, currently on diagnosing and repairing fine-grained discrimination failures in Mixture-of-Experts VLMs; and on **multimodal document understanding** for retrieval systems. Before that: generative models for image restoration, and real-time computer-vision systems now running at Seoul subway stations.

[![Website](https://img.shields.io/badge/Website-indraimanuel.github.io-00c878?style=flat&logo=googlechrome&logoColor=white)](https://indraimanuel.github.io)
[![Email](https://img.shields.io/badge/Email-indraimanuel145@gmail.com-red?style=flat&logo=gmail)](mailto:indraimanuel145@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-indra--imanuel-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/indra-imanuel/)
[![YouTube](https://img.shields.io/badge/YouTube-Indra%20in%20Korea-FF0000?style=flat&logo=youtube&logoColor=white)](https://www.youtube.com/@IndrainKorea)

**I'm currently looking for a postdoctoral position** (available from early 2027).

---

## 🔬 Current research

**The Calibration Law: diagnosing and repairing answer-position bias in MoE vision–language models**  
*Independent project · manuscript in preparation (ICML 2027 target) · project lead, with two collaborators*

MoE VLMs fail badly at telling apart images that differ in one small detail. We show much of the underlying failure is a severe answer-position bias, introduce a zero-cost diagnostic (the *bias index*), and establish, across eight open MoE VLMs, a "calibration law": training-free interventions (router steering, prompting, output-logit calibration) succeed in proportion to how well they calibrate that bias. A label-free recipe greatly improves the VisMin group score and transfers zero-shot to Winoground and ColorSwap, and the router-steering effect is localized causally to final-layer prefill routing.

**When can a second pass fix document structure? An end-to-end anatomy of hierarchy repair**  
*Laputa, 2026 · manuscript in preparation (ICDAR 2027 target) · proposed and lead the project*

PDF extractors recover text well and document hierarchy poorly. A self-supervised 115M pointer model, trained on pseudo-labels mined from section numbering and embedded PDF outlines with no human annotation, benchmarked end-to-end against deterministic rules, a 26B LLM, and the supervised 4B multimodal state of the art on three benchmarks. Preliminary results show deep, unnumbered book hierarchy is largely invisible to text-side and crop-level methods alike.

**Research interests:** vision–language models · Mixture-of-Experts and efficient architectures · fine-grained visual understanding · model diagnosis, repair, and evaluation methodology · multimodal document understanding · generative models for image restoration

## 📄 Publications (first author)

- [**Optimized Color Filter Array for Denoising Diffusion Null-Space Model-Based Demosaicing.**](https://doi.org/10.1109/ACCESS.2024.3448451) I. Imanuel, H. Yang, S. Lee.  
  *IEEE Access*, 2024. · `SCIE`
- [**Denoising Diffusion Null-Space Model and Colorization based Image Compression.**](https://doi.org/10.7236/IJIBC.2024.16.2.22) I. Imanuel, D. Kang, S. Lee.  
  *Int. J. Internet, Broadcasting and Communication*, 16(2), 2024 · `KCI`
- [**Demosaicing based Image Compression with Channel-wise Decoder.**](https://doi.org/10.7236/IJIBC.2023.15.4.74) I. Imanuel, S. Lee.  
  *Int. J. Internet, Broadcasting and Communication*, 15(4), 2023 · `KCI`
- [**Image Compression with Channel-wise Decoder.**](https://doi.org/10.1109/ICCE-Asia57006.2022.9954761) I. Imanuel, S. Lee.  
  *IEEE ICCE-Asia*, 2022. · `🏅 Best Paper Award (Silver Prize)`
- [**Super-resolution with adversarial loss on the feature maps of the generated high-resolution image.**](https://doi.org/10.1049/ell2.12360) I. Imanuel, S. Lee.  
  *Electronics Letters*, 58, 2022. · `SCIE`

## 💼 Experience
 
**AI Research Engineer. Laputa, Inc. (AI subsidiary of Sapyoung Publisher), Seoul · Dec 2025 – present**
- Develop an LLM-based multimodal Q&A system over Korean university textbooks
- Own the RAG and agentic workflow around a 26B VLM MoE model, the database and PDF-extraction pipeline, and cloud-GPU deployment (RunPod, Docker, EC2)
- Proposed and lead the document-hierarchy repair research project

`LLM` `RAG` `agentic workflows` `vLLM` `Qdrant` `Unsloth` `Docker` `RunPod` `EC2`
 
**AI Research Engineer. STANS, Inc. (MDS Intelligence subsidiary), Seoul · Oct 2024 – Nov 2025**
- Surveyed, fine-tuned, and quantized computer-vision models for intelligent CCTV: object detection, crowd counting, violence detection (action recognition + optical flow)
- Built auto-labeling pipelines and annotation guidelines; prepared the violence-detection system for KISA school-safety certification evaluation
- Detection and crowd-density systems deployed at Seoul subway stations

`object detection` `action recognition` `crowd counting` `ONNX` `TensorRT` `quantization` `MLOps`
 
**Graduate Student Researcher. Image Processing Lab, Dongseo University, Busan · Sep 2019 – Aug 2024**
- Generative models for image restoration under Prof. Suk-Ho Lee; five first-author papers
- Lab projects beyond the thesis: a commissioned DeepView implementation for ETRI, U-Net blood-vessel segmentation, CSRNet crowd counting
- Funded by NRF, ETRI, and Dongseo University research grants

`GAN` `diffusion models` `image restoration` `view synthesis` `segmentation`
 
**Android App Developer. PT. Mat Ali Teknologi, Surabaya · Feb – Jul 2019**
- Developed an Android chat application

`Kotlin` `Android` `Node.js`

## 🎓 Education

- **Ph.D., Computer Engineering**. Dongseo University, 2021–2024. Thesis: *Image Compression and Demosaicing based on Denoising Diffusion Null-Space Model*. GPA 4.33/4.50.
- **M.Sc., Computer Engineering**. Dongseo University, 2019–2021. Thesis: *Super-Resolution with Adversarial Loss on the Feature Maps of the Generated High-Resolution Image*. GPA 4.50/4.50.
- **B.Comp., Informatics Engineering**. University of Surabaya, 2015–2019. Thesis: *Committee Management System for Dept. of Informatics in University of Surabaya*. Summa cum laude, best graduate of the department. GPA 3.94/4.00.

## 🛠️ Selected projects

- **Unibook: Multimodal textbook Q&A**. RAG and agentic workflow around a 26B VLM MoE model; vLLM, Qdrant, Unsloth, Docker, RunPod *(Laputa)*
- **AWAS-Insight: Crowd-density and object detection for Seoul metro**. Real-time crowd-counting and object-detection models, TensorRT/ONNX, deployed at Seoul subway stations *(STANS)*
- **AWAS-Insight: School violence detection**. Action-recognition and optical-flow models integrated with real-time object detector, prepared for KISA certification evaluation *(STANS)*
- **Construction-site real-time translation**. early-stage R&D: STT, NMT, TTS, LLM fine-tuning/RAG *(STANS)*
- **Diffusion-based demosaicing and compression**. learned CFA pattern and optimization scheme *(Ph.D.)*
- **GAN super-resolution with feature-map adversarial loss**. outperformed the SOTA CVPR method on a real-world benchmark at the time *(M.Sc.)*
- **DeepView multi-plane view synthesis**. commissioned reimplementation for ETRI *(lab)*
- Class projects: DQN on Sonic 2, adversarial masking of re-ID models, deep learning for network routing, genetic algorithms for TSP, curve interpolation from scratch

Full list with details → [indraimanuel.github.io/projects](https://indraimanuel.github.io/projects.html)

## 🎤 Talks & teaching

- Guest lecture, *Vision–Language Models: Trends, Applications, and Implementation*. Indonesian undergraduate webinar (ProjekinAja), Nov 2025
- Speaker, International Symposium on Management 2025 (University of Surabaya × Ho Chi Minh University of Banking). AI applications and data generation, May 2025
- Guest lecture for graduate students, University of Surabaya. Computer vision and image generation (CNNs, GANs, diffusion), Sep 2024
- Teaching assistant, Department of Informatics, University of Surabaya. Algorithms & Programming, Web Design, Web Programming, 2016–2018

Full list with PPTs (coming soon) → [indraimanuel.github.io/talks](https://indraimanuel.github.io/talks.html)

## 🧰 Skills

**Frameworks & tools:** PyTorch, TensorFlow, ONNX, TensorRT, OpenCV · vLLM, Unsloth, Qdrant, Hugging Face Transformers, bitsandbytes · Docker, RunPod, EC2 · MLOps and production model deployment  
**Languages:** Indonesian (native) · English (IELTS 8.0) · Korean (KIIP Level 5 / TOPIK 4 equivalent)

## 🌏 Beyond research

- 🏝️ Field surveyor and translator for a Hansung University study on Indonesian and East Timorese laborers on remote Korean islands (Gaeya, Bogil, Nohwa), 2021
- 📱 Built a physics learning app for Indonesian high-school students for a volunteer education program (Unity/C#)
- 🎥 [Indra in Korea](https://www.youtube.com/@IndrainKorea). A YouTube channel about international student life and travel in Korea, 2019–2025; scripted, filmed, and edited everything myself
- 🏆 Excellent Researcher Award (Dongseo Graduate School) · Best Paper Award, IEEE ICCE-Asia 2022 · full scholarships across all three degrees

The story from Surabaya to Busan to Seoul → [indraimanuel.github.io/about](https://indraimanuel.github.io/about.html)
