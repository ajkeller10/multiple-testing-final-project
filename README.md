# Multiple Testing Final Project

Drew Keller and Charles Mayville
9 Mar 23

We analyze and extend [Adaptive Conformal Inference Under Distribution Shift](https://arxiv.org/abs/2106.00170). See `writeup.html` for project paper.

We replicate Figure 1 from the paper in both `empirical_q_analysis.Rmd` and `modified_batch_procedure.Rmd`. In the former, we compare results to the fixed-_QS_ setting; in the latter, we compare to a batched version of the procedure. `ACCCode.R` is original code [forked from the authors](https://github.com/isgibbs/AdaptiveConformal). The `data` directory contains CSVs of opening stock price data from the Wall Street Journal ([Nvidia](https://www.wsj.com/market-data/quotes/NVDA/historical-prices) and [Fannie Mae](https://www.wsj.com/market-data/quotes/FNMA/historical-prices)). 