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

I am a **Masters in Data Science student** at the **University of Virginia**, scheduled to graduate in May 2025. I have a strong background in machine learning, deep learning, data analytics, and AI product development. I previously worked as a **Research Scientist** at **University of Virginia** with [Dr. Donald E. Brown](https://engineering.virginia.edu/faculty/donald-e-brown) and [Dr. Sana Syed](https://research.med.virginia.edu/chrc/key-investigators/sana-syed-md-ms/). My work involved training and fine-tuning models for specific tasks and applying advanced natural language processing (NLP) and computer vision techniques to multimodal medical data. Previously I have interned at **BNY Mellon** and **ZestMoney** as a **Software Developer**. I also hold a **Master of Technology** and a **Bachelor of Technology** in **Geological Technology** with a minor in **Mathematics** from the **Indian Institute of Technology, Roorkee**. Find my [CV here](https://5anjana.github.io/assets/CV.pdf). 


# 📖 Education
- **2024 - present:** Masters in Data Science &#124; University of Virginia 
- **2021 - 2022:** Masters in Technology &#124; Indian Institute of Technology, Roorkee
- **2017 - 2021:** Bachelors in Technology &#124; Indian Institute of Technology, Roorkee 

# 💻 Experience
- **Research Scientist** at University of Virginia &#124; July 2022 - May 2024 <br>
  - Worked with a multi-disciplinary team of medical professionals and engineers to study gut functions.
  - Researched and implemented novel Deep Learning models for disease diagnosis and quantification.
  - Used Machine Learning for pattern recognition in tissue images, clinical data, and transcriptomic data.

- **Software Development Intern** at BNY Mellon &#124; Summer 2021 <br>
  - Implemented functional and unit testing for internal applications.
  - Developed a custom XML to CSV Parser Utility.
  - Fixed application and security vulnerabilities of the internal applications.

- **Software Development Intern** at ZestMoney &#124; Summer 2019 <br>
  - Integrated a Payment Gateway at checkout using SpringBoot & MySQL database.
  - Implemented a custom user Signup interface using Retrofit (Android) with MVVM architecture.
  - Developed a Base Adapter to reduce the code redundancy thus maintaining code’s usability.


# 📂 Projects
> **Evaluating efficacy of synthetic images generated using diffusion models** <br>
> Trained diffusion models to generate histology patches conditioned on nuclei locations. Evaluated the use of synthetic patches for improving downstream segmentation and classification tasks. <br>
> [Code](https://github.com/5anjana/diffusion-downstream)

> **Deep learning based detection and visual understanding of diseases using medical imaging data** <br>
> Performed patch-based invasive ductal carcinoma (breast cancer) and gastrointestinal disease detection. Implemented convolutional neural networks (CNN) for classifying whole slide images and biomarker data. Implemented Gaussian clustering methods to identify recurring visual patterns in diseased biopsies. <br>
> [Code](https://github.com/5anjana/ml-breast-cancer-detection)

> **Humorous Image Captioning System** <br>
> Implemented a self-attentive encoder-decoder framework to generate humorous captions for images indistinguishable from human generated memes. <br>

> **Correlating disease gene signature with imaging data** <br>
> Designed a deep learning framework to identify image features associated with functional gene clusters. Identified important gene signatures and their correlation with visual patterns in biopsies. <br>
> [Code](https://github.com/SyedLab-GI/ee-omics)

> **Deep learning based semantic segmentation on brain MR images** <br>
>  Performed tumor segmentation using a U-Net architecture on MRIs. Used PyTorch for training model on MRIs from The Cancer Genome Atlas (TCGA) lower-grade glioma collection. <br>
> [Code](https://github.com/5anjana/brain-tumor-mri-segmentation)

> **Petrographic characterisation of a chondrite sample** <br>
> Investigated the mineralogy and major element geochemistry of mineral phases present in the chondrite section. Performed Electron Probe Micro Analysis to obtain backscattered electron images of the sample. <br>

> **Buy and sell application** <br>
> Developed an intranet application for buying, selling and requesting goods among campus residents. Features include categorization of goods, subscribing, filtering, and searching based on users input. <br>

# 📝 Publications 

> **Machine-learning-based integrative–‘omics analyses reveal immunologic and metabolic dysregulation in environmental enteric dysfunction** <br>
> F. Zulqarnain, X. Zhao, K. Setchell, Y. Sharna, P. Fernandes, **S. Srivastava**, A. Shrivastava, L.Ehsan, V. Jain, S. Raghavan, C. Moskaluk, Y. Haberman, L.A. Denson, K. Mehta, N.T. Iqbal, N. Rahman, K. Sadiq, Z. Ahmad, R. Idress, J. Iqbal, S. Ahmed, A. Hotwani, F. Umrani, B. Amadi, P. Kelly, D.E. Brown, S.R. Moore, S.A. Ali, S. Syed. <br>
> iScience 2024. <br>
> [Paper](https://www.cell.com/iscience/fulltext/S2589-0042(24)01238-0)


> **Quantitative Morphometry and Machine Learning Model to Explore Duodenal and Rectal Mucosal Tissue of Children with Environmental Enteric Dysfunction** <br>
> M. Khan, Z. Jamil, L. Ehsan, F. Zulqarnain, **S. Srivastava**, S. Siddiqui, P. Fernandes, M. Raghib, S. Sengupta, Z. Mujahid, Z. Ahmed, R. Idrees, S. Ahmed, F. Umrani, N. Iqbal, C. Moskaluk, S. Raghavan, L. Cheng, S. Moore, S.A. Ali, J. Iqbal, S. Syed. <br>
> The American Journal of Tropical Medicine and Hygiene 2023. <br>
> [Paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10077000)
