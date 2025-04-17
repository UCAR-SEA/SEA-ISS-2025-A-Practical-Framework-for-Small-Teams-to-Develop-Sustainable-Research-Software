# A Practical Framework for Small Teams to Develop Sustainable Research Software
[![JupyterBook](https://github.com/UCAR-SEA/SEA-ISS-Template/actions/workflows/deploy.yml/badge.svg)](https://github.com/UCAR-SEA/SEA-ISS-Template/actions/workflows/deploy.yml)
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-green?style=flat-square&logo=Jupyter&color=green)](https://jupyter.org/try)
![Static Badge](https://img.shields.io/badge/DOI-10.XXXXX%2Fnnnnn-blue)

**Authors**: Ange (Phil) Du, Spencer Smith

**Abstract**:   
Currently, a knowledge gap exists between research software and general software engineering. The scientific literature is full of ideas to close this gap, including documentation templates, code generation, continuous integration/deployment and formal methods. Although these ideas are promising, they often assume a large team that includes individuals who have the required expertise.

Our proposed practical framework instead targets a small team of domain experts, with the only requirement being to find someone (either from the original team, or externally added) who is interested in deepening their software knowledge by volunteering for the developer role. Our framework, especially for the beginning stage of requirements elicitation, includes step-by-step guidance. The process begins with questions the developer asks the domain expert(s). These questions cover topics such as the expected inputs and outputs, the computational scale of the problem and special input cases with known solutions or trends. The methodology shows how to map the answers to these questions to the requirements, high-level design and verification documentation. Templates for all documentation, in markdown format, are provided in a GitHub template, along with the initial infrastructure for issue tracking and continuous deployment of the project's webpage. The proposed methodology incorporates four main pieces of advice: i) the notation and structure for documenting the theory should be selected to facilitate the transition to design and implementation; ii) continuous integration should be part of the project from the start; iii) the low-level design documentation should be done through structured comments in the code, like docstrings or doxygen; and, iv) the modular decomposition needs to consider the computational scale when balancing information hiding and performance. 

**Keywords:** [Use keywords that describe the content of your paper, comma separated]


**Acknowledgements**: [List any Acknowledgements]  

