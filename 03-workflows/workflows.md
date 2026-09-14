you need a workflow file: usually stored in the .github/workflows file

workflow structure:

name: (name of workflow)
triggers: (events that trigger the workflow, for example pull / push requests)
jobs: (tasks that run in the workflow)
    steps: (individual commands or tasks. that run in the job sequentially)
    - a
    - b
    - c
