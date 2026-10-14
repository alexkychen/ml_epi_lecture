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

## Code with AI assistant


