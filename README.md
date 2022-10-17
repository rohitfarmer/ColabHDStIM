# Google Colab interface to HDStIM (High Dimensional Stimulation Immune Mapping)

## Abstract
HDStIM is a method for identifying responses to experimental stimulation in mass or flow cytometry that uses high dimensional analysis of measured parameters and can be performed with an end-to-end unsupervised approach. In the context of in vitro stimulation assays where high-parameter cytometry was used to monitor intracellular response markers, using cell populations annotated either through automated clustering or manual gating for a combined set of stimulated and unstimulated samples, 'HDStIM' labels cells as responding or non-responding. The package also provides auxiliary functions to rank intracellular markers based on their contribution to identifying responses and generating diagnostic plots. Documentation website: https://niaid.github.io/HDStIM/ Source code: https://github.com/niaid/HDStIM/ CRAN page: https://cran.r-project.org/package=HDStIM
 
## Colab notebook
This notebook is an attempt to make it easier to use HDStIM. However, since it runs on [Google Colab](https://research.google.com/colaboratory/faq.html), it has its limitations. For example, uploading a large dataset is very slow and may not be straightforward. Also, the marker ranking function that utilizes multiple cores may be orders of magnitude slower than on a local machine with more than two cores. See the more information section at the bottom of the notebook on how to run this notebook locally (recommended).


| Notebook | Link |
| -------- | ---- |
| ColabHDStIM.ipynb | <a href="https://colab.research.google.com/github/rohitfarmer/ColabHDStIM/blob/main/ColabHDStIM.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |

*Note: Under default settings, the notebook should be able to run an example dataset.*

## Use links
1. [Google Colab Frequently Asked Questions](https://research.google.com/colaboratory/faq.html)
2. [Welcome to Colab!](https://colab.research.google.com/)
3. [Practical Introduction to Google Colab for Data Science (YouTube video)](https://www.youtube.com/watch?v=oCngVVBSsmA)