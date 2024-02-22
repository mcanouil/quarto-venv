# Quarto & Virtual Env

1. (Optional) In the command palette, search and select "Dev Containers: Reopen in Container".  
   Docker is required for this to work.  
   Alternatively, you can open the folder in a container by clicking the green "Code" button on GitHub and clicking on "Create codespace on main".
2. In the command palette:
   1. Search and select "Python: Create Environment...".
   2. Select "Venv".
   3. Select Python version/path.
   4. VSCode should automatically switch to the new environment, if not `source .venv/bin/activate`.
3. Install Jupyter: `python3 -m pip install jupyter`.
4. Check Quarto setup: `quarto check`.

See [Short video to show how to setup a Virtual Environment inside of a Dev Container](quarto-devcontainer-venv.mp4).

In this repository:

```txt
.
├── .devcontainer
│   └── devcontainer.json # Dev Container settings
├── .vscode
│   ├── extensions.json # Extensions to install
│   └── settings.json # VSCode settings, ensure "python.defaultInterpreterPath" is the default
├── README.md
└── quarto-devcontainer-venv.mov
```
