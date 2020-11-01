## Variation of git diff output

This project compares the output produced by two different `git diff`
algorithms - **Myers** and **Histogram** on the basis of:
1. Difference in NLA & NLD across commits
2. Difference in location of changed line acorss commits

> NLA: number of lines added
NLD: number of lines deleted

### Goal

Reproduce the output given in Table 5 of this
[research paper](https://arxiv.org/pdf/1902.02467.pdf) for the project
[butterknife](https://github.com/JakeWharton/butterknife).
