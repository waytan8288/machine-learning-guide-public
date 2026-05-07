# Machine Learning Guide — Hands-on Notebooks

Companion Colab notebooks for a self-study path through Andrew Ng's Machine Learning Specialization. Each notebook is a 30–60 minute hands-on session that implements one course-week's core algorithm from scratch.

## Layout

```
exercises/   ← skeleton notebooks with TODOs (you fill them in)
solutions/   ← fully worked solutions with detailed explanations
```

Open the **exercises** version first. Try to fill in each TODO yourself. Open the matching **solution** only after you've genuinely tried.

## Course 1 — Supervised Machine Learning: Regression and Classification

| Week | Topic | Exercise | Solution |
|---|---|---|---|
| 1 | Gradient descent on linear regression | [Open in Colab](https://colab.research.google.com/github/waytan8288/machine-learning-guide-public/blob/main/exercises/course1-week1-gradient-descent.ipynb) | [Solution](https://colab.research.google.com/github/waytan8288/machine-learning-guide-public/blob/main/solutions/course1-week1-gradient-descent-solution.ipynb) |
| 2 | Multivariate regression + feature scaling | [Open in Colab](https://colab.research.google.com/github/waytan8288/machine-learning-guide-public/blob/main/exercises/course1-week2-multivariate.ipynb) | [Solution](https://colab.research.google.com/github/waytan8288/machine-learning-guide-public/blob/main/solutions/course1-week2-multivariate-solution.ipynb) |
| 3 | Classification with logistic regression | [Open in Colab](https://colab.research.google.com/github/waytan8288/machine-learning-guide-public/blob/main/exercises/course1-week3-classification.ipynb) | [Solution](https://colab.research.google.com/github/waytan8288/machine-learning-guide-public/blob/main/solutions/course1-week3-classification-solution.ipynb) |

## Course 2 — Advanced Learning Algorithms

| Week | Topic | Exercise | Solution |
|---|---|---|---|
| 1 | Neural network forward propagation | [Open in Colab](https://colab.research.google.com/github/waytan8288/machine-learning-guide-public/blob/main/exercises/course2-week1-neural-net-forward.ipynb) | [Solution](https://colab.research.google.com/github/waytan8288/machine-learning-guide-public/blob/main/solutions/course2-week1-neural-net-forward-solution.ipynb) |
| 2 | Backpropagation + softmax for multi-class | [Open in Colab](https://colab.research.google.com/github/waytan8288/machine-learning-guide-public/blob/main/exercises/course2-week2-backprop-softmax.ipynb) | [Solution](https://colab.research.google.com/github/waytan8288/machine-learning-guide-public/blob/main/solutions/course2-week2-backprop-softmax-solution.ipynb) |
| 3 | Bias / variance + learning curves + regularization | [Open in Colab](https://colab.research.google.com/github/waytan8288/machine-learning-guide-public/blob/main/exercises/course2-week3-bias-variance.ipynb) | [Solution](https://colab.research.google.com/github/waytan8288/machine-learning-guide-public/blob/main/solutions/course2-week3-bias-variance-solution.ipynb) |
| 4 | Decision trees from scratch | [Open in Colab](https://colab.research.google.com/github/waytan8288/machine-learning-guide-public/blob/main/exercises/course2-week4-decision-trees.ipynb) | [Solution](https://colab.research.google.com/github/waytan8288/machine-learning-guide-public/blob/main/solutions/course2-week4-decision-trees-solution.ipynb) |

## Course 3 — Unsupervised Learning, Recommenders, Reinforcement Learning

| Week | Topic | Exercise | Solution |
|---|---|---|---|
| 1 | K-means + anomaly detection | [Open in Colab](https://colab.research.google.com/github/waytan8288/machine-learning-guide-public/blob/main/exercises/course3-week1-kmeans-anomaly.ipynb) | [Solution](https://colab.research.google.com/github/waytan8288/machine-learning-guide-public/blob/main/solutions/course3-week1-kmeans-anomaly-solution.ipynb) |
| 2 | Collaborative filtering + PCA | [Open in Colab](https://colab.research.google.com/github/waytan8288/machine-learning-guide-public/blob/main/exercises/course3-week2-recommenders-pca.ipynb) | [Solution](https://colab.research.google.com/github/waytan8288/machine-learning-guide-public/blob/main/solutions/course3-week2-recommenders-pca-solution.ipynb) |
| 3 | Q-learning on Mars rover | [Open in Colab](https://colab.research.google.com/github/waytan8288/machine-learning-guide-public/blob/main/exercises/course3-week3-q-learning.ipynb) | [Solution](https://colab.research.google.com/github/waytan8288/machine-learning-guide-public/blob/main/solutions/course3-week3-q-learning-solution.ipynb) |

## How to use

1. Click "Open in Colab" on a row above. Colab opens in your browser — no Python install required.
2. Read the markdown cells. They explain what you're doing and why.
3. Fill in each `# TODO` cell. The cell below sanity-checks your code with assertions — ✓ when right, AssertionError when wrong.
4. Stuck? Open the matching solution notebook.

## Verification

Every solution notebook is **executed end-to-end via `nbclient` before being committed.** All assertions pass; all cells produce output. The numerical anchors in the exercise tests come from the executed solutions, not from manual estimates.

## License & attribution

Notebooks are original implementations of standard algorithms. The conceptual scope follows Andrew Ng's specialization curriculum but the code, examples, and explanations are written from scratch — they are not transcripts or reproductions.

For the official course: <https://www.deeplearning.ai/courses/machine-learning-specialization/>
