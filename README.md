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
   - On Command Prompt:
     ```cmd
     .\env\Scripts\activate.bat
     ```

2. **Run Langflow**:
   ```powershell
   langflow.exe
   ```
   or
   ```powershell
   python -m langflow
   ```

3. **Access the Langflow UI**:
   - After starting Langflow, open your browser and go to the URL provided in the terminal (usually `http://localhost:7860`).

## Features

- Visualize and build language model flows interactively
- Integrate with popular Python libraries for NLP and data science
- Easily manage dependencies using the provided virtual environment

## Requirements

- Python 3.12 (already set up in `env/`)
- Windows OS (recommended for provided scripts)

## Useful Commands

- Install additional packages:
  ```powershell
  pip install <package-name>
  ```
- Run tests (if available):
  ```powershell
  pytest
  ```

## License

This demo is for educational and testing purposes. Please refer to the Langflow documentation for more details on usage and licensing.

## References

- [Langflow Documentation](https://github.com/logspace-ai/langflow)
- [Python Virtual Environments](https://docs.python.org/3/library/venv.html)
