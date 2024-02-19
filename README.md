# LR-SVM-principles-and-optimization
This is my undergraduate thesis, which contains part of the code and experimental results.

## Simulation on LR and SVM

*I found that if there is no penalty in training LR, the LR will never converge, which means that the loss function will decrease continually but never arrive in 0.*

*Also interesting, the L2 of parameters in LR will keep increasing in training.*

<p align="center">
  <img src="https://github.com/digbangbang/LR-SVM-principles-and-optimization/assets/78746384/eb1b2bef-ee4d-479e-8595-2ad9fd5044fb" alt="legend" width="600" height="300">
</p>

<p align="center">
  <img src="https://github.com/digbangbang/LR-SVM-principles-and-optimization/assets/78746384/6314a4e8-e8ed-4e08-ba25-cd0862b2ae61" alt="legend" width="600" height="400">
</p>

*When I draw this parameters, it shows that training can reduce the loss function(SSE is decreasing), but it is actually useless work(have already found the separation boundary).*

<p align="center">
  <img src="https://github.com/digbangbang/LR-SVM-principles-and-optimization/assets/78746384/f55ace25-3ce4-4662-9ace-a3fbe0b37f4e" alt="legend" width="600" height="400">
</p>

*The result in SVM, there is no situation above in SVM. Considering that SVM's hinge loss can descrease to 0, and in the linearly totally sperable situation, SVM can quickly find the seperabel boundary.*

<p align="center">
  <img src="https://github.com/digbangbang/LR-SVM-principles-and-optimization/assets/78746384/3bfe8cb2-5039-4d87-ae37-7804d4bead6c" alt="legend" width="600" height="400">
</p>

I also provide the paper.ipynb, which is already runned. (The picture's $\theta$ is little different with the $\theta$ in paper.ipynb in value due to the paper.ipynb was newly runned.)
