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

I am a **Masters in Data Science student** at the **University of Virginia**, scheduled to graduate in May 2025. I have a strong background in deep learning, computer vision, multimodal learning, product analytics, healthcare research, large language models, and resposible AI product development. <br><br>
I previously worked as a **Research Scientist** at **University of Virginia** with [Dr. Donald E. Brown](https://engineering.virginia.edu/faculty/donald-e-brown) and [Dr. Sana Syed](https://research.med.virginia.edu/chrc/key-investigators/sana-syed-md-ms/). My work involved using data science techniques and training machine learning models for disease classification and pattern recognition in multimodal medical data. <br><br>
I am currently working on a capstone project with **Deloitte** as a **Data Scientist**, focusing on evaluating large language models assessment methodologies, including NLP-based approaches and LLM-as-a-judge methods, to assess LLM-generated content across multiple dimensions. <br><br>
Previously I have interned at **BNY Mellon** and **ZestMoney** as a **Software Developer**. I also hold a **Master of Technology** and a **Bachelor of Technology** in **Geological Technology** and **Mathematics** from the **Indian Institute of Technology, Roorkee**. Find my [CV here](https://5anjana.github.io/assets/CV_Sanjana_Srivastava.pdf). 


# 📖 Education
- **2024 - May 2025:** Masters in Data Science &#124; University of Virginia 
- **2021 - 2022:** Masters in Technology &#124; Indian Institute of Technology, Roorkee
- **2017 - 2021:** Bachelors in Technology &#124; Indian Institute of Technology, Roorkee 

# 💻 Experience
- **Data Scientist** at Deloitte (Capstone Project) &#124; September 2024 - Ongoing <br>
  - Comparative study of large language model evaluation frameworks with a focus on NLP vs LLM-as-a-judge metric.
  - Analyzing large language model evaluation frameworks like AWS Bedrock, GCP Vertex, and RAGAS to assess LLM-generated content.
  - Investigating six dimensions of LLM assessment, including bias, hallucination, and toxicity detection.

- **Research Scientist** at University of Virginia &#124; July 2022 - May 2024 <br>
  - Worked with a multi-disciplinary team of medical professionals and engineers to study gut functions.
  - Implemented novel Deep Learning models for disease diagnosis and quantification.
  - Leveraged Machine Learning for pattern recognition in tissue images, clinical data, and transcriptomic data.

- **Software Development Intern** at BNY Mellon &#124; Summer 2021 <br>
  - Implemented functional and unit testing for internal applications.
  - Developed a custom XML to CSV Parser Utility.
  - Conducted A/B testing to assess performance optimizations in internal applications.

- **Software Development Intern** at ZestMoney &#124; Summer 2019 <br>
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

> **Alzheimer's disease analyses using patient data** <br>
> Explored factors associated with Alzheimer's, developed a predictive model, and conducted statistical analyses using regression models on patient chart data. <br>
> [Code] (https://github.com/5anjana/alzheimer-linear-regression)

> **Omniport Registration web application** <br>
> Developed an Intranet application for students, professors, and staff for Channel i registration. Channel i is the portal with intranet applications of IIT Roorkee. <br>
> [Website](https://channeli.in/maintainer_site/)

> **Buy and Sell application** <br>
> Developed an intranet application for buying, selling and requesting goods among campus residents. Features include categorization of goods, subscribing, filtering, and searching based on users input. <br>
> [Code] (https://github.com/IMGIITRoorkee/omniport-app-buy-and-sell)

> **People Search** <br>
> Developed an Intranet application to manage contact information of students and faculty of IIT Roorkee. Features consists of recursive searching and content filtering based on the users input. Implemented Student Homepages, a UI template to view each student's bio in a standard format. <br>
> [Code](https://github.com/IMGIITRoorkee/omniport-frontend-people_search)

> **Chicken Litte Run** <br>
> A fun run and dodge game developed on HTML Canvas where the Chicken Little must run and dodge the falling sky. <br>
> [Code] (https://github.com/5anjana/Chicken-Little-Run)

# 📝 Publications 

> **Machine-learning-based integrative–‘omics analyses reveal immunologic and metabolic dysregulation in environmental enteric dysfunction** <br>
> F. Zulqarnain, X. Zhao, K. Setchell, Y. Sharna, P. Fernandes, **S. Srivastava**, A. Shrivastava, L.Ehsan, V. Jain, S. Raghavan, C. Moskaluk, Y. Haberman, L.A. Denson, K. Mehta, N.T. Iqbal, N. Rahman, K. Sadiq, Z. Ahmad, R. Idress, J. Iqbal, S. Ahmed, A. Hotwani, F. Umrani, B. Amadi, P. Kelly, D.E. Brown, S.R. Moore, S.A. Ali, S. Syed. <br>
> iScience 2024. <br>
> [Paper](https://www.cell.com/iscience/fulltext/S2589-0042(24)01238-0)


> **Quantitative Morphometry and Machine Learning Model to Explore Duodenal and Rectal Mucosal Tissue of Children with Environmental Enteric Dysfunction** <br>
> M. Khan, Z. Jamil, L. Ehsan, F. Zulqarnain, **S. Srivastava**, S. Siddiqui, P. Fernandes, M. Raghib, S. Sengupta, Z. Mujahid, Z. Ahmed, R. Idrees, S. Ahmed, F. Umrani, N. Iqbal, C. Moskaluk, S. Raghavan, L. Cheng, S. Moore, S.A. Ali, J. Iqbal, S. Syed. <br>
> The American Journal of Tropical Medicine and Hygiene 2023. <br>
> [Paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10077000)
