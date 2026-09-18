# ThreatScope AI

A project exploring how clear explanations can help people recognize phishing and social engineering.

## Project goal

I am interested in the connection between cybersecurity, AI, and human decision-making. My goal for ThreatScope AI is to help users understand why a message may be suspicious and what they can do next.

## Current repository status

**Stage: Streamlit starter scaffold.**

The public code in this repository currently displays a starter title and message. It does not yet implement phishing detection, an AI model, risk scoring, or an analysis workflow. This repository should not be treated as a working security product or as the complete implementation of the broader project.

## What is included

| File | Purpose |
| --- | --- |
| [streamlit_app.py](streamlit_app.py) | Current Streamlit entry point |
| [requirements.txt](requirements.txt) | Python dependency list |
| [LICENSE](LICENSE) | Existing repository license |

## Run the current scaffold

From the repository directory, with Python installed:

```bash
python -m venv .venv
```

Activate the environment:

```powershell
# Windows PowerShell
.venv\Scripts\Activate.ps1
```

```bash
# macOS / Linux
source .venv/bin/activate
```

Then run:

```bash
python -m pip install -r requirements.txt
python -m streamlit run streamlit_app.py
```

**Expected result:** the starter Streamlit page, not a phishing analysis tool.

## Development direction

- Add an input flow for synthetic or sanitized example messages.
- Explain identifiable warning signs such as urgency, impersonation, and suspicious requests.
- Distinguish rule-based checks from any future model-based classification.
- Evaluate false positives and false negatives using labeled examples.
- Document the implementation, example results, limitations, and a working demonstration.

These items describe planned work for this public repository, not completed features.

## Evaluation goals

A useful result needs more than a risk label. I want users to see the reason for a flag, understand uncertainty, and know when further verification is needed. Any future accuracy claim should identify the test data, evaluation method, and error cases.

## Related work

- [Ethical Hacking Home Lab](https://github.com/luzmysterious23-sketch/ethical-hacking-home-lab): network setup, verification, and recovery preparation.
- [Password Security Analyzer](https://github.com/luzmysterious23-sketch/password-security-analyzer): a browser-based educational security application.
