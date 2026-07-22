# Agentic-Evals

## How to download

### Option A - Download as ZIP

1. Click the green **Code** button at the top right of this page.
2. Select **Download ZIP**.
3. Unzip the file on your computer. You will get an `Agentic-Evals-main` folder with everything inside.

### Option B - Clone with Git

```bash
git clone https://github.com/jothsnapraveena/Agentic-Evals.git
```

---

## Sessions

| Folder | Topic | Type |
|---|---|---|
| `01_evals` | Evals | Build-Along |

---

## API key

You will need an Anthropic API key for all build-along sessions.

Run the notebook setup cell once. It creates a gitignored **`.env`** file.

Open the `.env` file, paste your key like this, save, and re-run the setup cell:

```bash
ANTHROPIC_API_KEY=your_key_here
```

A green **API key verified** message confirms that you are connected.

Prefer to set it once from terminal? You can also run:

```bash
export ANTHROPIC_API_KEY=your_key_here
```

---

## Where to run

These build-alongs are meant to run in your own tooling:

- **VS Code / Cursor** - open the folder, then open the notebook with the Jupyter extension.
- **Claude Code CLI** - run `claude` inside the repo.
- **Claude Desktop** - keep it open alongside your coding environment for help with concepts and debugging.


---

## Setup and troubleshooting

The notebooks install what they need on first run.

If you hit setup issues, check [SETUP.md](SETUP.md).

For a pinned environment up front:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

For Windows:

```bash
.venv\Scripts\activate
pip install -r requirements.txt
```
