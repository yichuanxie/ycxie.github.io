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

Hello! I am Wang Ma (马旺), a third-year undergraduate in Data Science at [Southern University of Science and Technology (SUSTech)](https://sustech.edu.cn/en/), under the supervise of [Prof. Chao Wang](https://sites.google.com/view/cwang). I will be in UC Irvine in late March as a visiting student.


<br/>
I am generally interested in Machine Learning, Computer Vision(Deep Learning), Optimization and Statistics. 


<br/>
I have completed serval courses on Statistics, Machine Learning and Optimization(including a graduate-level one) in SUSTech, lately I've been paying special attention to AIGC models, especially diffusion models and Text-to-Image models.


<br/>
I devoted myself to practicing the Rubik's Cube during the first year of University. In May 2021, I improved my personal best record on the Square-1 cube and [ranked No.2 in mainland China](https://www.worldcubeassociation.org/results/rankings/sq1/average?region=China). With this experience of fighting for the things I love, I am confident that I will carry on this perseverance in the research I love in the future.

<br/>


# 🔥 My Progress
- 11/03/2023: I read the paper about [*Classfier-free Guidance*](https://arxiv.org/pdf/2207.12598.pdf).
- 09/03/2023: I read the paper about [*Latent Diffusion Models*](https://arxiv.org/pdf/2112.10752.pdf).
- 07/03/2023: I read the paper about [*DDPM(Denoising Diffusion Probabilistic Models)*](https://arxiv.org/pdf/2006.11239.pdf).
- 03/03/2023: I read the paper about [*Composer*](https://arxiv.org/pdf/2302.09778.pdf). 
- 03/02/2023: I read the paper about [*T2I-Adapters*](https://arxiv.org/abs/2302.08453).
- 02/28/2023: I read the paper about [*ControlNet*](https://arxiv.org/abs/2302.05543).
<br/>


# 📖 Experience
- *2023.03 - 2023.07*, University of California, Irvine
  - Visiting student 
- *2020.08 - 2024.07*, SUSTech
  - Undergraduate in [Department of Statistics and Data Science](https://stat-ds.sustech.edu.cn/?lang=en-us), majoring in Data Science and Big Data Technology 
  - Student Representative of Teaching Improvement Committee of School of Science (*2022/11 ~* )
  - Leader of the SUSTech Cube Association (*2021/08 ~* )
<br/>


# 📕 My Courses
**This part indicates the courses I have taken so far, attached with the used textbooks and(or) short lists of the contents. You can check my knowledge through this part.** ***[Transcripts](https://nbviewer.org/github/wma17/wma17.github.io/blob/main/docs/Transcript.pdf)***.
## Machine Learning
* **Statistical Learning**
  * Lecturer: [Prof. Bingyi Jing](https://www.sustech.edu.cn/en/faculties/jingbing-yi.html), chair professor, Department of Statistics and Data Science
  * Textbook: *[Introduction to Statistical Learning with R](https://hastie.su.domains/ISLR2/ISLRv2_website.pdf)*; *[Elements of Statistical Learning](https://hastie.su.domains/Papers/ESLII.pdf)*
  * Contents: Common ML models in Statistical View, VAE, GAN
  
* **Machine Learing and Its Medical Applications**
  * Lecturer: [Prof. Quanying Liu](https://www.sustech.edu.cn/en/faculties/liuquanying.html), assitant professor, Department of Biomedical Engineering
  * Textbook: /
  * Contents: Linear regression, Ridge regression, Logistic regression, SVM(hard/soft margin, kernel method), PCA, LDA, NN, CNN, RNN(LSTM).
 
## Optimization
* **Algorithms for Convex Optimization (*Graduate-level*)**
  * Lecturer: [Prof. Jin Zhang](https://www.sustech.edu.cn/en/faculties/zhangjin.html), associate profrssor, Department of Mathematics
  * Textbook: [First-order Methods in Optimization](https://epubs.siam.org/doi/10.1137/1.9781611974997) by Amir Beck
  * Contents: Convexity, Extended real-valued functions, Subgradients, Conjugate functions, Smothness and Strong Convexity, Proximal operater, Proximal gradient descent
   
* **Oprational Research and Optimization**
  * Lecturer: [Prof. Chao Wang](https://sites.google.com/view/cwang), assitant professor, Department of Statistics and Data Science
  * Textbook: /
  * Contents: Simplex method, Duality, Integer programming, Convex optimality, Gradient, Subgradients 
  
## Statistics
* **Statistical Linear Models**
  * Lecturer: [Prof. Jian Qing Shi](https://www.sustech.edu.cn/en/faculties/shijianqing.html), professor,Department of Statistics and Data Science
  * Textbook: [Linear Models in Statistics](https://www.utstat.toronto.edu/~brunner/books/LinearModelsInStatistics.pdf) by Alvin C. Rencher, G. Bruce Schaalje
  * Contents: Simple and Multiple Linear regression, Quadratic forms, Hypothesis testing and CI estimation, Model Validation and Diagnostics
  
* **Mathematical Statistics**
  * Lecturer: [Prof. Guoliang Tian](https://www.researchgate.net/profile/Guo-Liang-Tian), professor, Department of Statistics and Data Science
  * Textbook: Mathematical Statistics by Guoliang Tian
  * Contents: Sampling distributions, MLE, Moment estimation, Bayesian estimation, CI estimation, Hypothesis Testing.
   
* **Probability Theory**
  * Lecturer: [Prof. Jingrui Sun](https://www.sustech.edu.cn/en/faculties/sunjingrui.html), assitant professor, Department of Mathematics
  * Textbook: /
  * Contents: Probability space, Discrete & Continuous Random Variables, Random vectors, Joint distributions, Expectations(generating moment functions), Limiting theory(Weak Law of Large Number, CLE), Conditional expections
   
## Elementary Mathematics
* **Real Analysis**
  * Lecturer: [Prof. Zhan Li](https://www.sustech.edu.cn/en/faculties/lizhan.html), assitant professor, Department of Mathematics
  * Textbook: Real Analysis: Measure Theory, Integration, and Hilbert Spaces (Princeton Lectures in Analysis) by Elias M. Stein
  * Contents: Lesbegue Measure, Lesbegue integral, Differentiation and integration
    
* **Numerical Analysis**
  * Lecturer: [Prof. Jiang Yang](https://www.sustech.edu.cn/en/faculties/yangjiang.html), assicate professor, Department of Mathematics
  * Textbook: [Numerical Analysis](https://faculty.ksu.edu.sa/sites/default/files/numerical_analysis_9th.pdf), by Richard L. Burden
  * Contents: Root finding method(for numbers and matrices, linear and nonlinear), Interpolation, Numerical integration/differentiation, IVP(Euler method, RK4), Eigenvalue/eigenvector finding(Power method and inverse power method, QR decomposation, SVD), fitting
   
* **Advanced Linear Algebra**
  * Lecturer: [Prof. Yimao Chen](https://www.sustech.edu.cn/en/faculties/chenyimao.html), assicate professor, Department of Mathematics
  * Textbook: [Linear Algebra Done Right](https://apuntespme.cl/biblio/AXLER_LINEARALGEBRA.pdf)
  * Contents: all of the book, more theoretical than the following course
    
* **Linear Algebra**
  * Lecturer: [Prof. Wenlong Zhang](https://www.sustech.edu.cn/en/faculties/zhangwenlong.html), assitant professor, Department of Mathematics
  * Textbook: Linear Algebra and Its Applications by Gilbert Strang
  * Contents: all of the book
   
* **Discrete Mathematics**
  * Lecturer: [Yunhao Fu](https://www.sustech.edu.cn/en/faculties/fuyunhao.html), lecturer, Department of Mathematics
  * Textbook: Discre Mathematics and Its Applications, 9th Editon by Kenneth H. Rosen
  * Contents: Basic algoritms(complexity, growth of functions), basic number theory(divisibility, primes, congurenes), Induction and Recursion, Counting(permutations and combinations, bionomial coefficients and identities, linear recurrence relations, divide and conquer, Inclusion and Exclusion)
    
* **Mathematical Analysis I & II & III**
  * Lecturer: [Yunhao Fu](https://www.sustech.edu.cn/en/faculties/fuyunhao.html), lecturer, Department of Mathematics
  * Textbook: 数学分析教程 by 史济怀，常庚哲
  * Contents: Sets, Functions(single/multi variable, continuity, differentiable, integral), Series(numerical sequeunces, functional sequnences...)
<br/>


# 💻 Skills
**Programming:**

* Python, Matlab, Java, Julia (beginner)

**Software:**

* Texmacs, Typora, MS Office, Latex, Jupyter Notebook, Pycharm, VS code

**Language:**
* Mandarin Chinese, English, Shaanxi Dialect Chinese, Japanese (Elementary)
<br/>



# ⚾ More
* **Baseball**. I enjoy watching NPB games and the Japan High School Tournament, Koshien. My favorite NPB team is *<font color=Blue>Hokkaido Nippon Ham Fighters</font>*, where Shohei Otani started his professional career. I am also a super fan of Ohmi High School, the baseball rising-star school from Shiga Prefecture in Japan, see the highlights of Ohmi High School [here](https://www.bilibili.com/video/BV1bF411a7B4/?spm_id_from=333.999.0.0&vd_source=39c9e2f0249c14d448a63ad2dec02137), their blue uniforms shine brighter than the sky in August.

* I am a **speedcuber** who participated in more than 20 official games with Square-1 being my best event. My ranking in Square-1 Event is No.2 in mainland China now (Mar. 2023), and I got 2 **Bronze Medals from the National Championship** in 2017, 2018. You can watch some recordings of my solves in my [Bilibili Channel](https://space.bilibili.com/237775327/video). To see all my results in official games, please take a look at my [WCA page](https://www.worldcubeassociation.org/persons/2016MAWA01).

* **Anime**. My favorite short anime is *Spice and Wolf*, while my preferred long anime is *One Piece*. I have been watching *One Piece* since I was 8 years old, and watched the latest movie version on the first day it released in mainland China. Additionally, I enjoy Chinese Anime such as 超兽武装, 果宝特攻, 洛洛历险记, 星游记 and would be happy to discuss them with you!

* My hometown is Baoji, Shaanxi Province, which is the center of Acient China for the most of the past. I like reading **history** about here, especially the *Pre-Qin History*, the Warring States period of the Hundred Schools of Thought (百家争鸣的战国时代).
