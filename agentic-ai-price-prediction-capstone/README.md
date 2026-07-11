# Agentic AI Price Prediction Capstone

Week 8 capstone project: an agentic AI system for product price prediction and deal discovery. The project combines specialist pricing models, RAG, ensemble agents, scanning agents, messaging, and autonomous planning.

## Files

- `modal_specialist_agent.ipynb` - Modal setup and specialist pricing agent.
- `rag_frontier_ensemble_agents.ipynb` - RAG, frontier model, neural network, and ensemble agent workflow.
- `scanner_messaging_agents.ipynb` - deal scanning and push notification agents.
- `autonomous_planning_agent.ipynb` - autonomous planner and deal agent framework.
- `capstone_price_is_right_ui.ipynb` - final Gradio UI workflow.
- `results_analysis.ipynb` - results and analysis notebook.
- `price_is_right.py` - main capstone UI/application script.
- `deal_agent_framework.py` - framework for coordinating pricing and deal agents.
- `agents/` - reusable agent implementations.
- `pricer_service.py`, `pricer_service2.py`, `pricer_ephemeral.py` - pricing service helpers.
- `llama.py` - model helper script.
- `log_utils.py` - logging utilities.
- `requirements.txt` - Python dependencies from the course environment.

## Setup

```bash
pip install -r requirements.txt
python price_is_right.py
```

Some parts of the capstone use external services such as Modal, OpenAI, Hugging Face, and Pushover. Add the required credentials to your local `.env` file before running those cells or scripts.

Generated cache files, model checkpoints, local memory files, and vector databases are intentionally excluded so the repository stays clean for GitHub.
