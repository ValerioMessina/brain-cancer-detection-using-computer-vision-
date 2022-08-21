
---
title:  'Pediatric brain-cancer-detection-using-computer-vision-'
journal: 'not published'
author:
- name: Valerio Messina
email: v.messina04@gmail.com
  footnote: 1
abbreviation:
  - MRI, magnetic resonance imaging 
abstract: |
In this study, I tried to implement a DNN that detects and classify pediatric brain tumors using MRI imaging.
bibliography: 
acknowledgements: |
funding: |
contribution: |
additionalinformation: |

# Introduction


Some [red text **which supports** markdown.]{.red}


<!---
Comments look like this and do not show up in the PDF
-->

References are cited as @mittner2014brain or [@mittner2014brain].

# Methods

- some
- bullet
- points

Footnotes can be entered using this code[^1].

[^1]: a footnote

Figures are included like this.

![This is gonna be the caption.](pics/dummy.pdf){#fig:dummy width=100%}

And referenced from here as Fig. @fig:dummy.

Complex tables can use standard LaTeX code as this one.

Equations can be used inline $y=\beta_0 + \beta_1 x + \epsilon$ or as usual $$f(x)=\frac{1}{x}$$

<!---
Table in LaTeX format because of fancy formatting
-->

\begin{table}[ht]
\centering
\caption{Probability to observe Bayes Factors of a certain magnitude or above for the used sample-size of $N=60$ assuming the original and the null-hypothesis.}
\begin{tabular}{llrrr}
  & & \multicolumn{3}{l}{$P(\text{BF}\ge\theta)$}\\
  Hypothesis & BF Type & $\theta=3$ & $\theta=10$ & $\theta=20$ \\
  \hline
  $d\sim \mathcal{N}(1.57, 0.51)$ & JZS BF$_{10}$ & 0.98 & 0.97 & 0.96 \\
     & Replication BF$_{10}$ & 0.98 & 0.96 & 0.96 \\
     & Meta-Analysis BF$_{10}$ & 0.99 & 0.99 & 0.99 \\\cline{2-5}
    $d=0$ & JZS BF$_{01}$ & 0.81 & 0.00 & 0.00 \\
   & Replication BF$_{01}$ & 0.98 & 0.95 & 0.91 \\
     & Meta-Analysis BF$_{01}$ & 0.63 & 0.27 & 0.06 \\
   \hline
\end{tabular}
\label{tab:probbf}
\end{table}

# Results

# Discussion

# References
