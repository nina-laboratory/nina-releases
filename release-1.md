# Nina.CLI

- Create CLI tool
- Create the following commands:
    - list: Scans and lists all processes currently occupying ports 4000 to 4050.
    - kill: Terminates all processes found occupying ports 4000 to 4050.
    - commit: Plans and executes a deployment (commit & push).
    - build: Triggers the build-and-push workflow in the nina-infra repository.
    - deploy: Deploys a specific GitHub Actions run to your infrastructure using its URL.
    - release: Publishes release notes from local markdown files to Azure for a given release number.
    - start: Starts all applications that are configured with "run": true in config.json.
    - repo-structure: Verifies that your repositories adhere to the required file structure (e.g., biome.json, version.txt).
- Updated LLM model to gemini-2.0-flash-lite
    
# Nina.Home

- Initial Page

# Nina.Infra
- Initial Azure infrastructure
- Docker build pipeline on Github
- Azure Key Vault integration for managing secrets
- Managed Identity for Container Apps to access Key Vault
- Stable Application URLs configuration

# Nina.Journal

- Created base application
- Created docker image
- Initial Timeline Feature
- Fixed lint formatting issues

# Nina.Fit

- Added support for weighted reps exercises (Leg Extension, Leg Curl)
- Redesigned Session page with grid layout and compact cards
- Added custom vector assets for Leg Extension and Leg Curl

# Nina.Quick

- Fixed lint formatting issues

# Pedroaz.Home

- Initial Page