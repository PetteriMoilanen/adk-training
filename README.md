# adk-training
For labs of Google Agent Development Kit (ADK) training course by by Maurizio Ipsale.

Website: https://github.com/mauripsale/doc-adk-training?tab=readme-ov-file

## Lab 1
https://github.com/mauripsale/doc-adk-training/blob/main/training/module01-intro-to-ai-agents

Done. No code involved. 2026-08-27

## Lab 2
https://github.com/mauripsale/doc-adk-training/blob/main/training/module02-environment-setup/lab.md

- Setting up:

    uv init adk-training --python 3.12
    cd adk-training
    uv add "google-adk>=2.1.0" python-dotenv

- Added .env file (which is listed in .gitignore) for GOOGLE_API_KEY.
- Added verify_setup.py
- Run the verification with:
    uv run python verify_setup.py

All good. Done. 2026-08-27

