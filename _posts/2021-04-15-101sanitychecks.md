---
title: 100 ways to sanity check the code 
article_header:
  type: cover
  image:
    src: 
---

  
## Integral fluctuation theorum 

The IFT must hold *except* when the probability of the reverse transition is not possible or if you violate detailed balance. For example, if you start your system in a delta function distribution, the IFT does not hold.

For more and more samples, the IFT should approach one. If it does not, reguardless of how close it is, something is wrong. 

$$\langle e^{-\sigma} \rangle = 1$$ 

## Average entropy production

Ensemble level entropy production has to always be increasing. Here are plots with error bars for more and more samples. 

Additionally, for thermal relaxation, we can check the average entropy production from the KL divergence 

$$\langle \sigma \rangle = D(\bf{p(0)}\vert \vert \bf{p_{eq}}) −D(\bf{p(\tau} )\vert \vert \bf{p_{eq}})$$
Here is an example.
<!-- <img src="/files/250000.svg"> -->
<img src="/files/250000.svg">
**note to self: fix this plot (sum not rendering and formatting is off)

## Target spins

Due to symmetry, the entropy production will be the same regardless of the order of target spins. 
{:.warning}
**Example**
$$M_{012}=\boxed{\boxed{S_{0}} \quad  \boxed{S_{1}} \quad \boxed{S_{2}} \quad S_{3}\quad S_{4}}$$


These two configurations should produce the same EP plots... and indeed... they do!

## Ensemble probability

We  can also compare the probability distribution on the ensemble level to the value we get from exponentiating the rate matrix. 
<img src="/files/allones.png"> *here is an example for the probability distribution for one heat bath at T=1 and 500000 samples. As we add more samples, the KL divergence should decrease.

<img src="/files/probability1500000.svg">

## Information theoretic bounds 
Naoto Shiraishi derived information thoeretic bounds on thermal relaxation processes. Here is an example for T=1 and 
<!-- <img src="/files/250000.svg">
 -->
## Speed limit theorums 

Another result by Shiraishi:



