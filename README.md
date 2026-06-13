Useful commands:

- uv init. # environment setup using uv

- source .venv/bin/activate # activate the environment
  
- uv add mlflow openai "langchain[openai]" python-dotenv ipykernel langchain-tavily # install packages

- uv run mlflow server #command to start mlflow server

Command to add the jupyter kernek in vscode
-  uv run python -m ipykernel install --user --name=.venv --display-name "mlflow_tutorial"