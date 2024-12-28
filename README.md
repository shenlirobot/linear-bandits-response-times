# linear-bandits-response-times
This is the code for the paper `Enhancing Preference-based Linear Bandits via Human Response Time`
* Shen Li*, Yuyang Zhang*, Zhaolin Ren, Claire Liang, Na Li, Julie A. Shah
* Advances in Neural Information Processing Systems (NeurIPS) (2024)
* Oral presentation, acceptance rate: 0.39%
* [PDF](https://arxiv.org/abs/2409.05798)
* [Poster](https://shenlirobot.github.io/docs/24-NeurIPS-Li-Zhang-Ren-Liang-Li-Shah-poster.pdf)
* [Oral at the conference (0:59-19:19)](https://neurips.cc/virtual/2024/session/98061)
* [Slides](https://shenlirobot.github.io/docs/24-NeurIPS-Li-Zhang-Ren-Liang-Li-Shah-slides.pdf)

## Abstract
Interactive preference learning systems infer human preferences by presenting queries as pairs of options and collecting binary choices. Although binary choices are simple and widely used, they provide limited information about preference strength. To address this, we leverage human response times, which are inversely related to preference strength, as an additional signal. We propose a computationally efficient method that combines choices and response times to estimate human utility functions, grounded in the EZ diffusion model from psychology. Theoretical and empirical analyses show that for queries with strong preferences, response times complement choices by providing extra information about preference strength, leading to significantly improved utility estimation. We incorporate this estimator into preference-based linear bandits for fixed-budget best-arm identification. Simulations on three real-world datasets demonstrate that using response times significantly accelerates preference learning compared to choice-only approaches.
