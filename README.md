# Langflow Demo

This project demonstrates the use of Langflow, a tool for building and visualizing language model flows. It is set up with a Python virtual environment and includes various dependencies for working with language models, data processing, and web applications.

## Project Structure

- `env/` - Python virtual environment containing all dependencies and executables.
- `Lib/`, `Scripts/`, `Include/` - Standard Python environment folders.
- `langflow.exe`, `langflow-base.exe` - Langflow executables for running and managing flows.

## Getting Started

1. **Activate the virtual environment**:
   - On Windows PowerShell:
     ```powershell
     .\env\Scripts\Activate.ps1
     ```
    - Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
    -.\env\Scripts\Activate.ps1 
    - pip install uv  

2. **Run Langflow**:
   ```powershell
   - uv pip install langflow
   - uv run langflow run 
   ```
   or
   ```powershell
   python -m langflow
   ```

3. **Access the Langflow UI**:
   - After starting Langflow, open your browser and go to the URL provided in the terminal (usually `http://localhost:7860`).
## Requirements

- Python 3.12 (already set up in `env/`)

## References
- [Langflow reference] (https://github.com/cladius/agentic-ai/tree/master/langflow/Level4)
