# ML Project for Epi Lecture

## Set up project workspace

**Step 1**. Install Python from [python.org/downloads](https://www.python.org/downloads/).

**Step 2**. Install [Visual Studio Code](https://code.visualstudio.com/download) for your operating system.

**Step 3**. In VS Code, open **Extensions** (`Ctrl+Shift+X` on Windows/Linux or `Cmd+Shift+X` on macOS) and install Microsoft's [Python extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python) and [Jupyter extension](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter). These let you run the Python scripts and notebooks in this repository.

**Step 4**. Install an AI coding assistant in VS Code: [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot) or [OpenAI Codex](https://marketplace.visualstudio.com/items?itemName=OpenAI.chatgpt). Sign in and check the provider's current plan options; Copilot offers a free plan, while Codex availability depends on your ChatGPT plan.

**Step 5**. Get this repository: open [ml_epi_lecture on GitHub](https://github.com/alexkychen/ml_epi_lecture) and choose **Code → Download ZIP**, or clone it with Git:

```bash
git clone https://github.com/alexkychen/ml_epi_lecture.git
```

Then open the downloaded or cloned `ml_epi_lecture` folder in VS Code (**File → Open Folder**).

**Step 6**. Create a project environment and install the required Python libraries. In VS Code, open **Terminal → New Terminal** from the project folder and run:

```bash
python -m venv .venv
```

Activate the environment:

```bash
# Windows (PowerShell)
.venv\Scripts\Activate.ps1

# macOS or Linux
source .venv/bin/activate
```

Then install the packages listed in [`requirements.txt`](requirements.txt):

```bash
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

## Ask ChatGPT to guide you the setup step by step
```{markdown}
Guide me **step by step** through setting up a complete Python development environment in [Windows/MacOS], including installing Python + VS Code + Python & Jupyter extension in VS Code + cloning the Gitub repo (github.com/alexkychen/ml_epi_lecture) + creating Python virtual environment in the repo working directory + activating the virtual env + installing project dependencies in requirements.txt + installing Codex for VS Code extension and OpenAI account sign-up + running a quick test with a jupyter notebook.    
```
**Make sure to choose the computer operation system of your own in the prompt**

## References

- Bi Q, Goodman KE, Kaminsky J, Lessler J. What Is Machine Learning? A Primer for the Epidemiologist. *American Journal of Epidemiology.* 2019;188(12):2222–2239. [https://academic.oup.com/aje/article/188/12/2222/5567515](https://academic.oup.com/aje/article/188/12/2222/5567515)
- Morgenstern JD, Buajitti E, O'Neill M, et al. Predicting Population Health With Machine Learning: A Scoping Review. *BMJ Open.* 2020;10:e037860. [https://pmc.ncbi.nlm.nih.gov/articles/PMC7592293/](https://pmc.ncbi.nlm.nih.gov/articles/PMC7592293/)
- Scikit-leanr: A Python library for Machine Learning. [https://scikit-learn.org/stable/index.html](https://scikit-learn.org/stable/index.html)
- XGBoost library documentation [https://xgboost.readthedocs.io/en/stable/](https://xgboost.readthedocs.io/en/stable/)
- SHAP library documentation [https://shap.readthedocs.io/en/latest/](https://shap.readthedocs.io/en/latest/)

## Recommended ML full course

- Andrew Ng's ML course on Coursera [https://www.coursera.org/specializations/machine-learning-introduction](https://www.coursera.org/specializations/machine-learning-introduction)