# Deep unsupervised learning
The special course follows the [Berkeley CD294-158 Deep Unsupervised Learning](https://sites.google.com/view/berkeley-cs294-158-sp19/home).

## Location
Building 321, 1st floor, room 119/134, 10:00-12:00.

## Format
Each two hour session will go follow the following format:
* We recap the lecture for the week and discuss/clarify as needed
* A presenter will go through a paper (presenters and paper listed in schedule)
* Depending on the week:
  * Weeks 1-6 (before fall break): We discuss the homework from last time
  * Weeks 7-12 (after the fall break): We provide updates on projects in plenum or in smaller groups

In week 6 we present a short description of the project we intend to work on following the fall break. In week 13 each project group do a 5-10 min presetation of results.

## Paper presentations
Guidelines for presentation:
* Read the paper to the best of your ability (you're not expected to understand or be able to explain all the details)
* Prepare a (minimal) slideshow that:
  * is structured under the same headlines as the paper, and generally make sure to go through:
    * abstract/overview,
    * study background,
    * aim/objective/hypothesis of the paper,
    * methods,
    * results, and
    * discussion/conclusion
  * has bullet points for the content under headlines
  * includes main tables and figures
  * includes relevant personal considerations on e.g.:
    * design/methods used,
    * the authors discussion/interpretation of the results and study drawbacks,
    * significance of the paper

## Schedule
| Week  | Date  | Subject   | Presenter   | Homework  |
| ---   | ---   | ---       | ---       | ---       |
| 1     | Sep 6 | [Likelihood-based models I: autoregressive models](https://youtu.be/zNmvH6OXDpk)       | Rasmus Høegh       | [HW1](https://drive.google.com/file/d/1DtYllaV4Yk8ljgYcLBmdXNplEDTG6HT6/view)       |
| 2     | Sep 13 | [Lossless compression and Likelihood-based models II: flow models](https://youtu.be/mYCLVPRy2nc)       | Peter Ebert Christensen       | [HW2](https://drive.google.com/file/d/1xs9fFCrPs3c9HNnOlmgen1ZnLfs26VVM/view)       |
| 3     | Sep 20 | [Latent Variable Models I](https://youtu.be/NCRzGmM1ywE)       | Valentin Liévin       | [HW3](https://drive.google.com/file/d/1IrPBblLovAImcZdWnzJO07OxT7QD9X2m/view?usp=sharing)       |
| 4     | Sep 27 | [Latent Variable Models II and Bits-Back Coding](https://youtu.be/0IoLKnAg6-s)       | Frederik Boe Hüttel       | [HW3](https://drive.google.com/file/d/1IrPBblLovAImcZdWnzJO07OxT7QD9X2m/view?usp=sharing)       |
| 5     | Oct 4 | [Implicit Models/Generative Adversarial Networks](https://youtu.be/grsO57XMJMk)       | Didrik Nielsen       | [HW4](https://drive.google.com/file/d/1vBJro462ax_Pk4SN9TJdzNUN0vnRV0r-/view)       |
| 6     | Oct 11 | [Non-Generative Representation Learning I](https://youtu.be/5NMIUZ7_nrg)       | Umaer Hanif       | Project description       |
||Oct 18|Fall break||
| 7     | Oct 25 | [Non-Generative Representation Learning II](https://youtu.be/AC4l_MY2Dhc)       | Nicklas Hansen       | Project       |
| 8     | Nov 1 | [Semi-Supervised Learning](https://youtu.be/7o9dT6puHHg) and [Open AI: Reinforcement Learning](https://youtu.be/X-B3nAN7YRM)       | Andreas Brink-Kjær       | Project       |
| 9     | Nov 08 | [Unsupervised Distribution Alignment](https://youtu.be/0AxgLbQfyjQ) and [BAIR: Self-Supervision](https://youtu.be/PX11C5Vfo9U)       | Christoffer Riis       | Project       |
| 10     | Nov 15 | [OpenAI: Language Models](https://youtu.be/GEtbD6pqTTE)       | Alexander Neergaard Olesen       | Project       |
| 11     | Nov 22 | [Representation Learning in Reinforcement Learning](https://youtu.be/Yvll3P1UW5k)       |        | Project       |
| 12     | Nov 29 | [Deep Mind: Latent-Space Generative Models](https://youtu.be/QoCyQBzi7us?t=55)       |        | Project       |
| 13     | Dec 6 | Final project presentations      | All       |        |

## Reading
Reading is based on papers central to the talk or homework. Optionals are highlights beyond that paper from the various articles suggested [here](https://www.google.com/url?q=https%3A%2F%2Fwww.dropbox.com%2Fs%2Ff09vfmfjb9thaef%2Fgm_reading_list.zip%3Fdl%3D0&sa=D&sntz=1&usg=AFQjCNEnaHV6R9-39xyjkYqIbwMBPtVgcw). Suggestions for important highlights are welcome. You are free to swap presentation dates (and thereby paper) - coordinate between yourselves and notify Rasmus (rmth@dtu.dk).

* Week 1:
  * [Pixel Recurrent Neural Networks](https://arxiv.org/abs/1601.06759)
  * Optional: [MADE: Masked Autoencoder for Distribution Estimation](https://arxiv.org/abs/1502.03509)
  * Optional: [Generating Sequencies with Recurrent Neural Networks](https://arxiv.org/pdf/1308.0850.pdf)
  * Optional: [Attention Is All You Need](https://arxiv.org/abs/1706.03762)
* Week 2:
  * [Introduction to Data Compression](https://www.cs.cmu.edu/~guyb/realworld/compression.pdf)
  * [Density Estimation using Real NVP](https://arxiv.org/pdf/1605.08803.pdf)
  * Optional: [NICE: Non-linear Independent Components Estimation](https://arxiv.org/abs/1410.8516)
* Week 3:
  * [Importance weighted autoencoders](https://arxiv.org/abs/1509.00519)
  * Optional: [An Introduction to Variational Autoencoders](https://arxiv.org/abs/1906.02691)
* Week 4:
  * [Practical Lossless Compression with Latent Variables using Bits Back Coding](https://arxiv.org/abs/1901.04866)
  * Optional: [Variational Lossy Autoencoder](https://arxiv.org/abs/1611.02731)
* Week 5:
  * [Spectral Normalization for Generative Adverarial Networks](https://arxiv.org/abs/1802.05957)
  * Optional: [Generative Adversarial Nets](http://papers.nips.cc/paper/5423-generative-adversarial-nets.pdf)
* Week 6:
  * [Efficient Estimation of Word Representations in Vector Space (word2vec)](https://arxiv.org/abs/1301.3781)
  * Optional: [Unsupervised Visual Representation learning by Context Prediction](https://arxiv.org/abs/1505.05192)
* Week 7:
  * [Representation Learning with Contrastive Predictive Coding](https://arxiv.org/abs/1807.03748)
  * Optional: [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805)
* Week 8:
  * [Temporal Ensembling for Semi-Supervised Learning](https://arxiv.org/pdf/1610.02242.pdf)
  * Optional, OpenAI-paper, GPT2: [Language Models are Unsupervised Multitask Learners](https://d4mucfpksywv.cloudfront.net/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)
* Week 9:
  * [Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks](https://arxiv.org/abs/1703.10593)
  * Optional, BAIR-paper, pix2pix: [Image-to-Image Translation with Conditional Adversarial Networks](https://arxiv.org/abs/1611.07004)
  * Optional, BAIR-paper: [Audio-Visual Scene Analysis with Self-Supervised Multisensory Features](https://arxiv.org/abs/1804.03641)
  * Optional, BAIR-paper: [Fighting Fake News: Image Splice Detection via Learned Self-Consistency](https://arxiv.org/abs/1805.04096)
* Week 10:
  * [Improving Language Understanding by Generative Pre-Training](https://s3-us-west-2.amazonaws.com/openai-assets/research-covers/language-unsupervised/language_understanding_paper.pdf)
* Week 11
  * [Reinforcement Learning with Unsupervised Auxiliary Tasks](https://arxiv.org/abs/1611.05397)
* Week 12:
  * [Neural Discrete Representation Learning](https://arxiv.org/abs/1711.00937)
  * Optional: [WaveNet: A Generative Model for Raw Audio](https://arxiv.org/pdf/1609.03499.pdf)