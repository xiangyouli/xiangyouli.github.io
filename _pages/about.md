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


Dr. Li received his Ph.D. in Physical Electronics from [[Huazhong University of Science and Technology(HUST)]](https://www.hust.edu.cn/) in 2005. From 2009 to 2011, he worked as a JSPS Fellow at the National Institute of Advanced Industrial Science and Technology (AIST), Japan. He is currently a Research Professor at the **[[Wuhan National Laboratory for Optoelectronics]](https://wnlo.hust.edu.cn/)**, Huazhong University of Science and Technology.

His research focuses on **laser additive manufacturing (3D printing), laser micro/nano fabrication, and laser-induced breakdown spectroscopy (LIBS)**. In recent years, he has made significant contributions to the development of integrated spectroscopy analysis systems, real-time detection algorithms, and intelligent control software. His team has developed a series of proprietary instruments and software platforms for elemental analysis and laser processing, which have been successfully applied in aerospace and microelectronics industries.

Dr. Li has published over 200 scientific papers, including more than 100 as first or corresponding author in SCI-indexed journals. He holds over 70 granted Chinese invention patents, several U.S. patents, and multiple software copyrights. His research achievements have been recognized with the National Science and Technology Progress Award and other provincial-level honors, and featured in major national media outlets such as Xinhua News and People’s Daily.

I am looking for highly motivated master’s and PhD students. Applicants with the following qualities will be given priority:

- **Strong interest in scientific research**, and willingness to work on challenging problems.

- **Background in a relevant discipline**, such as optics/photonics, optoelectronics, mechanical engineering, materials science, control engineering, computer science, or related fields.

- **Good hands-on ability**, for experimental work, instrumentation, or software/hardware development.

- **Genuine interest in** laser additive manufacturing, spectroscopy, and intelligent detection systems (or related areas).

- **Solid foundation in mathematics and English**, sufficient for reading international literature and basic academic communication.

Interested students are welcome to contact me by email with a brief CV and a short description of their research interests.😊

<!-- # 🎓 Research
- **Processor Microarchitecture Design Based on LoongArch32R Instruction Set Architecture**  *2024.3-2024.8* [[project]](https://github.com/dzh314/BL-LA32R))
  + **Keywords**:Computer architecture, processor design, Verilog, FPGA, LoongArch, microarchitecture optimization
  + **Introduction**:This project designed and implemented a high-performance processor based on the LoongArch32R instruction set, featuring a seven-stage pipeline with a frequency of up to 100MHz, capable of running Linux. The project required efficient processor microarchitecture design skills and implementation on an actual FPGA platform for validation. The final result matched the best historical performance of Wuhan University.
  + **Personal Contributions**:
    * **Memory System Design**: Designed and optimized the processor's TLB (Translation Lookaside Buffer), cache, and other memory modules, improving memory access efficiency and data throughput, laying the foundation for the system’s subsequent operation.
    * **Platform Setup and Testing**: Led the deployment of the competition platform (Chiplab) based on FPGA development boards, and was responsible for testing and validating the processor's microarchitecture, including FPGA board and system functionality tests, ensuring the project's stability and performance met the standards.
  + **Project Outcome**:[Key Contributor] National Second Prize in the 2024 National University Computer System Ability Competition (Loongson Cup) - CPU Design Category

- **Probabilistic Feature Smoothed Gaussian Process for Imbalanced Regression** *2024.9-2024.10* [[paper]](https://openreview.net/forum?id=V1MDIFbqCp)
  + **Keywords**:Imbalanced learning, Gaussian process, Bayesian methods, machine learning
  + **Introduction**:This research proposed the Probabilistic Feature Smoothed Partially Independent Training Condition Approximation (PFS-PITC) method, which extracts statistical features through equidistant label spacing and applies kernel smoothing, effectively reducing the sensitivity of Gaussian Processes (GP) to imbalanced data. Experimental results show that this method significantly improves GP performance in imbalanced regression tasks and enhances robustness.
  + **Personal Contributions**:
    * **Experimental Code and Parameter Tuning**: Wrote code for some control experiments, adjusted model parameters, and compared performance metrics (MSE, MAE) with mainstream methods, ensuring the reproducibility and reliability of the results.
    * **Paper Writing and Data Visualization**: Contributed to writing the appendix of the paper and refined parts of the main content. Ran mainstream datasets and created experimental figures, ensuring the data presented in the paper was clear and met academic standards.
  + **Project Outcome**:[Second Author] The paper "Probabilistic Feature Smoothed Gaussian Process for Imbalanced Regression" was submitted to **ICLR 2025** (withdrawn submission).

- **Attention-free Sequence Prediction Modeling for Offline Embodied Learning** *2025.3*
  + **Keyword**s: Offline reinforcement learning, Sequence modeling, Attention dispersion
  + **Introduction**: This research treats offline reinforcement learning as a sequence modeling task. By analyzing the state-action-reward distribution mismatch in Decision Transformers leading to attention dispersion, we propose a hierarchical framework that combines a Token Merger and a parameter-free average-pooling Token Mixer, achieving dual improvements in both performance and computational efficiency.
  + **Personal Contributions**:
    * Responsible for writing the appendix and refining theoretical proofs, ensuring that the overall content meets academic standards.
  + **Project Outcome**: [Undergraduate Second Author] The paper "Less is More: an Attention-free Sequence Prediction Modeling for Offline Embodied Learning" has been submitted to **NeurIPS 2025**.

- **Internship at Digital Media and Intelligent Technology Research Institute**  *2025.1-present*
  + **Keywords**:Digital copyright protection, information hiding and watermarking, deep learning optimization, vector graphics automation design
  + **Introduction**:In the end-to-end vector font watermark generation study, implemented a novel SDF generation process optimization method, removing the reliance on derivative calculations, significantly enhancing the robustness of the watermark encoding system in complex environments. Improved the stability and accuracy of the model by adopting different neural network architectures to replace the traditional MLP used in the original method.

- **Internship at Post-Quantum Cryptography and Communication Systems Laboratory**  *2023.6-2024.12*
  + **Keywords**:Post-quantum cryptographic algorithms, chip design, hardware implementation, test platform development
  + **Introduction**:Worked on the hardware implementation of post-quantum cryptographic algorithms such as Kyber, Frodo, and SHA3. Designed a modular multiplication unit for the NTT butterfly operation unit, built platforms, and tested Frodo640, Frodo976, and Frodo1344.


# 📖 Educations
- *2022.08 - Now*, Undergraduate, [School of Computer Science](https://cs.whu.edu.cn/), [Wuhan University (WHU)](https://www.whu.edu.cn/), China. Majoring in Computer Science and Technology. 
- *2019.09 - 2022.06*, Senior Middle School,  [NO.1 Middle School affiliated to Central China Normal University](https://www.hzsdyfz.com.cn/), China.

# 🔧 Skills
- **Programming Skills**: Proficient in **C/C++**, **Verilog**, and **Python**. Experienced in algorithm competitions and computer hardware design projects. Additionally, skilled in data processing, deep learning model training, and optimization.
- **English Proficiency**: Successfully passed the **CET-4** and **CET-6** exams with good scores. Experienced in writing academic papers in English.
- **Development Tools**: Experienced with **VS Code**, **Xilinx Vivado**, **PyCharm**, **Visual Studio**, **LATEX** (Overleaf), and **Git**.
-->

<!--
# 🔥 News
- *2023.10* :I won the Lei Jun Computer Science Undergraduate Scholarship.
-->

<!--
# 📝 Publications 
*前面的世界，以后再来探索吧*
-->

<!--
# 🏆 Competition Awards
- **National Second Prize**: 2024 National College Student Computer Systems Capability Competition - CPU Design Contest (Loongson Cup), August 2024 [[certification]](https://yhish-yhish.github.io/certification/2024loongson.jpg)
- **National Silver Medal**: 2023 China Collegiate Programming Contest (CCPC), Silver Medal, October 2023 [[certification]](https://yhish-yhish.github.io/certification/CCPC2023NSCQ.pdf)
- **National Silver Medal**: 2022 China Collegiate Programming Contest (CCPC), Silver Medal, November 2022 [[certification]](https://yhish-yhish.github.io/certification/CCPC2022GCQ.pdf)
- **National Honorable Mention**: 2022 International Collegiate Programming Contest Asia Regional (ICPC Shenyang), November 2022 [[certification]](https://yhish-yhish.github.io/certification/icpcshenyang.png)
- **National Honorable Mention**: 2024 China Collegiate Computer Competition - Team Programming Ladder Contest, April 2024 [[certification]](https://yhish-yhish.github.io/certification/2024tianti.png)
- **National Honorable Mention**: 2023 China Collegiate Computer Competition - Team Programming Ladder Contest, May 2023 [[certification]](https://yhish-yhish.github.io/certification/2023tianti.png)
- **Provincial Third Prize**: 2024 China Collegiate Computer Design Competition - Central South Region, June 2024 [[certification]](https://yhish-yhish.github.io/certification/2024jishe.png)
- **Provincial Third Prize**: 2024 Blue Bridge Cup Hubei Regional C/C++ Programming University Group A, April 2024 [[certification]](https://yhish-yhish.github.io/certification/2024lanqiao.jpg)
- **Provincial Bronze Medal**: 2023 Hubei Province College Student Programming Contest (CCPC Hubei Provincial Contest), Bronze Medal, April 2023 [[certification]](https://yhish-yhish.github.io/certification/CCPC2023SSWH.jpg)
- **Provincial Third Prize**: 2023 Blue Bridge Cup Hubei Regional C/C++ Programming University Group A, April 2023 [[certification]](https://yhish-yhish.github.io/certification/2023lanqiao.pdf)
- **University First Prize (First Place)**: 2023 Wuhan University Cybersecurity Knowledge Competition, October 2023 [[certification]](https://yhish-yhish.github.io/certification/wangluoanquan.png)
- **University Bronze Medal**: 2022 Wuhan University Freshman Programming Contest, October 2022 [[certification]](https://yhish-yhish.github.io/certification/2022xinshengsai.jpg)
  <!-- - **University Top Four**: 2023 Wuhan University RISC-V Application Innovation Contest, December 2023 [[certification]](https://yhish-yhish.github.io/certification/riscv.jpg) -->
  
<!--
# 🎖 Scholarships and Honors
- *2024.11* **Wuhan University Special Scholarship – AEON Scholarship**: ￥8000, awarded to 25 students across four colleges
- *2024.10* **Wuhan University Merit Student Award**: Recognized as one of the top students at the university
- Other: **Wuhan University International Exchange Scholarship** and **Various Discipline Competition Scholarships**
- Cumulative total of over ￥30,000
-->

<!--
# 👨‍🎓 Student Activities
🌟Here are some highlights from the events I've participated in.
<div style="overflow-x: auto; white-space: nowrap;">
    <img src="https://yhish-yhish.github.io/images/guoxue_competition.png" style="display: inline-block; margin-right: 10px; height: 150px;" />
    <img src="https://yhish-yhish.github.io/images/ccpc_chongqing2023.jpg" style="display: inline-block; margin-right: 10px; height: 150px;" />
    <img src="https://yhish-yhish.github.io/images/renwentubu.png" style="display: inline-block; margin-right: 10px; height: 150px;" />
    <img src="https://yhish-yhish.github.io/images/guoxueshe_huanjie.jpg" style="display: inline-block; margin-right: 10px; height: 150px;" />
    <img src="https://yhish-yhish.github.io/images/icpc_shenyang.jpg" style="display: inline-block; margin-right: 10px; height: 150px;" />
    <img src="https://yhish-yhish.github.io/images/jiangxuejin.jpg" style="display: inline-block; margin-right: 10px; height: 150px;" />
</div>

- **Teaching Assistant, Computer Organization and Architecture** *Spring 2025*<br>
  Participated in a semester-long assisted teaching role as a teaching assistant. Introduced and modified experimental projects from other universities in order to design experiments that were deeply integrated with the course content; graded course assignments on time, answered undergraduate questions on duty and assisted in debugging experimental code.

- **Teaching Assistant, Digital Logic and Digital Circuits** *Spring 2024*<br>
  I assisted with the course for one semester, where my responsibilities included debugging Verilog lab code, grading the final exams for the entire year, and grading 10 course assignments on time. I also answered over 20 course-related questions from undergraduates, organized and participated in post-class discussions, and helped the instructor manage a class of over 80 students.

- **President & Academic Minister, LuoYuan Classical Culture Student Club, Wuhan University** *June 2023 - June 2024*  [[certification]](https://yhish-yhish.github.io/certification/luoyuan.pdf) <br>
  As the project leader for the 31st Wuhan University Club Culture Festival, I organized a university-wide Chinese culture studies knowledge competition. I collaborated with multiple student organizations to co-host events, promoted reforms in the club's structure and activity formats, and organized a full year of club activities. I also led classic literature readings and knowledge-sharing sessions with members, reviewed the club's academic content, and developed strong interdisciplinary thinking, a good sense of teamwork, and excellent organizational and communication skills.
-->

<!--
# 🎡 Activities
## Academic Services
*前面的世界，以后再来探索吧*
## Invited talks (Selected)
*前面的世界，以后再来探索吧*
-->

<!--
# 🔗 Useful Links
##  🤖 Course Recommendations

- *[高等数学-兆筱小分队](https://www.bilibili.com/video/BV1dJ411c7ab/?spm_id_from=333.788&vd_source=a8a064bcbd088bc6388119f018c52df7)*

- *[线性代数-limite](https://www.bilibili.com/video/BV1L7411a7Rz/?spm_id_from=333.999.0.0&vd_source=a8a064bcbd088bc6388119f018c52df7)*

- *[Essence of linear algebra](https://www.bilibili.com/video/BV1ys411472E/?spm_id_from=333.999.0.0&vd_source=a8a064bcbd088bc6388119f018c52df7)*

- *[Linear Algebra](https://www.youtube.com/watch?v=uUrt8xgdMbs&list=PLJV_el3uVTsNmr39gwbyV-0KjULUsN7fW)*

- *[汇编语言(王爽)](https://www.bilibili.com/video/BV1Wu411B72F/?spm_id_from=333.999.0.0&vd_source=a8a064bcbd088bc6388119f018c52df7)*

- *[c语言程序设计-翁凯](https://www.icourse163.org/spoc/course/zju-121004?tid=150003#/info)*

- *[CS231n Deep Learning for Computer Vision](http://cs231n.stanford.edu/)*

## 💻 Coding Skills

- *[GIT-菜鸟教程](https://www.runoob.com/git/git-tutorial.html)*

- *[Python最佳实践指南](http://itpcb.com/docs/pythonguide/)*

- *[Pytorch入门教程-小土堆](https://www.bilibili.com/video/BV1hE411t7RN/?spm_id_from=333.999.0.0&vd_source=a8a064bcbd088bc6388119f018c52df7)*

## 🧭 Examination or Study Guides

At present, I have no time to upload all the guides. If you need more, please send me an email (of course you need attach your grade, class and name).

-  *[网安导论知识点总结](https://github.com/1NormalGuy/1normalguy.github.io/raw/main/docs/dl.pdf)*

- *[指针数组 & 数组指针 & 二级指针 辨析](https://github.com/1NormalGuy/1normalguy.github.io/raw/main/docs/points.pdf)*

- *[2023年（2024届）网安院保研打分细则](https://github.com/1NormalGuy/1normalguy.github.io/raw/main/docs/2023baoyan.pdf)*

- *[武汉大学毕业论文&实验报告latex模版-overleaf](https://cn.overleaf.com/latex/templates/tagged/whu)*

-->

<!--## 📚 Textbooks

At present, I have no time to upload all the textbooks. If you need more, please send me an email (of course you need attach your grade, class and name).

- *[高等数学（下）-武汉大学](https://github.com/1NormalGuy/1normalguy.github.io/raw/main/docs\高等数学(上).pdf)*
-->


<!--
- 计算机设计大赛经验分享, Spring 2023. \[[Slides](https://github.com/AntigoneRandy/antigonerandy.github.io/raw/main/docs/ComputerDeignCompetition.pdf)\]

- 竞赛经验漫谈, Fall 2022. \[[Slides](https://github.com/AntigoneRandy/antigonerandy.github.io/raw/main/docs/Competitions-2022Fall.pdf)\]

- 新老生经验交流会, Fall 2021. \[[Slides and Other Materials](https://github.com/AntigoneRandy/antigonerandy.github.io/raw/main/docs/ExperienceSharing2021Winter.zip)\]
-->


<!--
$^\dagger$: equal contribution, $^*$: corresponding author
-->
<!-- ## 🛰️ Geoinformatics & Remote Sensing
- [Optimized Design Method for Satellite Constellation Configuration Based on Real-time Coverage Area Evaluation](https://ieeexplore.ieee.org/document/9963835)   
Jiahao Zhou, **Boheng Li**, Qingxiang Meng   
*The 29th International Conference on Geoinformatics (CPGIS), 2022*

- [Comprehensive Evaluation of Emergency Shelters in Wuhan City Based on GIS](https://ieeexplore.ieee.org/document/9963810)   
Tingyu Luo, **Boheng Li**, Jiahao Zhou, Qingxiang Meng   
*The 29th International Conference on Geoinformatics (CPGIS), 2022* -->

<!-- ## 🤖️ AI Security, Privacy & Intellectual Property (IP) Protection -->
<!--
- [What can Discriminator do? Towards Box-free Ownership Verification of Generative Adversarial Networks](https://arxiv.org/abs/2307.15860)   
Ziheng Huang$^\dagger$, **Boheng Li**$^\dagger$, Yan Cai, Run Wang, Shangwei Guo, Liming Fang, Jing Chen, Lina Wang   
*International Conference on Computer Vision (ICCV), 2023*

- [Free Fine-tuning: A Plug-and-Play Watermarking Scheme for Deep Neural Networks](https://arxiv.org/abs/2210.07809)   
Run Wang, Jixing Ren, **Boheng Li**, Tianyi She, Wenhui Zhang, Liming Fang, Jing Chen, Lina Wang  
*ACM Multimedia (MM), 2023*

- [Dual-level Interaction for Domain Adaptive Semantic Segmentation](https://arxiv.org/abs/2307.07972)   
Dongyu Yao, **Boheng Li**$^\*$   
*ICCV Workshop on Uncertainty Quantification for Computer Vision (UnCV), 2023*


Other 2 papers regarding IP protection of DL have currently been submitted to CCF-A tier conferences.
<!-- ## 🖨️ Preprints & In Submission
-->

<!-- # 💻 Internships
To be updated. -->

<!-- # 🔗 Useful Links

## Courses

- [Linear Algebra (Hung-yi Lee, NTU, 2018)](https://www.youtube.com/watch?v=uUrt8xgdMbs&list=PLJV_el3uVTsNmr39gwbyV-0KjULUsN7fW)

- [CS229: Machine Learning](https://cs229.stanford.edu/)

- [CS230 Deep Learning](https://cs230.stanford.edu/)

- [CS231n Deep Learning for Computer Vision](http://cs231n.stanford.edu/)

- [CS224n: Natural Language Processing with Deep Learning](http://web.stanford.edu/class/cs224n/)

- [CS131 Computer Vision: Foundations and Applications](http://vision.stanford.edu/teaching/cs131_fall2223/index.html)

- [北京邮电大学鲁鹏-计算机视觉 清晰版 国家级精品课程](https://www.bilibili.com/video/BV1VW4y1v7Ph/)

- [火炉课堂-深度学习 (厦门大学)](https://www.bilibili.com/video/BV1qq4y1f7Fm)

- [中科大-凸优化](https://www.bilibili.com/video/av40868517)

- [The Next Step for Machine Learning (Hung-yi Lee, NTU, 2019)](https://www.youtube.com/watch?v=XnyM3-xtxHs&list=PLJV_el3uVTsOK_ZK5L0Iv_EQoL1JefRL4)

- [人工智能的数学基础（清华出版社）](https://www.bilibili.com/video/BV15N4y1w7e1/)

- [理解机器学习](https://www.bilibili.com/video/BV1hg411h7ys)

## Writing

- 英文学术论文写作指南 \[[link](https://www.bilibili.com/video/BV1aa411H757/)\]

- 学术规范与论文写作-南开大学程明明 \[[link](https://www.bilibili.com/video/BV18F411M7YL/)\]

- [Matplotlib cheatsheets and handouts](https://matplotlib.org/cheatsheets/)

- [十分钟掌握Seaborn，进阶Python数据可视化分析](https://zhuanlan.zhihu.com/p/49035741)

- [科学写作与哲学](https://zhuanlan.zhihu.com/p/433168083)

- [绘图软件/编程大全](https://www.bilibili.com/video/BV1gR4y1y76U)

- [如何进行高质量科研论文的写作：Shui Yu 悉尼科技大学](https://www.bilibili.com/video/BV1a8411s7Nr?p=1)

## 💻 Coding Skills

- Python最佳实践指南 \[[link](http://itpcb.com/docs/pythonguide/)\]

- Python Cookbook 3rd Edition Documentation \[[link](http://itpcb.com/docs/python3cookbook/)\]

- 🥡 Git 菜单 \[[link](http://itpcb.com/docs/gitrecipes/)\]

- Linux 基础与工具教程 \[[link](http://itpcb.com/docs/linuxtools/base/index.html)\]

## 🤖️ Artificial Intelligence & Deep Learning

- 新手如何入门pytorch？ \[[link](https://www.zhihu.com/question/55720139/answer/2788304721)\]

- 人工智能与Pytorch深度学习 \[[link](https://space.bilibili.com/100682193/channel/collectiondetail?sid=689091)\]

- [A PyTorch Tools, best practices & Styleguide](https://github.com/IgorSusmelj/pytorch-styleguide)

## Roadmap

- [科研人必看！盘点那些最好用的 AI 学术科研工具](https://zhuanlan.zhihu.com/p/153279496)

- [本科生如何自学机器学习？](https://www.zhihu.com/question/332726203/answer/737596538)

- [计算机视觉中的对抗样本 (Adversarial example)](https://zhuanlan.zhihu.com/p/352456539)

- [简单梳理一下机器学习可解释性 (Interpretability)](https://zhuanlan.zhihu.com/p/141013178)

## Misc

- [网络安全领域的科学研究和论文发表 美国西北大学 Xinyu Xing](https://www.bilibili.com/video/BV1Le4y1S7uw)

- [CVPR 9999 Best Paper——《一种加辣椒的番茄炒蛋》](https://zhuanlan.zhihu.com/p/433237905)

- [深度学习理论与实践---深度学习中的信息论：熵、最短编码、交叉熵与互信息](https://zhuanlan.zhihu.com/p/565412701)

- [Pytorch实验代码的亿些小细节](https://github.com/ahangchen/windy-afternoon/blob/master/ml/pratice/torch_best_practice.md)

- [【万字长文详解】Python库collections，让你击败99%的Pythoner](https://zhuanlan.zhihu.com/p/343747724)

- [记一次神奇的 Rebuttal 经历](https://zhuanlan.zhihu.com/p/353761920)

- [精美的终端工具 - Rich](https://www.zhihu.com/question/317758961/answer/2627662722)

- [有没有什么可以节省大量时间的 Deep Learning 效率神器？-深度学习可视化中间变量的神器Visualizer](https://www.zhihu.com/question/384519338/answer/2620414587)

- [AI-research-tools](https://github.com/bighuang624/AI-research-tools/blob/master/README.md#ai-research-tools)

- [自动超参数搜索工具optuna](https://github.com/optuna/optuna)

- [科研写作技巧](https://www.zhihu.com/question/528654768/answer/2452424449) -->
