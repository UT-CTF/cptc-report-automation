# CPTC Report Automation

## Setup
- Download and Install [MiKTeX](https://miktex.org/)
- Use MikTeX console/CLI to update LaTeX packages to latest versions
- Create JSON data for vulnerabilities (single JSON for Lua or folder of JSONs for python)
- For Lua: Edit the file path (must be absolute path) in `cptc.lua:57` and compile pdf by running `lualatex cptc-lua-report.tex`
- For Python: compile pdf by running `python latex.py` (adding the `-h` flag will show additional configuration options)