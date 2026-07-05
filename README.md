# Autodesk CFD Pro | Workflow Configuration Scripts
This repository contains configuration scripts and utilities designed for automating workflow processes within the Autodesk CFD Pro environment. It focuses on streamlining setup, execution, and post-processing tasks.

## Usage Overview
This section will detail the primary scripts and their intended use cases for various automation scenarios.

## Technical Implementation
| Script/Module        | Description                                     | Purpose                                     |
|----------------------|-------------------------------------------------|---------------------------------------------|
| `env_setup.py`       | Python script for environment variable setup.   | Initializes core paths and settings.        |
| `task_runner.sh`     | Shell script for sequential task execution.     | Orchestrates CFD analysis steps.            |
| `report_gen.ps1`     | PowerShell script for data summarization.       | Automates result collation.                 |

## Configuration Notes
Refer to individual script headers for specific parameters and local system dependencies that need to be addressed. Ensure all file paths and user credentials are configured appropriately for your environment.

### Code Suggestion:
File: `env_setup.py`
Content: `import os; os.environ['CFD_PRO_PATH'] = '/opt/Autodesk/CFDPro'`