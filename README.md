# KODI Lite (Kimaru OpenDI Interface)

KODI Lite is a semantic translation engine built to convert open-source OpenDI Causal Decision Models (CDMs) directly into proprietary Kimaru Causal Decision Diagram (CDD) execution graph templates.

## 🚀 Day 1 Foundations Complete
The repository architecture has been initialized with an automated quality gate using GitHub Actions CI logic.

## 📁 Repository Structure
* `schemas/`: Holds the official core structural validation schemas (`Causal-Decision-Model.json`, `kimaru_cdd_schema.json`).
* `templates/`: Contains baseline manufacturing skeleton files for automated pipeline integration testing.
* `src/`: Core Python translation module workspace.

## 🛠️ Local Environment Verification
To install project tools and verify structural schema alignment manually on your workstation, execute:
```bash
pip install -r requirements.txt
check-jsonschema --schemafile schemas/Causal-Decision-Model.json templates/reference_empty.json
