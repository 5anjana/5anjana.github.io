---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a **Machine Learning Engineer** at **Trase ai**, specializing in deep learning, computer vision, multimodal learning, and responsible AI product development. Academically, I hold a **Master’s in Data Science** from the **University of Virginia**, and an integrated **Master and Bachelor of Technology** in **Geological Technology** and **Mathematics** from the **Indian Institute of Technology Roorkee**. <br>

Previously, I collaborated with **Deloitte** to build LLM evaluation pipelines and served as a **Research Scientist** at **Univesity of Virginia** with [Dr. Donald E. Brown](https://engineering.virginia.edu/faculty/donald-e-brown) and [Dr. Sana Syed](https://med.virginia.edu/chrc/key-investigators/sana-syed-md-ms/), where I trained ML models for disease classification and pattern recognition in multimodal medical data. Previously I have interned at **BNY Mellon** and **ZestMoney** as a **Software Engineer**. <br><b>


# 📖 Education
- **2024 - 2025:** Masters in Data Science &#124; University of Virginia 
- **2021 - 2022:** Masters in Technology &#124; Indian Institute of Technology, Roorkee
- **2017 - 2021:** Bachelors in Technology &#124; Indian Institute of Technology, Roorkee 

# 💻 Experience
- **Machine Learning Engineer** at Trase ai &#124; August 2025 - Ongoing <br>
  - Architecting and deploying machine learning solutions to automate complex data workflows and processing pipelines across the oil & gas and healthcare sectors.

- **Machine Learning Researcher** at University of Virginia &#124; July 2022 - May 2024 <br>
  - Worked with a multi-disciplinary team of medical professionals and engineers to study gut functions.
  - Implemented novel Deep Learning models for disease diagnosis and quantification.
  - Leveraged Machine Learning for pattern recognition in tissue images, clinical data, and transcriptomic data.

- **Software Engineering Intern** at BNY Mellon &#124; Summer 2021 <br>
  - Implemented functional and unit testing for internal applications.
  - Developed a custom XML to CSV Parser Utility.
  - Conducted A/B testing to assess performance optimizations in internal applications.

- **Software Engineering Intern** at ZestMoney &#124; Summer 2019 <br>
  - Implemented a Payment Gateway at checkout using SpringBoot & MySQL database.
  - Developed a custom user Signup interface using Retrofit (Android) with MVVM architecture.
  - Improved code usability in a high-paced fintech industry startup environment.


# 📂 Projects
> **Evaluating efficacy of synthetic images generated using diffusion models** <br>
> Developed diffusion models to generate histology patches conditioned on nuclei locations. Validated the use of synthetic patches for improving downstream segmentation and classification tasks. <br>
> [Code](https://github.com/5anjana/diffusion-downstream)

> **Deep learning based detection and visual understanding of diseases using medical imaging data** <br>
> Performed patch-based invasive ductal carcinoma (breast cancer) and gastrointestinal disease detection. Implemented convolutional neural networks (CNN) for classifying whole slide images and biomarker data. Implemented Gaussian clustering methods to identify recurring visual patterns in diseased biopsies. <br>
> [Code](https://github.com/5anjana/ml-breast-cancer-detection)

> **StyleSwap: Text-driven latent diffusion model for localized fashion image editing** <br>
> Designed a localized fashion image editing pipeline using text-driven latent diffusion and semantic segmentation. <br>
> [Code](https://github.com/5anjana/StyleSwap)

> **Humorous Image Captioning System** <br>
> Implemented a self-attentive encoder-decoder framework to generate humorous captions for images indistinguishable from human generated memes. <br>
> [Code](https://github.com/5anjana/humorous-caption-generation)

> **Correlating disease gene signature with imaging data** <br>
> Designed a deep learning framework to identify image features associated with functional gene clusters. Identified important gene signatures and their correlation with visual patterns in biopsies. <br>
> [Code](https://github.com/SyedLab-GI/ee-omics)

> **Deep learning based semantic segmentation on brain MR images** <br>
>  Performed tumor segmentation using a U-Net architecture on MRIs. Used PyTorch for training model on MRIs from The Cancer Genome Atlas (TCGA) lower-grade glioma collection. <br>
> [Code](https://github.com/5anjana/brain-tumor-mri-segmentation)

> **Petrographic characterisation of a chondrite sample** <br>
> Investigated the mineralogy and major element geochemistry of mineral phases present in the chondrite section. Performed Electron Probe Micro Analysis to obtain backscattered electron images of the sample. <br>

> **Alzheimer's disease analyses using patient data** <br>
> Explored factors associated with Alzheimer's, developed a predictive model, and conducted statistical analyses using regression models on patient chart data. <br>
> [Code](https://github.com/5anjana/alzheimer-linear-regression)

> **Chicken Litte Run** <br>
> A fun run and dodge game developed on HTML Canvas where the Chicken Little must run and dodge the falling sky. <br>
> [Code](https://github.com/5anjana/Chicken-Little-Run)

# 📝 Publications 

> **Comparative Study of Large Language Model Evaluation Frameworks with a Focus on NLP vs LLM-As-A-Judge Metrics** <br>
> **S. Srivastava**, A. Alabdulwahab, C. Japic, C. Le, D. Dubey, D. Trivedi, J. Hope, P. Stone, A. Tashman, A. Zhang. <br>
> Systems and Information Engineering Design Symposium (SIEDS) 2025. <br>
> [Paper](https://ieeexplore.ieee.org/document/11021089)

> **Machine-learning-based integrative–‘omics analyses reveal immunologic and metabolic dysregulation in environmental enteric dysfunction** <br>
> F. Zulqarnain, X. Zhao, K. Setchell, Y. Sharna, P. Fernandes, **S. Srivastava**, A. Shrivastava, L.Ehsan, V. Jain, S. Raghavan, C. Moskaluk, Y. Haberman, L.A. Denson, K. Mehta, N.T. Iqbal, N. Rahman, K. Sadiq, Z. Ahmad, R. Idress, J. Iqbal, S. Ahmed, A. Hotwani, F. Umrani, B. Amadi, P. Kelly, D.E. Brown, S.R. Moore, S.A. Ali, S. Syed. <br>
> iScience 2024. <br>
> [Paper](https://www.cell.com/iscience/fulltext/S2589-0042(24)01238-0)

> **Quantitative Morphometry and Machine Learning Model to Explore Duodenal and Rectal Mucosal Tissue of Children with Environmental Enteric Dysfunction** <br>
> M. Khan, Z. Jamil, L. Ehsan, F. Zulqarnain, **S. Srivastava**, S. Siddiqui, P. Fernandes, M. Raghib, S. Sengupta, Z. Mujahid, Z. Ahmed, R. Idrees, S. Ahmed, F. Umrani, N. Iqbal, C. Moskaluk, S. Raghavan, L. Cheng, S. Moore, S.A. Ali, J. Iqbal, S. Syed. <br>
> The American Journal of Tropical Medicine and Hygiene (ASTMH) 2023. <br>
> [Paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10077000)
