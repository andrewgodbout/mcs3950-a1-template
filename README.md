# MCS 3950 · Assignment 1 — Dimensionality Reduction with Animal Faces

**Released** Wed Oct 21, 2026 · **Due** Mon Nov 9, 2026, 11:59 pm (Atlantic) ·
**Weight** 10% (60 points, marked automatically) · **Individual**

You will build PCA from the SVD, check it against scikit-learn, and use it on 1,500 grayscale
animal faces: choose how many components to keep, test what happens to inputs that are not
animal faces, interpret what the components encode, and (challenge) find out whether "face
space" is a better place to search than pixel space.

Everything you need is in **`A1_PCA_Animal_Faces.ipynb`**. Read its *How this assignment is
marked* and *Instructions* sections first.

**How it is marked.** After the deadline a program re-runs your notebook from a fresh kernel and
checks the *graded variables* named in each question, testing your functions on data you
have not seen. Keep those names exactly, do not edit the provided cells, and make sure the
notebook runs top to bottom. The 🧠 *Think about it* prompts are not marked, but questions like them
may appear on Tests 2 and 3.

## Files

| File | What it is |
|---|---|
| `A1_PCA_Animal_Faces.ipynb` | The assignment. Your answers go in this notebook. |
| `requirements.txt` | Packages, only needed if you work on your own computer. |
| `.gitignore` | Keeps the downloaded images out of your repository. Do not delete it. |
| `LICENSE.md` | Where this assignment and its images come from. |

The images (14 MB) are **not** in this repository. The notebook downloads them into `data/` the
first time you run it.

## Working in Google Colab (recommended)

1. Go to [colab.research.google.com](https://colab.research.google.com) and choose
   **File → Open notebook → GitHub**.
2. Tick **Include private repos** (authorise Colab with GitHub if asked), select **this
   repository**, and open `A1_PCA_Animal_Faces.ipynb`.
3. To save, use **File → Save a copy in GitHub**: choose this repository, branch `main`, keep the
   file name `A1_PCA_Animal_Faces.ipynb`, and write a commit message that says what you did
   (e.g. *"Exercise 2: MyPCA passes all tests"*). Every save is a commit.

*If this repository does not appear in Colab's list*, open
[github.com/settings/connections/applications](https://github.com/settings/connections/applications),
find **Colaboratory**, and grant (or request) access for the course organisation.

## Working on your own computer

```bash
git clone <this repository's URL>
cd <repository folder>
pip install -r requirements.txt
jupyter lab A1_PCA_Animal_Faces.ipynb
# ... work ...
git add A1_PCA_Animal_Faces.ipynb
git commit -m "Exercise 3.1: variance curve and reconstructions"
git push
```

## Submitting

Your submission is the notebook as it is on GitHub at the deadline. Before then:

- [ ] Restart and run all cells: nothing crashes
- [ ] Every graded variable is set; no `...` left in code cells
- [ ] **`ai_disclosure`** filled in (last cell of the notebook)
- [ ] At least **three commits** spread over your work, the last one pushed before the deadline
- [ ] No data files committed (`git status` should never show `data/`)

**Late work:** up to 48 hours late loses 35%; after 48 hours it is not accepted without prior
arrangement. Your last commit before the deadline is marked. If you commit again within 48 hours,
that version is also marked with the penalty, and the better of the two counts.

**Academic integrity:** discuss ideas with classmates, but submit your own code and writing.
Generative-AI tools are allowed only if you disclose how you used them.
