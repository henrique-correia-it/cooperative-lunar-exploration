# IEEE paper

[`rsdis_paper.pdf`](rsdis_paper.pdf) is the final paper (IEEEtran conference
class). [`main.tex`](main.tex) is its source, with the measured comparison table in
[`comparison_results.tex`](comparison_results.tex) and the figures in
[`figures/`](figures/).

The paper describes the implemented prototype, the research question, the
allocation equations, the paired comparison protocol, the measured results from
16 Gazebo runs and the limitations. [`rsdis_apresentacao.pptx`](rsdis_apresentacao.pptx)
is the final presentation (in Portuguese).

`make_figures.py` regenerates the figures and `summarize_evaluation.py` rebuilds
the results table from the run data in `../examples/paired_gazebo_20261108/`.

Build on Ubuntu:

```bash
sudo apt-get install latexmk texlive-publishers texlive-latex-recommended texlive-fonts-recommended
cd report
latexmk -pdf main.tex
```
