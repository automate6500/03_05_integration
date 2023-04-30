# 03_05_integration
This repo is for the integration workflow.

1. In the first repo, add a workflow for a Python application.  Create a workflow using the starter workflow for *Python applications*.

    From the repo homepage, Select:

    `Actions` -> `Python application` -> `Configure`.

1. Update the workflow so it can be called from another workflow.

    Edit the Python application workflow and remove all triggers.

    Add a trigger for `workflow_call` so the `on` section appears as follows:

        on:
          workflow_call:
