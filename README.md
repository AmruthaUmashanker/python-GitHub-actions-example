*Python CI using Azure DevOps*

This project demonstrates a basic Continuous Integration (CI) setup for a Python application using Azure DevOps Pipelines



 *What I did in this project*

- Created a Python application with unit tests
- Pushed the source code to GitHub
- Created an Azure DevOps project
- Configured an Azure DevOps CI pipeline using YAML
- Installed Python and dependencies automatically in the pipeline
- Executed unit tests using pytest



 *Project Structure*
 
src/ Application source code,
tests/ Unit test cases,
requirements.txt Python dependencies,
azure-pipelines.yml CI pipeline configuration




* Azure DevOps Pipeline Flow *

- Triggered on commits to the `main` branch
- Uses Microsoft-hosted `ubuntu-latest` agent
- Installs Python 3.10
- Installs dependencies from `requirements.txt`
- Runs tests using `pytest`



* Tools & Technologies Used *

- Python 3.14.2
- Pytest
- Azure DevOps Pipelines
- YAML
- GitHub



* Outcome *

- CI pipeline successfully created
- Automated build and test execution
- Improved code validation on every commit


