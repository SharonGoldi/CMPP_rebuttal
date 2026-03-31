# CMPP_rebuttal

### CIFAR10
![Cifar10_across_r](figures/ratio_to_supervised_row.pdf)

*Figure 1. Accuracy relative to supervised learning across labeled-to-unlabeled sample ratios.*
Accuracy ratio relative to supervised learning across labeled-to-unlabeled ratios 
\( r = \frac{n}{N-n} \). Values above 1 indicate improvement. The dashed line marks the supervised 
baseline and the gray band shows its standard deviation. 
Each subplot corresponds to a different partial-label teacher. The x-axis also reports the ratio 
of optimal interpolation weights \( r_{\lambda_0} = \lambda_0^{\text{cPPI}} / \lambda_0^{\text{PPI}} \), 
where \( \lambda_0 = 1 - \lambda \).
cPPI consistently outperforms supervised learning, while PPI often does not, especially at low \( r \).

---

