
Notes
Model runs fully locally

No API keys required

Tested on macOS (Apple Silicon)

---

## What this is
- Fine-tuned DistilBERT model on IMDb
- Deterministic agent that evaluates movie reviews
- Produces clear decisions: recommend / avoid / needs human judgment

## Project Structure

imdb-ai-agent/
├── imdb_agent/
│ ├── inference.py
│ ├── agent.py
├── models/
│ └── imdb_model/
├── training/
│ └── train_imdb.py
├── requirements.txt
└── README.md




## Setup (Local) - bash(Linux/MacOS)/powershell (Windows)

```bash
git clone <repo-url>
cd imdb-ai-agent
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
Run a Quick Test
bash
Copy code
python
python
Copy code
from imdb_agent.agent import MovieAgent

agent = MovieAgent()
agent.decide("An absolute masterpiece")
----------------------------------------------------------------------------

 What Your Team Will Do (Copy This to Them)
bash
Copy code
git clone https://github.com/<org>/imdb-ai-agent.git
cd imdb-ai-agent
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python
python
Copy code
from imdb_agent.agent import MovieAgent
MovieAgent().decide("Your review here")

