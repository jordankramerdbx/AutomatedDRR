# AutomatedDRR
- created agentic diagram (Jordan)
- Courtney's: This is the repo that holds the part that I did: 
https://github.com/finos-labs/opensource-reg-reporting

CDM - (Yanglet's team Kaiwen, Sarah, Keyi, Colin, Charlie)
- process data
- include comments on data source, purpose of data, how it is used, and outline main steps
- https://drr.docs.rosetta-technology.io/source/download.html (Dev Eaxamples DRR Examples was used)
- join tables and check quality

Agent (through Mosaic AI Framework, Jordan and Courtney)
https://docs.databricks.com/en/generative-ai/tutorials/agent-framework-notebook.html
- If a regulation changes:
- PDF document outlines the change
- AI agent extracts the change
- AI agentmaps the change to CDM
- AI agent looks at CDM data to understand impact of the change
- Evaluation framework to review output of the agent
- Metrics: precision and recall for classification, derive F1 score

- create report (Yanglet's team Kaiwen, Sarah, Keyi, Colin, Charlie)
- Could assume same format as output of tables

To solve:
- Decide on UI for engaging with the agent (Yanglet's app or Genie)

If time:
- find a sample regulatory change document (meeting minutes, etc) - Jordan and Courtney
- Build a workflow handling regulation changes

Plan:
- Weds - coding and building architecture
- Thursday - prepare presentation and upload the git repo

Resources:
- https://drr.docs.rosetta-technology.io/source/overview.html
- example python notebook for reference (https://www.databricks.com/notebooks/tempo/03_tempo_volatility.html)
- Regulatory texts:
  - CFR Title 17: https://www.ecfr.gov/current/title-17
  - EMIR 2: https://www.esma.europa.eu/data-reporting/emir-reporting
