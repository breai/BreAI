# BreAI
BreAI is a submission based on challenge #2 - the respiratory dataset.

To see the submission, visit [BreAI.ipynb](https://github.com/breai/BreAI/blob/master/BreAI.ipynb) and visit it on Google Colab.

This currently shows a graph that we use to show local minima and maxima from
the PPG output. Ultimately, the idea is to plot across the maxima to compute the
RIIV, and use this plot to predict respiratory rate.

Legend:

- Purple - measured respiration (pneumograph)
- Yellow - annotated breath
- Blue - PPG measurements
- Green - local maximum for PPG
- Red - local minimum for PPG
